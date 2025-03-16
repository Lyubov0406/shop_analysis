# shop_analysis

В этом репозитории Вы найдете файлы, касающиеся анализа данных деятельности продуктового магазина за определенный период.

Все статистические рассчеты были выполнены на языке Python с использованием библиотек pandas, numpy, scipy, scikit_posthocs, seaborn, matplotlib. 

В работе была проведена подготовка данных к анализу: 
1. оценка и и зменение типов данных
2. проверка на наличие пропущенных знасений
3. повторяющихся значений и ошибок в данных
4. создание новых столбцов для подсчета коммулятивных значений
5. проверка на наличие выбросов и их удаление

Используемые методы: 
1. описательный анализ
2. построение столбчатых диаграмм и нормированной столбчатой диаграммы по сводной таблице, груговой диаграммы
3. корреляционный анализ (r-Спирмена) + heatmap
4. сравнительный анализ с применением критерия Краскела-Уоллиса и posthoc критерия Данна + barplot
5. сравнитлельный анализ с применением критерия U-Манна-Уитни + barplot

Файлы:
1. project1_data.csv - используемый датасет, содержащий данные о социально-демографических хараткеристиках покупателей, их покупках в онлайн- и офлайн магазинах, результатах маркетинговых компаний и пр.
2. dictionary.png - описание переменных/столбцов датасета
3. shop_analysis.ipynb - файл со всеми рассчетами на Python и сопутствующими описаниями
4. shop_analysis_peresentation.pdf - итоговая презентация



