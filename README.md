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
| [8. Выбор локации для скважины](08_oil_extraction_location) | Построение модели машинного обучения для определения наиболее прибыльного региона для бурения скважины на основе данных о 3ех регионах с 10000 месторождениями в каждом. Имеются описания каждой скважины и количество нефти в ней, бюджет на освоение, стоимость барреля нефти. Прибыль и риски проанализированы техникой Bootstrap. Использовалась LinearRegression. | *pandas*, *sklearn*, *numpy*, *scipy.stats*, *seaborn*, *matplotlib.pyplot* |
| [9. Коэффициент восстановления золота из золотосодержащей руды](09_gold_recovery) | Построение модели машинного обучения для предсказания коэффициента восстановления золота из руды. Имеется большое количество параметров сложного технологического процесса, состоящего из 3 этапов: флотация и 2 этапа очистки. Данные нужно подготовить, проверить на наличие аномалий. Использовались модели: LinearRegression, DecisionTreeRegressor, RandomForestRegressor. Оптимальные параметры находились с помощью кросс-валидации. | *pandas*, *sklearn*, *numpy*, *seaborn*, *matplotlib.pyplot* |
| [10. Защита персональных данных клиентов](10_customer_data_encryption) | Разработка метода шифрования данных посредством умножения признаков на обратимую матрицу. Корректность метода математически обоснована. Показано, что качество линейной регрессии на преобразованных данных не меняется. | *pandas*, *sklearn*, *numpy*, *seaborn*, *matplotlib.pyplot* |
| [11. Определение стоимости автомобилей](11_car_prices_boosting) | Построение модели машинного обучения для предсказания рыночной цены автомобиля на основе исторических данных. Данные были подготовлены, категориальные данные закодированы с помощью OrdinalEncoder. Использовались модели: Gradient Boosting, Random Forest. Оптимальные параметры были найдены с помощью GridSearchCV. Были построены графики важности факторов. | *pandas*, *sklearn*, *numpy*, *seaborn*, *matplotlib.pyplot*, *plotly*, *lightgbm* |
| [12. Прогнозирование количества заказов такси](12_time_series) | Построение модели машинного обучения для временных рядов, а именно для прогнозирования количества заказов такси на следующий час. Был проведен ресемплинг данных по 1 часу, были изучены тренды и сезонность. Добавлены новые фичи: календарные признаки, отстающие значения и скользящее среднее. Использовались следующие модели: Gradient Boosting (CatBoost), Linear Regression. Оптимальные параметры были найдены с помощью GridSearchCV. | *statsmodels.tsa.seasonal*, *catboost*, *pandas*, *sklearn*, *numpy*, *matplotlib.pyplot* |
| [13. Анализ тональности текста](13_nlp) | Разработка модели машинного обучения для обработки текстов, а именно анализ их тональности. Тексты были очищены от лишних символов и лемматизированы с помощью Spacy. Были использованы следующие модели: CatBoost, TF-IDF + Logistic Regression | *catboost*, *pandas*, *sklearn*, *re*, *nltk* |
| [14. Аналитика предпочтений клиентов авиакомпании](14_sql) | Анализ полетов клиентов в разные города в сентябре 2018 года. Изучение базы данных и выгрузка необходимой информации. Анализ средствами python. | *pandas*, *PostgreSQL* |


                                                          
















