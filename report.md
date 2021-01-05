# Отчет о тестировании Credit Card Number Validator
## Краткое описание

04.01.2020-04.01.2020 было проведено функциональное тестирование приложения Credit Card Number Validator.
На тестирование затрачено 1 час

В результате тестирования выявлены следующие дефекты:
* [ключи, которые заявлены как валидные: 80b427f8-92cd-3aae-ba04-3927fbe17c6 и 387eedc6-12e9-3b32-9881-63b6b5e85317 являются невалидными](https://github.com/helenkhim/fisthomework1.1/issues/1)
* 15 значные номера карт системы American Express не валидны
* 11 значные номера карт Dankort (PBS) не валидны
* 14 значные номера карт Dinners Club не валидны
* 13 значные номера карт Visa не валидны
## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* [руководство по установке IntelliJ IDEA](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md) 


В качестве тестовых данных использовались [сгенерированные номера карт](https://www.kobzarev.com/other/testoviye-nomera-kreditnyh-kart/)

Тип карты		Длина	Номер		
American Express	15	378282246310005	
American Express	15	371449635398431	
Amex Corporate		15	378734493671000	
Australian BankCard	16	561059108101825
Dankort (PBS)		11	76009244561	
Dankort (PBS)		16	5019717010103742	
Dinners Club		14	38520000023237	
Dinners Club		14	30569309025904	
Discover		16	6011111111111117	
Discover		16	6011000990139424	
JCB			16	3530111333300000	
JCB			16	3566002020360505	
Master Card		16	5105105105105100	
Master Card		16	5555555555554444	
Switch/Solo (Paymentech)16	6331101999990016
Visa			13	4222222222222	
Visa			16	4111111111111111
Visa			16	4012888888881881
Visa			16	4300000000000777
 
 Тестирование производилось в следующем окружении:
* Windows 10 64bit
* Java 11.0.9.1
