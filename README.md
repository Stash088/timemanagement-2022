# Решение 57 места для Всероссийского чемпионата  г. Владивосток.

### Для решения задачи был использован комбинированный подход:
### Предобработка данных,
### Генерация признаков ,
### Частотное кодирование категориальных признаков,
### TF-IDF + SVD подход для текстового признака ,
### Подбор гиперпараметров для градиентного бустинга Catboost
### Данное решение получено при обучении модели с подобранными параметрами на различных (KFold_random_state * n_splits) фолдах

