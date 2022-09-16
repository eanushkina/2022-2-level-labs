git remote add upstream# Лабораторные работы для 2-го курса ФПЛ (2022/2023)

В рамках предмета
["Программирование для лингвистов"](https://www.hse.ru/edu/courses/749664186)
в НИУ ВШЭ - Нижний Новгород.

**Преподаватели:**

* [Демидовский Александр Владимирович](https://www.hse.ru/staff/demidovs) - лектор
* [Тугарёв Артём Михайлович](https://github.com/artyomtugaryov) - преподаватель практики
* [Казюлина Марина Сергеевна](https://github.com/marina-kaz) - академический и технический ассистент
* [Кащихин Андрей Николаевич](https://github.com/WhiteJaeger) - автор лабораторных работ

**План лабораторных работ:**

1. [Лабораторная работа №1. Выделение ключевых слов с помощью частот](./lab_1_keywords_tfidf/README.md)
    1. Дедлайн: `XX` сентября
2. [Лабораторная работа №2 (нет описания)](./README.md)
    1. Дедлайн: `XX` октября
3. [Лабораторная работа №3 (нет описания)](./README.md)
    1. Дедлайн: `XX` ноября
4. [Лабораторная работа №4 (нет описания)](./README.md)
    1. Дедлайн: `XX` декабря

## История занятий

| Дата       | Тема лекции                             | Материалы практики                   |
|:-----------|:----------------------------------------| :--- |
| 02.09.2022 | Преимущества и недостатки языка Python. | N/A |

Более полное содержание пройденных занятий в виде 
[списка ключевых тем](./docs/public/lectures_content_ru.md).

## Литература

### Базовый уровень

1. :books: :us: M. Lutz.
   [Learning Python](https://www.amazon.com/Learning-Python-5th-Mark-Lutz/dp/1449355730).
2. :video_camera: :ru: Хирьянов Т.Ф. Видеолекции.
   [Практика программирования на Python 3](https://www.youtube.com/watch?v=fgf57Sa5A-A&list=PLRDzFCPr95fLuusPXwvOPgXzBL3ZTzybY)
   . 2019.
3. :video_camera: :ru: Хирьянов Т.Ф. Видеолекции.
   [Алгоритмы и структуры данных на Python 3](https://www.youtube.com/watch?v=KdZ4HF1SrFs&list=PLRDzFCPr95fK7tr47883DFUbm4GeOjjc0)
   . 2017.
5. :bookmark: :us: [Официальная документация](https://docs.python.org/3/).

### Продвинутый уровень

1. :books: :us: M. Lutz.
   [Programming Python: Powerful Object-Oriented Programming](https://www.amazon.com/Programming-Python-Powerful-Object-Oriented/dp/0596158106)
2. :books: :us: J. Burton Browning.
   [Pro Python 3: Features and Tools for Professional Development](https://www.amazon.com/Pro-Python-Features-Professional-Development/dp/1484243846)
   . 
3. :video_camera: :ru: Хирьянов Т.Ф. Видеолекции.
   [Основы программирования и анализа данных на Python](https://teach-in.ru/course/python-programming-and-data-analysis-basics)
   . 2022.

## Порядок сдачи и оценивания лабораторной работы

Порядок сдачи:

1. лабораторная работа допускается к очной сдаче.
2. студент объяснил работу программы и показал её в действии.
3. студент выполнил задание ментора по некоторой модификации кода.
4. студент получает оценку:
    1. соответствующую ожидаемой, если все шаги выше выполнены и ментор удовлетворён ответом студента
    2. на балл выше ожидаемой, если все шаги выше выполнены и ментор решает поощрить студента за отличный ответ
    3. на балл ниже ожидаемой, если лабораторная работа сдаётся на неделю позже срока сдачи и выполнены критерии в 4.1
    4. на два балла ниже ожидаемой, если лабораторная работа сдаётся на две недели и позже от срока сдачи и выполнены
       критерии в 4.1

> Замечание: студент может улучшить оценку по лабораторной работе, если после основной сдачи выполнит
> задания следующего уровня сложности
> относительно того уровня, на котором выполнялась реализация.

Лабораторная работа допускается к очной сдаче, если выполнены все пункты ниже:

1. представлена в виде пулл реквеста (Pull Request, PR) с правильно составленным названием по шаблону:
   `Laboratory work #<NUMBER>, <SURNAME> <NAME> - <UNIVERSITY GROUP NAME>`.
   Пример: `Laboratory work #1, Kashchikhin Andrey - 21FPL1`.
2. имеет заполненный файл `target_score.txt` с ожидаемой оценкой. Допустимые значения: 4, 6, 8, 10.
3. имеет "зелёный" статус - автоматические проверки качества и стиля кода, соответствующие заданной ожидаемой оценке,
   удовлетворены.
4. имеет лейбл `done`, выставленный ментором. Означает, что ментор посмотрел код студента и удовлетворён качеством кода.

## Ресурсы

1. [Таблица успеваемости](https://docs.google.com/spreadsheets/d/1MEH1VMmOeVBs1n88x_j_U_jat6JYkDNNKN6v0RJYFyA/edit?usp=sharing)
2. [Инструкция по запуску юнит тестов](./docs/public/tests.md)
3. [Инструкция по подготовке к прохождению курса](./docs/public/starting_guide_ru.md)
4. [Инструкция по настройке и обновлению репозитория](./docs/public/repository_ru.md)
