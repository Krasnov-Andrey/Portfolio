# Прогнозирование оттока клиента Банка

## Описание проекта

Из банка стали уходить клиенты. Банковские маркетологи посчитали: сохранять текущих клиентов дешевле, чем привлекать новых. Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет.

## Направление 
- Машинное обучение
- Классификация

## Навыки и инструменты

- **python**
- **pandas**
- **numpy**
- **Matplotlib**
- from sklearn.preprocessing import **StandardScaler**
- sklearn.linear_model.**LogisticRegression**
- sklearn.ensemble.**DecisionTreeClassifier**
- sklearn.ensemble.**RandomForestClassifier**
- sklearn.model_selection.**GridSearchCV**
- sklearn.metrics.**f1_score**, **roc_auc_score**, **roc_curve**


## Общий вывод

В исходных данных наблюдался значительный дисбаланс (80% на 20%). Проведено исследование трёх типов моделей, базовые модели характеризовались высокой степенью точности и низким качеством F1 меры. Далее рассмотрено три варианта борьбы с дисбалансом и оценены метрики моделей. В конечном итоге выбрана upsampling модель случайный лес. 

Проект из обучающих курсов Яндекс. Практикум
### Источник данных: https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling
