# Отчет о тестировании Credit Card Number Validator
## Краткое описание

04.01.2020-04.01.2020 было проведено функциональное тестирование приложения Credit Card Number Validator.
На тестирование затрачено 1 час

В результате тестирования выявлены следующие дефекты:
* [15 значные номера карт системы American Express не валидны](https://github.com/helenkhim/-java-1.2/issues/1)
* [15 значные номера карт системы Amex Corporate  не валидны](https://github.com/helenkhim/-java-1.2/issues/2)
* [11 значные номера карт Dankort (PBS) не валидны](https://github.com/helenkhim/-java-1.2/issues/3)
* [14 значные номера карт Dinners Club не валидны](https://github.com/helenkhim/-java-1.2/issues/2)
* [13 значные номера карт Visa не валидны](https://github.com/helenkhim/-java-1.2/issues/5)
## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* [руководство по установке IntelliJ IDEA](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md) 


В качестве тестовых данных использовались [сгенерированные номера карт](https://www.kobzarev.com/other/testoviye-nomera-kreditnyh-kart/)

Тип карты | Длина | номер
------ | ------|----------
American Express      | 15     | 378282246310005
American Express       | 15   | 371449635398431	
Amex Corporate      | 15     | 378734493671000  
Australian BankCard      | 16    | 561059108101825
Dankort (PBS)      | 11   | 76009244561
Dankort (PBS)      | 16      | 5019717010103742  
Dinners Club| 14     |38520000023237
Dinners Club       | 14   | 30569309025904
Discover      |  16     | 6011111111111117	  
Discover       | 16   | 6011000990139424	
JCB      |  16     | 3530111333300000  
JCB    | 16   | 3566002020360505
Master Card    |     16  | 5105105105105100 
Master Card   |     16  | 5555555555554444  
Switch/Solo (Paymentech)       | 16  | 6331101999990016
Visa      |    13   | 4222222222222  
Visa   | 16      | 4012888888881881
Visa       | 16   | 4300000000000777
 
 Тестирование производилось в следующем окружении:
* Windows 10 64bit
* Java 11.0.9.1
