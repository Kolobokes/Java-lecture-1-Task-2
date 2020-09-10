# Отчет о тестировании модуля Credit Card Number Validator

## Краткое описание

09.09.2020 - 10.09.2020 было проведено функциональное тестирование модуля Credit Card Number Validator.

На тестирование затрачено: 2 часа

В результате тестирования выявлены следующие дефекты:

- при проверке номера карты 373076784322553 American Express (AMEX), номер карты невалидный ([баг репорт](https://github.com/Kolobokes/Java-lecture-1-Task-2/issues/1#issue-698262373))
- при проверке номера карты 36990808059901 Diners Club - International, номер карты невалидный ([баг репорт](https://github.com/Kolobokes/Java-lecture-1-Task-2/issues/2#issue-698264955))
- при проверке номера карты 3530116812010681833 JCB, номер карты невалидный ([баг репорт](https://github.com/Kolobokes/Java-lecture-1-Task-2/issues/3#issue-698266484))
- при проверке номера карты 30296703775443 Diners Club - Carte Blanche, номер карты невалидный ([баг репорт](https://github.com/Kolobokes/Java-lecture-1-Task-2/issues/4#issue-698270555))
- при проверке номера карты 4024007199080023129 VISA, номер карты невалидный ([баг репорт](https://github.com/Kolobokes/Java-lecture-1-Task-2/issues/5#issue-698271932))

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:

- баг репорты
- отчет о тестировании

В качестве тестовых данных использовались данные [онлайн генератора номеров карт](https://www.freeformatter.com/credit-card-number-generator-validator.html).

Тестирование производилось в следующем окружении:

- ПК
- Windows 10
- IntelliJ IDEA 2020.2.1 (Community Edition)
  Build #IC-202.6948.69, built on August 25, 2020
  Runtime version: 11.0.8+10-b944.31 amd64
  VM: OpenJDK 64-Bit Server VM by JetBrains s.r.o. 
- openjdk version "11.0.8" 2020-07-14
- OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.8+10)
- OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.8+10, mixed mode)

