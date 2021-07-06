# Projects from "Data Science Specialist" course from Yandex

The following projects were completed during my studies in [Yandex.Practicum](https://practicum.yandex.com/data-scientist/). The projects are listed in chronological order, so it is possible to see my Data Scientist skill toolkit grow. 


| Project name  | Description | Libraries |
| :------------- | :------------- |:-------------|
| [1. Big city music](01_yandex_music)  | Preferences comparison of Yandex.Music users from Moscow and St. Petersburg depending on time and day. Data preparation, cleaning, exploratory analysis. | *pandas* |
| [2. Сredit worthiness analysis](02_credit_scoring) | Investigation on the effect of family status, number of children and income on credit repayment. Data preparation, cleaning, exploratory analysis, variable categorization. | *pandas*, *pymystem3* |
|[3. Real estate analysis](03_real_estate_prices)| 	Determining the market value of real estate in St. Petersburg and its suburbs and defining parameters that make it possible to create an automated system capable of detecting anomalies and fraud. Data preparation, feature engineering, exploratory analysis, correlation between the real estate price and different parameters. | *pandas*, *matplotlib.pyplot*,  *plotly.express* |
| [4. Determination of a promising tariff for a telecom company](04_telecom_tariff) | User behavior analysis for a telecom company to determine the most profitable tariff. Data preparation, cleaning, feature engineering, statistical analysis, hypothesis testing. | *pandas*, *matplotlib.pyplot*,  *plotly*, *numpy*, *scipy.stats* |
|[5. Computer games popularity research](05_games)| Game popularity prediction depending on genre and platform based on historical data. Exploratory data analysis, user portrait analysis, hypothesis testing. | *pandas*, *matplotlib.pyplot*,  *plotly*, *numpy*, *scipy.stats* |
| [6. Telecom tariff recommendation](06_users_classification)| Building a machine learning model for user classification. The training is conducted on historical data with user behavior, the model will be used to recommend a suitable tariff to users. Data preparation and cleaning was not required here. The following models have been tested: DecisionTreeClassifier, RandomForestClassifier, LogisticRegression. | *pandas*, *sklearn*, *numpy* |
| [7. Bank customer churn modeling](07_bank_customer_churn_modeling) | Building a machine learning model for customer churn prediction based on historical data with customer behavior. Data preparation, cleaning, OHE encoding of categorical variables, scaling of numerical variables, dealing with imbalanced data (class weight, upsampling, downsampling). Different models have been tested (DecisionTreeClassifier, RandomForestClassifier, LogisticRegression), optimal hyperparameters were found with GridSearchCV. F1-score and AUC-ROC were calculated. | *pandas*, *sklearn*, *numpy*, *matplotlib.pyplot* |
| [8. New oil well location](08_oil_extraction_location) | Creating a model that analyzes different proposed locations for a new oil well that will maximize profits while minimizing risk. Profits and risk were analyzed using Bootstrap technique. LinearRegression was used as a model. | *pandas*, *sklearn*, *numpy*, *scipy.stats*, *seaborn*, *matplotlib.pyplot* |
| [9. Gold recovery coefficient](09_gold_recovery) | Building a machine learning model to predict the amount of gold extracted from gold ore based on extraction and purification data. Different models have been tested: LinearRegression, DecisionTreeRegressor, RandomForestRegressor. Optimal hyperparameters were found with cross-validation. | *pandas*, *sklearn*, *numpy*, *seaborn*, *matplotlib.pyplot* |
| [10. Customers' personal data encryption](10_customer_data_encryption) | Developing a method for data encryption based on multiplication of features by an invertible matrix. The correctness of the method is mathematically justified. It is shown that the quality of linear regression on the transformed data does not change. | *pandas*, *sklearn*, *numpy*, *seaborn*, *matplotlib.pyplot* |
| [11. Car prices prediction](11_car_prices_boosting) | Building a machine learning model for car prices prediction based in historical data. Data was preprocessed, categorical features were encoded with OrdinalEncoder. Models used: Gradient Boosting, Random Forest. Optimal hyperparameters were found with GridSearchCV. Feature importance chart was plotted. | *pandas*, *sklearn*, *numpy*, *seaborn*, *matplotlib.pyplot*, *plotly*, *lightgbm* |
| [12. Number of taxi orders forecast](12_time_series) | Time-series forecasting for a number of taxi orders. Data resampling, trend and seasonality analysis. New features were added: calendar features, lag and rolling mean values. Models used: Gradient Boosting (CatBoost), Linear Regression. Optimal hyperparameters were found with GridSearchCV. | *statsmodels.tsa.seasonal*, *catboost*, *pandas*, *sklearn*, *numpy*, *matplotlib.pyplot* |
| [13. Sentiment analysis](13_nlp) | Building a model to study tonality of texts. Texts were preprocessed, lemmatized with Spacy. Models used: CatBoost, TF-IDF + Logistic Regression | *catboost*, *pandas*, *sklearn*, *re*, *nltk* |
| [14. Analytics of airline customers' preferences](14_sql) | Analysis of customers' flights to different cities in September 2018. Studying the database and extracting the necessary information. Data analysis in python. | *pandas*, *PostgreSQL* |


                                                          
















