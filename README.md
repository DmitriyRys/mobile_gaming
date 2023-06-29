# Mobile Gaming

Анализ данных разработчика мобильных игр.

Цели исследования:

- Написать функцию для подсчета Retention по дням от даты регистрации игрока.

- На основе результатов A/B теста с разными наборами акционных предложений определить, какой набор можно считать лучшим и на основе каких метрик стоит принять правильное решение.

- Предложить метрики для оценки результатов последнего прошедшего тематического события в игре.

Библиотеки, используемые в проекте: Pandas, Numpy, Seaborn, Matplotlib, Scipy, Pingouin.

Результаты:

1. Были предложены на выбор 3 функции расчета Retention, возвращающие:

- Среднее значение Retention N-Day.

- График среднего Retention N-Day.

- Когортный анализ Retention N-Day.

Все функции включают различные опции, например, выбор схемы расчета, рассматриваемого периода и N-Day.

2. В 3х различных вариантах были выбраны наилучшие наборы акицонных предложений:

- C фильтрацией выбросов.
   
- Сравнение с помощью медиан.

- Работа с выбросами и транмформацией распределений.

В рамках анализа: 

- Провели: Т-тесты, U-тесты Манна-Уитни, Bootstrap, критерий Хи-Квадрат, тест Фишера. 

- Для всех тестов проверили мощность и тенденцию к ошибкам 1го рода.

- С помощью Монте-Карло рассчитали размер необходимой выборки для повышения мощности теста с расчетом Хи-Квадрат при текущем MDE.

3. Сформировали набор из 17 метрик для анализа успешности проведенных внутриигровых событий.


