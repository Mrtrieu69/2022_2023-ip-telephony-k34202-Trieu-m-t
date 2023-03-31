University: ITMO University

Faculty: FICT

Course: IP telephony technology

Year: 2023

Group: K34202

Author: Trieu Minh Tam

Lab: Lab2

Date of create: 31.03.2022

Date of finished:

Тема работы: Построение сети ip-телефонии между удаленными маршрутизаторами

Цель работы: Изучить построение сети IP-телефонии между удаленными филиалами с помощью маршрутизаторов Cisco 2811 и коммутаторов Cisco 2950Т.Изучить построение сети IP-телефонии между удаленными филиалами с помощью маршрутизаторов Cisco 2811 и Cisco 2600XM.

Ход работы:
Собрана схема соединения, указанная на рисунке 1.
![image](https://user-images.githubusercontent.com/87965299/229058576-37014d74-01a4-4a8a-b508-0ee7f190e4cb.png)

Настроен интерфейс fa0/0 на маршрутизаторах Cisco 2811.
![image](https://user-images.githubusercontent.com/87965299/229044632-478bb467-c9a9-4eee-80cb-b4be9d2606a9.png)

Настроен интерфейс s0/3/0 на маршрутизаторах Cisco 2811.
![image](https://user-images.githubusercontent.com/87965299/229044701-28e0fe12-3785-437a-9277-a0f18fb0a1d3.png)
![image](https://user-images.githubusercontent.com/87965299/229044848-0a313117-5f6a-4f95-928c-a9922ca9c377.png)

Настроен маршрутизатор Cisco 2811, коммутатор Cisco 3950Т, IP-телефоны аналогично лабораторной работе №2.
![image](https://user-images.githubusercontent.com/87965299/229050223-1d035bd2-2045-4236-932b-20d8fa8e15c2.png)
![image](https://user-images.githubusercontent.com/87965299/229054472-3fee0b07-ffe9-4ec0-b6f9-03be5954d9c3.png)

Настроены DHCP сервера на маршрутизаторах для передачи голоса и данных между ними.
![image](https://user-images.githubusercontent.com/87965299/229058342-801080e1-2715-4633-81ab-a98b67e767f8.png)

Настроена динамическая маршрутизация RIP между маршрутизаторами для передачи информации друг другу.
![image](https://user-images.githubusercontent.com/87965299/229058972-13906fa0-59ea-4072-9b87-7446863632dd.png)

Настроены услуги телефонии Cisco CallManager Express на маршрутизаторе 2811.
![image](https://user-images.githubusercontent.com/87965299/229059395-98ac9a3b-6075-4203-bef5-d9c95c422f50.png)
![image](https://user-images.githubusercontent.com/87965299/229059638-99ff83c4-0865-40b5-afea-03dab65ad5e5.png)
![image](https://user-images.githubusercontent.com/87965299/229059922-297236cb-1229-4e92-b997-f3c13b773fb7.png)

Проверены вызовы между удаленными IP-телефонами.
![image](https://user-images.githubusercontent.com/87965299/229062006-d009d79e-b1d7-41bc-bcae-1c6ce20c632a.png)

Вывод:
В ходе выполнения лабораторной работы было изучено построение сети IP-телефонии между удаленными филиалами с помощью маршрутизаторов Cisco 2811 и коммутаторов Cisco 2950Т, при помощью инструментов Cisco Packet Tracer.
