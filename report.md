# Отчёт о тестировании "Credit Card Number Validator"
## Краткое описание
14.02.2020 - 14.02.2020 было проведено проверка валидности банковских карт различных организации приложения Credit Card Number Validator

На тестирование затрачено: 30мн

В результате тестирования не выявлены дефекты:

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:

* Тестовый сценарий 
* отчёт тестрирование

В качестве тестовых данных использовались данные https://www.freeformatter.com/credit-card-number-generator-validator.html:

### VISA
* result for 4929878435366751: OK
* Result for 4916529272906598: ОК
### MasterCard  
* Result for 5567158069476083: OK
* Result for 2221007688227572: OK
### Maestro
* Result for 5038287491650899: OK
* Result for 6304094686221659: OK
### VISA Electron
* Result for 4508612218386895: OK
* Result for 4913352505303050: OK

Тестирование производилось в следующем окружении:

* Windows 10 Домашняя для одного языка х64, версия 1909
* OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.6+10)
* OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.6+10, mixed mode)
