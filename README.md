[<img src='https://community.drivendata.org/uploads/default/optimized/1X/e055d38472b1ae95f54110375180ceb4449c026b_1_690x111.png'>](https://www.drivendata.org/)
<br><br>

![Banner Image](https://s3.amazonaws.com/drivendata-public-assets/banner.jpg)

# Random Walk of the Penguins
## Goal of the Competition
Data on penguin populations are limited because most monitored colonies are near permanent research stations and other sites are surveyed only sporadically. Because the data are so patchy, and time series relatively short, it has been difficult to build statistical models that can explain past dynamics or provide reliable future predictions.

Your goal is to create better models to estimate populations for hard-to-reach sites in the Antarctic, and thereby greatly improve our ability to use penguins to monitor the health of the Southern Ocean!

## What's in this Repository
This repository contains code volunteered from leading competitors in the [Random Walk of the Penguins](https://www.drivendata.org/competitions/47/penguins/) DrivenData challenge.

#### Winning code for other DrivenData competitions is available in the [competition-winners repository](https://github.com/drivendataorg/competition-winners).


## Winning Submissions

Place |Team or User | Public Score | Private Score | Summary of Model
--- | --- | --- | --- | --- 
1 | ulery | 3.0239 | 2.9415 | I limited myself to using ordinary least squares regression. I spent a lot of time visualizing the data to understand what was going on, get an intuitive sense for pattern vs. noise, and to select some thresholds.
2 | lz01 | 3.0436 | 2.9694 | I used a random forest algorithm, with some feature engineering. I used only microclimtate data when it was available and macroclimate data from guelmim when it was not.
3 | oliviers | 3.0514 | 2.9723 | I made a program which allows to easily build some "mini models" which use only a part of the data and different aggregation techniques, and then choose the best performing "mini model" for each line of the submission.

#### Interview with winners: [Random Walk of the Penguins - Guest Post by Dr. Grant Humphries](http://drivendata.co/blog/random-walk-of-the-penguins/)

#### Benchmark Blog Post: ["Simple Linear Models"](http://drivendata.co/2017/04/28/penguins-benchmark/)
