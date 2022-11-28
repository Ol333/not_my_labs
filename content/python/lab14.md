---
title: "Python. Лабораторная работа №14"
summary: Работа с БД через SQLAlchemy
description: Работа с БД через SQLAlchemy
draft: false
math: false
weight: 140
robotsNoIndex: true
showToc: false
---

### Задания для самостоятельного выполнения

Создайте объектно-реляционную модель классов и приложение для работы с БД. Необходимо реализовать заполнение БД, а также вывод данных по запросу.

### Варианты заданий

**1. Преподаватели кафедр**

{{< svg "static/images/python_lab14_1.svg" >}}

Запросы:
* Все преподаватели: «ФИО преподавателя», «возраст преподавателя»,  «название кафедры», «должность преподавателя».
* Все кафедры: «название кафедры», «число преподавателей на кафедре».


**2. Животные**

{{< svg "static/images/python_lab14_2.svg" >}}

Запросы:
* Все животные: «кличка», «пол», «возраст», «название корма», «цена корма».
* Все корма: «название корма», «сколько животных им питается».


**3. Дети и врачи**

{{< svg "static/images/python_lab14_3.svg" >}}

Запросы:
* Все дети: «ФИО ребенка», «возраст ребенка», «ФИО врача».
* Все врачи: «ФИО врача», «профессия врача» «сколько детей он лечит».


**4. Товары**

{{< svg "static/images/python_lab14_4.svg" >}}

Запросы:
* Все товары: «№ товара», «название товара», «стоимость товара», «цвет товара», «наличие»
* Все цвета: «цвет товара», «количество товаров».


**5. Контент авторов**

{{< svg "static/images/python_lab14_5.svg" >}}

Запросы:
* Весь контент: «название контента», «раздел», «ник автора» «аннотация».
* Все авторы: «ник автора», «email автора» «число постов».


**6. Сотрудники организаций**

{{< svg "static/images/python_lab14_6.svg" >}}

Запросы:
* Все сотрудники: «ФИО сотрудника», «должность», «организация».
* Все фирмы: «организация», «ИНН», «число сотрудников».


**7. Преподаватели и дисциплины**

{{< svg "static/images/python_lab14_7.svg" >}}

Запросы:
* Все дисциплины: «дисциплина», «ФИО преподавателя», «вид контроля».
* Все преподаватели: «ФИО преподавателя», «число дисциплин».


**8. Расписание**

{{< svg "static/images/python_lab14_8.svg" >}}

Запросы:
* Все дисциплины: «название дисциплины», «день недели», «номер пары».
* Все дни недели: «день недели», «число пар в этот день».


**9. Кафедры и дисциплины**

{{< svg "static/images/python_lab14_9.svg" >}}

Запросы:
* Все дисциплины: «название дисциплины», «лекции», «практики», «лабораторные», «кафедра».
* Все кафедры: «кафедра», «число дисциплин».


**10. Адреса**

{{< svg "static/images/python_lab14_10.svg" >}}

Запросы:
* Все страны: «страна», «код», «список городов».
* Все города: «город», «число улиц».


**11. Автомобили и владельцы**

{{< svg "static/images/python_lab14_11.svg" >}}

Запросы:
* Все автомобили: «марка», «модель», «VIN», «мощность двигателя», «цвет», «ФИО владельца».
* Все владельцы: «ФИО владельца», «число автомобилей в собственности».


**12. Книги**

{{< svg "static/images/python_lab14_12.svg" >}}

Запросы:
* Все книги: «название», «аннотация», «ISBN», «число страниц», «издательство», «авторы».
* Все издательства: «издательство», «город», «количество изданных книг».