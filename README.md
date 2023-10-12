# Video-Game-Analysis
## Introduction of the data set:
The data set contains over 199 games data from the year 1980 to 2015.
### Let’s start the analysis:
We will conduct this analysis by follow the steps of the google analytics course, which are:
- Ask
- Prepare
- Process
- Analyze
- Share        
- Act
## Phase 1, Ask:

| Q.NO | DATA ANALYSIS QUESTIONS |
| :---: | :--- |
| 1 | Genre with the most sales.  |
| 2 | Maximum number of game on each platform.  |
| 3 | Platform having most sales.  |
| 4 | Are games being made increasing per year?  |
| 5 | Bestselling games per year. |
| 6 | Trend in the preferred genres from 1985 – 2020.  |

## Phase 2, Prepare:
- This data set was located and download from kaggle. Here is the link 
https://www.kaggle.com/datasets/gregorut/videogamesales
- This data set has information about, the games, publisher, year of release, North America’s sales, Europe sales, other region sales and Global sales, which will help bring insights to the questions in the ask phase.
- This data has no licence but the common licence of Attribution 4.0 International (CC BY 4.0) states that data set can be adjusted, tampered or modified according to the need. Only citation of the data set source is required.
- The data provided in the link is clean, but for the sake of showing skills in this portfolio, it was made unclean. Following components were added to make the data unclean:
- Extra rows.
- Duplicates.
- Extra spaces in cells contains strings.
- Missing Values.
- Alignment wrong.
- Splitting of columns to another sheet for SQL joining.
- For the sake of showing skills, I have split the data set into two tables and uploaded them in dataworld data storage, so that I can demonstrate some SQL skills in retrieving the data. The name of the two tables are table_a and table_b.
### Using SQL to retrieve data from the dataworld database:
Let us start the process by locating the video game analysis dataset in the dataworld database. After locating the dataset. Here is the process:
- The Schema of the dataset shows that data sets shows that there are two tables, table_a and table_b.
- table_a has 7 fields and 16,804 records.
- table_b has 5 fields and 16,804 records.
- Using the following command to inspect table_a:
- Select  *
- From table_a
































































### Question 1:
#### Genre with the most sales
![Genre with most sales](https://github.com/AbsarBabar861/Video-Game-Analysis/assets/146658018/40ef5b0f-5b60-49ca-a10b-f7f304df5dcd)
-	Judging by the column graph, it appears that the genre with the most sales is the shooter genre.
-	We can also find the games with the most global sales with respect to their genre in this graph too.


![genera with sales](https://github.com/AbsarBabar861/Video-Game-Analysis/assets/146658018/a330cd97-1667-4774-9ba6-fe4e101c079f)
-	Now we can see the game with the most global sale with respect to their genre. If I hovers my mouse to the tip of the shooter genre bar. I can see that Battlefield 3 has the most global sale in this genre.
### Question 2:
#### Maximum number of games on each Genre:
![Maximum number of games on each Genre](https://github.com/AbsarBabar861/Video-Game-Analysis/assets/146658018/78856000-97b4-4f0a-a193-b1e71c2d3e4c)
-	According to the bar chart created, the Maximum number of games on each genre is the action genre, having 36 games from the period 1982 – 2015.
-	This chart also has a year filter, which can filter the data according to the year.
### Question 3:
#### Platform having most sales.
![Platform having most sales](https://github.com/AbsarBabar861/Video-Game-Analysis/assets/146658018/355c4c0c-6f9f-404d-8369-feb63a7e8542)
-	According to this column chart, the platform that have the most sales is the WII platform.
### Question 4:
#### Are games being made increasing per year?
![asdasdas](https://github.com/AbsarBabar861/Video-Game-Analysis/assets/146658018/2c6f1e9c-cf32-428e-b536-539bd0e04f10)
-	By analysing this line chart, I came to know that the amount of games that have been released increased from 1982 to 2010, after that it’s a downward trend, meaning that the amount of games being made are decreasing.
### Question 5:
#### Best-selling games per year?
![Best-selling games per year](https://github.com/AbsarBabar861/Video-Game-Analysis/assets/146658018/43ac5ab0-fa3f-49f6-8c5c-fe8c9137dce3)
-	By this heat map. It appear that for the year 2007, the best-selling game is WII fit, followed by Call of duty 4 and Halo 3.
### Question 6:
#### Genre preference from 1984-2015:
![Genre preference from 1984-2015](https://github.com/AbsarBabar861/Video-Game-Analysis/assets/146658018/f76bfa8a-4234-4a93-8589-94c05a3fda3f)
-	I have compared the action genre, shooter and sports genre with each other and the line graph show a trend in their preference through the years.
