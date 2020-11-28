# Практическое задание
## Введение в наследование

В этом практическом задании вам необходимо создать несколько
классов. 

Внимательно читайте задание.

Перед отправкой выполненного задания запускайте автотесты

## Задание 1

Разработать и протестировать набор классов для решения 
задачи подсчета зароботной платы сотрудников некоторой фирмы.

На фирме есть несколько способов оплаты труда:

* ставка – указывается, сколько сотрудник получает за
рабочий день; для каждого сотрудника записывается,
сколько дней он отработал в месяце;
* почасовая – указывается, сколько сотрудник получает в
час, для каждого сотрудника; записывается, сколько часов
он отработал в месяце
* сдельная – указывается, сколько сотрудник получит за
выполненную работу; для каждого сотрудника записываются
суммы для каждой работы, что он успел сделать за месяц.

Программа должна уметь выводить отчет по всем сотрудникам фирмы 
о заработной плате в виде:

  ФИО    |  Вид оплаты  |  Сумма
---------|--------------|------------
 Иванов  |    ставка    |  3000 грн
 Сидоров |   почасовая  |  800 грн
 Петров  |    сдельная  |  5500 грн
 Итого   |              |   9300 грн
 
## Задание 2
 
 Для предыдущего задания вывести отчет с учетом налогов. 
 * Для сотрудников, которые на ставке и почасовой оплате – налог 20%.
 * Для сотрудников со сдельной оплатой труда – 15%.
 
 Программа должна уметь выводить отчет по всем сотрудникам фирмы о заработной плате в виде:
 
  ФИО    |  Налог, % | Сумма (грн) | К оплате (грн)
---------|-----------|-------------|---------------
 Иванов  |   20%     |  3000       |    2400
 Сидоров |   20%     |   800       |     640
 Петров  |   15%     |   5500      |    4675
  Итого   |          |             |    7865
  
 
## Задание 3
 
На основе предыдущего задания сделать новый отчет
таким образом, что для сотрудников, у которых нет детей,
ставка налога выше на 5%.

## Задание 4

На основе предыдущего задания переделать отчет, с учетом того, 
что сотрудники с почасовой оплатой, половину
зарплаты получают в валюте (тугриках), по курсу на день
начисления заработной платы.
   
   ФИО     | Налог, % | Сумма (грн)  |    К оплате (грн/тугрики) Курс 1/8
-----------|----------|--------------|-----------------
   Иванов  |  20%     |  3000        |       2400
   Сидоров |  20%     |   800        |     320 / 40
   Петров  |  15%     |  5500        |       4675

## Задание 5
   
Фирма переводит часть сотрудников в офшорную зону.
Сотрудники, находящиеся в офшоре, не платят налогов. 
Создать новый отчет с учетом данного нововведения.
   
## Задание 6
   
Фирма вводит премии в 20% сотрудникам, которые работали
больше 200 часов в месяц, но не находятся в офшоре. 
Премии должны суммироваться в основную зарплату. Создать
новый отчет с учетом изменений.