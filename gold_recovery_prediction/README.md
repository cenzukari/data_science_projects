# Восстановление золота из золотосодержащей руды

[HTML](https://github.com/cenzukari/Portfolio/blob/main/Gold%20recovery/gold_odds_prediction.html)     [ipynb](https://github.com/cenzukari/yandex_practicum_data_science_projects/blob/main/gold_recovery_prediction/gold_recovery_prediction.ipynb)

## Описание проекта

Нужно подготовить прототип модели машинного обучения, которая должна предсказать коэффициент восстановления золота из золотосодержащей руды. В нашем распоряжении имеются данные с параметрами добычи и очистки. Модель должна помочь оптимизировать производство, чтобы не запускать предприятие с убыточными характеристиками.



## Навыки и инструменты

- **python**
- **pandas**
- **numpy**
- **matplotlib**
- **seaborn**
- sklearn.model_selection.**cross_val_score**
- sklearn.model_selection.**GridSearchCV**
- sklearn.metrics.**mean_absolute_error**
- sklearn.preprocessing.**StandardScaler**
- sklearn.linear_model.**LinearRegression**
- sklearn.tree.**DecisionTreeRegressor**
- sklearn.ensemble.**RandomForestRegressor**


## Общий вывод

В ходе работы было сделано:
- обработка данных
- анализ данных
- обучено несколько моделей
- выбрана и проверена на тестовых данных лучшая модель RandomForestRegressor
