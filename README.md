# NBA Deep Dive
A deep dive into NBA stats and a model to predict the outcome of games. 

Check out this [medium article](https://medium.com/@maxbrenner110) (Currently being published) I wrote diving into some of the analyses and describing the model. 

## Data
`processed-data/` contains all the data used in exploration. It includes data such as games, salary, player stats, etc. Many of the data spans the past 5 seasons 15-16 to 19-20. It is scraped from different sources such as [nba.com](https://www.nba.com/) and [basketball-reference.com](https://www.basketball-reference.com/). `full-data/` contains processed train/test data for the model.

## Exploration
The data is explored in both SQL and [Tableau](https://www.tableau.com/). [SQLite3](https://docs.python.org/3/library/sqlite3.html) for Python is used, as a light-weight SQL engine. Make sure you also have pandas installed. You can try Tableau for free or get it with a student email. 

## Model
`fit-model.ipynb` contains the code for the model which uses XGBoost in Python. It also explores the outcomes of the trained model. 
