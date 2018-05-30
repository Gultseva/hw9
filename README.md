#Регулярные выражения

(Все регулярные выгажения даются в кавычках) 

##1.Удалить все пустые строки

Я использовала регулярное выражение: "\n+ +\n+"

И заменила все вхождения на: "\n"

![](https://pp.userapi.com/c845521/v845521463/67fca/3GbQqT1yJMM.jpg)

##2.Найти всех князей и города, имя и название которых оканчивается на "слав"

Я использовала регулярное выражение: "[А-Я][а-я]*слав[^\s.,\?!:;-]{0,4}"

Всего упоминаний о князьях и городах: 592

![](https://pp.userapi.com/c845521/v845521463/67fe8/Icka1XuIJQY.jpg)

##3.Найти все упоминания Новгорода

Я использовала регулярное выражение: "Новъ?городъ?[^\s.,\?!:;-]{0,4}"
 
Всего упоминаний Новгорода: 9

![](https://pp.userapi.com/c845521/v845521463/67ff2/cjdR_zAqTSc.jpg)

##4.Пробелы после знаков препинания (Бонус)

Все действия и регулярные выражения представлены в скриншотах

![](https://pp.userapi.com/c845521/v845521463/68009/6AV0s9279rM.jpg)
![](https://pp.userapi.com/c845521/v845521463/68013/RusKGWHsE1g.jpg)
![](https://pp.userapi.com/c845521/v845521463/6801d/uX9INvU-Eeo.jpg)
![](https://pp.userapi.com/c845521/v845521463/68027/XCovC6nM10g.jpg)
