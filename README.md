### Bitcoin High's/Low's Prediction

### Summary?
Predicting Price by building optimized model using machine learning and deep neural networks.
For building a financial industrial software, I will be predicting the Bitcoin price where we have more than 9000+ rows and 12 columns for making data-driven models.
According to the source this dataset is from CoinMarketCap Data From August 4 to November 4, 2017. Before proceeding further I will be better first pre-processing the data and preparing it for further models fittings. Got dataset for bitcoin from this source: https://www.kaggle.com/datasets/paulrohan2020/crypto-data

In this noteboook I have carried out different algorithms:
- Linear Regression
- Decision Tree Regressor
- Support Vector Regressor
- Ensemble Learning - Votting
- Bagging using DTR
- Deep Neural Network - Keras

Trained the models, evaluated through mean absolute errors and tuned the hyper parameters for the better predictions.


### Access Project At this: <a href="https://www.kaggle.com/code/osamaakrambaig/financial-market-software?scriptVersionId=97420410">Link</a>

### Summary about the analyses and visualizations
Different Models I used and their MSE (Mean Squared Errors) comparisons:

| Models | MAE/MSE |
| --- | --- |
| Decision Tree Regressor | 0.0004938 |
| Linear Regression | 0.0000962 |
| Support Vector Regressor | 0.0650580 |
| Enselble Voting Regressor | 0.0217078 |
| Bagging - DTR | 0.0002752 |
| Deep Neural Network | 0.0235000 |

### I got these estimations where value loss and improved error on the testing data was seen through deep neural network. 
* I will better carry on with the Linear Regression, Neural Network or Decision Tree Regressor. 
* Models are even performing well on the unseen data as well where we can predict price formation.
* Price with the use of these features ('market cap', 'circulating supply', 'volume', '% 1h', '% 24h', '% 1wk').
* Further research can be made over the live data which we can made to predict price and then trade accordingly. 

### Results:
First 5 Predicted Test Values <br>
[0.5591178  0.32097495 0.705351   0.80211806 0.79585695] <br><br>
First 5 Actual Test Values <br>
[0.57361236 0.32422314 0.72289184 0.85558872 0.8371862 ] <br>

### Built With
* [Python](https://www.python.org/)
For further documentation visit: <a href="https://www.python.org/doc/">About Python</a>
* [Tensorflow-keras](https://www.tensorflow.org/)
For further documentation visit: <a href="https://www.tensorflow.org/learn">About Tensorflow</a>
* [Scikit-Learn](https://scikit-learn.org/stable/)
For further documentation visit: <a href="https://scikit-learn.org/stable/user_guide.html">About Scikit-Learn</a>


### Installation
1. Clone the repo
   ```sh
   git clone https://github.com/usama-akram-gt/predicting_btc_in_financial_industry.git
   ```
2. Install Python and libraries
3. Run cell by cell
   

### Contributing
Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.


### References:
* https://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeRegressor.html
* https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html
* https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.cross_val_score.html
* https://scikit-learn.org/stable/modules/generated/sklearn.metrics.mean_squared_error.html
* https://www.tensorflow.org/tutorials/quickstart/beginner
