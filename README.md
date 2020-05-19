# four_factors

## Introduction

The purpose of this paper is twofold. The first is to introduce and visualize historical changes of [Dean Oliver's](http://www.basketballonpaper.com/)["Four Factors of Basketball Success in the NBA"](https://www.basketball-reference.com/about/factors.html). The second is to use these four factors to create models to predict wins, margin of victory, and net rating for different NBA teams.

## What's In This Repository?

#### Report
  * thesis.pdf
  * thesis.zip
      * main.tex
      * images
      
#### Notebooks
  * modeling.ipynb <br>
  * visualizations.ipynb <br>
  * basketball_reference_scraping.ipynb <br>

#### Datasets 
  * per_100_posessions_historical.xlsx
  * four_factors_20xx_to_20xx.xlsx
  * four_factors_all_seasons.xlsx

#### Figures
  * Historical changes
      * eFG.png <br>
      * TOV.png <br>
      * OREB.png <br>
      * FTF.png <br>
  * Modeling

## Python Libraries Used

#### Data Scraping


#### Data Processing
[NumPy](https://numpy.org/)<br>
[Pandas](https://pandas.pydata.org/) 

#### Data Visualization
[Matplotlib](https://matplotlib.org/)<br>
[Seaborn](https://seaborn.pydata.org/) 

#### Machine Learning
[Sci-kit learn](https://scikit-learn.org/stable/)

## Models Used

[Multiple Linear Regression](https://faculty.marshall.usc.edu/gareth-james/ISL/ISLR%20Seventh%20Printing.pdf#page=83)<br>
[Random Forest](https://faculty.marshall.usc.edu/gareth-james/ISL/ISLR%20Seventh%20Printing.pdf#page=328) (upcoming) <br>
[Gradient Boosting](https://web.stanford.edu/~hastie/Papers/ESLII.pdf#page=378) (upcoming) 

## Additional Resources

[An Introduction to Statistical Learning: with Applications in R](https://faculty.marshall.usc.edu/gareth-james/ISL/ISLR%20Seventh%20Printing.pdf)<br>
* Resource for understanding statistical learning models

[The Elements of Statistical Learning](https://web.stanford.edu/~hastie/Papers/ESLII.pdf)<br>
* Resource for understanding statistical learning models in greater depth

[Basketball Reference](www.basketball-reference.com)
* Resource for obtaining NBA data
