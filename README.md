# Оценка результатов призеров ВСОШ в следующем году

## Введение

Соревновательный дух и стремление к интеллектуальному развитию являются ключевыми аспектами Всероссийских школьных олимпиад. Эти мероприятия предоставляют уникальную возможность школьникам продемонстрировать свои знания и способности в различных научных областях. В данной работе я сосредоточился на изучении долгосрочных результатов призеров ВСОШ в течение двух лет: 2022-2023 и 2023-2024 годов. Моя цель - исследовать, оказывает ли статус призера олимпиады влияние на академические достижения учащихся в будущем.

## Методология
### Гипотеза
**Призеры прошлого года будут показывать более высокий результат на текущей олимпиаде**
### Сбор данных

Для исследования были выбраны предметы: Экономиика, Физика, Математика   
По годам: 21-22, 22-23. 23-24.   
Имеющиеся в открытых источниках данные были в формате pdf без возможности редактирования, поэтому были применены методы OCR([сайт](https://tools.pdf24.org/ru/ocr-pdf)) и ручной парсинг полученных txt-файлов.

### Выборка

Для анализа были выбрана когорта учащихся, ставших призерами в прошлом учебном году, что сократило охватываемые в исследовании годы: 22-23, 23-24. Как контрольная группа были выбраны все остальные участники соревнования текущего года.

### Инструменты анализа

Для тестирования гипотез о различиях между призерами и непризерами использовались следующие статистические тесты:

1. **Тест Шапиро-Уилка**: для проверки нормальности распределения полученных баллов.
2. **Тест Левена**: для проверки гомогенности дисперсий двух групп.
3. **T-тест Стьюдента**: для проверки статистически значимых различий между средними значениями двух групп при условии нормальности распределения и равенства дисперсий.
4. **Тест Колмогорова-Смирнова**: для сравнения функций распределения двух выборок и определения статистического различия в их развитии.
5. **Для визуализации использовались графики:** Гистограмма, QQPlot, Boxplot и график доверительных интервалов для средних, если проведение Т-Теста.
6. **Для представления имеющихся графиков был создан дашборд:** [Streamlit](https://statsarospetproject.streamlit.app/)

### Выводы

Анализ показал наличие статистически значимых различий для следующих выборок:
* Математика 22-23 в 10м и 11м классе
* Математика 23-24 в 10м и 11м классе
* Физика 23-24 в 10м классе
* Экономика 22-23 в 10м классе
* Экономика 23-24 в 10м и 11м классе

## Результаты

Гипотеза демонстрирует статистическую достоверность для 66.6 процентов выборок при уровне значимости p=0.05.

Было установлено следующее: 
1) Для группы математиков все четыре анализируемых выборки продемонстрировали статистическую значимость полученных результатов.  
2) Среди экономистов статистическая значимость наблюдалась в трёх из четырёх случаев.  
3) Однако в группе физиков только одна выборка из четырёх подтвердила статистическую значимость результатов.  
4) В 10-м классе 5 из 6 выборок показали статистическую значимость.  
5) В 11-м классе 3 из 6 выборок показали статистическую значимость.  
6) В 22-23 году 3 из 6 выборок показали статистическую значимость.  
7) В 23-24 году 5 из 6 выборок показали статистическую значимость.
## Обсуждение и заключение
В данном исследовании были проанализированы результаты ВСОШ призеров прошлых лет по математике, физике и экономике за 22-23 и 23-24 год. Были обнаружили некоторые интересные тенденции.

Однако, следует отметить, что наши выводы подвержены ряду ограничений. Например, маленький размер выборок, влияние региональных заданий, а также различия в эффективности олимпиадных школ могут оказывать значительное влияние на результаты. Эти факторы не были полностью учтены в данном исследовании.

Тем не менее, наши результаты наводят на мысль о возможном влиянии дополнительных факторов на успех участников в различные годы и предметы. Эти наблюдения подчеркивают важность проведения более глубоких исследований, учитывающих разнообразные факторы, чтобы более точно определить причины различий в результатах участников.


---
