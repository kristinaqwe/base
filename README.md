ЛР1

Выберите из таблицы orders все заказы
SELECT * FROM orders

![image](https://github.com/user-attachments/assets/1b866fb4-4469-4e3e-92df-82d362075864)

Выберите из таблицы orders все заказы кроме новых. У новых заказов status равен "new". Использовать in

SELECT * FROM orders WHERE STATUS IN ('cancelled','in_progress','delivery')

![image](https://github.com/user-attachments/assets/db90c63f-44aa-4a43-852f-0a1994980910)

Выберите из таблицы orders все новые и отмененные заказы. У отмененных заказов status равен "cancelled". У новых заказов status равен "new".

![image](https://github.com/user-attachments/assets/1bab57a8-2ed4-4a74-b9c7-f5403e1c4679)

Выберите из таблицы orders все заказы содержащие более 3 товаров (products_count). Вывести нужно только номер (id) и сумму (sum) заказа.

![image](https://github.com/user-attachments/assets/f7b5ad58-4a12-40ee-803d-27d07851cab8)

2 Лр

Выберите из таблицы orders 3 самых дешевых заказа за всё время. Данные нужно отсортировать в порядке убывания цены. Отмененные заказы не учитывайте. 

![image](https://github.com/user-attachments/assets/cc53d70b-f7b6-4f3f-912e-9d5267c7e3fc)

Выберите из таблицы orders 2 самых дорогих заказов за всё время. Данные нужно отсортировать в порядке убывания цены. Отмененные заказы не учитывайте.
SELECT * FROM orders WHERE

 ![image](https://github.com/user-attachments/assets/0157b75e-b031-468f-a460-b8980688787f)

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

