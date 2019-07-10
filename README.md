Data source: All data was readily available for use through the website "Kaggle".
Data description: data1 is a list of meteoritic reviews for 1000+games, as well as its user score and platform.
data2 lists off the total sales for each game, cataloging several hundred games. The data may be outdated, however.
data3 contains information akin to that of data2, but it seems to be more comprehensive and recent.
Project overview:
In this project, we aim to find the correlation between a game's reception and its sales. Our hypothesis is that the better a game is reviewed, the more sales it would have.

see http://www.vgchartz.com/game/83196/grand-theft-auto-v/ to compare numbers to determine the units.

## Project description
The aim of this project was to discover a correlation between a game's reception and its sale. Disregarding any external factors, we anticipated that a mutual relationship exists between such two aspects of a game, and a game with high sale is likely to be rated high.

## Data description
Found in a well-known data community website "Kaggle," three data have been combined to produce the outcome of the project:
  
- [Data1](https://www.kaggle.com/destring/metacritic-reviewed-games-since-2000): Shows the ratings of the games that is shown by meta score and user score.
- [Data2](https://www.kaggle.com/rush4ratio/video-game-sales-with-ratings): Contains both ratings and sales. It has global sales data and also shows rating by the critic score and the user score.
- [Data3](https://www.kaggle.com/rgwegwegwe/vgsaledata): Gives both ratings and sales. It's rating is shown by the user score.
  
  Then, ALL THREE DATA are merged into one that contains key informations of total sales and and user score. It also has informtions of the console, release date and name to help people see what is actually going on. 

## Technology
Python 3 is the programming language that is selected mainly for inherent "pandas" and "matplotlib" libraries, which are useful to combine, operate, and visualize data. All contents of the project have been recorded and updated via an online web application Jupyter Notebook.

Documentations of the libraries can be found in:
- [pandas 0.24.2 documentation](https://pandas.pydata.org/pandas-docs/stable/getting_started/tutorials.html)
- [matplotlib 3.1.1 documentation](https://matplotlib.org/3.1.1/tutorials/introductory/usage.html)

## Analysis / Conclusion
