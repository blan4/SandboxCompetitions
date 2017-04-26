# Задача "Бинарные данные"

http://mlbootcamp.ru/sandbox/6/

Ни для кого не секрет, что сегодня анализ данных с успехом используется в огромном количестве приложений от составления прогнозов погоды до анализа различных бизнес­процессов. При этом каждая предметная область привносит свою специфическую составляющую, учитывая которую зачастую можно получить значительное улучшение качества решения по сравнению со стандартными и универсальными подходами. Поэтому, часто, то, насколько глубоко специалист в области анализа данных погружается в предметную область, насколько развита его интуиция относительно процессов, отраженных в изучаемых массивах данных, зависит успешность получаемых им решений.

Однако сейчас мы предлагаем абстрагироваться от содержательной постановки задачи (она останется скрытой до самого момента подведения результатов) и испытать свои аналитические способности по полной программе, исследуя данные, представляющие собой двоичные наборы.

Все предоставленные для данной задачи данные разбиты на две части: обучающую (x_train.csv и y_train.csv) и тестовую (x_test.csv). Каждая строка файлов x_train.csv и x_test.csv представляет собой описание некоторых объектов в виде наборов бинарных значений (признаков), перечисленных через запятую. Все объекты распределены по трем категориям (классам). Для объектов из обучающей выборки данное разбиение известно и приведено в файле y_train.csv. Перед вами стоит задача классификации: на основе известного распределения по классам обучающих элементов, распределить также и тестовые. В качестве ответа для данной задачи принимается текстовый файл, каждая строка которого соответствует строке в файле x_test.csv и содержит номер класса
(0, 1 или 2).

В качестве критерия качества решения задачи будет приниматься точность классификации, т.е. доля правильно классифицированных объектов. Тестовая выборка случайным образом разбита на две части в соотношении 40/60. Результат на первых 40% будет определять положение участников в рейтинговой таблице на всем протяжении конкурса. Результат на оставшихся 60% станет известен после окончания конкурса и именно он определит финальную расстановку участников.