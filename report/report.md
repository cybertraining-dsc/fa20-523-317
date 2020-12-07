# Big Data Analytics in the National Basketball Association

[![Check Report](https://github.com/cybertraining-dsc/fa20-523-317/workflows/Check%20Report/badge.svg)](https://github.com/cybertraining-dsc/fa20-523-317/actions)
[![Status](https://github.com/cybertraining-dsc/fa20-523-317/workflows/Status/badge.svg)](https://github.com/cybertraining-dsc/fa20-523-317/actions)
Status: Final, Type: Report

- [ ] please follow our template from now on
- [ ] please follow the citation rules and samples we gave, do not invent your own format.
- [ ] citations must be before the "." not after 

Igue Khaleel, [fa20-523-317](https://github.com/cybertraining-dsc/fa20-523-317/), [Edit](https://github.com/cybertraining-dsc/fa20-523-317/blob/master/report/report.md)

{{% pageinfo %}}

## Abstract

The National Basketball Association and the deciding factors in understanding how certain awards such as the MVP (Most Valuable Player) and DPOY (Defensive Player of the Year) are awarded is something that is continuosly researched and predicted. There has been a lot of controversy surrounding this topic as many individuals feel as if storylines and politics are the determinant of who wins these respective awards. In addition to the above another interesting topic that can be investigated is the leagues implementation of analytics to determine the way basketball has been played. Countless examples could be shown through small-ball lineups and the transition to heavy amounts of three-point shot attempts that occurred in the league the past five years. The results have been shown as seemingly every year the league breaks their scoring records and a team always breaks offensive records on a yearly basis.

Contents

{{< table_of_contents >}}

{{% /pageinfo %}}

**Keywords:** basketball, sports, team, mvp, statistics

## 1. Introduction

The National Basketball Association was first created in the year of 1946 with the name of BAA (Basketball Association of America). However, in 1949 the name was changed to the NBA with a total of 17 teams[^1]. As time progressed the league started picking up steam and more and more teams began to join and it wasn’t until the 90’s that we see the total amount of NBA teams be produced.This league consists of professional basketball players from both national and international spaces of the world. As there are 16 roster spots per team and 32 teams in total, only the very most athletic, skillfull, and colossal individuals are chosen to represent this league.  Now, knowing the special skillsets of individual players, the founder of basketball, James Naismith, created positions to maximize these individual players for team success. On the court there are 5 positions : point guard, shooting guard, small forward, power forward, and center[^1].

#### 1.1 Point Guard

Starting with the point guard, generally these individuals are the smallest players on the court with an average height around 6'2 tall. With what these player lack in height they make up for in skillset in terms of quickness, passing, agility, ball handling, and natural shooting ability. Point guards are generally looked at to be the floor general of the team and take up the job of setting up the coach's gameplan and teamates. 

#### 1.2 Shooting Guard

The shooting guard is a generally a slightly taller player than the point guard and like the name suggests they are generally the player known for their indiviualisitc shooting prowess whehter if it is beyond the 3 point line or in the mid-range. Shooting guards are known to be positioned in the perimeter(outside the arc) as a partner to the point guard. On occasion, the role of the shooting guard is expanded in the case that the point guard is pressured so the role may be for the shooting guard to be better at defense or a player that can help in the playmaking duties of the point guard. 

#### 1.3 Small Forward

The small forward is where things change in terms of roles when comparing to the guards of that were previously mentioned above. They can be considered hybrids in the sense that they can both operate on the perimeter like guards and can go down low like power forwards and centers which will be discussed later. Noramlly with wings(another name for small forward) with an average height around 6'7, there are a plethora of responsibilites in order to be considered effective. The reason for this is because generally speaking, small forwards are the most athletic player on the court. They basically have most the agility and ball handling of guards and most of the physicallity and power of power forwards/centers. Understandibly, there are tasked with big defensive assignments and are usually looked at to be a decent to above-average producer on offense. 

#### 1.4 Power Forward

The power forward position is where the physicallity of players matters more. Generally these players are around 6'9 to 6'11 and are heavier than most players. Becuase of this they give up speed and shooting which is why they operate around the free throw line and basket. They are looked at to protect the interior with the center from smaller players and small forwards driving in the lane to the basket.

#### 1.5 Center

The center is considered mostly the point guard of the defense of the team. They are generally the anchor that protects the rim primarily and takes up defensive assignemtns and calls. Without a competent center, a team can see their defense take a hit. Along with defense, centers are good options to go to when the team has offensive lulls since the easiest shot to make in the nba is a hook shot or layup and the center operates 3 feet from the basket. Centers generally range from 6'11 to as high as 7'6 in height. On rare occasions you can see 6'9 to 6'10 centers take the court and that is generally because of play-style or above-average defense.


## 2. Era of Analytics

The National Basketball Association continues to not only grow in the sense of continued personell but an increase of cap(cash flow) amongst teams as well. Within the scope of this prosperous cap situation that the NBA has accumulated over the years through merchandising, tickets, and tv deals, teams have found flexibility in the ability to create the optimal situation for whatever version of basketball the General Manager sees fit for the vision of the team. In terms of better understanding how this can be accomplished it is best to understand what spurred this action of finding styles to lead to the best team success. 

That particular action is players such as Stephen Curry, a 6-3 NBA point guard, that led to the change in utilizing analytics. The year Steph Curry broke through as an MVP, his team; the Golden State Warriors broke the former Chicago Bulls record of 72-9. This in big part was due to Steph Curry breaking the 3pt record as well as Golden State adopting the small ball philosophy. This particular year gave birth to the era of analytics because of how dominate those two approaches were.

#### 3.1 The Houston Rockets

This has then inspired teams to introduce analytics departments to measure ways to beat the game and exploit mismatches in defensive schemes and height within players. An example of a team that spearheaded this change in strategy is the Houston Rockets. Their GM(General Manager) Daryl Morey was a MIT graduate who advocated for a team that primarily shoots three point shots as their main forte[^2]. The science behind this concept was that 33% shooting from the three point line measure to 50% from the two point line respectively. This was in the works in the year of 2017 just two years removed from Steph Curry's three point dominance in his MVP season. In terms of numbers representing the change, the 2018 Houston Rockets attempted approximately 82% of their shot attempts around the three point line and the restricted area(the circle around ~5 feet in diameter surrounding the rim)[^2]. The next best team in that department was eleven percent down at 71% in terms of attempts. In this year, the Rockets won their conference at a record of 65 wins - 17 losses as well as break the NBA record in three pointers attemted and made.

#### 3.2 Tools

In order to evaluate these players and acquire the data necessary for analyization, the NBA partnered with a company name STATS to provide the necessary tools for data collection. STATS worked with the NBA by installing six cameras in each basketball arena in order to, "track player and referee movements at 25 frames per second to get the most analytical data for teams and the NBA to analyze[^3]." This is very effective in terms of showing the play-by-play moves of players in a system as well as even how referees move. With players, these tools can serve as a chess board where the coach is able to watch pieces move and can determine where certain positions could be optimized to its maximum efficiency. This allows for film sessions to be more productive and helpful for players to better see where they fit and even improve in. In terms of referees, throughout sports it is known that referees have cost some games due to missed calls or questionable decisions. This technology can help in terms of understanding: 1) how a specific referee calls certain fouls and 2) if there seems to be a number count of fouls depending on what team the referee is reffing historically. Understanding both the tendencies of players and refs alike gives coaching staffs a direction to go in when preparing for opponents on a game-by-game basis[^3]. 

#### 3.3 Draft Philosophy

Another facet of the game that is likewise impacted by the tools and techniques described in 3.2 is the NBA draft. The NBA draft consists a total of 60 players selected in two rounds combined. The general consensus before this analytics era was to choose the best player avaible most of the time. Teams back then usually drafted big men(e.g. forwards and centers) because it was considered a safe pick and known to help your team better in more areas. As time passed, we've seen a shift to more guards that are drafted instead to fit the narrative the analytics presents to teams regarding the best path to success. For example, earlier Stephen Curry was mentioned to be one of the foundational reasons that the analytics movement was largely adapted. The year Curry got drafted, the #1 pick in the draft was Blake Griffin who at the time was considered the best Power Forward in the draft while Curry was drafted at 8th overall and even James Harden of the Houston Rockets was drafted 3rd[^4]. As we fast forward to 2020, both Curry and Harden are looked at as the two best players from their draft class with Curry revolutionizing the three point shot and Harden being the ultimate analytics player with his ability to manipulate the defense and draw free throws from fouls like no player has ever done. As years passed, there has been a shift in drafting players with the mindset of that particular players' potential over fit in the sense that teams look for the best available player that fits the teams system the most efficiently[^4]. An example is the upcoming 2020 NBA draft where there is a question of who will become the #1 and 2 pick respectively. The Golden State Warriors have the 2nd pick in the draft because of a year of injuries for all of their star players. So, they typically aren't looking for a player like most losing teams are doing in the draft. In the eyes of many scouts, some view a player like Lamelo Ball, a 6'7 point guard as the best player or at least second best and others see players like Anthony Edwards(SG), James Wiseman(C) and Deni Advija(SG) as potentially better fits and safer picks. However, for the warriors rumors over social media from notable sources have shown that they aren't interested in drafting Lamelo Ball as he is a point guard and they have Steph Curry already. They instead prefer to choose a Small Forward or Center that can help their defensive potential and style of play. Years ago, that may not have been the case as the best player available would usually come off the board and the team would figure it out after that. Thus, this shows how analytics has not only persuaded teams to change their play styles and system but also the players that come with it whether they are veterans or incoming rookies.

## 4. Background Work and Advanced Analytics in Basketball

Considering how the impacts of how implemented analytics has aided the NBA atmosphere as mentioned above, we look to learn technologies and work that help bring this about. This begins with camera systems that have been implemented by a company named SportVU who've helped bring about change in NBA arenas since 2013 that track player and basketball movement across the arenas[^5]. This system goes further in the analysis of collecting data in the context of individual player statistics being captured as well as their positioning on the court and speed in particular instances.

Thus by capturing the basic statistics such as points, assists, rebounds, steals and blocks. Analytical tools such as Player Efficiency Ratings and Defensive Metrics were better used to analyze players and their individualistic impacts on the basketball court. The impacts of these analytical/computational metrics are represented in many organizations abilities to understand the scope of player's salaries and positioning on the court, who to draft, and helps sports analyst on TV shows such as FS1 and ESPN to easily break down the game of Basketball. 

This is where algorithims come to play as an algorithim needs a dataset from which it can train itself and develop statistical patterns to help in predictive analysis and representation for coaches and teams to utilize respectively. An example of this is show through students named Panna Felsen and Lucy from the University of California Berkely, who are developing a software name Bhostgusters that helped analyze the body positions of players and further the response and movements of a team to certain plays run by the opposition[^5]. The end goal of this for coaches to be able to draw up a play on a tablet and see potential conflicts, results, and how opponents may counteract that particular play.

Other technologies that are being developed and implemented are things like, CourtVision, which is technology that shows the statistics of a player making a shot based on that players' past statistics and position on the court. As the player is moving through the court the numbers change to reflect his efficiency on certain areas on the court based on this. As stated by Marcus Woo, the author of this article, these technologies aren't meant to replace the systems in place but instead are there the help in efficiency and effectiveness[^5]. 

## 5. Algorithims associated with NBA

When it comes to the variety of algorithims used in the National Basketball Association, we will be analyzing
the range of algorithims discussed through articles and papers on google scholar. We looked at a total of five
algorithims that were commonolu shown to be used of the most searches when it came to predictive and learning
analysis within NBA analytics departements and outside agencies. The algorithims as presented are: K-means,
Artificial Neural Networks, Linear Regression, Logistic Regression, and Support Vector Machines. Linear
Progression was by far the most written on topic within the five algorithims listed above with a total of 11,000
searches. It is followed by the Support Vector Machines with 5,240, Logistic Regression with 4,500, Artificial
Neural Networks with 4,300, and K-Means with 1,590 search results(*all results via google scholar search bar).

#### 5.1 K-Means

The first algorithim we'll look at is K-Means which is classified as generally the "clustering algorithim" which takes the form of initializing a single point of k or the mean and organizing the data towards that particular mean[^7]. This is then repeated over and over until the appropriate results are found and compiled. Now as National Basketball Association statistics are inserted this can be used to cluster players together than fit the criteria on certain outcomes of points, rebounds, assists, and blocks. 

#### 5.2 Linear Regression

Linear Regression, which is very commonly used in machine learning is very effective as a predictor tool. It works by forming "regression coefficients" that stems from pitting together independent variables which help in predictions within a game[^7]. So, throught the input and output variables taht are presented predictive measurements can be performed to highlight potential productivety. An example is the "Box-Plus-Minus". This was created to show a basketball player's overall court production and effect through their statistics, what position they play on the court and the wins and losses that team incurs because of this[^8]. This was built through linear regression and shows through charts based on statistics how productive a player is or potentially can be given the system and oppurtunities.

#### 5.3 Logistic Regression

Similarly to Linear Regression, Logistic Regression shares a lot of feautures in terms of the formula used for prediction except it utilizes a sigmoid as opposed to a linear function when performing calculations. Weight values are the main form of predictions in whatever form of scenario or situation in which that analyst wants to produce[^7]. An example of this is shown through a logistical regression analysis performed by Oklahoma State University on clutch and non-clutch shots by NBA players. The premise of this is taking the data of an individual player based on their shooting percentages in spots on the floor relative to the distance of the defender on them and using that to figure out the potential of a player making a shot in the clutch(universally known as the last 2 minutes in a close game)[^9]. This then shows how a predictive algorithim can be utilized not only based on solely percentages and efficiences but also with the inclusion of situation on a basketball floor.  

#### 5.4 Support Vector Machines

Support Vector Machines are considered to be a very formidable tool when it comes to measuring classification issues. This modeled machine creates a decision-making tree that helps in the predictions of basketball games and thus can help coaches form strategies and gameplans around what the model predicts can happen. Additional advantages that come with this tool is its ability to operate in high dimensions, the ability to identify kernels, and its memory efficiency[^11]. The minor issue with this machine is the lack of rule generation but as it is more of an emerging tool overtime this is something that is relatively fixable[^12]. The advantages 

#### 5.5 Artificial Neural Networks

With Artificial Neural Networks the use of the Multi-Layer Perceptron is prevalent and it is highlighted by the vertices of a group in correlation to input varables and comes out with the output[^11]. This tool according the Beckler is also considered to be, "an adaptive system that changes its structure based on external and internal information flows during the network training phase[^7]. With this, the Artificial Neural Network is considered to be one of the most accurate predictive tools when it comes to basketball and can predict patterns as more data is inputed[^11].

## 6. Conclusion

As time progresses, we will continue to see the use of analytics as well as the expanision of analytics departments in not only the National Basketball Association but other professional sports as well. The impacts of analytics have been highlighted through recent years as mentioned above with the change to styles of play, and the way coaches approach gameplans before each respective game is played. As Adam Silver, the commissioner of the National Basketball Association stated, "Analytics have become front and center with precisely when players are rested, how many minutes they get, who they’re matched up against[^6]." Through this, Silver explains not only to technical aspect of basketball that analytics supports but the physical aspect which can aid in preventing things like player injuries and rest. Understandibly, this highlights how analytics can help the league now and in the future; especially when more sophisticated machine learning tools and algorithims are produced for this purpose.
 
## 7. Acknowledgment

The author would like to thank Dr. Gregor von Laszewski, Dr. Geoffrey Fox, and the associate instructors in the *FA20-BL-ENGR-E534-11530: Big Data Applications* course (offered in the Fall 2020 semester at Indiana University, Bloomington) for their continued assistance and suggestions with regard to exploring this idea and also for their aid with preparing the various drafts of this article.


## 8. References

[^1]: Online, N., 2020. NBA History. [online] Nbahoopsonline.com. Available at: <https://nbahoopsonline.com/History/#:~:text=The%20NBA%20began%20life%20as,start%20of%20the%20next%20season>. [ Accessed 20 October 2020].

[^2]: Editor, M., 2020. How NBA Analytics Is Changing Basketball | Merrimack College. [online] Merrimack College Data Science Degrees. Available at: <https://onlinedsa.merrimack.edu/nba-analytics-changing-basketball/> [Accessed 16 November 2020].

[^3]: N. M. Abbas, "NBA Data Analytics: Changing the Game," Medium, 21-Aug-2019. [Online]. Available: <https://towardsdatascience.com/nba-data-analytics-changing-the-game-a9ad59d1f116>. [Accessed: 17-Nov-2020]. 

[^4]: C. Ford, "NBA Draft 2009," ESPN. [Online]. Available: <http://www.espn.com/nba/draft2009/index?topId=4279081>. [Accessed: 17-Nov-2020]. 

[^5]: M. Woo, "Artificial Intelligence in NBA Basketball," Inside Science, 21-Dec-2018. [Online]. Available: <https://insidescience.org/news/artificial-intelligence-nba-basketball>. [Accessed: 07-Dec-2020]. 

[^6]: 2017 A. S. M. N. A. Jun 01, "The NBA's Adam Silver: How Analytics Is Transforming Basketball," Knowledge@Wharton. [Online]. Available: <https://knowledge.wharton.upenn.edu/article/nbas-adam-silver-analytics-transforming-basketball/>. [Accessed: 07-Dec-2020]. 

[^7]: M. Beckler and M. Papamichael, "NBA Oracle," 10701 Report, 2008. [Online]. Available:<https://www.mbeckler.org/coursework/2008-2009/10701_report.pdf>. [Accessed: 06-Dec-2020].  

[^8]: R. Anderson, "NBA Data Analysis Using Python &amp; Machine Learning," Medium, 02-Sep-2020. [Online]. Available: <https://randerson112358.medium.com/nba-data-analysis-exploration-9293f311e0e8>. [Accessed: 07-Dec-2020]. 

[^9]: J. P. Hwang, "Learn linear regression using scikit-learn and NBA data: Data science with sports," Medium, 18-Sep-2020. [Online]. Available: <https://towardsdatascience.com/learn-linear-regression-using-scikit-learn-and-nba-data-data-science-with-sports-9908b0f6a031>. [Accessed: 07-Dec-2020]. 

[^10]: L. Edmunds, "How Can an NBA Player Be Clutch?: A Logistic Regression Analysis," Mwsug, 2017. [Online]. Available: <https://www.mwsug.org/proceedings/2017/AA/MWSUG-2017-AA13.pdf>. [Accessed: 06-Dec-2020]. 

[^11]: J. Perricone, I. Shaw, and W. Swie¸chowicz, "Predicting Results for Professional Basketball Using NBA API Data," Stanford.edu, 2016. [Online]. Available: <http://cs229.stanford.edu/proj2016/report/PerriconeShawSwiechowicz-PredictingResultsforProfessionalBasketballUsingNBAAPIData.pdf>. [Accessed: 06-Dec-2020]. 

[^12]: A. P. B. N. Barakat, J. H. F. L. Breiman, M. T. R. Burbidge, K.-S. S. T. Chen, J. L. R. WW. Cooper, V. N. V. C. Cortes, E. F. M. Hall, J. Holland, R. C. E. J. Kennedy, K. J. Kim, K. H. T. K. Kirchner, J. S. S. P. Kvan, A. C. W. BL. Lee, B. B. D. Martens, J. Mercer, J. K. B. Min, O. B. K. Muata, J. S. L. IS. Oh, P. M. M. M. Pal, J. R. Quinlan, F. P.-C. FJR. Ruiz, W. H. C. JY. Shih, H. M. E. I.-D. MBA. Snousy, P. V. E. Štrumbelj, L. C. FEH. Tay, V. V. S. S. Tripathi, G. Valentini, V. N. Vapnik, G. D. N. Vlastakis, J. N. Wang, E. Y. K. A. Widodo, C. F. H. TA. Zak, and J. S. J. Zhou, "Analyzing basketball games by a support vector machines with decision tree model," Neural Computing and Applications, 01-Jan-1970. [Online]. Available: <https://link.springer.com/article/10.1007/s00521-016-2321-9>. [Accessed: 07-Dec-2020]. 


