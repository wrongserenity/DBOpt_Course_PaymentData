# DBOpt_Course_PaymentData
Задание к курсу Оптимизация баз данных - расчёт балансов

## Порядок выполнения и взаимодействия
1. Все вопросы оформлять в виде Issue
2. Все изменения и результаты оформлять в виде Pull Request из собственного fork

## Требования к окружению
MS SQL Server любой версии (предпочтительно 2016 и старше).
Допустимо использование иной СУБД при портировании исходного скрипта с учётом конечного диалекта SQL.
## Начальные действия
1. Ознакомиться с документом, описывающим формулы расчёта баланса и примером его изменения
2. Ознакомиться со скриптом создания базы данных
3. Ознакомиться с программными компонентами (функции, триггера)
4. Разработать и применить генератор тестовых данных
5. Разаботать простой тест на корректность расчёта баланса

Ожидаемый результат - доступная для оптимизации БД с тестовыми данными

## Задачи первого уровня
1. Реализовать индексы, повышающие производительность операций вставки и изменения платежей без модификации программных компонент
