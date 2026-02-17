# Дәріханалардағы дәрілік заттарды басқару жүйесі (PostgreSQL)

## Файлдар
- pharmacy_management.sql — DDL (tables, constraints, indexes) + roles/grants + test queries
- er_diagram.png — ER-диаграмма

## Схема
Барлық объектілер: `pharmacy` схемасында.

## Рөлдер
- pharmacy_admin — толық құқық
- pharmacist — дәрі/партия/қоймаға өңдеу, сатуды оқу
- cashier — сату енгізу, тауарды оқу

## Тест сұраныстар
SQL файлдың соңында `-- TEST QUERIES` бөлімінде берілген.
