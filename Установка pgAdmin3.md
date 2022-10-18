# Задание3
## _Установка pgAdmin3_

Пакет pgAdmin4 не доступен для установки из официальных репозиториев Ubuntu. Поэтому мы будем устанавливать его из репозитория pgAdmin4 APT. Для этого сначала необходимо установить данный репозиторий.
<br>
Добавим публичный ключ для репозитория и создадим его конфигурационный файл. Для чего набераем следующие команды:
<br>
```sh
$ curl https://www.pgadmin.org/static/packages_pgadmin_org.pub | sudo apt-key add
$ sudo sh -c 'echo "deb https://ftp.postgresql.org/pub/pgadmin/pgadmin4/apt/$(lsb_release -cs) pgadmin4 main" > /etc/apt/sources.list.d/pgadmin4.list && apt update'
```
<br>

![alt-текст](https://sun9-9.userapi.com/impg/zTeXgg3Pzh5-mWbNsl6gzRHl2ezGTLoGfvPe4g/SLyKecBBp-w.jpg?size=966x548&quality=96&sign=e6d09d4f27e522bdb2f851c4a7285dca&type=album "Текст заголовка логотипа 1")<br>
после чего терминал потребует ввести пароль от учетной записи. Вводим пароль и команду:<br>
```sh
$ sudo apt install postgresql
```
<br>
Так как программа "curl" на данный момент не установленаБ установим ее следуя указаниям терминала и введем команду<br>
```sh
$ sudo apt install curl
```
<br>
Повторим ввод команд 
<br>
```sh
$ curl https://www.pgadmin.org/static/packages_pgadmin_org.pub | sudo apt-key add
$ sudo sh -c 'echo "deb https://ftp.postgresql.org/pub/pgadmin/pgadmin4/apt/$(lsb_release -cs) pgadmin4 main" > /etc/apt/sources.list.d/pgadmin4.list && apt update'
```
<br>

![alt-текст](https://sun9-9.userapi.com/impg/zTeXgg3Pzh5-mWbNsl6gzRHl2ezGTLoGfvPe4g/SLyKecBBp-w.jpg?size=966x548&quality=96&sign=e6d09d4f27e522bdb2f851c4a7285dca&type=album "Текст заголовка логотипа 1")<br>
Вводим команду установки pgAdmin4
```sh
$ sudo apt install pgAdmin4
```
<br>
Однако терминал уведомляет "Не удается найти пакет pgAdmin4". Но это не беда вместо pgAdmin4 можно установить pgAdmin3.
<br>
Вводим команду установки pgAdmin3
<br>
```sh
$ sudo apt install pgAdmin3
```
<br>
![alt-текст](https://sun9-1.userapi.com/impg/B4H2PDeuVZFgjT47wF_XWNJXuLY8622Loc1ZAg/Jq0uQCY4hj8.jpg?size=976x548&quality=96&sign=094767b23d761d8c6295c03bd4a658c1&type=album "Текст заголовка логотипа 1")
<br>
Установка завершена. Проверим наличие приложения.
<br>
![alt-текст](https://sun9-80.userapi.com/impg/t2d1QxUE4rGu0V5PdoQNDmFctn5hCsOiFZcJoQ/CDaPXRj1Dsc.jpg?size=966x548&quality=96&sign=f418c2a09ecf898c60e3d3b363b48327&type=album "Текст заголовка логотипа 1")
<br>
Отлично, pgAdmin3 установлен!

