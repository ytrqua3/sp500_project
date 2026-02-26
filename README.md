# sp500_project
this project is inspired by Algorithmic Trading – Machine Learning & Quant Strategies Course with Python created by Luke Hardy original code of the course: https://github.com/Luchkata/Algorithmic_Trading_Machine_Learning Since this is my first time combining coding and machine learning with finance, I adopted the idea to work on the financial indicators from the video.

1. Load the prices of stocks using yahoo finance moduel
2. Compute technical indicators
3. aggregate to monthly
4. standardize all features (the original code does not standardize rsi, which puts too much emphasize on momentum of price movement.)
5. using pca to reduce number of features
6. applying kmeans model with k=2~6 
7. assign weights to each cluster of stocks using max sharpe ratio on efficient frontier
8. Compute the time-weighted return for each cluster then compare the returns with sp500 and risk free rate.
