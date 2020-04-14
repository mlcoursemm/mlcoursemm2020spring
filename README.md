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
* (2020-04-14) Выложены [девятая лекция](./lectures/lecture09-boost.pdf) и [семинар](./seminars/seminar09-ensembles.ipynb).
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
| 08            | 07.04.2020    | Ансамбли                                          | Обзор площадки Kaggle и соренование | 
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
