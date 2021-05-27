hello new file 
Для работы FDU необходима запущенная служба СУБД PostgreSQL со следующими
параметрами:
Логин: postgres
Пароль: postgres
Имя базы данных: discount
При необходимости базу данных можно создать самому через утилиту PGadmin, которая
входит в комплект PostgreSQL.
1.1.2. Установка на Linux (Ubuntu 15, 16LTS)
Поставить PostgreSQL, поставить пакет FDU командой:
$ sudo dpkg -i <имя deb-пакета FDU>
Запустить службу:
$ sudo service frontol-du start
