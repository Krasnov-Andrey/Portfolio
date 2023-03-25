# Улучшение процесса обогащения золота

[ipynb](https://github.com/Krasnov-Andrey/Portfolio/blob/main/Gold%20recovery/Gold%20recovery.ipynb)

## Описание проекта

Требуется подготовить прототип модели машинного обучения, который должен предсказать коэффициент восстановления золота из золотосодержащей руды и спрогнозировать концентрацию золота при проведении процесса очистки золота. Модель поможет оптимизировать производство, чтобы не запускать предприятие с убыточными характеристиками.

## Направление 
- Машинное обучение
- Регрессия
- Аналитик (универсал)
- EDA

## Навыки и инструменты

- **python**
- **pandas**
- **numpy**
- **Matplotlib**
- **Seaborn**
- **scipy**
- sklearn.model_selection.**cross_val_score**
- sklearn.metrics.**mean_absolute_error**, **make_scorer**
- sklearn.preprocessing.**StandardScaler**
- sklearn.linear_model.**LinearRegression**
- sklearn.tree.**DecisionTreeRegressor**
- sklearn.ensemble.**RandomForestRegressor**

## Общий вывод

Было проведено обучение выбранных моделей для стадий грубой и тонкой очистки, проведена проверка выбранных обученных моделей на тестовом наборе и выбрана одна для запуска в производство.
