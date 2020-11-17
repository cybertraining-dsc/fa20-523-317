# Big Data Analytics in the National Basketball Association

[![Check Report](https://github.com/cybertraining-dsc/fa20-523-317/workflows/Check%20Report/badge.svg)](https://github.com/cybertraining-dsc/fa20-523-317/actions)

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

The National Basketball Association was first created in the year of 1946 with the name of BAA (Basketball Association of America). However, in 1949 the name was changed to the NBA with a total of 17 teams[^1]. As time progressed the league started picking up steam and more and more teams began to join and it wasn’t until the 90’s that we see the total amount of NBA teams be produced.This league consists of professional basketball players from both national and international spaces of the world. As there are 16 roster spots per team and 32 teams in total, only the very most athletic, skillfull, and colossal individuals are chosen to represent this league.  Now, knowing the special skillsets of individual players, the founder of basketball, James Naismith, created positions to maximize these individual players for team success. On the court there are 5 positions : point guard, shooting guard, small forward, power forward, and center. 
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

## 2. Background Research and Work

In terms of Background work in this topic area it is very generalized. There are a lot of sources of analysis by individuals on what the NBA is doing in terms of implementing analytics to improved the efficiency of gameplanning and gameplay alike. The differences in the work are the approaches used to come to a judgement on how the NBA could best use analytics as well as different perspectives on how analytics changed the landscape of the league.

## 3. Era of Analytics

The National Basketball Association continues to not only grow in the sense of continued personell but an increase of cap(cash flow) amongst teams as well. Within the scope of this prosperous cap situation that the NBA has accumulated over the years through merchandising, tickets, and tv deals, teams have found flexibility in the ability to create the optimal situation for whatever version of basketball the General Manager sees fit for the vision of the team. In terms of better understanding how this can be accomplished it is best to understand what spurred this action of finding styles to lead to the best team success. 

That particular action is players such as Stephen Curry, a 6-3 NBA point guard, that led to the change in utilizing analytics. The year Steph Curry broke through as an MVP, his team; the Golden State Warriors broke the former Chicago Bulls record of 72-9. This in big part was due to Steph Curry breaking the 3pt record as well as Golden State adopting the small ball philosophy. This particular year gave birth to the era of analytics because of how dominate those two approaches were.

#### 3.1 The Houston Rockets
This has then inspired teams to introduce analytics departments to measure ways to beat the game and exploit mismatches in defensive schemes and height within players. An example of a team that spearheaded this change in strategy is the Houston Rockets. Their GM(General Manager) Daryl Morey was a MIT graduate who advocated for a team that primarily shoots three point shots as their main forte[^2]. The science behind this concept was that 33% shooting from the three point line measure to 50% from the two point line respectively. This was in the works in the year of 2017 just two years removed from Steph Curry's three point dominance in his MVP season. In terms of numbers representing the change, the 2018 Houston Rockets attempted approximately 82% of their shot attempts around the three point line and the restricted area(the circle around ~5 feet in diameter surrounding the rim)[^2]. The next best team in that department was eleven percent down at 71% in terms of attempts. In this year, the Rockets won their conference at a record of 65 wins - 17 losses as well as break the NBA record in three pointers attemted and made.

#### 3.2 Tools
In order to evaluate these players and acquire the data necessary for analyization, the NBA partnered with a company name STATS to provide the necessary tools for data collection. STATS worked with the NBA by installing six cameras in each basketball arena in order to, "track player and referee movements at 25 frames per second to get the most analytical data for teams and the NBA to analyze[^3]." This is very effective in terms of showing the play-by-play moves of players in a system as well as even how referees move. With players, these tools can serve as a chess board where the coach is able to watch pieces move and can determine where certain positions could be optimized to its maximum efficiency. This allows for film sessions to be more productive and helpful for players to better see where they fit and even improve in. In terms of referees, throughout sports it is known that referees have cost some games due to missed calls or questionable decisions. This technology can help in terms of understanding: 1) how a specific referee calls certain fouls and 2) if there seems to be a number count of fouls depending on what team the referee is reffing historically. Understanding both the tendencies of players and refs alike gives coaching staffs a direction to go in when preparing for opponents on a game-by-game basis. 

