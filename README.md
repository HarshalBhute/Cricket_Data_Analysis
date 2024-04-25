# Cricket Data Analytics

## Objective:- To showcase Data Analytics Skills.

## Skills used:- Data Scrapping, Data Modelling, Python, Pandas, Jupyter Notebook and Power BI.

### Problem Statement :-
__ICC__ Cricket regulating body of the world has decided to felicitate top emerging players of the world but they have a condition that they should felicitate only 11 Players all accross a Globe.\
And also to cover all dimensions of cricket that is Bowling, Batting and Fielding they came up with a unique idea.\
Idea was to pickup 11 Best Players of the world according to their performance in __T-20 World Cup 2022__.\
Hence they decided to take help of __Data Analytics__ to find Best 11 T-20 players accroding to performance in 2022 World Cup.


### Approach :-
__Data Analyst__ scrutinized the problem and came up with a solution.\
They decided to form a team of Best 11 from the countries that played in World Cup.\
Team should score 180 runs on an average and at the same time defend 150 runs.\
Structure of the team decided was
1. 2 Openers whose
   Batting Average > 30,\
   Strike Rate > 140,\
   Innings Batted > 3,\
   Boundary % > 50,\
   Batting Position < 4

2. 3 Middle Order/Anchors whose
   Batting Average > 40,\
   Strike Rate > 125,\
   Innings Batted > 3,\
   Average Balls Faced > 20,\
   Batting Position > 2

3. 1 Finisher whose
   Batting Average > 25,\
   Strike Rate > 130,\
   Innings Batted > 3,\
   Average Balls Faced > 12,\
   Batting Position > 4,\
   Innings Bowled > 1

4. 2 All Rounders/Lower Order Batsman/Spin whose
   Batting Average > 15,\
   Strike Rate > 140,\
   Total Innings Batted > 2,\
   Order in which batter played > 4,\
   Total Innings Bowled > 2,\
   Bowling Economy< 7,\
   Bowling Strike Rate < 20

5. Specialist Fast Bowler whose
   Innings Bowled > 4,\
   Bowling Economy < 7,\
   Bowling Strike Rate < 16,\
   Bowling Style = Fast,\
   Bowling Average < 20,\
   Dot Ball % > 40


### Process :-
1. __Data Collection__:- Data was collected from ESPNcricinfo website.
   __Bright Data__ was used as a __web crawler__ to collect data.\
    BrightData collector uses a Smart proxy network due to which user can have seamless data collection without worrying about IP Blocking.\
    It is a sort of VPN which uses different IP's reducing issues of data collection process.

2.__Data Transformation__:- Transforming JSON format to CSV format using __Python Pandas__.

3. __Data Cleaning__:- Power BI contains __Power Query__ which allows to remove null values, duplicate values etc.

4. __Building New Columns__:- As we are given conditions like Batting Average, Bowling Average etc we need to create new columns for it using __DAX__.\
    Data Analysis Expressions (DAX) is a formula expression language used in Analysis Services, Power BI, and Power Pivot in Excel.\
    DAX formulas include functions, operators, and values to perform advanced calculations and queries on data in related tables and columns in tabular data models.

5. __Data Modelling__:- After making Fact Table, Dimension Table a __star schema__ is made showing one to many relationship.

6. __Data Visualization__:- After proper arrangement of Data visualization was made so that non tech user can also understand performance via Visualizations.\
   Here different sheets were made showing different aspect and later a Dashboard showing Best 11 of World.

   ### Note:- In repository all the codes used are compressed in Zip File for better organization of code folder.
