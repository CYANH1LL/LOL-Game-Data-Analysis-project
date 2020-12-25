# CS411Project

This is a semester-long project designed by me and my teammates utillizing Java and Android Studio. More in README

Android application with crawled Esports data from official website and data analysis function. Tomcat Server as web server and AWS as database platform.

Description:

League of Legends Esports Game Analysis

League of Legends is a multiplayer online battle arena video game which draws millions of attention every year. We want to create a web application that provides users with the latest information about major League of Legends tournaments.

Our offered information includes:

1.Champion Ban/Pick Rates related statistics.

2.Champion Win Rates.

3.Champion Equipment Recommendation.

4.Lineup Winner Prediction.

5.Recent matchup information for every team.

6.Win rate progression of completed match-ups.

Usefulness:

1.Overview of all esports game statistics

2.Find game winner strategies

3.Real-time game winner prediction

PS: There are some websites that give the statistics for each esport game (For example: https://gol.gg/tournament/tournament-stats/LPL%20Regional%20Finals%202020/).

However, these websites only give the recorded game statistics. In addition to that, we can provide analysis for the lineup and present a more intuitive interpretation to key factors affecting the result of each game.

Also, many applications in the market are not free, which might stop the user from using the application. Therefore we propose to create this database and help other players to get their wanted information and data.

Realness:

We will crawl data from https://lol.gamepedia.com/League_of_Legends_Esports_Wiki

Also we have https://developer.riotgames.com/ which have stats directly from riot games.

Basic Functions:

Users can create accounts, set password and profile information.

Users can update password and profile information.

The data in the database is crawled from other websites as mentioned in the above section. Result of each completed match if major tournaments will be stored into a database.

INSERT:

Newly created user accounts will be inserted into a database. Recently finished match-up information will be included into a database.

UPDATE: Edited user information will be updated. After a match finishes, the ranks, match histories of contestant teams will be updated. Meanwhile, the win-rates and counts of picked/banned champions will be updated.

SEARCH: User will be allowed to search for information about specific esports teams and champions. Advanced Function 1

Analysis and Prediction

The application should analyse the game statistics from the dataset and give game winning rate prediction towards each game.

Advanced Function 2

Potential Teammates Search

The application uses the Neo4j database to store the user information of users that have signed up with our application. Neo4j can perform the graph nodes and edges search from the database. Users can search for their potential teammates by either searching their favorite position or favorite champion.
