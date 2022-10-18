# Задание2
## _Установка PostgreSQL_

Поскольку PostgreSQL устанавливается из стандартных репозиториев Ubuntu, для запуска установки подключимся к нашему серверу под учётной записью, входящей в группу sudo, и наберем в командной строке:
<br>
```sh
$ sudo apt update
```
<br>

![alt-текст](https://sun9-57.userapi.com/impg/vlhZ44dLgZsStvXw-c2FG59BHomJpXVbIWgNnQ/f6JZ6vvA288.jpg?size=960x548&quality=96&sign=c1702077ac5324d46a503c08f95dd4ca&type=album "Текст заголовка логотипа 1")<br>
после чего терминал потребует ввести пароль от учетной записи. Вводим пароль и команду:<br>
```sh
$ sudo apt install postgresql
```

![alt-текст](https://sun9-1.userapi.com/impg/MBrb15FSPlOHGNzpEWN0FoPfWUGtzWOz7xVBPQ/A8FxOzQ4yHg.jpg?size=974x548&quality=96&sign=f2f1419b1aed450d86b2dbbde5b23646&type=album "Текст заголовка логотипа 1")<br>
При установке пакета инсталлятор создаст новый PostgreSQL-кластер. Данный кластер представляет из себя коллекцию баз данных, которая управляется одним сервером. Также, установщик создаст рабочие директории для PostgreSQL. Данные, необходимые для работы PostgreSQL, будут находится в каталоге /var/lib/postgresql/12/main, а файлы конфигурации – в каталоге /etc/postgresql/12/main.<br>

После завершения установки убедимся, что служба PostgreSQL активна. Для чего в командной строке набераем:<br>
```sh
$ sudo systemctl is-active postgresql
```
<br>
![alt-текст](https://sun9-64.userapi.com/impg/H5N8zhU_aWBoBS4RMIqtEkO78WNctDy8O1GOGg/1AkuM6dYpzc.jpg?size=976x548&quality=96&sign=39f7d28d1c8174dad062bb01fc97cebc&type=album "Текст заголовка логотипа 1")<br>
Отлично, служба PostgreSQL активна!
