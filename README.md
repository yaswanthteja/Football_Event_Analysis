# Football_Event_Analysis

- [Data Set Link](https://www.kaggle.com/datasets/secareanualin/football-events?resource=download)

This dataset is a result of a very tiresome effort of webscraping and integrating different data sources. The central element is the text commentary. All the events were derived by reverse engineering the text commentary, using regex. Using this, I was able to derive 11 types of events, as well as the main player and secondary player involved in those events and many other statistics. In case I've missed extracting some useful information, you are gladly invited to do so and share your findings. The dataset provides a granular view of 9,074 games, totaling 941,009 events from the biggest 5 European football (soccer) leagues: England, Spain, Germany, Italy, France from 2011/2012 season to 2016/2017 season as of 25.01.2017.
There are games that have been played during these seasons for which I could not collect detailed data. Overall, over 90% of the played games during these seasons have event data.

The dataset is organized in 3 files:

events.csv contains event data about each game. Text commentary was scraped from: bbc.com, espn.com and onefootball.com
ginf.csv - contains metadata and market odds about each game. odds were collected from oddsportal.com
dictionary.txt contains a dictionary with the textual description of each categorical variable coded with integers
Past Research
I have used this data to:

create predictive models for football games in order to bet on football outcomes.
make visualizations about upcoming games
build expected goals models and compare players
Inspiration
There are tons of interesting questions a sports enthusiast can answer with this dataset. For example:

What is the value of a shot? Or what is the probability of a shot being a goal given it's location, shooter, league, assist method, gamestate, number of players on the pitch, time - known as expected goals (xG) models
When are teams more likely to score?
Which teams are the best or sloppiest at holding the lead?
Which teams or players make the best use of set pieces?
In which leagues is the referee more likely to give a card?
How do players compare when they shoot with their week foot versus strong foot? Or which players are ambidextrous?
Identify different styles of plays (shooting from long range vs shooting from the box, crossing the ball vs passing the ball, use of headers)
Which teams have a bias for attacking on a particular flank?
And many many more…
