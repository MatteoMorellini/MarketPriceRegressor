# MarketPriceRegressor
Regressor model complete with exploratory data analysis and web-scraping function
This project introduces a sophisticated approach to predicting the market price of football players. The predictive model is built using a stacking technique, incorporating multiple high-performing models at level 0. The selection of these models was carried out through a nested cross-validation process, ensuring robust performance. Hyperparameter optimization was achieved using Optuna to fine-tune each model for optimal predictive accuracy. At level 1 of the stacking model, XGBoost and its hyperparameters were chosen as said before.

The dataset used for training the model was constructed using an automated web scraper. The scraper, designed for efficiency, requires only the input of the league name to create a comprehensive dataset encompassing all players within that league. This automation was executed systematically over the past two seasons, providing a rich historical context for predicting market prices.

The dataset includes essential player attributes such as age, the difficulty level of the league they played in, and percentile rankings for five categories over the last three seasons. These additional features contribute depth and relevance to the predictive model, offering a holistic understanding of each player's context within the market.
