# dvorak2023

Clustering and geo-location analysis of GPS data on South African taxis for the 2023 Standard Bank Lab and MOBALYZ data science hackathon.

## team

- sarah ingram [team leader]
- daniel bockle
- sean morrison 
- jean marx

## cleaning
aggregating csv files, fixed column types, added 60 as minimum road speed, and replaced NAs with closest average.

## analysis

### clustering
normalized data, performed principle component analysis and performed k-nearesr neighbour clustering analysis.

### geographical 
visualized key gps events such as idling, gps signal lost/lock, speeding, and ignition on for interactive analysis.

## risk
determined risk categories through examining time periods of driving activity (shift risk), total time driving and speeding (driving duration and speeding risk), and historical claims and accidents (claim risk). 
