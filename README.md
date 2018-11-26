# 30
mysql
Д.З
развернуть базу из дампа и настроить репликацию
В материалах приложены ссылки на вагрант для репликации
и дамп базы bet.dmp
базу развернуть на мастере
и настроить чтобы реплицировались таблицы
| bookmaker |
| competition |
| market |
| odds |
| outcome

* Настроить GTID репликацию

варианты которые принимаются к сдаче
- рабочий вагрантафайл - https://github.com/dmirty/30/blob/master/Vagrantfile
- скрины или логи SHOW TABLES- https://github.com/dmirty/30/blob/master/SHOW%20TABLES.JPG
* конфиги
* пример в логе изменения строки и появления строки на реплике https://github.com/dmirty/30/blob/master/INSERT.JPG
