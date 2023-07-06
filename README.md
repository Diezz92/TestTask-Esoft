# Тестовое задание для кандидата на вакансию “Специалист по тестированию ПО”


## Все задания выполнены на окружении:
Windows 11 Pro 21Н2, Яндекс.Браузер, версия 23.5.3.904 (64-bit). <br> За основу взят пример из задания: [Ссылка](https://www.etagi.com/zastr/jk/pervaya-liniya-plyazh-7972/)

## 1. Составить чек-лист для проверки страницы новостройки.
* [Чек-лист](https://docs.google.com/spreadsheets/d/1GMS2Cj2aQKm1pma9ZlhgvjAeDJJdqX-9cz5Rt1tQPGU/edit?usp=sharing)
#### *Примечание:*
Приоритизация общая.

## 2. Составить тест-кейс для фильтра на странице новостройки.
* [Тест-кейс](https://docs.google.com/spreadsheets/d/1Mob2OA226ow47J3SHbi8HDvRBhLkVFp6ZtLIMg8Ph4I/edit?usp=sharing)
  
## 3. Найти и описать максимальное количество дефектов на странице новостройки в формате: краткое описание + серьезность дефекта.
* [Дефекты](https://docs.google.com/document/d/1uKHS6jIXC4iZ1bj-g7qUNkij_VtVD1qh7I7UTZlP3ME/edit?usp=sharing)

## 4. Выделить самый критичный из найденных дефектов и составить по нему баг-репорт в формате: сценарий воспроизведения, фактический и ожидаемый результат, приоритет и серьезность дефекта.
* [Баг-репорт](https://docs.google.com/document/d/1Emahfr9iptuKvESoOW7DM19Byjd62ub2ab7PjoOw8LY/edit?usp=sharing)

## Дополнительное задание: SQL
Необходимо написать запросы, которые выводят:
1.	Город и номер телефона клиентов только с фамилией «Попов»
* *SELECT city, phone FROM customers WHERE fio LIKE ’Попов%’*
  
2.	Количество клиентов из Тюмени
* *SELECT COUNT (fio) FROM customers WHERE city=’Тюмень’*
