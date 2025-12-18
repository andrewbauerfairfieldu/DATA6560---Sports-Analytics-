Title: The Value of 3pt Shooting As Players Age
This project analyzes the value of 3-point shooters as players age in attempt to
deliver more accurate data on how to structure contracts to young vs. aging players in the
NBA.
Stakeholders include NBA Executives and GM's.

All data is gathered from basketball-reference.com and is player data from the 2024-2025 NBA season. 

I first analyzed the trends and effects of 3pt shooting on win shares as the age of players increased. 
This established preliminary trends, showing higher win share contributions from 3pt shooters in older player pools.
Once this trend was established, I needed to define the value of one win share during the 2024-2025 season, which was done by
comparing a team of replacement level players on replacement level contracts and comparing them to the average player and wins. 
Once the value of 1 WS was established, I needed to determine how much the 3pt shot contributes to one win share at different age ranges. 
I broke the NBA ages into 3 categories; Young players (19-24), Prime Age Players (25-29), and Veterans (30+). 
I ran regression models at each of these age ranges and evaluated the effect that the 3pt shot had on win shares at those ages. 
I had to eliminate some of the x variables as some were statistically insignificant and throwing off my results (variables like rebounds or assists)
Once these variables were eliminated, I was able to see a trend that in the oldest age group, 3pt shooting contributed the most to win shares with 
the highest regression coefficient, followed by Prime players, and finally, young players.

<img width="777" height="453" alt="3Pt Make Value by Age" src="https://github.com/user-attachments/assets/15efd780-61dd-4a1f-ab1a-f432bea22082" />

The results from this project are as follows: 

The value of 1 additional 3pt make for a player 30+ is equivalent to $4,680,482.62

The value of 1 additional 3pt make for a player 25-29 is equivalent to $4,564,190.19

The value of 1 additional 3pt make for a player 19-24 is equivalent to $1,762,416.01


The data analysis can be found in the /data folder in Basketball Reference Data.xlsx
This file includes all of the analysis and troubleshooting work that was done in this project. 
Noteable figures can be found in the /figures folder. All checkpoints from each week can be found in the /reports folder. Checkpoints indicate progress that was done each week during this project.
