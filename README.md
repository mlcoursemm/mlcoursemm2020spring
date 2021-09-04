[EN version](#en)

# Введение в компьютерный интеллект. Машинное обучение.

## Содержание
* [Новости](#news)
* [Краткая информация](#info)
* [Время и место](#ww)
* [Связь с преподавателями](#feedback)
* [Результаты выполнения заданий](#marks)
* [Программа курса](#program)
* [Список литературы](#lit)
* [Полезные ссылки](#links)
## <a name="news" /> Новости
* (2020-05-08) Выложена [десятая лекция](./notebooks/lecture10-matplotlib.ipynb), прочитанная В. Корвяковым и Э. Казиахмедовым.
* (2020-04-14) Выложены [девятая лекция](./lectures/lecture09-boost.pdf) и [семинар](./notebooks/seminar09-ensembles.ipynb).
* (2020-04-07) Открыто соревнование на [kaggle](https://www.kaggle.com/t/013153ddc406442fa919d6384ebf5875). Дедлайн: до 15 мая включительно.
* (2020-04-07) Выложена [восьмая лекция](./lectures/lecture08-ensembles.pdf)
* (2020-04-01) Выложено [второе практическое задание](./assignments/programming02). Дедлайн отправки: до 01 мая включительно.
Отправку задания необходимо делать с темой письма [ML2020:prac02]
* (2020-04-01) Выложены [седьмая лекция](./lectures/lecture07-trees.pdf) и [семинар](./seminars/seminar07-missing_values.pdf).
* (2020-03-24) Выложено [второе теоретическое задание](./assignments/theory02.pdf). Дедлайн отправки: до 14 апреля включительно.
Отправку задания необходимо делать с темой письма [ML2020:th02]
* (2020-03-24) Выложена [шестая лекция](./lectures/lecture06-svm.pdf).
* (2020-03-17) Выложена [пятая лекция](./lectures/lecture05-lincls.pdf).
* (2020-03-11) Выложено [первое практическое задание](./assignments/programming01). Дедлайн отправки: до 01 апреля включительно.
Отправку задания необходимо делать с темой письма [ML2020:prac01]
* (2020-03-11) Выложена [четверная лекция](./lectures/lecture04-linreg.pdf) и [семинар по pandas](./seminars/seminar04-pandas.pdf).
Был добавлен раздел с примерами кода [notebooks](./notebooks)
* (2020-03-04) Выложено [первое теоретическое задание](./assignments/theory01.pdf). Дедлайн отправки: до 25 марта включительно.
Отправку задания необходимо делать с темой письма [ML2020:th01]
* (2020-03-04) Выложена [третья лекция](./lectures/lecture03-prob.pdf)
* (2020-02-27) Выложена [вторая лекция](./lectures/lecture02-knn.pdf)
* (2020-02-19) Выложена [первая лекция](./lectures) и [первый семинар](./seminars)
* Первая лекция состоится во вторник 18 февраля, в 18:30 в аудитории 1205 (ГЗ МГУ) 
* В этом семетре помимо лекций будут проходить еще и семинарские занятия, на которых будут обсуждаться практические вопросы машинного обучения. Семинары будут проходить сразу после лекций.
## <a name="info" /> Краткая информация 
В весеннем семестре 2020 года на механико-математическом факультете МГУ им. М. В. Ломоносова начинается чтение нового спецкурса по выбору студента, посвященного классическим алгоритмам машинного обучения. 

Курс будет читаться на базе кафедры [Математической Теории Интеллектуальных Систем](http://intsys.msu.ru) под руководством д.ф.-м.н., профессора [Бабина Д. Н.](http://intsys.msu.ru/staff/babin/) Курс будут читать к.ф.-м.н. Петюшко А. А. и к.ф.-м.н. Иванов И. Е.
## <a name="ww" /> Время и место 
Курс читается по вторникам в 18:30, ГЗ МГУ, аудитория 1205 (ГЗ МГУ). 
## <a name="feedback" /> Связь с преподавателями
* [Telegram-канал](https://t.me/joinchat/AAAAAEUmx5cJLOdLXsOt8g), в котором будут появляться все важные новости
* Обратная связь - по почте mlcoursemm@gmail.com
* Ну и всегда можно написать в [issues](https://github.com/mlcoursemm/mlcoursemm2019spring/issues) :)
## <a name="marks" /> Результаты выполнения заданий
* [Итоговая таблица с результатами](https://docs.google.com/spreadsheets/d/1rK32FuGOz1QT5IG5jU24uPJPF6OW_UH2oSRW4PQQ1To/edit?usp=sharing)
## <a name="program" /> Программа курса 
| Номер         | Дата          | Лекция                                            | Семинар                                 |
| ------------- | ------------- | -------------                                     | -------------                           |   
| 01            | 18.02.2020    | Вводная лекция                                    | Вводное занятие по Python               |
| 02            | 25.02.2020    | Непараметрические методы классификации и регрессии| Вводное занятие по Python (продолжение) |
| 03            | 03.03.2020    | Вероятностный подход к классификации              | Разбор домашних заданий из курса по CV  |
| 04            | 10.03.2020    | Регрессия и оценка качества                       | Введение в pandas                       | 
| 05            | 17.03.2020    | Линейные классификаторы                           | Метрики качества классификаторов | 
| 06            | 24.03.2020    | SVM                                               | Построение SVM | 
| 07            | 31.03.2020    | Решающие деревья. Случайный лес                   | Работа с пропущенными значениями. Выбор признаков| 
| 08            | 07.04.2020    | Ансамбли                                          | Обзор площадки Kaggle и соревнование | 
| 09            | 14.04.2020    | Ансамбли                                          | Обзор методов ансамблирования в sklearn | 
| 10            | 21.04.2020    | Разведывательный анализ                           | Разведывательный анализ                 | 
| 11            | 28.04.2020    | Методы уменьшения размерности                     | Разбор домашних заданий курса           | 

## <a name="lit" /> Список литературы
1. [Курс лекций по машинному обучению](http://www.machinelearning.ru/wiki/index.php?title=Машинное_обучение_%28курс_лекций%2C_К.В.Воронцов%29) на http://www.machinelearning.ru от Воронцова К. В.
1. Hastie, T. and Tibshirani, R. and Friedman, J. [The Elements of Statistical Learning](https://web.stanford.edu/~hastie/ElemStatLearn/printings/ESLII_print12.pdf), 2nd edition, Springer, 2009.
2. Bishop, C.M. [Pattern Recognition and Machine Learning](https://www.microsoft.com/en-us/research/uploads/prod/2006/01/Bishop-Pattern-Recognition-and-Machine-Learning-2006.pdf), Springer, 2006.
## <a name="links" /> Полезные ссылки 
### Шпаргалки
* Краткая справочная информация по Python, NumPy, SciPy, SciKit-learn, Pandas, MatPlotLib, Jupyter Notebook: см. в [папке с документацией](https://github.com/mlcoursemm/mlcoursemm2019spring/tree/master/cheatsheets) курса 2019 года
### Введение в Python
* Python Programming in 15 min: [Part1](https://towardsdatascience.com/python-programming-in-15-min-part-1-3ad2d773834c), [Part2](https://towardsdatascience.com/python-programming-in-15-min-part-2-480f78713544), [Part3](https://towardsdatascience.com/python-programming-in-15-min-part-3-ce882f9ab9b2)
* Python Programmin - A Modern Approach: [Code, notebooks and slides](https://github.com/vamsi/python-programming-modern-approach)
* Playground and Cheatsheet for Learning Python: [github repo](https://github.com/trekhleb/learn-python)
### Введение в машинное обучение
* Homemade Machine Learning: [github repo](https://github.com/trekhleb/homemade-machine-learning)
* Machine learning: [Курс](https://www.coursera.org/learn/machine-learning) Andrew Ng на площадке https://www.coursera.org

* [Материалы прошлогоднего курса](https://github.com/mlcoursemm/mlcoursemm2019spring)



### <a name="en" /> EN version


# Introduction to Computer Intelligence. Machine learning.

## Content
* [News](#news1)
* [Short info](#info1)
* [Time and place](#ww1)
* [Communication with teachers](#feedback1)
* [Task results](#marks1)
* [Course program](#program1)
* [Bibliography](#lit1)
* [Useful links](#links1)
## <a name="news1" /> News
* (2020-05-08) Uploaded [10th lecture](./notebooks/lecture10-matplotlib.ipynb), read by V. Korviakov and E. Kaziakhmedov.
* (2020-04-14) Uploaded [9th lecture](./lectures/lecture09-boost.pdf) and [seminar](./notebooks/seminar09-ensembles.ipynb).
* (2020-04-07) Competition is open on [kaggle](https://www.kaggle.com/t/013153ddc406442fa919d6384ebf5875). Deadline: until May 15 inclusive.
* (2020-04-07) Uploaded [8th lecture](./lectures/lecture08-ensembles.pdf)
* (2020-04-01) Uploaded [second practical task](./assignments/programming02). Deadline for submit: until May 01 inclusive.
Submitting an assignment must be done with the subject title [ML2020:prac02]
* (2020-04-01) Uploaded [7th lecture](./lectures/lecture07-trees.pdf)and [seminar](./seminars/seminar07-missing_values.pdf).
* (2020-03-24) Uploaded [second theoretical task](./assignments/theory02.pdf). Deadline for submit: until April 14 inclusive.
Submitting an assignment must be done with the subject title [ML2020:th02]
* (2020-03-24) Uploaded [6th lecture](./lectures/lecture06-svm.pdf).
* (2020-03-17) Uploaded [5th lecture](./lectures/lecture05-lincls.pdf).
* (2020-03-11) Uploaded [first practical task](./assignments/programming01). Deadline for submit: until April 01 inclusive.
Submitting an assignment must be done with the subject title [ML2020:prac01]
* (2020-03-11) Uploaded [4th lecture](./lectures/lecture04-linreg.pdf) and [seminar pandas](./seminars/seminar04-pandas.pdf).
A section with code examples has been added [notebooks](./notebooks)
* (2020-03-04) Uploaded [first theoretical task](./assignments/theory01.pdf). Deadline for sending: until March 25 inclusive.
Submitting an assignment must be done with the subject title [ML2020:th01]
* (2020-03-04) Uploaded [3rd lecture](./lectures/lecture03-prob.pdf)
* (2020-02-27) Uploaded [2nd lecture](./lectures/lecture02-knn.pdf)
* (2020-02-19) Uploaded [1st lecture](./lectures) and [first seminar](./seminars)
* The first lecture will take place on Tuesday 18, February, at 18:30 in room 1205 (main bilding MSU) 
* This semester, in addition to lectures, we will also include seminars on which practical issues of machine learning will be discussed. Seminars will be held immediately after the lectures.
## <a name="info1" /> Short info 
In the spring semester of 2020 at the Faculty of Mechanics and Mathematics of Lomonosov Moscow State University begins reading a new special course of the student's choice, dedicated to classical machine learning algorithms.

The course will be taught on the basis of the Department of [Mathematical Theory of Intelligent Systems](http://intsys.msu.ru) under the guidance of Doctor of Physical and Mathematical Sciences, Professor [Babin D.N.](http://intsys.msu.ru/staff/babin/) The course will be delivered by Ph.D. [Petiushko A.A.](https://petiushko.info) and Ph.D. Ivanov I.E.
## <a name="ww1" /> Time and place 
The lessons are to be taught on Tuesdays at 18:30, main bilding MSU, room 1205. 
## <a name="feedback1" /> Communication with teachers
* [Telegram-channel](https://t.me/joinchat/AAAAAEUmx5cJLOdLXsOt8g), where all important news will appear
* Feedback - by email mlcoursemm@gmail.com
* Well, you can always write in [issues](https://github.com/mlcoursemm/mlcoursemm2019spring/issues) :)
## <a name="marks1" /> Task results
* [Summary table with results](https://docs.google.com/spreadsheets/d/1rK32FuGOz1QT5IG5jU24uPJPF6OW_UH2oSRW4PQQ1To/edit?usp=sharing)
## <a name="program1" /> Course program
| Number        | Вate          | Lecture                                            | Seminar                                        |
| ------------- | ------------- | -------------                                      | -------------                                  |   
| 01            | 18.02.2020    | Introductory lecture                               | Introductory Python Lesson                     |
| 02            | 25.02.2020    | Nonparametric classification and regression methods| Introductory Python Lesson (Continued)         |
| 03            | 03.03.2020    | Probabilistic approach to classification           | Analysis of homework from the CV course        |
| 04            | 10.03.2020    | Regression and quality assessment                  | Introduction to pandas                         | 
| 05            | 17.03.2020    | Linear classifiers                                 | Classifier quality metrics                     | 
| 06            | 24.03.2020    | SVM                                                | Building SVM                                   | 
| 07            | 31.03.2020    | Decision trees. Random forest                      | Working with missing values. Feature selection | 
| 08            | 07.04.2020    | Ensembles 1                                        | Kaggle site overview and challenge             | 
| 09            | 14.04.2020    | Ensembles 2                                        | An overview of ensemble methods in sklearn     | 
| 10            | 21.04.2020    | Exploratory data analysis                          | Exploratory data analysis                      | 
| 11            | 28.04.2020    | Dimension reduction methods                        | Analysis of the course homework                | 

## <a name="lit1" /> Bibliography
1. [Machine Learning Lecture Course](http://www.machinelearning.ru/wiki/index.php?title=Машинное_обучение_%28курс_лекций%2C_К.В.Воронцов%29) on http://www.machinelearning.ru from Vorontsov K.V.
1. Hastie, T. and Tibshirani, R. and Friedman, J. [The Elements of Statistical Learning](https://web.stanford.edu/~hastie/ElemStatLearn/printings/ESLII_print12.pdf), 2nd edition, Springer, 2009.
2. Bishop, C.M. [Pattern Recognition and Machine Learning](https://www.microsoft.com/en-us/research/uploads/prod/2006/01/Bishop-Pattern-Recognition-and-Machine-Learning-2006.pdf), Springer, 2006.
## <a name="links1" /> Useful links 
### Cheat sheets
* Quick reference information on Python, NumPy, SciPy, SciKit-learn, Pandas, MatPlotLib, Jupyter Notebook: see in [document folder](https://github.com/mlcoursemm/mlcoursemm2019spring/tree/master/cheatsheets) of course 2019 year
### Introduction to Python
* Python Programming in 15 min: [Part1](https://towardsdatascience.com/python-programming-in-15-min-part-1-3ad2d773834c), [Part2](https://towardsdatascience.com/python-programming-in-15-min-part-2-480f78713544), [Part3](https://towardsdatascience.com/python-programming-in-15-min-part-3-ce882f9ab9b2)
* Python Programming - A Modern Approach: [Code, notebooks and slides](https://github.com/vamsi/python-programming-modern-approach)
* Playground and Cheatsheet for Learning Python: [github repo](https://github.com/trekhleb/learn-python)
### Introduction to machine learning
* Homemade Machine Learning: [github repo](https://github.com/trekhleb/homemade-machine-learning)
* Machine learning: [Course](https://www.coursera.org/learn/machine-learning) by Andrew Ng on the site https://www.coursera.org

* [Last year's course materials](https://github.com/mlcoursemm/mlcoursemm2019spring)

