# NFL-Wide-Receivers
A look at the top NFL wide receivers of the past decade.

As a fan of fantasy football, I am naturally curious about the traits and trends that are shared by the top NFL Wide Receivers as sorteed by the amount of fantasy points they scored each season for the past 10 seasons (2013 - 2022). For fantasy points scored, the Half-Point per Reception scoring system was used. This means that a wide receiver would score 0.5 points per successful reception, 0.1 points per yard gained (rushing or receiving) and 6 points per touchdown scored. For instance, in 2013, Demaryius Thomas was the highest scoring wide receiver with 273.0 points. This point total was reached with 92 receptions (46 points), 1,430 receiving yards (143 points) and 14 receivng touchdowns (84 points) with no rushing statistics. 

For this set of analysis, I chose to rank the wide receivers by total points scored on the season. Some analysts prefer to do a points per game with minimum games played qualifier to rank players as a way to balance players who missed games due to injury or suspension. I may further explore the data with the points per game method in the future, but for this first look I wanted to use total points scored on the season as these are the points that would actually be scored for someone's fantasy team and to reward the players who showed that one of their best abilities was availability.

The data was primarily sources from Fantasy Pros. Fantasy Pros is a sport website that stores and aggregates rankings and statistics from major sports. With a free account, the site allows users to download statistics on a per season basis. I started my analysis process by downloading the ten most recent seasons for wide receivers. Here is the webpage where I downloaded the 2022 data from:
https://www.fantasypros.com/nfl/stats/wr.php?year=2022&scoring=HALF

After downloading, I manually added the final five columns. Those being the round each player was originally drafted in the NFL Draft, the year of the data, the year they were drafted, which season of their career they were in and the team that originally drafted them. With the NFL Draft quickly approaching and Fantasy Football Dynasty Drafts following shortly thereafter, I wanted the draft data as a way to inform how a player eventually performs based on where they were drafted.

Why 10 years of data?
The NFL, player analysis and fantasy football are constantly evolving. I wanted to keep data as current as possible while creating a large enough sample size to find trends. 10 years worth of top 24 Wide Receivers seemed like it would present a good mix of those two.

Why 24 players per year?
The most common league size in fantasy football is 12-teams and the most common starting line-up size has two starting wide receiver slots. As a result, the most common league will be starting two wide receivers each week, making the league have 24 fantasy relevant wide receivers each week. 

My initial exploratory data analysis is contained in the Jupyter Notebook NFL WRs.ipynb . As expected, the most frequent drafted round for top receivers was the first round. Interestingly though, was the domination of Day 1 and Day 2 picks (rounds 1, 2 and 3) vs the field of rounds 4-7 and undrafted players where 81% of wide receivers with finishes in the top 24 were originally drafted in rounds 1, 2 and 3. This helps the argument for those that argue the most important indicator for future and prolonged fantasy success is draft capital. Donut charts were created from these findings and saved as PNGs to make them shareable.

