# dota_analysis

Project to analyze character (heroes) compositions and assist in hero picks for the game DOTA 2.

For more information on DOTA 2, check out Purge's guide https://purgegamers.true.io/g/dota-2-guide/ "Dota Basics".

The idea is to have a database with the characteristics of each of the heroes, such as "stun", "invulnerability", "ranged" and "building damage". There are currently 55 planned attributes and 123 heroes.
This database will then be used to check each attribute's win rates and trends to identify possible positive and negative outliers, or identify important attributes missing in a hero composition and suggest hero picks.

### Currently implemented:
 - Webscraping of the heroes and abilities lists from www.dota2.com, www.dotabuff.com, https://liquipedia.net/dota2/ and https://dota2.fandom.com/wiki using a webdriver on Google Colab with Python pandas and selenium. Includes the handling of errors, detection and handling of new heroes or abilities, restoration and creation of backup files.

### Planned:
 - Manually attribute skills, heroes and the correlation matrix.
 - Use machine learning to discover the correlation matrix values.
 - Create a dashboard to quickly analyze trends and hero win rates daily.
