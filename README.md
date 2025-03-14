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

Добавьте в таблицу orders данные о новом заказе стоимостью 8000 рублей. В заказе 4 товара (products).

![image](https://github.com/user-attachments/assets/fadda9c3-b421-4e29-adc2-5f8ad14a2b3a)

![image](https://github.com/user-attachments/assets/d3a3b3b3-2424-440f-9650-48b1d1fc32af)

Добавьте в таблицу products новый товар — «VR-очки», стоимостью 70000 рублей в количестве (count) 2 штук.

![image](https://github.com/user-attachments/assets/64ab3a8e-2553-4c62-a39c-ccd5bb605d64)

![image](https://github.com/user-attachments/assets/b80a5818-5c38-4383-8a93-a35a5c27ff86)

В таблицу products внесли данные с ошибкой, вместо "PS5" в наименовании написали IMAC. Исправьте ошибку.

![image](https://github.com/user-attachments/assets/f0af3d88-fedf-4bd1-abe3-4603dcfb79d2)

![image](https://github.com/user-attachments/assets/f89fdd8c-b4bf-43ec-99ca-ba5e17c61992)

ЛР3

Создайте таблицу users с полем id типа INT и двумя текстовыми полями, которые будут хранить имя (first_name) и фамилию (last_name). Длина имени и фамилии не превышает 50 символов.

Добавьте в таблицу трех пользователей: Дмитрия Иванова, Анатолия Белого и Дениса Давыдова.

![image](https://github.com/user-attachments/assets/412010e6-a4fa-4f43-8c9e-c41192f5efa8)

![image](https://github.com/user-attachments/assets/cade026c-ab63-4d96-9d82-c1702785bad9)

