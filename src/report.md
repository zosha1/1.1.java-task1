# Отчёт о тестировании Credit Card Number Validator

## Краткое описание

11.05.2021 - 11.05.2021 было проведено функциональное тестирование компонетна приложения Credit Card Number Validator.

На тестирование затрачено: 1,5 часа

В результате тестирования выявлены следующие дефекты:
* [Баг 1](https://github.com/zosha1/1.1.java-task1/issues/1)
* [Баг 2](https://github.com/zosha1/1.1.java-task1/issues/2)
* [Баг 3](https://github.com/zosha1/1.1.java-task1/issues/3)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* [credit card number generator](https://www.freeformatter.com/credit-card-number-generator-validator.html)

В качестве тестовых данных использовались данные из [credit card number generator](https://www.freeformatter.com/credit-card-number-generator-validator.html):
* 4485936831440063184 **ожидаемый результат:** Result is OK
* 30490924028175 **ожидаемый результат:** Result is OK
* 378626170600833 **ожидаемый результат:** Result is OK
* 4844574665658940 **ожидаемый результат:** Result is OK

Тестирование производилось в следующем окружении:
* MacBook Air, macOS
* Java 11
* IntelliJ IDEA