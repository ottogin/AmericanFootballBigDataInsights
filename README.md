# American Footbal Big Data Insights
How many yards will an NFL player gain after receiving a handoff?

# Abstract
Sport data always contains a lot of very interesting insights. Having been inspired by [Sheldon Cooper](https://youtu.be/XfYI8ILGuv0?t=28) we decided to find out what helps professional sport players win.
American football is a complex sport and defintely contains many secrets to discover for data scientists.
Deeper insight about what is important and what is not will help teams, media, and fans better understand the game, and for coaches to find better strategies. 

As good data scientists we are going to start discovering the data with nice visualizations. Looking at players positions, understanding coach strategies and team statistics will hopefully give us surprising ideas. As a model task we will use our insights to predict how many yards will an NFL player gain after receiving a handoff.


# Research questions
* Which parameters of team, tactics and environment really affect the result of the game?
* How these parameters are connected with each other? For example, do the temperature and wind speed affect player speed?
* How to build perfect American Football team?
* What is the best data representation of in-game situation to analyze and build ML models upon it?
* Which model is the best to predict the result of the play?
* Was Sheldon Cooper right? ;)

# Dataset
The data is provided by the running [Kaggle competition](https://www.kaggle.com/c/nfl-big-data-bowl-2020/data) and presented in tabular data containing 509762 rows and 49 columns. Each line is a time-stamp of one of the players for one of the 512 games. For each time-stamp we know player position and even orientation he looks at, we also know what wether it was, so there is a really huge space for interesting correlations!

# A list of internal milestones up until project milestone 2

To 11.11:
* Learn rules of American Football
* Explore dataset and clear it if needed
* Create simple initial visualizations (like histograms of features)
* Analyze initial visualizations and try to find something unusual in data

To 18.11:
* Using prevous results, try to find some more deeper connections between features and visualize it
* Try to understand which parameters really affect result of a game and criteria of good team for American Football
* Investigate possible data representations and feature engineering

To 25.11:
* Use insights from previous analysis to build model which predicts how many yard player will gain after handoff and submit results to kaggle
* Prepare a report

# Questions for TAa
* What tools you can advise for building video-visualisations for time-series?
