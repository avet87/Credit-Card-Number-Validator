# Отчёт о тестировании <Credit Card Number Validator>
## Краткое описание
<18.01.2021> - <18.01.2021> было проведено позитивное и негативное тестирование функционала приложения "Credit Card Number Validator".

На тестирование затрачено: <3 часа>

**В результате тестирования выявлены следующие дефекты**

* [не распознается карта Visa Electron](https://github.com/avet87/Credit-Card-Number-Validator/issues/1#issue-787805755)
* [не распознается карта ChinaUnion Pay](https://github.com/avet87/Credit-Card-Number-Validator/issues/2#issue-787806542)
* [не распознается карта Maestro](https://github.com/avet87/Credit-Card-Number-Validator/issues/3#issue-787807543)
* не распознается карта American Express

**В качестве тестовых данных использовались данные Credit Card Number Generator**

**Visa**
* 4841669241018032 ожидаемый результат ОК

**MasterCard**
* 5122732357206150 ожидаемый результат ОК

**American Express**
* 378694280608476 ожидаемый результат ОК

**Discover**
* 6011186409448827 ожидаемый результат ОК

#### Тестирование производилось в следующем окружении:
* HP, windows 10, 64 разрядная ОС.
* java version-Java 11
