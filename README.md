## Project description
The aim of this project was to discover a correlation between a game's reception and its sale. We anticipated that a mutual relationship exists between such two aspects of a game, and a game with high sale is likely to be rated high. 

Before we chose this topic of research, we had several different options that we found interesting to research for it, but most of them were unable to collect enough data, or we couldn't find the correlation or causation. We all came to an agreement that we think this topic is interesting and reasonable. We were able to find the data that we needed and we could also go ahead and find correlation that might show the causation.

## Data description
Found in a well-known data community website "Kaggle," three data have been combined to produce the outcome of the project:
  
- [Data1](https://www.kaggle.com/destring/metacritic-reviewed-games-since-2000): Shows the ratings of the games that is shown by meta score and user score.
- [Data2](https://www.kaggle.com/rush4ratio/video-game-sales-with-ratings): Contains both ratings and sales. It has global sales data and also shows rating by the critic score and the user score.
- [Data3](https://www.kaggle.com/rgwegwegwe/vgsaledata): Gives both ratings and sales. It's rating is shown by the user score.
  
Then, ALL THREE DATA are merged into one that contains key informations of total sales and and user score. It also has informtions of the console, release date and name to help people see what is actually going on. 
   
See http://www.vgchartz.com/game/83196/grand-theft-auto-v/ to compare numbers to determine the units.

## Technology
Python 3 is the programming language that is selected mainly for inherent "pandas" and "matplotlib" libraries, which are useful to combine, operate, and visualize data. All contents of the project have been recorded and updated via an online web application Jupyter Notebook.

Documentations of the libraries can be found in:
- [pandas 0.24.2 documentation](https://pandas.pydata.org/pandas-docs/stable/getting_started/tutorials.html)
- [matplotlib 3.1.1 documentation](https://matplotlib.org/3.1.1/tutorials/introductory/usage.html)

## Analysis / Conclusion
![scatter plot 2](https://github.com/shpark61/data_science_project/blob/master/graphs/scatter%20plot%202.png)


The conclusion that we can earn from this research is that people do not consider the ratings of others as much when they purchase the video games. The hypothesis of higher sale and higher ratings seems like that it is not true, and we can't find such correlation between those two. 
