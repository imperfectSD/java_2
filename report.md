# Отчёт о тестировании Credit Card Number Validator #

**Краткое описание**

16.01.2021 было проведено функциональное тестирование приложения Credit Card Number Validator.

На тестирование затрачено: 1 час

**В результате тестирования были выявлены следующие дефекты:**

1. [При отправке номера карты системы American Express вывод приложения выдаёт FAIL](https://github.com/imperfectSD/java_2/issues/1)
2. [При отправке номера карты системы Diners Club - International вывод приложения выдаёт FAIL](https://github.com/imperfectSD/java_2/issues/2)
3. [При отправке номера карты системы Diners Club - Carte Blanche вывод приложения выдаёт FAIL](https://github.com/imperfectSD/java_2/issues/3)

**В качестве тестовых данных использовались данные:**

1. [Руководство по установке IntelliJ IDEA](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md)
2. [Credit Card Number Generator](https://www.freeformatter.com/credit-card-number-generator-validator.html)

**Тестирование производилось в следующем окружении:**

* Устройство: HUAWEI Honor MagicBook 14
* ОС: Windows 10 Home
* Версия Java: 11.0.9.1 2020-11-04
