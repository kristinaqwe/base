ЛР1
![image](https://github.com/user-attachments/assets/1416db84-28fe-4bc4-975a-f83d2350c791)
Выберите из таблицы orders все заказы
SELECT * FROM orders
![image](https://github.com/user-attachments/assets/3ff06dfa-1e41-4dc3-87ca-58fb60ed4cd5)
Выберите из таблицы orders все заказы кроме новых. У новых заказов status равен "new". Использовать in
SELECT * FROM orders WHERE STATUS IN ('cancelled','in_progress','delivery')
![image](https://github.com/user-attachments/assets/7de17470-2117-416d-8c97-e628f8f2d7db)
Выберите из таблицы orders все новые и отмененные заказы. У отмененных заказов status равен "cancelled". У новых заказов status равен "new".
SELECT * FROM orders WHERE STATUS IN ('cancelled','new')
![image](https://github.com/user-attachments/assets/db6d3a42-b74b-4ab8-a7a7-f281d1539d07)
Выберите из таблицы orders все заказы содержащие более 3 товаров (products_count). Вывести нужно только номер (id) и сумму (sum) заказа.
SELECT id, sum FROM orders WHERE products_count > 3
![image](https://github.com/user-attachments/assets/b1216515-95ed-46c9-8106-997341a149bf)

2 Лр
Выберите из таблицы orders 3 самых дешевых заказа за всё время. Данные нужно отсортировать в порядке убывания цены. Отмененные заказы не учитывайте.
SELECT * FROM orders WHERE status != 'cancelled' ORDER BY sum ASC LIMIT 3;
![image](https://github.com/user-attachments/assets/77cb7c91-c06c-45a8-b63b-b8c029905a1b)
Выберите из таблицы orders 2 самых дорогих заказов за всё время. Данные нужно отсортировать в порядке убывания цены. Отмененные заказы не учитывайте.
SELECT * FROM orders WHERE

![image](https://github.com/user-attachments/assets/7de17470-2117-416d-8c97-e628f8f2d7db) 
