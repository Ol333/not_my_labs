---
title: "ТП. Практика №1"
summary: Списки
description: Списки
draft: false
math: false
weight: 90
robotsNoIndex: true
showToc: false
---
### Задания для самостоятельного выполнения

Склонируйте [этот репозиторий](https://github.com/still-coding/lists) и [вот этот репозиторий](https://github.com/Ol333/lists_intr).

1. Напишите код, который проходит тесты из репозитория - это базовый вариант.
2. На его основе напишите тесты для своего варианта списков.
3. Напишите код, проходящий ваши тесты.
4. Имея отлаженный код списков, проходящий все тесты, используйте его для решения задачи по своему варианту.

В итоге у вас должны быть следующие части практики:
1. Код, проходящий тесты из репозитория.
2. Тесты для своего варианта списков:
    * на Python,
    * на С (неинтрузивный вариант),
    * на С (интрузивный вариант).
3. Код своего варианта списков.
4. Решение задачи во варианту.



#### Варианты заданий

1. Двусвязный список. Узел списка — информация о студенте: фамилия, год рождения, год поступления, оценки по предметам. Студентов, поступивших в нечетном году, занести в другой список (с удалением из первого).
2. Очередь в магазине. Узел очереди: номер, индикатор — является ли человек в очереди ветераном. Переставить ветеранов в начало очереди, сохраняя их порядок.
3. Кольцевой список. Узел - данные об [академиках](https://ru.wikipedia.org/wiki/%D0%9A%D0%B0%D1%82%D0%B5%D0%B3%D0%BE%D1%80%D0%B8%D1%8F:%D0%94%D0%B5%D0%B9%D1%81%D1%82%D0%B2%D0%B8%D1%82%D0%B5%D0%BB%D1%8C%D0%BD%D1%8B%D0%B5_%D1%87%D0%BB%D0%B5%D0%BD%D1%8B_%D0%90%D0%9D_%D0%A1%D0%A1%D0%A1%D0%A0). Сформировать списки с физиками и математиками, упорядоченные по дате избрания в АН.
4. Двусвязный кольцевой список. Узел — информация о [лётчиках](https://ru.wikipedia.org/wiki/%D0%9A%D0%B0%D1%82%D0%B5%D0%B3%D0%BE%D1%80%D0%B8%D1%8F:%D0%9B%D1%91%D1%82%D1%87%D0%B8%D0%BA%D0%B8_%D0%92%D0%B5%D0%BB%D0%B8%D0%BA%D0%BE%D0%B9_%D0%9E%D1%82%D0%B5%D1%87%D0%B5%D1%81%D1%82%D0%B2%D0%B5%D0%BD%D0%BD%D0%BE%D0%B9_%D0%B2%D0%BE%D0%B9%D0%BD%D1%8B): имя, год рождения, звание, число  полетов, число побед, статус (служит, в отставке, погиб в бою, пропал без вести). Получить список лётчиков в отставке.
5. Хоккейные команды. Два стека: [ВХЛ](https://ru.wikipedia.org/wiki/%D0%92%D1%81%D0%B5%D1%80%D0%BE%D1%81%D1%81%D0%B8%D0%B9%D1%81%D0%BA%D0%B0%D1%8F_%D1%85%D0%BE%D0%BA%D0%BA%D0%B5%D0%B9%D0%BD%D0%B0%D1%8F_%D0%BB%D0%B8%D0%B3%D0%B0) и [КХЛ](https://ru.wikipedia.org/wiki/%D0%9A%D0%BE%D0%BD%D1%82%D0%B8%D0%BD%D0%B5%D0%BD%D1%82%D0%B0%D0%BB%D1%8C%D0%BD%D0%B0%D1%8F_%D1%85%D0%BE%D0%BA%D0%BA%D0%B5%D0%B9%D0%BD%D0%B0%D1%8F_%D0%BB%D0%B8%D0%B3%D0%B0). Запись о команде: название и число набранных очков. 4 лучшие команды ВХЛ перевести в КХЛ, 4 худшие команды КХЛ перевести в ВХЛ (сортировка стека).
6. Дек сотрудников предприятия. Данные: ФИО, пол, возраст, должность, стаж. Разделить мужчин и женщин на два дека и распечатать их.
7. Магазин. Список с товарами (название, категория, цена). Очередь покупателей (покупаемые товары, количество товара). Список с товарами редактируется по мере обслуживания очереди, покупатели, совершившие покупки - удаляются.
8. Двусвязный список [чёрных дыр](https://ru.wikipedia.org/wiki/%D0%A1%D0%BF%D0%B8%D1%81%D0%BE%D0%BA_%D0%BD%D0%B0%D0%B8%D0%B1%D0%BE%D0%BB%D0%B5%D0%B5_%D0%BC%D0%B0%D1%81%D1%81%D0%B8%D0%B2%D0%BD%D1%8B%D1%85_%D1%87%D1%91%D1%80%D0%BD%D1%8B%D1%85_%D0%B4%D1%8B%D1%80). Разделить на три новых списка (квазары, блазары, и нет данных), упорядоченных по массе.
9. Кольцевой список [дистрибутивов Linux](https://en.wikipedia.org/wiki/List_of_Linux_distributions). Извлечь и содать 3 новых списка, упорядоченных по дате появления дистрибутива: Debian-based, Arch-based и Gentoo-based.
10. Двусвязный кольцевой список [морских портов](https://ru.wikipedia.org/wiki/%D0%A1%D0%BF%D0%B8%D1%81%D0%BE%D0%BA_%D0%BC%D0%BE%D1%80%D1%81%D0%BA%D0%B8%D1%85_%D0%BF%D0%BE%D1%80%D1%82%D0%BE%D0%B2_%D0%A0%D0%BE%D1%81%D1%81%D0%B8%D0%B8). Разбить на несколько списков по бассейнам, упорядочив по пропускной способности.
11. Реализовать выполнение арифметических операций с помощью стека и [обратной польской записи](https://ru.wikipedia.org/wiki/%D0%9E%D0%B1%D1%80%D0%B0%D1%82%D0%BD%D0%B0%D1%8F_%D0%BF%D0%BE%D0%BB%D1%8C%D1%81%D0%BA%D0%B0%D1%8F_%D0%B7%D0%B0%D0%BF%D0%B8%D1%81%D1%8C).
12. Дек [экзопланет](https://ru.wikipedia.org/wiki/%D0%A1%D0%BF%D0%B8%D1%81%D0%BE%D0%BA_%D1%8D%D0%BA%D0%B7%D0%BE%D0%BF%D0%BB%D0%B0%D0%BD%D0%B5%D1%82_%D0%B2_%D0%BE%D0%B1%D0%B8%D1%82%D0%B0%D0%B5%D0%BC%D0%BE%D0%B9_%D0%B7%D0%BE%D0%BD%D0%B5). Упорядочить планеты по расстоянию от Солнца и температуре поверхности.
