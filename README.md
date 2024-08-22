# NBA_Injury_Analysis
This is an analysis that I did on NBA Injuries from the 2011 - 2020 NBA season.

This project was used to discover and visualize patterns in injuries for NBA teams across the previous decade, and how teams could avoid them or adapt their playstyle to become more injury resilient.

## Analysis
![Screenshot 2024-08-15 150732](https://github.com/user-attachments/assets/d0e3f0de-4eb9-42c6-acbd-3d27c9cb8364)
This visual plots every team's injury statistics and shows a line of the mean number of injuries across the league per season.\
This visual shows that injuries generally over time are decreasing, with a spike in 2014 and a low in the 2020 NBA Season. \
It can be noted that the 3 highest injury counts (Lakers, Bucks, Rockets) occured in 2014.
![Screenshot 2024-08-15 145932](https://github.com/user-attachments/assets/b29be0ff-047d-4742-b6b7-4616fed87b76)
This visual allows the user to scroll through the season and see the distribution of injuries across the league. \
Using the slider, which changes the year we observe the injury counts for each team, we notice that none of the teams are consistently injury-free or injury-prone. \
This isn't revolutionary, but it suggests that injuries are mostly random, despite certain practices team may have. \
![Screenshot 2024-08-15 150613](https://github.com/user-attachments/assets/6fa112cb-4b96-4f89-9d9a-12113c0fa429)
This is a 3D scatterplot of pace, year, and injury count. The graph can be rotated to show the trend line of any 2 variables. 
![Screenshot 2024-08-22 132604](https://github.com/user-attachments/assets/f43bbf12-16a7-4e14-8841-d0417b28a94f)
One of the suspected factors of injury, Pace, didn't have a high correlation with Injury Count. \
Pace was increasing over the years but injuries seemed to be decreasing.
![Screenshot 2024-08-22 133038](https://github.com/user-attachments/assets/537760ca-5ff0-474d-8e84-a9e22de08a5f)
It should be noted that early years injuries seem to impact playoff admission more than in recent years. In other words, in recent years teams who are impacted by injury still have great chances of making the playoffs.
![Screenshot 2024-08-15 150251](https://github.com/user-attachments/assets/67bb5e92-7640-4be1-9ae3-bcb00373b0a4)
This visual on the left shows the total injuries per each month for the whole decade with the numbers represent the month (October == 10). The graph on the right aggregates total injuries for the decade. We can select specific years to see how injuries were distributed over a certain span of time (such as 2015 - 2020). \
The graph on the left can be used to depict how injuries are affected by month. We notice that injuries are increasing steadily until the all-star break in February, and then decrease again in April as teams get ready for the playoffs.
![Screenshot 2024-08-15 150343](https://github.com/user-attachments/assets/dafedcb0-0ba3-4bdf-a131-0ff8b3f29ebf)
This is the visual where only the years 2015-2020 are considered. The Warriors had the most injuries in that time frame and still appeared in 4 finals, winning 3 of them, which backs up our claim that injuries are becomeing less prevalent to affecting teams' winning chances.
![Screenshot 2024-08-15 150443](https://github.com/user-attachments/assets/f45263f7-0bcd-4f49-86db-7b072025bb84)
This scatterplot compares true shooting percentage with injuries, and shows playoff status, with teams and red being teams that sustained a number of injuries greater than or equal to 1.5 standard deviations from the mean. \
We notice here that teams that make the playoffs generally have a high TS% (their make/miss ratio is particularly high). \
Teams with a high injury count (1.5 standard deviations above the mean) still make the playoffs if they have a high TS% - this is the optimal playstyle to make the playoffs regardless of injuries on the roster.

## Key Takeaways
Injuries have been shown to be fairly random overtime, and that outside of basic load management systems, there’s little that teams can do to prevent injuries from impacting their rosters.
Teams can reduce the effect of injuries by focusing more on outside shooting and overall being more offensively-minded.
Teams will have better chances of making the playoffs if they build their roster around shooting 3 pointers and having a more modern style of play.

### Library Versions
MatPlotLib - 3.8.0 \
Seaborn - 0.13.1 \
Plotly - 5.9.0 \
Altair - 4.2.2 \
Dash - 2.17.1 \
dash-vega-components - 0.11.0
