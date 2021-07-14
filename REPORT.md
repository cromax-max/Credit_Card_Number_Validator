# Отчёт о тестировании Credit Card Number Validator

## Краткое описание

10 июля 2021 - 10 июля 2021 было проведено Компонентное (модульное) тестирование приложения Credit Card Number Validator.

На тестирование затрачено: 00:30 ч.

В результате тестирования выявлены следующие дефекты:
* [Значения карт отличные от 16 символов не валидны](https://github.com/cromax-max/Credit_Card_Number_Validator/issues/1#issue-941931983)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* [Задача №1 - Credit Card Number Validator](https://github.com/netology-code/javaqa-homeworks/tree/master/intro#%D0%B7%D0%B0%D0%B4%D0%B0%D1%87%D0%B0-1---credit-card-number-validator)

В качестве тестовых данных использовались данные: [Credit Card Number Generator & Validator](https://www.freeformatter.com/credit-card-number-generator-validator.html)
* 5235807828804066 /ожидаемый результат "Result is OK"
* 2720992154960051 /ожидаемый результат "Result is OK"
* 4664015016514532611 /ожидаемый результат "Result is OK"

Тестирование производилось в следующем окружении:
* Windows10 (64-bit);
* openjdk version "11.0.11" 2021-04-20  
  OpenJDK Runtime Environment AdoptOpenJDK-11.0.11+9 (build 11.0.11+9)  
  OpenJDK 64-Bit Server VM AdoptOpenJDK-11.0.11+9 (build 11.0.11+9, mixed mode)
* IntelliJ IDEA