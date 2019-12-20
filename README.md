# Info for Milestone 3

## The results are formulated in our [DataStory](https://ottogin.github.io)
Reserve link for the datastory: https://ottogin.github.io

## Code
All data analysis is in the notebook DataExploration.ipynb. We use plotly for some visualizations, so the best way to look at our work without downloading and running it is to open this notebook with nbviewer: [https://nbviewer.jupyter.org/github/ottogin/AmericanFootballBigDataInsights/blob/master/DataExploration.ipynb](https://nbviewer.jupyter.org/github/ottogin/AmericanFootballBigDataInsights/blob/master/DataExploration.ipynb) (Downloading and opening without running will also hide some important visualizations, so please use nbviewer, sorry for inconvience (plotly plots are just so beautiful ;))).

## Contribution
* Fedor: part of data cleaning, story about geography of games and players, feature importances from LightGBM
* Artem: part of data cleaning, Sheldon's story, frontend
* Davit: a lot of text writing and checking, some initial data analysis, story about players' weights, positions etc
* Oganes: story about tactics, a lot of visualizations, part of states' story, different experiments.

Despite the roles described above, we constantly helped each other in working on different tasks. In our opinion, we all contributed equally to this project.

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