#### 3.3 Draft Philosophy
Another facet of the game that is likewise impacted by the tools and techniques described in 3.2 is the NBA draft. The NBA draft consists a total of 60 players selected in two rounds combined. The general consensus before this analytics era was to choose the best player avaible most of the time. Teams back then usually drafted big men(e.g. forwards and centers) because it was considered a safe pick and known to help your team better in more areas. As time passed, we've seen a shift to more guards that are drafted instead to fit the narrative the analytics presents to teams regarding the best path to success. For example, earlier Stephen Curry was mentioned to be one of the foundational reasons that the analytics movement was largely adapted. The year Curry got drafted, the #1 pick in the draft was Blake Griffin who at the time was considered the best Power Forward in the draft while Curry was drafted at 8th overall and even James Harden of the Houston Rockets was drafted 3rd[^4]. As we fast forward to 2020, both Curry and Harden are looked at as the two best players from their draft class with Curry revolutionizing the three point shot and Harden being the ultimate analytics player with his ability to manipulate the defense and draw free throws from fouls like no player has ever done. As years passed, there has been a shift in drafting players with the mindset of that particular players' potential over fit in the sense that teams look for the best available player that fits the teams system the most efficiently[^4]. An example is the upcoming 2020 NBA draft where there is a question of who will become the #1 and 2 pick respectively. The Golden State Warriors have the 2nd pick in the draft because of a year of injuries for all of their star players. So, they typically aren't looking for a player like most losing teams are doing in the draft. In the eyes of many scouts, some view a player like Lamelo Ball, a 6'7 point guard as the best player or at least second best and others see players like Anthony Edwards(SG), James Wiseman(C) and Deni Advija(SG) as potentially better fits and safer picks. However, for the warriors rumors over social media from notable sources have shown that they aren't interested in drafting Lamelo Ball as he is a point guard and they have Steph Curry already. They instead prefer to choose a Small Forward or Center that can help their defensive potential and style of play. Years ago, that may not have been the case as the best player available would usually come off the board and the team would figure it out after that. Thus, this shows how analytics has not only persuaded teams to change their play styles and system but also the players that come with it whether they are veterans or incoming rookies.

## 4. Styles of Play


The National Basketball Association was first created in the year of 1946 with the name of BAA (Basketball Association of America). However, in 1949 the name was changed to the NBA with a total of 17 teams[^3]. As time progressed the league started picking up steam and more and more teams began to join and it wasn’t until the 90’s that we see the total amount of NBA teams be produced.

To better understand the basis of analysis, the game of basketball needs to be understood first. The National Basketball Association builds its organizations on the backs of mostly 20-year-old individuals who are standouts at their respective regions of the United States. Making the NBA is nearly an impossible feat as only a minor 60 players get drafted on a yearly basis. In terms of the draft, most individuals are screened and selected from college. Previously, the NBA allowed individuals to come straight from high school, however, the rule changed so that there was a one year of college eligibility status that had to be met.

When it comes to on-court play, there are a total of five positions: point guard, shooting guard, small forward, power forward and center. Each takes up a specific spot on the floor with the guards at around the three-point line and the forwards and center inside or surrounding the paint.

At this moment the current dataset that I’m utilizing consists of all NBA players and certain statistics of theirs dating back to 1950’s when stats were starting to get recorded. However, I feel as if another data set would be necessary to quantify the impacts of what the three-pointer and positional basketball has done for basketball. 

My plan is to take the data and demonstrate through bars and graphs the impacts of these changes from the modern NBA to the classic NBA and the differences that were shown through that. Using Notebook might be needed to get all the data visualized for the report.


## 5. Inference

This section will be addressed upon project completion.

## 6. Conclusion

This section will be addressed upon project completion.

## 7. Acknowledgment

The author would like to thank Dr. Gregor Von Laszewski, Dr. Geoffrey Fox, and the associate instructors in the *FA20-BL-ENGR-E534-11530: Big Data Applications* course (offered in the Fall 2020 semester at Indiana University, Bloomington) for their continued assistance and suggestions with regard to exploring this idea and also for their aid with preparing the various drafts of this article.


## 8. References


[^1]: Online, N., 2020. NBA History. [online] Nbahoopsonline.com. Available at: <https://nbahoopsonline.com/History/#:~:text=The%20NBA%20began%20life%20as,start%20of%20the%20next%20season>. [ Accessed 20 October 2020].

[^2]: Editor, M., 2020. How NBA Analytics Is Changing Basketball | Merrimack College. [online] Merrimack College Data Science Degrees. Available at: <https://onlinedsa.merrimack.edu/nba-analytics-changing-basketball/> [Accessed 16 November 2020].

[^3]: N. M. Abbas, “NBA Data Analytics: Changing the Game,” Medium, 21-Aug-2019. [Online]. Available: https://towardsdatascience.com/nba-data-analytics-changing-the-game-a9ad59d1f116. [Accessed: 17-Nov-2020]. 

[^4]: C. Ford, “NBA Draft 2009,” ESPN. [Online]. Available: http://www.espn.com/nba/draft2009/index?topId=4279081. [Accessed: 17-Nov-2020]. 

## Plan of Action

- [ ] delete befor e final submission

-	Describing the NBA game

There are many individuals who may be aware of basketball but not knowledgeable enough to understand my report. So, I’ll give a little background on the NBA game and how things have transpired in generations.

-	Describing Analytics Impacts

As stated earlier above, I talked about certain points in how certain changes due to analytics have enhanced the game of basketball and how this was spurred through the Golden State Warriors.

-	Demonstrating the Data

To show the impacts of the data, I was planning to compile the data from the different datasets and demonstrate them in graphs and bars for readers to better understand the message I’m trying to display.




