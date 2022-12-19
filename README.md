# What Makes The Best Tennis Player? 
## Catboost Group

## Dataset Overview

The Association of Tennis Professionals (ATP) is the governing body of the men's professional tennis circuits; this project uses a total of 17 datasets. In these datasets there are individual csv files for ATP tournament from 2000 to 2017. The numbers in the last columns are absolute values.

The following is the naming abbrevations of the column names used in the data:

ace = absolute number of aces

df = number of double faults

svpt = total serve points

1stin = 1st serve in

1st won = points won on 1st serve

2ndwon = points won on 2nd serve

SvGms = serve games

bpSaved = break point saved

bpFaced = break point faced

All tables were merged into one table which contained 53,571 rows and 49 columns.
From the table, columns not feasible for the study were dropped. Thereafter, the duplicates and null values were removed. Finally, the dataset was formatted. 

The wrangled dataset contained 44,310 rows and 25 columns.

The features of our study are: Winner Name, Winner Hand, Winner Height, Winner Rank Points, Winner Ace, Winner Double Faults, Winner serve points, Winner 1st in, Winner 1st Won, Winner 2nd Won.

## Summary of Findings

- 40% of top winners have height above the average height of players and 60% of top winners have height below the average height. 

- We discovered that the top ten players had more aces on Grass Surface.

- Switzerland, Serbia, United State of America, United Kingdom, Czech Republic, Chile and Australia have one top tennis player. However, Spain has three top players.

- 90% of the top ten winners were right-handed while the other 10% were left-handed.
​
- We discovered that the best tennis player is Roger Federer.

- The surface which most events were held on was hard. 

## Key Insights

- Best players maximize their aces on the Grass surface. ​

- Clay is the natural surface of Spain and this surface is very vital for the development of a player.  Thus, to become the top player, it is vital to practice on Clay surface.​

- Top players take advantage of their first serve. However, if they fail during their first serve, they still have potential of winning their second serve. ​

- Top players are coached in the direction of reducing the number of double faults.  ​

- The height of player has a minimal bearing on the performance of the player. ​

- To be considered as a top or outstanding tennis player, it is crucial to really dominate at least 2 or 3 of the top ten tennis tournaments​

​

## Resources

1. [Kaggle](https://www.kaggle.com/datasets/gmadevs/atp-matches-dataset?resource=download)
2. [A page on top ten tennis players](https://www.espn.com/tennis/rankings)
3. [Atricle on Performance Indicators in ATP Tournaments](https://scholar.ufs.ac.za/bitstream/handle/11660/11745/CarlisleJ.pdf?sequence=1&isAllowed=y)


## Notes

- The dataset for 2016 and 2017 had a structure issue with the date column, so we transformed it using Microsoft Excel.

