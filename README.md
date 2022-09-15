# Анализ населения мира
Проект по анализу и исследованию взаимосвязи показателей на основе датасета от CIA World Factbook 2017-2019 годов.

**Цель проекта**: исследовать наличие взаимосвязей (корреляции) между ключевыми показателями по странам мира и визуализировать результаты исследования.

Набор данных: датасет содержит 9 столбцов и 219 строк. 

Он имеет следующие показатели:
- Страна (Country),
- Численность населения, чел. (People),
- Площадь всего, кв км. (Area_total),
- Площадь суши, кв км. (Area_land),
- Площадь водных объектов, кв км. (Area_water),
- Средняя продолжительность жизни, лет (Life_expectancy),
- Коэффициент рождаемости (Fertility_rate),
- ВВП по паритету покупательной способности, млрд $ (GDP_(PPP))
- ВВП на душу населения, $ (GDP_per_capita_(PPP))

**Идея проекта**: построить средствами Python матрицу корреляций показателей, 
определить наличие и силу взаимосвязей между показателями (по коэффициенту корреляции Пирсона),
для показателей с высокой корреляцией построить и визуализировать регрессионные модели (используя библиотеку Seaborn).
