
# Industry

## Проект на иссследование возможности снижения издержек производства металлургического комбината

### Описание проекта:

На основе данных, полученных с металлургического комбината, требуется построить прототип модели машинного обучения, которая предскажет температуру стали перед введением легирующих добавок.

### Навыки и инструменты:

- python
- pandas
- numpy
- matplotlib.pyplot
- seaborn
- sklearn.linear_model.LinearRegression
- sklearn.tree.DecisionTreeRegressor
- sklearn.ensemble.RandomForestRegressor
- sklearn.model_selection.GridSearchCV
- sklearn.metrics.make_scorer
- sklearn.model_selection.train_test_split
- sklearn.metrics.accuracy_score
- sklearn.metrics.f1_score 
- sklearn.metrics.mean_squared_error
- sklearn.metrics.mean_absolute_error 
- sklearn.preprocessing.StandardScaler
- catboost.CatBoostRegressor
- lightgbm.LGBMRegressor

### Вывод:

На предоставленных данных о материалах и результатах измерения, проведено несколько этапов(первичный анализ, предобработка данных, разработка и построение модели), в результате чего построена, проанализирована и протестирована
модель машинного обучения, которая предсказывает температуру стали на финальной стадии перед введением легирующих добавок. Лучшей моделью, наиболее качественно предсказывающей финальную температуру нагрева стали в ковше для плавления стали 
стала модель градиентного бустинга CatBoostRegressor. 
Выявлен самый важный признак лучшей обученной модели.
