# NCAA-data-visualisation-with-d3.js

Parallel coordinates visualisation of basketball team statistics of 2016 NCAA regular season.
Each poly-line corresponds to a team with average performance plotted across 14 unique statistics and a ranking. Data points are rounded to integers in order to make clusters more recognisable.
  
There are two identical charts available, providing one with the possibility to compare how teams with different characteristics (game styles) play against each other.

Brushing and Bundling tools are provided for interaction with the data.

Specific example:

To illustrate the work of this project I put together a specific example. If one would filter chart 1 to include teams with turnover (TO) amount above average, personal fouls(PF) below average and placed them against teams from chart 2, with low turnover amount and high personal foul numbers, the result of the comparison would show chart 1 teams being superior. I found the outcome of this comparison rather surprising, as the winning pattern of teams with greater amount of turnovers and less personal fouls (chart 1) turned out to be significantly greater.

###Resources

####Libraries used
*d3.js*

*d3.parcoords.js*

*divgrid.js*

####Data 

*avg2016stats.csv* - avarege statistic by team.

*rsr2016.csv* - historical data of 2016 NCAA regular season.

Original data was downloaded from [Kaggle.com](https://www.kaggle.com/c/march-machine-learning-mania-2016/data)
March Machine Learning Mania 2016 competition.
