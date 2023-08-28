# NBA-fantasy-draft-model
Python project using pandas.

Projection model for NBA players' stats in the 2023-24 season.

Steps in the model:
1. normalise data across seasons
2. find 10 most similar players seasons historically
3. rank and weight each of those 10 players seasons stats depending on how similar they are
4. look at 10 players following season stats
5. use weighted averages to predict current players next season

Repeat for each player in 2023-24
