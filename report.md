# Отчёт о тестировании Credit Card Number Validator

## Краткое описание

12.07.2021 было проведено функциональное тестирование приложения Credit Card Number Validator.

На тестирование затрачено: 0,5 часов.

В результате тестирования выявлены следующие дефекты:
* https://github.com/xeniya-izotowa/Java1/issues/1
* https://github.com/xeniya-izotowa/Java1/issues/2
* https://github.com/xeniya-izotowa/Java1/issues/3
* https://github.com/xeniya-izotowa/Java1/issues/4

## Описание процесса тестирования

В качестве тестовых данных использовались данные из источника : [credit-card-number-generator]: https://www.freeformatter.com/credit-card-number-generator-validator.html
* VISA (4916655433306327, 4532490863947752, 4929921637819934481)
* MasterCard (5294884194347747, 5195628389242464, 5237669775184985)
* American Express (AMEX) (377907938888899, 372746575242449, 376026079651270)
* Discover (6011651551837309, 6011522487559046, 6011069438952663145) 
* JCB (3543330488678714, 3534631061753803)
* Diners Club - North America (5582395228561444, 5458264494303900) 
* Maestro (5893593768969670, 6761405848179336)
* Visa Electron (4026932757556291 4508677829638968)
* InstaPayment (6389255945012340 6376799013731070)

* **Валидные номера карт** --> Expected Result: Status: Result is OK

Тестирование производилось в следующем окружении:
* Windows 10 x64 (19042.1052)
* Java version 11.0.11
