<b>Скрипт ищет обращения с типом <U>BOT_BLOCKED</U> и закрывает их с тегом «Неинформативно»</b>
<br>Для запуска скрипта необходимо создать .env файл, в нем указать:

```Bash
KEY = "Basic токен" #Получить можно на аккаунте infobip
AGENT_ID = "11111222222333334444" #ID агента с правами супервайзера
TAG = "Неинформативно" #Тег с которым будет закрываться обращение
INTERVAL = 60 # В секундах
```
