# four_factors

_"All models are wrong, but some are useful."_ - George E.P. Box

## Introduction

This research intends to:


1) Introduce [Dean Oliver's](http://www.basketballonpaper.com/)[ "Four Factors of Basketball Success in the NBA"](https://www.basketball-reference.com/about/factors.html) and test if the four factors are statistically significant predictors of success in the NBA
2) Use the four factors to predict a team's number of wins and average margin of victory in the NBA using historical data and various machine learning models 
3) Compare the observed weightings of the different factors in our models to those proposed by Dean Oliver and Ed Küpfer.

## What's In This Repository?

#### Report
  * thesis_draft.pdf
  * thesis_draft.zip
      * main.tex
      * images
      
#### Notebooks
  * Modeling Oliver’s Four Factors.pdf <br>
  * R_four_factors.Rmd <br>
  * basketball_reference_scraping.ipynb <br>
  * historical_changes_visualizations.ipynb <br>
  * modeling.ipynb <br>

#### Datasets 
  * per_100_posessions_historical.xlsx
  * four_factors_20xx_to_20xx.xlsx
  * four_factors_all_seasons.xlsx

#### Figures


## Python Libraries Used

#### Data Processing
[NumPy](https://numpy.org/)<br>
[Pandas](https://pandas.pydata.org/)<br>

#### Data Visualization
[matplotlib](https://matplotlib.org/)<br>
[seaborn](https://seaborn.pydata.org/)<br>

#### Machine Learning
[Scikit-Learn](https://scikit-learn.org/stable/)<br>
[Statsmodels](https://www.statsmodels.org/dev/index.html)<br>

## R Libraries Used

#### Analysis
[sjstats](https://cran.r-project.org/web/packages/sjstata/index.html)<br>

#### Data Processing
[dplyr](https://cran.r-project.org/web/packages/dplyr/index.html)<br>
[readxl](https://cran.r-project.org/web/packages/readxl/index.html)<br>
[tidyr](https://cran.r-project.org/web/packages/tidyr/index.html)<br>

#### Data Visualization
[corrplot](https://cran.r-project.org/web/packages/corrplot/index.html)<br>
[GGally](https://cran.r-project.org/web/packages/GGally/index.html)<br>
[ggplot2](https://cran.r-project.org/web/packages/ggplot2/index.html)<br>
[plotly](https://cran.r-project.org/web/packages/plotly/index.html)<br>
[scales](https://cran.r-project.org/web/packages/scales/index.html)<br>
[viridis](https://cran.r-project.org/web/packages/viridis/index.html)<br>

#### Machine Learning
[car](https://cran.r-project.org/web/packages/car/index.html)<br>
[caret](https://cran.r-project.org/web/packages/caret/index.html)<br>
[gbm](https://cran.r-project.org/web/packages/gbm/index.html)<br>
[randomforest](https://cran.r-project.org/web/packages/randomforest/index.html)<br>

## Models Used

[Multiple Linear Regression](https://faculty.marshall.usc.edu/gareth-james/ISL/ISLR%20Seventh%20Printing.pdf#page=83)<br>
[Random Forest](https://faculty.marshall.usc.edu/gareth-james/ISL/ISLR%20Seventh%20Printing.pdf#page=328)<br>
[Gradient Boosting](https://web.stanford.edu/~hastie/Papers/ESLII.pdf#page=378)<br>
[Neural Network](https://web.stanford.edu/~hastie/Papers/ESLII.pdf#page=411) (future work)

## Additional Resources

[An Introduction to Statistical Learning: with Applications in R](https://faculty.marshall.usc.edu/gareth-james/ISL/ISLR%20Seventh%20Printing.pdf)<br>
* Resource for understanding statistical learning models

[The Elements of Statistical Learning](https://web.stanford.edu/~hastie/Papers/ESLII.pdf)<br>
* Resource for understanding statistical learning models in greater depth

[Basketball Reference](www.basketball-reference.com)
* Resource for obtaining NBA data
