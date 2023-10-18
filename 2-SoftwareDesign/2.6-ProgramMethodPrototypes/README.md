# Прототипи методів програмних класів
| FR  | Опис вимоги          | Назва класу        | Назва методу класу  |
| --- | -------------------- | ------------------ | ------------------- |
| FR1.1 | Створення облікових записів тренера/користувачів  |Користувач | createAccount()    |
| FR1.2 | Користувач робить тренеру запит на нові комплекси вправ   |Користувач    |makeExerciseRequest()   |
| FR1.3 | Тренер дає доступ до каталогу тренувань та процедур|Тренер   | grantAccessToCatalog()    |
| FR1.5 |Користувач обирає конкретні вправи|Користувач   | selectExercises()  |    
|FR2.1|Користувач може внести і зберігти дані про своїх тренування або процедури, включаючи кількість повторень, вагу, тривалість   | Користувач    | saveUserProgress()    |
| FR2.3 | Тренер надає прогрес користувачів, індивідуалізовані поради та рекомендації| Тренер |provideUserFeedback   |
|FR2.4 | Тренер надсилає мотиваційні повідомлення та сповіщення користувачам|Тренер   | sendMotivationalMessage   |