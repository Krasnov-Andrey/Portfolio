# Построение модели определения стоимости автомобиля

[ipynb](https://github.com/Krasnov-Andrey/Portfolio/blob/main/Determining%20the%20cost%20of%20cars/Determining%20the%20cost%20of%20cars.ipynb)

## Описание проекта

Для сервиса по продаже автомобилей с пробегом нужно построить систему рекомендации, которая будет определять рыночную стоимость автомобиля на основе его описания.
При выборе модели кроме качества также важно учесть скорость предсказания и время обучения.

## Направление 
- Машинное обучение
- Регрессия
- Кодирование
- Бустинг

## Навыки и инструменты

- **python**
- **pandas**
- **numpy**
- **Matplotlib**
- from sklearn.preprocessing import **StandardScaler**, **OrdinalEncoder**
- sklearn.linear_model.**LogisticRegression**
- sklearn.ensemble.**DecisionTreeRegressor**
- sklearn.ensemble.**RandomForestRegressor**
- from catboost import **CatBoostRegressor** 
- from lightgbm import **LGBMRegressor**
- sklearn.model_selection.**GridSearchCV**, **KFold**, **cross_val_score**
- sklearn.metrics.**mean_squared_error**

## Общий вывод

Была проведена исследовательская работа по обработке данных, обучению и выбору модели для сервиса по продаже автомобилей. Исходя из полученных значений метрики RMSE и времени - следует, что LGBMRegressor обучается быстрее, чем CatBoostRegressor, но CatBoostRegressor лучше предсказывает RMSE, при этом скорость предсказаний сопостовима у обеих моделей. Итоговая модель CatBoostRegressor.
