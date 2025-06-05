# MLB-Roster-Construction-Based-On-Market-Size
STAT 306 Topics in Statistics: Multivariate Sports Analytics - Project #4

Topic: Ideal MLB Roster Construction based on team market status

Kenyon College

Malcolm Gaynor and Parker Gibbons

Question of Interest: The basic question is: what is the ideal MLB roster/payroll construction to win games, in the regular season and in the playoffs? However, this question is nuanced, because there is no salary cap in the MLB. Therefore, the Kansas City Royals (a team with a bottom ten payroll) cannot build a championship team in the same way that the Los Angeles Dodgers (a team with a top ten payroll) can. Therefore, our question of interest depends on the different types of teams, their respective payrolls and allocation of payroll amongst the roster. We also want to explore any possible similarities between successful teams despite any differences in payroll. In conclusion, we want to explore the ideal roster construction of MLB teams, depending on their market status.

Dataset: We will get most of the data from spotrac, fangraphs, https://bleacherreport.com/articles/961412-mlb-power-rankings-all-30-mlb-teams-by-market-size. The variables we are looking into for the clustering are total payroll, market size, owner net worth, size of fan base, etc. For the analysis, we will consider things such as payroll breakdowns by position, largest/longest contract, median contract size, roster breakdown in terms of how many players were acquired via trade, free agency, the draft, or international scouting, how many players on the team are on arbitration contracts, average age of players, etc. The response variable(s) will be regular season wins and playoff success.

Methods Used:
- K-means clustering
- Multiple linear regression
- MARS (Multivariate adaptive regression splines)
