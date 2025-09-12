# sp500_project
this project is heavily inspired by Algorithmic Trading – Machine Learning & Quant Strategies Course with Python created by Luke Hardy original code of the course: https://github.com/Luchkata/Algorithmic_Trading_Machine_Learning Since this is my first time combining coding and machine learning with finance, the structure of the code is credited to the course. Adjustments to the code is made starting when it introduces fama-french factors.

1. use excess return as label instead of return
2. standardize all features (the original code does not standardize rsi, which puts too much emphasize on momentum of price movement.)
3. using pca to reduce number of features
4. applying kmeans model with k=2~6 
5. construct portfolio by looking at its time-weighted return (the course did it by choosing the portfolio with highest rsi)
6. I introduce the model to new test data to help me assess the performance of portfolios. Then, compare the returns with sp500 and risk free rate.
