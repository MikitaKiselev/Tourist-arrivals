# Прогнозирование туристических посещений
## Описание
Данный проект посвящен прогнозированию туристических посещений с использованием методов продвинутого анализа данных и машинного обучения. Реализованное решение включает в себя обширную инженерию признаков, исследовательский анализ данных и применение регрессионной модели CatBoost для прогнозирования.
# ЗАМЕЧАНИЕ
Моя текущая позиция - 7 изи 80

Так как соревнования ещё идут, то на данный момент предоставлен черновой вариант кода
## Набор данных
Набор данных состоит из тренировочных (train_df.csv) и тестовых (test_df.csv) данных, содержащих информацию о туристических посещениях и различных характеристиках, связанных со спотами, объектами, районами, городами, типами, событиями и другими.
## Инженерия признаков
### 1.Предобработка даты:
Преобразование столбца 'date' в формат datetime.

Извлечение дополнительных временных признаков, таких как 'year', 'month', 'day',
### 2.Определение сезона:
Создание признака 'season', отражающего временное распределение весеннего, летнего, осеннего и зимнего периодов.

Добавление признака 'season_num' с числовым представлением сезона.
### 3. Кодирование признаков (тригонометрические функции):
Реализация кодирования категориальных признаков ('month', 'day', 'dayofweek', 'season_num') с использованием тригонометрических функций.
### 4. Нормализация данных:
Применение стандартизации к выбранным числовым признакам для обеспечения однородности данных.
#
## Использование модели CatBoost
Для прогнозирования туристических посещений была использована модель CatBoost. Обучение модели проводилось на предобработанных тренировочных данных, а затем были получены прогнозы для тестового набора данных. Дополнительно проведен поиск по сетке параметров для оптимизации производительности модели.
# Результаты
На данный момент я занимаю лидирующую позицию на этих соревнованиях(7 из 80). Однако, так как соревнования ещё идут, то я планирую улучшить свой результат
#
#
#
#
# Tourist arrivals
## Description
This project focuses on forecasting tourist visits using advanced data analysis and machine learning methods. The implemented solution includes extensive feature engineering, exploratory data analysis, and the application of the CatBoost regression model for forecasting.
# NOTE
My current position is 7 out of 80.

As the competition is still ongoing, the provided code is currently in draft form.
## Dataset
The dataset consists of training (train_df.csv) and test (test_df.csv) data containing information about tourist visits and various characteristics related to spots, facilities, areas, cities, types, events, and more..
## Feature Engineering
### 1. Date Preprocessing:
Converting the 'date' column to datetime format.

Extracting additional time-related features such as 'year', 'month', 'day'.
### 2. Season Definition:
Creating the 'season' feature reflecting the temporal distribution of spring, summer, fall, and winter periods.

Adding the 'season_num' feature with a numerical representation of the season.
### 3. Feature Encoding (Trigonometric Functions):
Implementing the encoding of categorical features ('month', 'day', 'dayofweek', 'season_num') using trigonometric functions
### 4. Data Normalization:
Applying standardization to selected numerical features to ensure data homogeneity.
#
## CatBoost Model Usage
To forecast tourist visits, the CatBoost model was utilized. The model training was conducted on preprocessed training data, and predictions were obtained for the test dataset. Additionally, a grid search for parameter optimization was performed to enhance model performance.
# Results
Currently, I hold the leading position in this competition (7 out of 80). However, since the competition is still ongoing, I plan to improve my result.

