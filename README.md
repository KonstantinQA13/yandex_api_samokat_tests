﻿# Тест на создание  заказа клиентом и проверку, что по треку заказа можно получить данные о заказе в Яндекс.Самокате с помощью API Яндекс.Самокат.
- Для запуска тестов должны быть установлены пакеты pytest и requests
- Запуск всех тестов выполянется командой pytest

- Код тестов находится "po_treku_zakaza_poluchit_dannie_o_zakaze_test"
- Основные функции описны в файле "otpravka_zaprosov"
    - post_new_order - Создание заказа;
    - get_order_by_track - Получение заказа по трек номеру, принимает в качестве параметра трек номер;
- Примеры тела запросов можно посмотреть в файле "data.py".
