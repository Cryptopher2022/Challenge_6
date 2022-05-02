# Challenge 6 - Real Estate Analysis for the San Francisco, CA area

Having obtained 3 pertinent data sets, this program sets a process for analyzing both Sales Price per square foot and Gross rents (for rentals) segregated by neighborhood.  

The major tasks to be completed are:

1. *Calculate and plot the housing units per year.*

2. *Calculate and plot the average prices per square foot.*

3. *Compare the average prices by neighborhood.*

4. *Build an interactive neighborhood map.*

5. *Compose your data story.*

Evaluating the potential for market dislocations that lead to attractive investment opportunities is the goal.  In the balance is the question, "Should your company spend the time and resources to build a 'one-button' app that can buy (and presumably sell) rental properties that can generate attractive returns; both from the rents charged to the all-in returns (typically calculated as internal rate of return - IRR to take into account the time element).  

Having the data separated by neighborhood provides the advantage of looking at the trends for gross rents and for sales price per square foot on a more granular level. 

---

## Technologies

The program is written in Python and several libraries are employed to assist in the evaluation both numerically and visually.  These are:

1. import pandas as pd

The pandas library is one of the most used libraries for financial analysis and calculations.  Reference material can be found at:

(https://pandas.pydata.org/)

2. import hvplot.pandas

hvplot is associated with pandas and allows numerous visualizations of the data generated using pandas libraries.  Reference material can be found at:

(https://hvplot.holoviz.org//)

3. from pathlib import Path

The Path function found within the pathlib library allows us to create dataframes and pull in external data sets and the like.  Reference material can be found at:

(https://docs.python.org/3/library/pathlib.html/)

---

## Installation Guide

Navigate to the folder where the program resides with Git Bash or Terminal and when in the highest parent directory call Jupyter Lab and continue navigating to the file named:

san_francisco_housing.ipynb

Working with Jupyter Lab and your terminal/git bash and your browser is all found in these sets of instructions:

(https://jupyterlab.readthedocs.io/en/stable/getting_started/starting.html)


---

## Usage

Below you'll see the tables and plots and charts available when using the libraries described above:

In this Chart 1 - you'll see the aggregate across the region for gross rents and sales prices/square foot.  The trend is clearly steeper for rentals than for sales prices.  

![Chart 1](../Challenge_6/Images/Chart_1_gross.png)

In Chart 2 - we use a very cool interactive chart that will allow the user to select which neighborhood they'd like to see for rental and sales data.  

![Chart2](../Challenge_6/Images/Chart_2_by_neighborhood.png)

In Chart 3 - the individual neighborhoods have been analyzed as if they were a stock or crypto, using the percent change from one period to the next.  When you graph a 5 year period for each neighborhood, the results appear not so convincing.  

![Chart3](../Challenge_6/Images/Chart_3_individual_pct_change.png)

These somewhat conflicting data visualizations give cause to dig deeper.  The interim conclusion is that the app should be built using data that provides a clear cut answer to the user.  

---

## Contributors

Christopher Todd Garner

---

## License

You may use this program as you choose as long as you site the contributors and the name of the program and it's location as a source reference.  
