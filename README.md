# F1-2022-Data-Analytics-Project
This is my hub for all things data and all things F1.

# Season 2022 Excel Sheet
This sheet contains all the data regarding points, position, and pretty much everything else that doesn't have to do with timing or telemetry. A majority of the tables are pretty self explanatory, and I have already made the sheet for 2023. 

[This is the link to the spreadsheet](https://semo0-my.sharepoint.com/:x:/g/personal/ejreyes1s_semo_edu/EX-ACKNVDqBPgKA2fhm1nJ8BVM21plp5LbJwMgyLZzw-aw?e=vT1hIK)

  The main table is the drivers points-by-race. I update these based on how they perform in each race. Below that table are the drivers and constructors totals, as well as the points gained per race. I have these to track the total points per race as well as get a general overview of how the teams progressed relative to their rivals throughout the season. While points per race is not the entire picture, I find that it paints a general picture of where teams are compared to their rivals. Another reason to track the points as I did was to view the points percentage split among the two teammates. In a sport with as many variables as F1, the closest thing to a control variable is your own teammate. When the machinery is equal, the points percentage split can be one of the easiest ways to notice a gap between teammates. However, no data tells the whole story and while it is good at what it is made for, it is also horribly crude and an extremely simplified way of looking at the points.

  Other tables on the excel sheet include a points totals graph for the drivers and teams, as well as a row at the bottom to check the maximum remaining points. One neat thing about this row is that it automatically checks to see if there is a winner. It uses some cells to check if there are still available points in the season, and the maximum points possible to achieve until the end. If the points gap between the top team and the other teams is greater than the maximum remaining points, the driver or teams name will appear in the Winner? box. The last few charts count the wins and podiums, as well as write down the names of the winners of each race.

  Sheet 2 is the qualifying sheet. On it are simple graphs that show drivers qualifying (not starting) positions. I input these manually after every qualifying, and the sheet updates the pole position table, qualifying head to head table, as well as the constructors qualifying wins table. While some of the tables are useful at a glance, one of my favorite tables is the qualifying head to head. It takes each drivers qualifying position and whichever is higher on the grid gets a point. The graph will total the points and split the difference with a percentage. I feel that this is a much more telling table than the points percentage split in the teammate head to head battle. There is a lot less variables in one lap and it is extremely likely that both drivers are going to be in extremely similar conditions. This is the table that I look at the most when looking at teammate head to heads. 

  Both of these sheets combined hold a lot of useful information. For example, the closest rivalry in terms of qualifying was between Esteban Ocon (won 45.45% of qualifying battles) and Fernando Alonso (54.55%), while the biggest gap between teammates was between Lando Norris (90.91%) and Daniel Ricciardo (9.09%). Also despite outscoring his teammate by 35 points, George Russell actually lost the qualifying battle with his teammate, Lewis Hamilton, 9 - 13. 

# Race Analysis 
For the 2022 races I used FastF1 and Python to graph and analyze the telemetry and timing data from each race. All of the analysis and opinions in this project are my own. 
