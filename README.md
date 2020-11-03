# Messenger

*Project from course of GeekBrains (III/IV quarter)*

Простой мессенджер разработан на курсе "Клиент-серверные приложения".
Краткое описание приложения и его функционал на YandexDisk

[![YandexDisk](https://icon-icons.com/icons2/1379/PNG/96/folderblueyandexdisk_92979.png)](https://yadi.sk/i/GwjQmY0HlTDVCQ)

### Установка и запуск

###### Установка сервера и клиента
[![PyPI](https://pypi.org/static/images/logo-small.6eef541e.svg)](https://pypi.org/user/GregoryVins/)
```
$ pip install Vins__server_messenger
$ pip install Vins_client_messenger
```

###### Запуск

Для начала работы необходимо скачать серверную и клиентскую части, далее следует запустить серверную часть
```
$ cd server
$ python server.py
```
После чего уже можно слушать и принимать клиентов
```
$ cd /client
$ python client.py
```

### Документация

Вся документация находится в проекте как для серверной, так и для клиентской части соответственно, 
в удобном и читаемом формале HTML.
```
/client/docs/build/html/index.html
/server/docs/build/html/index.html
```

### Уроки и практические задания

##### I четверть

###### # Урок 1-2
- Вводная информация и повторение о концепциях хранения информации:
###### # Урок 3
- Простое клиент-серверное взаимодействие по протоколу JIM (JSON instant messaging)
###### # Урок 4
- Unittest для предыдущих уроков + уроков из прошлой четверти
###### # Урок 5
- Логирование с использованием модуля logging
###### # Урок 6
- Реализация логирования в виде декоратора @log
###### # Урок 7
- Реализация обработки нескольких клиентов на сервере. Клиенты должны общаться в «общем чате»
- Реализация функции отправки/приема данных на стороне клиента. Клиентское приложение либо только принимает, либо 
только отправляет сообщения в общий чат. Реализация функции в отдельных скриптах.
###### # Урок 8
- Реализоция приема и отправки сообщений, на клиенте, с помощью потоков в P2P-формате

##### II четверть

###### # Урок 1
- Повторение модулей subprocess, ipaddress, os, tabulate, pprint
###### # Урок 2
- Реализация метакласса ClientVerifier, ServerVerifier выполняющеи базовую проверку класса «Клиент» и «Сервер»
- Реализация дескриптора для класса серверного сокета
###### # Урок 3
- Хранение данных в БД. ORM SQLAlchemy
###### # Урок 4
- Хранение данных в БД (продолжение) 
- Основы PyQt5
###### # Урок 5
- PyQt5 (продолжение)
- PyQt5 и потоки
###### # Урок 6
- Безопасность
- Реализация аутентификации пользователя на сервере
- Реализация декоратора @login_required
- Реализация хранения паролей в БД сервера(HASH образ пароля с добавление "соли")
###### # Урок 7
- Подготовка документации с помощью sphinx-doc
- Проверка стиля кода с использованием autopep8 и Pylint
###### # Урок 8
- Формирование whl-пакетов с дистрибутивами сервера и клиента
- Процедура сборки созданного проекта с помощью cx_Freeze
- Загрузка сформированных whl-пакетов с дистрибутивами сервера и клиента в репозиторий сервиса PyPi

