﻿# Отчёт о тестирование " Credit Card Number Validator"

## Краткое описание:
02.03.2021-02.03.2021
было проведено "Функциональное тестирование".
Приложения Credit Card Number Validator .  

На тестирование затрачено: 1час.  


В результате тестирования выявлены следующие дефекты:
* [Карта с номером "3786291369055365"- невалидная](https://github.com/RomanMachnev/Card-Number-Validator/issues/1)


## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* Артефакты не использовались


В качестве тестовых данных использовались данные из "https://www.getcreditcardnumbers.com/" 

Валидные номера:
* 4929307412405960
* 4716324568558812
* 4716546643844995
* 3786291369055365

Невалидные номера:
* 372731433072634
* 370269354948583
* 349110800388073
* 348144276047427

где OK означает, что номер карты валидный, FAIL - невалидный.


 Тестирование производилось в следующем окружении:
* Windows 10.Разрядносность ОП 64.
* Version Java "11.0.10".
