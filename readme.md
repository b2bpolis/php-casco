# Виджет на сайт, для продажи КАСКО

## Описание
Модуль калькулятора расчета стоимости страхования для сайта.

## Установка

1. Загрузить все файлы из данного репозитория на ваш хостинг.
2. Зайти через браузер по ссылке:  `ваш_сайт.ру/index.html` 
   С тестовыми настройками виджет показывает тарифы одной страховой компании
3. Настроить адрес электронной почты для отправки писем с заказами на ваш адрес:
    настраивается в файле: `backend/settings.php`.
4. Для расширения кол-ва страховых компаний, запросите логин и пароль у вашего менеджера в поддержке сервиса Умный полис (helpdesk@b2bpolis.ru)
   Полученный логин/пароль необходимо ввести в в файле `backend/private.php`.
   
   
## Релиз	
Список версий и изменения к ним:

**v.2.1**
- отделили пройденные шаги от не пройденных;
- оставили последние 10 лет (2016-2006) при выборе автомобиля;
- сделали кнопку неактивной до момента заполнения всех необходимых данных на странице;
- починили валидацию возраста/стажа;
- убрали на 3-м этапе информацию по расчету до тех пор, пока нет номера расчета;
- прогресс бар исчезает после загрузки;
- другие мелкие изменения.

**v2.0**
- Калькулятор полностью переписан.

**v3.0**
- Калькулятор переработан, теперь на _Angularjs. Иправлены многие ошибки.





