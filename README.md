# Oakland-A-s-MLB-Baseball-Data-Analysis-Using-Alteryx-And-Tableau

Database : Latham database
Objective: Use Excel spreadsheets from the Latham database tables to create Alteryx workflows and Tableau
visualizations in order to analyze baseball data.
Data: Choose a MLB team from the Google sheet. (Note: Do not include the 1981, 1994, 1995, and 2020
seasons as they were shortened seasons with less than 162 games)

Alteryx Workflows 
For your team only, - My team is Oakland
1. Teams Analysis
  a. In the same workflow (using multiple branches), using the TEAMS table:
    i.  Find the average number of wins (W) by each team in your team’s league
    (AL or NL) between 2000-2019. Create a report and highlight your team. Where
    does your team rank?
    ii. How successful is your team? Find the number of times your team has
    achieved winning the Wild Card (WCWin), Division (DivWin), League (LgWin), and
    World Series (WSWin). Create a report.
    iii. Using the Rank field, create a report that identifies how many times your
    team has ranked between 1st and 5th place in their division between 2000-2019.

2. Salaries Analysis
  a. Using the Salaries spreadsheet include the records for your team (Note: the time
  period for this table is between 1985 and 2016), find the minimum and maximum salary for
  each year.
  b. Create a new field “Key Player” using a conditional statement in a Formula that
  should be set to “Min” for the player(s) with the minimum salary, “Max” for the player(s)
  with the maximum salary and “Neither” for all other players.
  c. Join the PEOPLE spreadsheet to include the player’s name.
  d. Include only the players that represent the minimum and maximum salaries.
  e. Sort the information by year.
  f. Create a report that includes: Team Name, Year, Minimum Salary, Maximum
  Salary, Player Salary, Player Name.

3. Attendance Analysis
  a. Using the HomeGames spreadsheet, find the average attendance for each
  ballpark for your team between 1969-2021 (excluding 1981, 1994, 1995 and 2020).
  b. Calculate the difference between each season’s attendance and the average
  attendance for the ballpark.
  c. Remove any ballparks with less than 5 games.
  d. Join the PARKS spreadsheet to include the ballpark name.
  e. Create a report with appropriate information and export the report to Excel.
  

Tableau Visualizations -
For the parts 1-4 use the 2000-2019 seasons only,
  1. Using the Teams spreadsheet, create a line graph showing the number of wins for your
  team. Add total number of runs as a dual axis graph using a different type of graph. Add a
  reference line to indicate the average number of wins over this time period.
  2. Using the Teams spreadsheet, create a visualization that displays your team’s season BA
  over this time period. You will need to create a calculated field for BA, which can be calculated as
  H/AB. Adjust the format of BA to 3 decimal places. Adjust the y axis to make the visualization
  better.
  3. Using the Teams spreadsheet, create a visualization that compares your team’s number
  of wins with the other teams in their division (DivID) over this time period. You may also need to
  create groups to combine teams that changed names. You should have a maximum number of 5
  teams on your graph. Use a distinct color to represent your team.
  4. Using the Salaries spreadsheet, create a visualization to compare the average annual
  salary for each season comparing the NL vs. AL (LgID).
  5. Using the Teams spreadsheet, for the 1960-1969 seasons, create a visualization (Note:
  this could be a table) to show the total wins for each team. Sort the graph in descending order to
  identify the team with the most wins in this decade. Use the team name in the visualization and
  color to enhance the graph.
  6. Build a dashboard that includes at least two of your visualizations.
  Guidelines for your visualizations:
    • Title should be appropriate for the graph.
    • Axis names should be changed where necessary.
    • The graph should be visually appealing, so be careful with the use of color.


Alteryx Workflows

Tableau Link
