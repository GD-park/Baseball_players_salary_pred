# Baseball_players_salary_pred
I tried to predict Baseball players salaries.
Hypothesize : salary will be based on player's performance.

## Working Process
- Data Crawling : got data from Statiz(http://www.statiz.com)
- Data Preprocessing 
 1) There are alot of feature so using my domain Knowledge decrease feature from 109 to 39
 2) All feature have different Scope so I did scaling
 3) Some Feature have correlation so I used PCA to get rid of correlation
- Modeling : I did prediction using regression model(76.5% R-squared)

If you see the summary.ipynb, you can see all of my work process & code
