# EPL Team and Player Performance Analysis
This project aims to explore and analyzes English Premier League (EPL) team and player performance, using data-driven metrics like progressive actions, expected goals (xG), and shot-creating actions (SCA) to reveal tactical styles and individual contributions.

# Data collection and preperation
1- I used Python to scrape Premier League stats from FBref. The script initializes a headless Chrome browser, navigates to the EPL stats page, and waits for the relevant table to load. It then extracts the table HTML and converts it into a Pandas DataFrame for further analysis

2- For data cleaning, after obtaining the data, I converted the DataFrame to Excel format. The cleaning process involved:
Removing duplicate entries to ensure data integrity.
Eliminating unnecessary columns that were not relevant for the analysis.
Handling missing data to maintain consistency and accuracy.

# Data visualisation
I imported the cleaned data into Tableau for visualization. This step allowed me to create various charts and plots to analyze team and player performances effectively.
https://public.tableau.com/app/profile/adam.janeb/vizzes
***


This visualization provides crucial insights into team finishing quality and attacking efficiency in the Premier League. By comparing expected goals (xG) with actual goals scored, we can identify which teams are clinical finishers and which are wasteful with their chances. Teams above the diagonal line are exceeding expectations, demonstrating efficient finishing, while those below are struggling to convert their chances at an expected rate. This metric is particularly valuable for understanding whether a team's goal-scoring form is sustainable or likely to regress.

![Attack effeciency](https://github.com/user-attachments/assets/1a37b548-12c4-4f6d-b50d-f4dcbe1c458a)
***

This plot chart evaluates shot efficiency by comparing expected goals (xG) per shot with shot conversion percentage. It identifies players who effectively capitalize on scoring opportunities, highlighting those who not only take high-quality shots (reflected in xG) but also convert them into goals at a high rate. This dual analysis offers insights into players' finishing abilities and overall attacking prowess.

![Sheet 3](https://github.com/user-attachments/assets/61108a18-ee66-4a9f-a692-e24bf8f3e75c)

***

This analysis reveals distinct playing styles and tactical approaches in the Premier League. By mapping possession percentage against progressive actions, we can identify four distinct tactical profiles: dominant teams that both keep the ball and advance it effectively, possession-based teams that struggle to penetrate, counter-attacking sides that progress efficiently with less possession, and teams that struggle in both aspects. This visualization helps understand team philosophies and their effectiveness in translating possession into meaningful attacking progress.

![Sheet 5](https://github.com/user-attachments/assets/06849823-772c-4f24-a041-0b31d0dc194d)

***

This visualization effectively demonstrates both the volume and quality of players' ball progression through progressive passes and progressive carries. The data points represent total progressive actions, while the circle size reflects the progressive distance achieved. This approach helps identify players who not only advance the ball frequently but do so with significant distance gains. Bigger circle sizes indicate players who make substantial territorial advances rather than just short progressive movements

![PlayerBallProgression](https://github.com/user-attachments/assets/db3c0cb0-584d-4283-83ef-9116df14e452)

***

The player finishing analysis maps expected goals against actual goals scored, revealing individual scoring efficiency. Players above the diagonal line are outperforming their xG, showing clinical finishing ability, while those below may be experiencing finishing struggles. This visualization is crucial for identifying both clinical finishers and players who might be experiencing unsustainable scoring runs, whether positive or negative.

![xgVsGoals](https://github.com/user-attachments/assets/1309f48e-afb0-4cf2-91fc-facb42076f1d)

***

This visualization combines expected assisted goals (xAG), shot-creating actions per 90 (SCA90), and key passes (shown by circle size) to provide a comprehensive view of players' creative contributions. Players in the top-right quadrant elite creators who excel in both metrics - they create high-quality chances frequently and consistently find teammates in dangerous positions.

![CreativeOutput](https://github.com/user-attachments/assets/07f07ff5-a540-4d48-84d7-c396902df67e)

***

This detailed breakdown illustrates the diverse ways players contribute to shot creation. By segmenting each player's shot-creating actions into six categories (take-ons, defensive actions, fouls drawn, shots, dead ball passes, and live ball passes), we can identify players' unique creative styles. This helps understand whether a player creates primarily through dribbling, passing, or other actions, providing insight into their tactical role.

![HowPlayersCreateGoals](https://github.com/user-attachments/assets/e161f98c-41ef-4458-a200-9385588beb2c)

***

This visualization maps players' ball progression abilities through both carrying and passing.The chart helps identify specialists (those who primarily progress through either carries or passes) and complete progressors who can advance the ball effectively in multiple ways. This is particularly valuable for understanding a player's role in their team's build-up play.

![PlayerBallProgression](https://github.com/user-attachments/assets/e9d4231a-d254-4fba-a20b-0149ea9f5405)

***

This analysis shows player activity distribution across different thirds of the pitch. The horizontal bars represent the percentage of actions in each third, providing clear insight into a player's primary operating areas. This helps identify true box-to-box players versus those who specialize in specific zones, and can highlight positional versatility or specialized roles within a team's tactical setup.

![PlayerActivity](https://github.com/user-attachments/assets/634acfde-2223-44a6-bbe7-25b7b68ace30)












