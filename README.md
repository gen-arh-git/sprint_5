# Сдача проектной работы 4 спринта

Активируйте виртуальное окружение: rasa_env\Scripts\activate

Замените настроенные конфигурации в соответствующих директориях: endpoints.yml

cors:
  enabled: true
  origins:
    -"http://localhost:3000"

Запустите ассистента: rasa run --cors "*" --enable-api --log-file DEBUG -vv

Лог в файле DEBUG	
 
 
