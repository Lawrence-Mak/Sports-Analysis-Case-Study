# Introduction

The purpose of this case study is to identify and analyize the differences between a multitude of variables to find trends and patterns within the Los Angeles Clippers team situated within the National Basketball Association.

The patterns and trends identified provides athletes and coaches with objective information that helps them understand performance. 
This process is underpinned by systematic observation, which provides valid, reliable and detailed information relating to performance.

The variables this case study will cover are:
<ul>
  <li> Winning Percentage vs. Average Attendance
    <li> Payroll vs. Average Attendance
      <li> Team Payroll vs. Winning Percentages
        <li> Which coefficients have an effect on salary?
          </ul>         
It is important to remember that correlation does not imply causation. 

## Winning Percentage vs. Average Attendance

The first two variables we will be comparing are winning percentage and attendance. The question is - does having a higher attendance mean the team has a higher possibility to win?

<br> To find this, we will need to use data from our <a href = "https://github.com/Lawrence-Mak/SportsAnalysis/blob/main/SportsAnalysisDataFile.xlsx"> database </a>

<br> We are able to vizualise trends and patterns by creating a graph.
![image](https://user-images.githubusercontent.com/83872954/207110109-25b64267-eb15-4479-ac05-697381b3b438.png)

This graph illustrates the connection between the LA Clippers winning percentage versus their home game attendance average from 2000 to 2018. From the trendline observed, it is evident that there is a positive, linear correlation between the two variables. In other words, when the LA Clippers win more games, more fans will come out to home games to support them. Having a high R^2 value also proves that there is a high correlation between the two variables, and the 63.7% of the variation in the output variable can be explained by the input variables.

Diving deeper, we can hypothesize that demand analysis explains the observed linear trend, with the premise that home game attendance is extremely closely tied to ticket demand, or ticket sales. 
There are several factors that might influence the number of tickets required. The demand curve would be affected by, for example, drafting, purchasing, or trading for a more attractive roster, having a better coach, having a more interesting style of play, an increase in ads for the LA Clippers, or a change in the preference or income of individuals in the region. The demand curve would shift rightwards in these instances, ceteris paribus, and there would be a bigger amount sought at each price.

To illustrate this, the 2011 - 2012 Clippers team can be used as an example – The season where the Clippers drafted Chris Paul, who immediately turned the clippers into one of the leagues most entertaining and dangerous teams. Before this trade, from 2000 – 2011, the Clippers had an average win rate of 39%. After this trade, from 2013 - 2018 the team had an average win rate of 63.5%. This is a huge increase, and the improvement was reflected in their home game attendance, and the rate at which tickets were bought. Of course, Chris Paul was not the only contributing factor to such a high average win rate, Blake Griffin, fellow All-star, and Captain of the Clippers also pushed sales in the 2013 season, averaging 18.0 points per game and 8.3 rebounds per game in 32.5 minutes per game. He and Chris Paul led the Los Angeles Clippers to a 56–26 record, leading to the highest win percentage in the last ten years of Clippers History. 

On the other hand, the 2000-2001 Clippers season seems to be the largest outlier in the positive Winning percentage vs Attendance trend. Even though they had a 38%-win rate, they didn’t have nearly as many fans as some of the seasons where the team had even worse win rates. After finishing with the worst record the previous season, the Clippers decided it was time to rebuild, drafting Darius Miles in the third pick, alongside other young talents such as Keyon Dooling and Corey Magette. Having such a young team with no prospects to back them up really hurt the Clippers Attendance, as nobody even knew who these players were. Ultimately, leading to one of the Clippers worst selling and performing years.

## Team Payroll vs. Average Attendance 

After observing a clear correlation between winning percentange and average attendance, we will examine whether there is a correlation between team payroll and average attendance. The question this time being - does having a more expensive roster increase average attendance at home games?

We are once again able to visualize trends and patterns by creating a graph using the same <a href = "https://github.com/Lawrence-Mak/SportsAnalysis/blob/main/SportsAnalysisDataFile.xlsx"> database </a>
![image](https://user-images.githubusercontent.com/83872954/207113650-435b1a83-2dab-4328-9cb9-7875f13982f6.png)

Similarly, to Figure 1, it can be observed that these two factors share a positive correlation and linear trend, albeit not as much as the first two factors discussed previously. The graph can tell us that an increase in payroll, leads to an increase in attendance. This graph has a R^2 of 0.1755, which means that the level of corellation between the two variables is relatively low.

Again, a demand-side analysis can be used to justify this. Home game attendance may be thought to represent ticket demand, and the team's salary can be viewed as an investment in bolstering the squad with better players. A player's ability level determines how useful and desirable he is to other teams. This increases the player's “price” by shifting the player's demand to the right. As a result of the player's increased worth and price, the team's salary would rise. As previously discussed, adding a talented player such as CP3, would improve the team's overall winning rate, resulting in increased game attendance.

There is no clear outlier in the relationship between payroll and attendance for the Clippers in 2000 – 2018. It is shown that a lower payroll would lead to a lower attendance average percentage, which is demonstrated by the very first point on the graph where in 2001 the team had the lowest payroll at $31 million, and the lowest average attendance at 77%. From looking at the trendline, this point itself could be seen as an outlier. However, in the very next year, the payroll remained moderately the same at a moderate $34 million, just a $3 million increases from last year, but the attendance average shot up by almost 18%, landing at 95% attendance average per game. This is the year the team drafted Elton Brand, who became the second highest paid player on the Clippers Roster, being paid $5.9 million, just short of Michael Olowokandi at $7.1 million. These two players had a huge following, with Elton brand coming off 2 successful seasons from the Chicago Bulls, and with Michael Olowokandi being seen as a top 2 pick in the 1998 draft due to his 7ft 6in wingspan, eventually being drafted as number 1 by the LA Clippers. The two of these players reignited the Clippers fanbase and was the reason why the attendance average shot up by 17%.

## Team Payroll vs Winning Percentage 

To wrap it up, we will see if there is any correlation between payroll and winning percentage. These two variables have both shown a positive correlation with average attendance, and so it will be interesting to see if there is a positive correlation between themselves. 

We are once again able to visualize trends and patterns by creating a graph using the same <a href = "https://github.com/Lawrence-Mak/SportsAnalysis/blob/main/SportsAnalysisDataFile.xlsx"> database </a>
![image](https://user-images.githubusercontent.com/83872954/207116602-6f147daf-a9a6-418f-a4b6-5fe788c20c20.png)

This graph shows the relationship between the LA Clippers team payroll compared to their winning percentages from 2000-2018. It can be observed from this figure that as payroll increases, so does the team’s winning percentage. Similarly, to figures 1 and 2, there is a positive linear trend and correlation between these two factors. However, The R^2 for this graph is 0.2418. This tells us that the level of correlation between the two variables is still relatively low. 

When comparing home game attendance and team salary, this study is similar to the prior one. A greater team payroll results in a higher winning % since better players are a primary contributing reason to higher winning percentages, and higher salaries are required to attract these players. For example, in the 2016-2017 season, Chris Paul, DeAndre Jordan, and Blake Griffin all had salaries of $25,779,687, $23,859,750, and $22,650,611 respectively. Though these numbers were high, these 3 were seen as the core of the team, with strong supporting players like Jamal Crawford, and Austin Rivers with salaries of 13 and 11 million respectively. This team had a win rate of 70%, the highest seen in this decade. Contrasted to the 2006/07 Clippers where the highest paid player being first round pick Elton Brand at 19 million and second highest being Cuttino Mobley being at 10 million, suggested that the Clippers invested into Elton Brand as their star player, who was unfortunately unable to perform as well as before, with his shooting average dropping in 2006/07. Expectedly, this team only had a winning percentage of 49%. 

The 2008/09 Clippers showed one of the lowest win rate percentages of 23%, despite having a reasonable payroll of $55 million. As soon as the team signed Baron Davis, it appeared as though the team was headed in a good place. However, as the trade happened, Elton Brand got traded to Philadelphia and the team was left with Zach Randolph, who was suspended promptly after punching Louis Amundson in the jaw, and so the Clippers were left with no stars on the field. For this season, Alex Acker received the team MVP, despite being paid much less than all the others on the roster, only being paid 711k. Thus, this season can be seen as an outlier in the trend between team payroll vs winning percentages. Although the team payroll was higher than previous seasons, ejections, and trades that left the team without a usable core did not translate to a higher win percentage, consequently resulting in an outlier. 

## Which coefficents have an effect on salary?

In order to find out which coefficients have an effect on player salary, we will be performing a linear regression using a multitude of variables which in theory should be correlated. We will be using data from the 2018-2019 season found in this <a href = "https://github.com/Lawrence-Mak/Sports-Analysis-Case-Study/blob/main/SportsAnalysisData2.xlsx"> database </a>. The regression results and calculations can also be found within the database.

The hypothesis is that all variables should have a positive effect on salary. The variables we will be using are: Career Games, Minutes per Game, Points per Game, Assists per Game, Rebounds per Game, Blocks and Steals per Game, and Field Goal Percentage per Game.

After performing a linear regression, the results show are:
<br> Salary = -1716992.44 + 13831.59CG + 288690.19Min + 156261.79P - 1861952.55A - 282462.01R - 1289671.79BS + 7158822.05FG%

<br> n = 20             Adjusted R^2 = 0.417483185

<br> 𝑤ℎ𝑒𝑟𝑒,
<br> 𝑆𝑎𝑙𝑎𝑟𝑦 = 𝑃𝑙𝑎𝑦𝑒𝑟 𝑠𝑎𝑙𝑎𝑟𝑦 𝑓𝑜𝑟 2018 − 2019
<br> 𝐶𝐺 = 𝐶𝑎𝑟𝑒𝑒𝑟 𝐺𝑎𝑚𝑒𝑠 𝑢𝑝 𝑡𝑜 𝑡ℎ𝑒 𝑠𝑡𝑎𝑟𝑡 𝑜𝑓 2018 − 2019
<br> 𝑀𝑖𝑛 = 𝑀𝑖𝑛𝑢𝑡𝑒𝑠/𝑔𝑎𝑚𝑒 𝑖𝑛 2018 − 2019
<br> 𝑃 = 𝑃𝑜𝑖𝑛𝑡𝑠/𝑔𝑎𝑚𝑒 𝑖𝑛 2018 − 2019
<br> 𝐴 = 𝐴𝑠𝑠𝑖𝑠𝑡𝑠/𝑔𝑎𝑚𝑒 𝑖𝑛 2018 − 2019
<br> 𝑅 = 𝑇𝑜𝑡𝑎𝑙 𝑅𝑒𝑏𝑜𝑢𝑛𝑑𝑠/𝑔𝑎𝑚𝑒 𝑖𝑛 2018 − 2019
<br> 𝐵𝑆 = (𝐵𝑙𝑜𝑐𝑘𝑠 + 𝑆𝑡𝑒𝑎𝑙𝑠)/𝑔𝑎𝑚𝑒 𝑖𝑛 2018 – 2019
<br> 𝐹𝐺% = 𝐹𝑖𝑒𝑙𝑑 𝐺𝑜𝑎𝑙 𝑃𝑒𝑟𝑐𝑒𝑛𝑡𝑎𝑔𝑒 𝑖𝑛 2018 – 2019

#### Coefficient Analysis
I initially believed that all the coefficients should have a positive correlation to salary. However, in the regression results for the LA Clippers in the 2018/2019 season, Assists, Rebounds, and Blocks/Steals had a negative coefficient. This means that when salary goes up, these three variables go down. This was confusing because I assumed that players that were paid more would be able to do it all. 
However, upon investigating further, these negative coefficients made sense. Players who score more are paid more, which is evident through the positive coefficient for points per game, and field goal percentage. The players who specialize in scoring will usually leave the assists, rebounds, and blocks/steals to other teammates. An example is Danilo Gallinari, who was the highest paid player in the 2018/2019 LA Clippers roster. He was almost at the top of the roster in terms of points per game, but only ranked fifth in rebounds, fifth in assists, and eighth in blocks + steals. The only exceptions may be players who strive for triple doubles, such as Russel Westbrook, but on the LA Clippers, there seem to be no outliers.

#### R^2 Analysis
The adjusted R^2 measures the corrected goodness of fit. It identifies the percentage of variance in the model. The Adjusted R^2 I got for the LA Clippers linear model was 0.417483185. This value would mean that the coefficients have a relatively low level of correlation. However, this is probably due to the low sample size and specific salary composition. 

#### Utilizing regression results

Using the regression results, we are able to calculate and see whether a player on the LA Clippers Roster is actually being underpaid or overpaid, depending on their stats and numbers. We are able to calculate their estimated salary using data from the season, and compare it against their actual salary. 
![image](https://user-images.githubusercontent.com/83872954/207121447-bceedea1-c851-483f-aabf-27dab24481cd.png)

#### Adding a new variable to regression

After observing previous regression results, I am interested in adding another variable which should have a postive correlation with salary. I hypothesize that free throws should have a positive correlation with salary. I chose this variable because getting a free throw opportunity means that the player is fouled. I think getting fouled in the NBA is actually really significant because it puts pressure on the enemy team of getting “fouled out” and it also means theres an opportunity to get 1 or 2 additional points. In my thinking, players that get fouled a lot are the best players. The most fouled players are usually the ones who attack the paint often or attract double teams on the perimeter. This means that they are usually the biggest threat on the field according to the other team. An example is 2020-2021 MVP candidate Giannis Antetokounmpo, who was the most fouled player in the season. Furthermore, from the LA Clippers, the top three most fouled players also had the top three points per game. Lou Williams had 5.7 free throws per game, and 20 points per game, Danilo Gallinari had 5.4 FT/Game and 19.8 PPG, and Tobias Harris had 3.5 FT/Game and 20.9 PPG.

After adding free throws, the new regression will look like this:

<br>Salary = - -3285188.35 + 10724.90CG + 773076.62Min - 1192015.37P - 2744074.04A - 48915.93R - 3068938.38BS + 8802751.60FG% + 3966455.09FT

<br>n = 20             Adjusted R^2 = 0.522365013

<br>𝑤ℎ𝑒𝑟𝑒,
<br>𝑆𝑎𝑙𝑎𝑟𝑦 = 𝑃𝑙𝑎𝑦𝑒𝑟 𝑠𝑎𝑙𝑎𝑟𝑦 𝑓𝑜𝑟 2018 − 2019
<br>𝐶𝐺 = 𝐶𝑎𝑟𝑒𝑒𝑟 𝐺𝑎𝑚𝑒𝑠 𝑢𝑝 𝑡𝑜 𝑡ℎ𝑒 𝑠𝑡𝑎𝑟𝑡 𝑜𝑓 2018 − 2019
<br>𝑀𝑖𝑛 = 𝑀𝑖𝑛𝑢𝑡𝑒𝑠/𝑔𝑎𝑚𝑒 𝑖𝑛 2018 − 2019
<br>𝑃 = 𝑃𝑜𝑖𝑛𝑡𝑠/𝑔𝑎𝑚𝑒 𝑖𝑛 2018 − 2019
<br>𝐴 = 𝐴𝑠𝑠𝑖𝑠𝑡𝑠/𝑔𝑎𝑚𝑒 𝑖𝑛 2018 − 2019
<br>𝑅 = 𝑇𝑜𝑡𝑎𝑙 𝑅𝑒𝑏𝑜𝑢𝑛𝑑𝑠/𝑔𝑎𝑚𝑒 𝑖𝑛 2018 − 2019
<br>𝐵𝑆 = (𝐵𝑙𝑜𝑐𝑘𝑠 + 𝑆𝑡𝑒𝑎𝑙𝑠)/𝑔𝑎𝑚𝑒 𝑖𝑛 2018 – 2019
<br>𝐹𝐺% = 𝐹𝑖𝑒𝑙𝑑 𝐺𝑜𝑎𝑙 𝑃𝑒𝑟𝑐𝑒𝑛𝑡𝑎𝑔𝑒 𝑖𝑛 2018 – 2019
<br>FT = Free Throws/Game 𝑖𝑛 2018 – 2019

As predicted, the new variable increased the adjusted R^2 in comparison from my R^2 from problem 1. The new variable is also significant at the 90% confidence interval. As mentioned before, this is expected because the players that are fouled the most on the court are usually either deemed the biggest threat by the other team, like Giannis, or are the most creative in ways of getting extra points, like Steph Curry or James Harden (Before the three-point rule change). Thus, the best players would demand a higher salary. This hypothesis was evident in the data from the 2018-2019 LA Clippers, as the top three players with the most free throws per game also held the record for top three points per game.

### Conclusion

It is important to remember that the correlation between the variables above do not imply causation.

This being said, it is interesting to see the correlation between all the different variables. The regression between winning percentage and average attendance boasted the highest R^2 out of all results, whereas the regression between payroll and average attendance had the lowest level of correlation. 










