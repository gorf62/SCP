# SCP

Springboard Capstone Project
Joe Gorfinkle
December 21, 2017

NBA Free throws

Will the analysis outcome be useful?
- Yes, NBA fans want to know to what extent referee foul calls that become free throw attempts and influence the outcome of games will find this interesting and insightful.

Questions for the analysis:
1.	What are the relationships between free throws across the regular seasons by year, by period, by close game, by “crunch time”, and # of Super-stars?
2.	What are the relationships between free throws across the playoff seasons by year, by period, by close game, by “crunch time”, and # of Super-stars?
3.	Are the relationships between the regular season and playoffs consistent?
4.	Are the relationships between close games consistent in the regular season and playoffs?
5.	Are the relationships in the 4th period and during “crunch time” consistent in the regular season and playoffs?
6.	Are the relationships of teams with and without Super-stars consistent across the regular season, playoffs, 4th period, and “crunch time”?

Is the Data available and is it rich and sufficient?
- The free throw data spans 10 regular season and playoff games, about 618,000 total, and is in CSV format here:
- https://www.kaggle.com/sebastianmantey/nba-free-throws/data

The Top 30 regular season and Top 16 playoff season Super-stars are here:
- http://stats.nba.com/leaders/

Free Throw Data set and variables
Variable	  Description
end_result	Final Score of Game
game	      Abbreviated team names
game_id	    Numerical identifier
period	    Period the free throw was taken
play	      Outcome of free throw shot
player	    Player taking the free throw shot
playoffs	  Playoff or Regular season ID
score	      Score after the shot was taken
season	    Two Year span when games was played
shot_made	  1-Yes, 0-No
time	      Time remaining in period

What is your approach for this analysis?
1.	Bind the data set NBA Stats into the free throw data set to create a feature classification of Super-stars.
2.	Data Wrangling across variables; year, regular season, playoffs, period, close game, “Crunch time”, and # of Super-stars.
3.	Exploratory Data Analysis will be done across all variables to determine relationships, trends, correlations, and potentially further analysis ideas. The result of this step is that the analysis questions above are confidently determined by the completion of this step.

What are your deliverables?
Deliverables will include all the R-code, data sets, definitions, and slide summary to visualize the findings and insights. The deliverables will be uploaded to GitHub.

Some Noteworthy Information and Definitions
a.	The NBA has 30 teams throughout the period analyzed (2006-2016)
b.	There are 5 players/starters per team or 150 total starters
c.	There are 82 regular season games per team per season
d.	Each games consists of 4 twelve minute periods with subsequent periods for overtime (score is equal)
e.	Each yearly playoff season has 15 series of between 4 and 7 games each, or a range of 60 to 105 games
f.	Close games are arbitrarily classified as <= 14 points
g.	“Crunch time” is arbitrarily classified as in the 4th period with less than 4 minutes remaining
h.	RSS-Superstar is classified as player in the Top 30 in total points scored per game in regular season
i.	PSS-Superstar is classified as any player in the Top 16 in total points scored per game in playoff season

paste("Just a piece of R to get R-Studio to allow me to commit an .RMD file")
## [1] "Just a piece of R to get R-Studio to allow me to commit an .RMD file"
