# Multimedia

Выполнила студентка группы М8О-406Б-21 Деревянко Екатерина Андреевна

Метрикой для сравнения для задачи классификации выбрана точность, для регрессии - средняя квадратическая ошибка.

В качестве данных для задачи классификации я выбрала данные о раке молочной железы, из-за постоянной актуальности данной проблемы. Рак молочной железы является самым распространенным видом рака, для женщин в России риск заболеть им составляет 5-6%, а значит крайне важна его правильное определение и классификация.

Для задачи регрессии я выбрала датасет с данными по оценкам IMDB сериалов и фильмов Netflix, так как с помощью машинного обучения можно было бы предугадывать оценку новых релизов и на основе этого рекомендовать из пользователям.

| Алгоритм + задача  | Бейзлайн |Улучшенный бейзлайн|Самостоятельная имплементация алгоритма|Самостоятельная имплементация алгоритма улучшенный бейзлайн|
| ------------- | ------------- |-------------|-------------|-------------|
|KNN классификация|0,97|0,95|0,97|0,97|
|KNN регрессия|1,45|1,15|1,31|1,15|
|Логическая регрессия|0,96|0,96|0,97|0,99|
|Линейная регрессия|1,31|1,17|1,31|1,17|
|Решающее дерево классификация|0,92|0,96|0,91|0,93|
|Решающее дерево регрессия|1,15|1,12|1,15|1,12|
|Случайный лес классификация|0,97|0,97|0,97|0,97|
|Случайный лес регрессия|1,12|1,06|1,14|1,09|
|Градментный бустинг классификация|0,98|0,98|0,95|0,95|
|Градментный бустинг регрессия|1,12|1,09|1,12|1,07|
