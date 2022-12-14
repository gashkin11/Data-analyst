# Исследование надежности заемщиков
## Данные

Входные данные от банка — статистика о платёжеспособности клиентов:

- количество детей в семье
- общий трудовой стаж в днях
- возраст клиента в годах
- уровень образования клиента
- идентификатор уровня образования
- семейное положение
- идентификатор семейного положения
- пол клиента
- тип занятости
- имел ли задолженность по возврату кредитов
- ежемесячный доход
- цель получения кредита

## Задача

Заказчик — кредитный отдел банка. Нужно разобраться, влияет ли семейное положение и количество детей клиента на факт погашения кредита в срок. Результаты исследования будут учтены при построении модели кредитного скоринга — специальной системы, которая оценивает способность потенциального заёмщика вернуть кредит банку.

## Описание проекта

На основе данных кредитного отдела банка исследовал влияние семейного положения и количества детей на факт погашения кредита в срок. Была получена информация о данных. Определены и обработаны пропуски. Заменены типы данных на соответствующие хранящимся данным. Удалены дубликаты. Категоризованы данные. Один датафрейм декомпозирован на три.

## Вывод 

В ходе исследования были проверены и подтверждены несколько гипотез:

* Количество детей в семье влияет на факт погашения кредита в срок;
* Статус семейного положения влияет на факт погашения кредита в срок;
* Уровень дохода кредитора влияет на факт погашения кредита в срок;
* Цель кредита влияет на факт погашения кредита в срок.

Рекомендации:

Собрать более полную выборку для повторной проверки всех гипотез, с целью получения более точных результатов исследования данных

## Статус проекта 

Завершен. 

## Навыки и инструменты

Pandas, предобработка данных
