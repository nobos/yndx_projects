# Приоритизация гипотез, запуск A/B-тест и анализ результатов.

В рамках проекта был проанализирован список гипотез для увеличения выручки интернет магазина по методикам RICE и ICE. Проведена оценка A\B теста для выбора одного из решений: 1. Остановить тест, зафиксировать победу одной из групп; 2. Остановить тест, зафиксировать отсутствие различий между группами; 3. Продолжить тест.
<br>В процессе работы были использованы библиотеки Pandas, Numpy, Matplotlib.pyplot, Scipy.


### Основные выводы

1. Группа А и В имеют статистически значимые различия в конверсии, но схожи в среднем чеке, как по сырым, так и по очищенным данным.
2. Данные по кумулятивной конверсии показывают превосходство группы В.
3. В то же время очищенные данные по среднему чеку указывают на недостаток группы В.

По результатам исследования тест можно закончить, признав превосходство группы B по конверсии.
