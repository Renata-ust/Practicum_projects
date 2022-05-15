# Practicum_projects
Проекты, выполненные в рамках курса Data Science от Яндекс.Практикума

#### Содержание: 

- **Модуль 01** 
  - **Базовый Python** - Project_1 
  - **Предобработка данных** - Project_2
  - **Исследовательский анализ данных** - Project_3
  - **Статистический анализ данных** - Project_4
  - **Сборный проект** - Project_5
  
- **Модуль 02** 
  - **Введение в машинное обучение**:    Решение задачи бинарной классификации с использованием DecissionTreeClassifier, RandomForestClassifier и LogisticRegression - Project_6
  - **Обучение с учителем**: Решение задачи бинарной классификации с использованием DecissionTreeClassifier, RandomForestClassifier и LogisticRegression с кросс-валидацией  - Project_7
  - **Машинное обучение в бизнесе**: Задача регрессии + Bootstrap
 - Project_8
  - **Сборный проект 2**: Предобработка+анализ+обучение регрессионой модели с СV** - Project_9

- **Модуль 03** 
  - **Линейная алгебра**: Регрессия + разработка алгоритма преобразования данных - Project_10
  - **Численные методы**: Decision Tree vs Linear regression vs Catboost vs LightGBM vs XGBoost - Project_11
  - **Временные ряды**: Кросс-валидация во временных рядах - Project_12
  - **Машинное обучение для текстов**: Catboost vs TF-IDF vs BERT - Project_13


## Project_1 
### Базовый Python

На реальных данных Яндекс.Музыки необходимо проверить гипотезы и сравнить поведение пользователей двух городов - Москвы и Санкт-Петербурга.

*Гипотезы:*
1. Активность пользователей зависит от дня недели. Причём в Москве и Петербурге это проявляется по-разному.
2. Утром в понедельник в Москве преобладают одни жанры музыки, а в Петербурге — другие. Это верно и для вечера пятницы.
3. Москва и Петербург предпочитают разные жанры музыки. В Москве чаще слушают поп-музыку, в Петербурге — русский рэп.


## Project_2
### Предобработка данных
Заказчик — кредитный отдел банка. Нужно разобраться, влияет ли семейное положение и количество детей клиента на факт погашения кредита в срок. Входные данные от банка — статистика о платёжеспособности клиентов.
Результаты исследования будут учтены при построении модели кредитного скоринга — специальной системы, которая оценивает способность потенциального заёмщика вернуть кредит банку.


## Project_3
### Исследовательский анализ данных
В вашем распоряжении данные сервиса Яндекс.Недвижимость — архив объявлений о продаже квартир в Санкт-Петербурге и соседних населённых пунктов за несколько лет. Нужно научиться определять рыночную стоимость объектов недвижимости. Ваша задача — установить параметры. Это позволит построить автоматизированную систему: она отследит аномалии и мошенническую деятельность.


## Project_4
### Статистический анализ данных
Вы аналитик компании «Мегалайн» — федерального оператора сотовой связи. Клиентам предлагают два тарифных плана: «Смарт» и «Ультра». Чтобы скорректировать рекламный бюджет, коммерческий департамент хочет понять, какой тариф приносит больше денег.


## Project_5
### Сборный проект
Вы работаете в интернет-магазине «Стримчик», который продаёт по всему миру компьютерные игры. Из открытых источников доступны исторические данные о продажах игр, оценки пользователей и экспертов, жанры и платформы (например, Xbox или PlayStation). Вам нужно выявить определяющие успешность игры закономерности. Это позволит сделать ставку на потенциально популярный продукт и спланировать рекламные кампании.


## Project_6
### Введение в машинное обучение

**Решение задачи бинарной классификации с использованием DecissionTreeClassifier, RandomForestClassifier и LogisticRegression**

Оператор мобильной связи «Мегалайн» выяснил: многие клиенты пользуются архивными тарифами. Они хотят построить систему, способную проанализировать поведение клиентов и предложить пользователям новый тариф: «Смарт» или «Ультра».
В вашем распоряжении данные о поведении клиентов, которые уже перешли на эти тарифы. Нужно построить модель для задачи классификации, которая выберет подходящий тариф.Постройте модель с максимально большим значением accuracy. 


## Project_7
### Обучение с учителем

**Решение задачи бинарной классификации с использованием DecissionTreeClassifier, RandomForestClassifier и LogisticRegression с кросс-валидацией** 

Из «Бета-Банка» стали уходить клиенты. Каждый месяц. Немного, но заметно. Банковские маркетологи посчитали: сохранять текущих клиентов дешевле, чем привлекать новых. Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. Вам предоставлены исторические данные о поведении клиентов и расторжении договоров с банком.


## Project_8
### Машинное обучение в бизнесе

**Задача регрессии + Bootstrap**

Допустим, вы работаете в добывающей компании «ГлавРосГосНефть». Нужно решить, где бурить новую скважину. Вам предоставлены пробы нефти в трёх регионах: в каждом — 100 000 месторождений, где измерили качество нефти и объём её запасов. Постройте модель машинного обучения, которая поможет определить регион, где добыча принесёт наибольшую прибыль.


## Project_9
### Сборный проект 2

**Предобработка+анализ+обучение регрессионой модели с СV**

Подготовьте прототип модели машинного обучения для «Цифры». Компания разрабатывает решения для эффективной работы промышленных предприятий. Модель должна предсказать коэффициент восстановления золота из золотосодержащей руды. В вашем распоряжении данные с параметрами добычи и очистки. Модель поможет оптимизировать производство, чтобы не запускать предприятие с убыточными характеристиками.


## Project_10
### Линейная алгебра

**Регрессия + разработка алгоритма преобразования данных**

Вам нужно защитить данные клиентов страховой компании «Хоть потоп». Разработайте такой метод преобразования данных, чтобы по ним было сложно восстановить персональную информацию.


## Project_11
### Численные методы

**Decision Tree vs Linear regression vs Catboost vs LightGBM vs XGBoost**

Сервис по продаже автомобилей с пробегом «Не бит, не крашен» разрабатывает приложение для привлечения новых клиентов. В нём можно быстро узнать рыночную стоимость своего автомобиля. В вашем распоряжении исторические данные: технические характеристики, комплектации и цены автомобилей. Вам нужно построить модель для определения стоимости.


## Project_12
### Временные ряды

**Кросс-валидация во временных рядах**

Компания «Чётенькое такси» собрала исторические данные о заказах такси в аэропортах. Чтобы привлекать больше водителей в период пиковой нагрузки, нужно спрогнозировать количество заказов такси на следующий час. Постройте модель для такого предсказания.


## Project_13
### Машинное обучение для текстов

**Catboost vs TF-IDF vs BERT**

Интернет-магазин «Викишоп» запускает новый сервис. Теперь пользователи могут редактировать и дополнять описания товаров, как в вики-сообществах. То есть клиенты предлагают свои правки и комментируют изменения других. Магазину нужен инструмент, который будет искать токсичные комментарии и отправлять их на модерацию.
Обучите модель классифицировать комментарии на позитивные и негативные. В вашем распоряжении набор данных с разметкой о токсичности правок.
