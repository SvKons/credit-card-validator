# Отчёт о тестировании Credit Card Number Validator

## Краткое описание

Дата проведения тестирования 25.07.2021 - 25.07.2021

На тестирование затрачено: 0 ч 20 мин

В результате тестирования выявлены следующие дефекты:
* <ссылка на описание дефекта>
* <ссылка на описание дефекта>
* <ссылка на описание дефекта>

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* Программа IntelliJ idea
* Валидные и невалидные номера банковских карт
* Файл Main.java

В качестве тестовых данных использовались данные <code>[Credit Card Number Generator & Validator](https://www.freeformatter.com/credit-card-number-generator-validator.html)
</code> :
* **Visa**
  
  * 4556883698036794 - Result is OK
  * 4716122080701369 - Result is OK
  * 4916106658982578602 - Result is FAIL
    
* **Discover**
  
  * 6011377869205605 - Result is OK
  * 6011604373311441 - Result is OK
  * 6011725397521903059 - Result is FAIL
    
* **Diners Club - Carte Blanche**
  
  * 30439097442507 - Result is FAIL
  * 30089019168795 - Result is FAIL
  * 30530741343305 - Result is FAIL
    
* **Visa Electron**
  
  * 4508386187017878 - Result is OK
  * 4917307120318400 Result is OK 
  * 4508781042243174 - Result is OK
    
* **MasterCard**
  
  * 5124372976754567 - Result is OK
  * 5142883422657392 - Result is OK
  * 2720994358476348 - Result is OK
    
* **JCB**
  
  * 3539381460726134 - Result is OK
  * 3541276991436235 - Result is OK
  * 3589499416361513331 - Result is FAIL
    
* **Diners Club - International**
  
  * 36320881256721 - Result is FAIL
  * 36809933575088- Result is FAIL
  * 36758478738876 - Result is FAIL
    
* **InstaPayment**
  
  * 6391748377629744 - Result is OK
  * 6380395763063154 - Result is OK
  * 6375452649845366 - Result is OK
    
* **American Express (AMEX)**
  
  * 378484841303704 - Result is FAIL
  * 343890175120575 - Result is FAIL
  * 372779738263028 - Result is FAIL
    
* **Diners Club - North America**
  
  * 5484887258801863 - Result is OK
  * 5462337580717649 - Result is OK
  * 5424757173931074 - Result is OK
    
* **Maestro**
  
  * 6759266201390892 - Result is OK
  * 6762596350941839 - Result is OK
  * 5020350915877785 - Result is OK  



Тестирование производилось в следующем окружении:
* Windows 10 Домашняя 64-разрядная ОС, процессор x64
* Java version "11.0.11" 2021-04-20
