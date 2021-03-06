# Отчёт о тестировании Credit Card Number Validator

## Краткое описание

24.11.21 было проведено функциональное тестирование приложения Credit Card Number Validator.

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:
* https://github.com/shade1471/2_Credit-Card-Number-Validator/issues/1#issue-1062164980

## Описание процесса тестирования

В качестве тестовых использовались данные полученные в генераторе номеров кредитных карт доступные по https://www.getcreditcardnumbers.com/generated-credit-card-numbers и https://www.freeformatter.com/credit-card-number-generator-validator.html#fakeNumbers:
* Любые платежные системы с валидным 16-ти значным номером карты, с ожидаемым положительным результатом проверки
* Любые платежные системы с валидным 15-ти значным номером карты, с ожидаемым положительным результатом проверки
* Любые платежные системы с валидным 13-ти значным номером карты, с ожидаемым положительным результатом проверки
* Любые платежные системы с валидным 19-ти значным номером карты, с ожидаемым положительным результатом проверки
* Любые платежные системы с невалидным 16-ти значным номером карты, с ожидаемым отрицательным результатом проверки
* Любые платежные системы с невалидным 19-ти значным номером карты, с ожидаемым отрицательным результатом проверки

Тестирование производилось в следующем окружении:
* ОС Windows 11, 64 bit
* JAVA 11.0.12
* IDEA 2021.2.3