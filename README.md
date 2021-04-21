
**Pay to Win**

For this project I was given an open ended opportunity to analyze the European Soccer Transfer Market
I looked through several different databases to build my dataset. 

Transfer Data:
Github user ewenme compiled database of transfer data dating back 28 years
Team and Player Statistics
API-FOOTBALL
Foootball Reference

*Data Cleaning*
  - Used Europe’s top 5 leagues (England, Germany, France, Italy, and Spain) over the last 5 years
  - Brought in team and player stats from API-FOOTBALL
  - Advanced stats for the last 3 years applied to the top 20 transfers over that time period

**Analysis**

Do teams that spend more in the transfer market win more? (reference fig spending vs. wins)
	
  For this question I looked at the total number of team wins over the last 5 years vs the amount a club spent during that same time period. In my prediction I thought there would be a correlation between the two variables. And with a correlation coefficient of 0.67 we can say there is a moderate correlation between the two variables. We can confidently say that by increasing the amount spent during the transfer windows you will increase your teams total number of wins for that same time period. This is shown in figure 1-1, below.
 
![spending_v_wins](https://user-images.githubusercontent.com/47986124/115578635-b3beb480-a282-11eb-9572-94fb0a4dd228.png)
(figure 1-1: Club Spending vs. Wins) 

 

 A very interesting finding that almost counters our previous findings is looking at club profits vs wins. We actually see a positive correlation between a clubs profits and their total number of wins during a given period of time. This would mean that clubs that focus on developing players and then selling them are finding success as well. This could be a result of a lag in results as it takes time for a new player to impact a new team. Similarly, a team losing a player could experience a lag in performance until they fully realize the lose of said player. We can also say that for these most profitable clubs they are selling top players. There is more to be said about teams having a top player vs how much they spend on that top player. With this finding we see those clubs developing players to their peak are just as likely to win as those purchasing the fully developed player. Figure 1-2 show sthe relationship between club profits from selling players compared to wins.
 
![profits_v_wins](https://user-images.githubusercontent.com/47986124/115578888-e8327080-a282-11eb-86f9-98925956f5b4.png)
(figure 1-2: Club Profits vs. Wins)


Do clubs that spend more finish higher in the league? (reference fig spending vs. lgrk)
	
  I wanted to take a dive into this analysis and look at league position. While determining wins can be of benefit, I wanted to see the result. How does spending impact a clubs final standing? I was able to find a moderate correlation of -0.52 between club spending and average league position.  Club’s whose total spending is higher on average finish higher in the league. This backs up my claim even further that you can pay to win in modern European club soccer. The correlation is negative because a lower league position is a better result.
 
  Looking at the profits and losses of clubs I was unable to find any kind of correlation between the two. I cannot say that taking a buying or selling approach has any impact on the final league standings. 

Null Hypothesis:  If club spending is related to clubs’ wins, then spending more during the transfer windows will lead to more wins.
Alternative Hypothesis: If club spending is not related to clubs wins, then spending more during the transfer windows will not lead to more wins.

Final conclusion:
  For both analysis looking at total spending vs wins and total spending vs average league position we get p-values of 2.5741895304617124e-11 and pvalue=2.0425314254857977e-13 respectively. With both p-values being significantly smaller than 0.05 we can say there is very little evidence in support of the null hypothesis. We are therefor forced to reject the Null Hypothesis and fail to reject the Alternative Hypothesis. While we had moderate correlation between the variables in each analysis the p-values turned out to be too small to confidently say that there is a connection between club spending and wins.
