# BaseServer
Программа для получения информации и вывода сообщения с сервера
___________________________________________________________________________________________________________________________________________________________________________________
## Запуск приложения
Запуск программы происходит с помощью библиотеки uvicorn, для начала надо установить библиотеки python с помощью командной строки переходим к файлам программы 
### Установка библиотек
Для установки бибилиотек используются команды:
- ```pip install --requirement requirements.txt``` или ```python pip install --requirement requirements.txt```

### Запуск с помошью консоли
C помощью команды ```.\config.py название файла``` добавляется файл конфигов, после чего запускаем ```main.py```

### Ссылка на проверку работаспособности сервера
После запуска сервера переходим по URL ссылке ```http://(указанный хост в config.ini):(указанный порт в config.ini)/info``` и видим текс, программа работает!

### Добавлени файлов и работа с базой
Добавлять и отслеживать файлы можно по ссылке ```http://(указанный хост в config.ini):(указанный порт в config.ini)/docs```
___________________________________________________________________________________________________________________________________________________________________________________
## Запуск тестов программы

### Передача конфигов
C помощью команды ```.\config.py название файла``` добавляется файл конфигов

### Запуск тестов
Для запуска теста вам понадобится **pytest**, запуск теста можно реализовать с помощью команды ```pytest -v -s test_sql.py``` и ```pytest -v -s test_app.py```
