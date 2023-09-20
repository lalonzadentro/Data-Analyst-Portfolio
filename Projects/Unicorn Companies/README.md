# Описание проекта
Цель данного проекта — анализ набора данных **Unicorn Companies** для выявления общих закономерностей и интересных инсайтов.

## ℹ️ Источник данных
Набор данных из [Maven Analytics's Data Playground](https://mavenanalytics.io/data-playground?page=2)

## 🐍 Код с очисткой и анализом данных

## 🏆 Цели
* Найти общие закономерности для компаний-единорогов, получивших наибольшую инвестиционную оценку.
* Выделить регионы (региональные центры), в которых находятся штаб-квартиры самых успешных компаний/ большинства компаний

## ❓ Вопросы для изучения


## ✅ Выполнено
* Очистка данных
* Анализ данных
* Описание выводов и инсайтов
  
## 🧗 Сложности
* столбцы "Оценка" и "Финансирование" содержали разные измерения (миллионы и миллиарды)
* В столбцах "Оценка" и "Финансирование" изначально присутствовали данные с типом объекта, содержащим валюту, число и B или M в одной ячейке (пример - "$180M")
* Для некоторых компаний не хватало данных для столбца "Город". Для замены Null значения в этом столбце, я использовала столицы стран из столбца "Страна".


## 🛠 Стек:

* **Python:* *
  * Pandas
  * Numpy
  * Matplotlib
  * Seaborn



</br></br>
## 🇬🇧In English
# Project's Description
This project aims to analyze a dataset of **Unicorn Companies** to uncover common patterns and interesting insights.

✅ 
* **Data Collecting, Cleaning and Analysis** for this project could be found here.
* **Data Visualisation** for this project could be found here.
* The article about the **insights from this analysis** could be found here.

# Summary

## ℹ️ Data source
Dataset from [Maven Analytics's Data Playground](https://mavenanalytics.io/data-playground?page=2)

## 🏆 Goals
* Find common patterns of companies that received the highest valuation
* Gain curious insights

## ❓ Questions to cover

## ✅ Performed
* Data Cleaning
* Data Analysis
* Presenting conclusions and insights
* 
## 🧗 Challenges
* 'Valuation' and 'Funding' columns containeddifferent measurements (millions and billions)
* 'Valuation' and 'Funding' columns initially had data with the object type that contained currency, number and B or M at one cell (example – '$180M')
* There were missing data for a column 'City' for some companies — I handled it using the capital of the Country


## 🛠 Stack:

* **Python:**
  * Pandas
  * Numpy
  * Matplotlib
  * Seaborn
