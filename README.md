# Репозиторий по практике Java для 2го курса СПбГЭТУ кафедры МО ЭВМ

## Распределение по командам

Цвет   | Первый           | Второй            | Третий            | Задача
------ | ---------------- | ----------------- | ----------------- | ---------------------------
Blue   | Никитенко (7303) | Шестопалов (7303) | Ермолаев (7303)   | Пятнашки
Red    | Швец (7303)      | Батурин (7303)    | Мищенко (7303)    | Алгоритм Форда — Фалкерсона
Green  | Дегтерева (7303) | Аплачкина (7303)  | Ласковенко (7383) | Алгоритм Форда — Фалкерсона
Yellow | Алексо (7303)    | Бондарчук (7303)  | Овчинников (7304) | Мосты
Orange | Сергеев (7304)   | Нгуен З (7304)    | Нгуен К (7304)    | Алгоритм Форда — Фалкерсона
White  | Запевалов (7304) | Попов (7304)      | Субботин (7304)   | Алгоритм Ахо — Корасик

## Статус выполнения практики

Color  | Intro Task | Use Case + UI | Class Diagram | Version 1 | Version 2 | Final
------ | ---------- | ------------- | ------------- | --------- | --------- | -----
Blue   |     +      |       -       |       -       |     -     |     -     |  -   
Red    |     -      |       -       |       -       |     -     |     -     |  -   
Green  |     -      |       -       |       -       |     -     |     -     |  -   
Yellow |     -      |       -       |       -       |     -     |     -     |  -   
Orange |     -      |       -       |       -       |     -     |     -     |  -   
White  |     -      |       -       |       -       |     -     |     -     |  -   

## Требуемые артефакты

1. В папке doc команды должны лежать:
    * use_case.png - диаграмма сценариев использования приложения
    * class_diagram.png - диаграмма классов модели
    * report.pdf и report.docx - отчеты по практике
2. В папке source команды должны лежать исходные коды, разделеные на пакеты ui, model и controller, а так же пакет test с классами модульного тестирования и pom.xml файл для сборки проекта системой maven
3. В папке bin должен лежать собранный контрольный jar-архив с реализованной программой проекта.

## Этапы выполнения задач практики

1. Выполнить вводное задание.
2. Построить диаграмму сценариев использования (Use Case) используя нотацию UML. Определившись с функционалом требуется сделать прототип пользовательского интерфейса (UI) на Swing-е. 
3. Построить модель решения задачи, описав ее диаграммой классов (Class diagram) в нотации UML (рекомендуется еще диаграмма состояний (State-Machine diagram), а так же реализовать требуемые алгоритмы на собственноручно написанных структурах данных. Проверить корректность алгоритмов при помощи модульного тестирования (использовать библиотеку JUnit, собирать весь проект, тестировать, а так же управлять зависимостями требуется при помощи системы Maven).
4. Связать UI и модель решения задачи посредством промежуточных управляющих классов, передающих данные между UI и моделью. На данном этапе программа уже должна уметь считывать/генерировать данные, а так же корректно показывать результат. Программа должна компилироваться, тестироваться, а так же собираться в jar-архив при помощи системы Maven.
5. Добавление оставленного на конец работы функционала, исправление ошибок программы. Написание отчета согласно шаблону.

## Пояснения

Согласно требованиям кафедры (присылались файлы в архиве первым письмом, в частности "Отчет, спецификация, репозиторий 2019.docx") стедунты должны описать спецификацию разрабатываемого проекта. Наиболее лаконично ее можно выразить при помощи UML диаграмм, а так же DFD - Data Flow Diagram. Последний тип диаграм позволяет определить входные и выходные данные программы, а так же предоставляет возможность по детализации разработки, уточняя реализацию спускаясь ниже по уровню абстракции. Мной рекомендуется именно при помощи UML (DFD по желанию, но рекомендую тоже попробовать - много времени не займет, зато навык и представление о данных инструментах уже будет) выполнить описание спецификации, т.е. первый раздел отчета, ввиду лаконичности и последующей пользы для студентов в плане знаний.

План разработки предлагаю составлять соотнеся свои силы и возможности. В идеале за 5 занятий работа должна быть окончена. Последняя дата: 12 июля. Встречи проходят через день (по четным дням) в 11:40, встреча на кафедре с последующим уточнением аудитории. 

Распределиться рекомендуется следующим образом:
* Первый студент занимается Use case диаграммой и UI.
* Второй студент занимается диаграммой классов и моделью задачи.
* Третий студент занимается тестированием модели и соединением UI с моделью посредством реализации промежуточных управляющих классов, а так же общим оформлением отчетов на основе наработок двух других коллег.

Таким образом все студенты так или иначе занимаются написанием кода, документации своей работы, все студенты должны принимать участие в работе с репозиторием.

Студенты вольны распределиться иначе, но в любом случае от каждого требуется знание Java, работа с кодом и документация своей деятельности в отчете.

Все вопросы и предложения вне встреч пишите посредством создания issue на гитхабе. Во время встреч будет проверяться pull-request команды, который она должна выслать до 8 утра в день встречи, отразив все те наработки, которые она считает важными и достойными для закрепления и демонстрации.

в папке materials лежат презентация по UML и шаблон отчета. 

## Рекомендуемые ресурсы

1. Герберт Шилдт, Java 8. "Полное руководство" - Java вообще.
2. Кей Хорстманн, "Java. Библиотека профессионала" Том 1 и 2 - Java и Core-библиотеки, включая Swing.
3. draw.io - для рисования диаграмм.
4. www.apache-maven.ru - про maven.
