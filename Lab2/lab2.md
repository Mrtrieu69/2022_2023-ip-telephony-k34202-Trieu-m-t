University: ITMO University

Faculty: FICT

Course: IP telephony technology

Year: 2023

Group: K34202

Author: Trieu Minh Tam

Lab: Lab2

Date of create: 21.03.2022

Date of finished:

Тема работы: Конфигурация voip в среде Сisco packet tracer

Цель работы: Изучить построение сети IP-телефонии с помощью маршрутизатора Cisco 2811, коммутатора Cisco catalyst 3560 и IP телефонов Cisco 7960.

Ход работы:

Создана схема, подключены все устройства</br>
![image](https://user-images.githubusercontent.com/87965299/226693971-74770913-b29b-4cff-a8f4-df26494fc224.png)</br>

В конфигурационном режиме изменено название маршрутизатора на CMERouter.</br>
![image](https://user-images.githubusercontent.com/87965299/226688650-1bfee1f8-0e8d-48d3-a1d0-089dd8fb9090.png)</br>

Отключен синтаксис ввода слов от DNS серверов.</br>
![image](https://user-images.githubusercontent.com/87965299/226689042-1261ab43-4667-4708-8d96-1a07f4b13e2f.png)</br>

Заданы пароли для защиты маршрутизатора как в удаленном режиме, так и в режиме консоли.</br>
![image](https://user-images.githubusercontent.com/87965299/226689714-93e43014-8475-4314-90c6-08f92dac8484.png)</br>

Настроен интерфейс fa0/0 на маршрутизаторе Cisco 2811 (CMERouter).</br>
![image](https://user-images.githubusercontent.com/87965299/226691080-593b5251-39e7-4cc1-a7be-00507c92c477.png)</br>

Настроен DHCP сервер для передачи голоса и данных на маршрутизаторе Cisco 2811.</br>
![image](https://user-images.githubusercontent.com/87965299/226695028-b838f2dd-36a2-4429-8cd0-56de7e308651.png)</br>

Настроить услуги телефонии Cisco CallManager Express на маршрутизаторе 2811.</br>
![image](https://user-images.githubusercontent.com/87965299/226695860-d25726e3-0a30-4437-85f4-ca7bd35ba4b3.png)</br>

Созданы VLAN порты на коммутаторе Cisco Catalyst 3560 для взаимодействия коммутатора с маршрутизатором и подключены IP телефоны.</br>
![image](https://user-images.githubusercontent.com/87965299/226696432-ac9fd498-1077-4eb0-a8ad-279b36e83cbd.png)</br>

Осуществленна настройки IP-телефоноы и их соединение с коммутатором Cisco Catalyst 3560. После чего осуществленны тестовые звонки.</br>
![image](https://user-images.githubusercontent.com/87965299/226697172-bede1aa5-71e0-4444-8f9f-085f11639461.png)</br>

Создана новая схема </br>
![image](https://user-images.githubusercontent.com/87965299/226708379-152b3b4c-9042-449a-a9cc-0b2ee506b26d.png)</br>

Созданы VLAN порты на коммутаторе для взаимодействия коммутатора с маршрутизатором и подключены IP телефоны.</br>
![image](https://user-images.githubusercontent.com/87965299/226700793-cc3b0f0f-978a-45bd-9d1f-51ea88005d5d.png)</br>
![image](https://user-images.githubusercontent.com/87965299/226702030-b2d01794-dee2-4ae9-b32c-4f9133a42816.png)</br>
![image](https://user-images.githubusercontent.com/87965299/226702097-b0d20843-ab77-479d-832f-e2f9e9316f6f.png)</br></br>
![image](https://user-images.githubusercontent.com/87965299/226704086-5c98e876-669a-432c-bf07-2b4fceebe805.png)</br>

Задан маршрут по умолчанию командой ip default-gateway.</br>
![image](https://user-images.githubusercontent.com/87965299/226704862-411e3b92-055f-41e1-b934-236aafc40ed0.png)</br>

Настроен порт как канал типа trunk.</br>
![image](https://user-images.githubusercontent.com/87965299/226705123-d349096c-ea3d-4c25-baea-872e9cf20819.png)</br>

Настроен DHCP сервера для передачи голоса и данных на маршрутизаторе Cisco 2811.</br>
![image](https://user-images.githubusercontent.com/87965299/226705580-3c349994-28c5-4fb8-b590-7af1c2f68cb9.png)</br>

Настроены услуги телефонии Cisco CallManager Express на маршрутизаторе.</br>
![image](https://user-images.githubusercontent.com/87965299/226706109-8c5c3126-9a32-41dd-bcd6-4de36f1438dc.png)</br>
![image](https://user-images.githubusercontent.com/87965299/226706723-2f6ac477-ae31-49cb-869a-26a9594d6a70.png)</br>

Осуществленна настройка IP-телефонов и конечных устройств, а также их соединение с коммутатором. После чего осуществленна проверка звонков между телефонами и пингов между кончеыми узлами.</br>
![image](https://user-images.githubusercontent.com/87965299/226707830-a18eed9a-bd2c-4b5a-8928-9adcc8edb0b3.png)</br>

Вывод: Изучено построение сети IP-телефонии с помощью маршрутизатора Cisco 2811, коммутатора Cisco catalyst 3560 и IP телефонов Cisco 7960.
