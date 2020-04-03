Перед запуском программы заполните следующие данные:

auth_params = {    
    'key': "Enter your key !!!",    
    'token': "Enter your token !!!", }  
  
board_id="Enter your board_id"

Команды для консоли:

python trello_console_client.py - Для просмотра всех задач

python trello_console_client.py create "задача_name" "колонка_name" - создать "задачу_name" в "колонке_name".

python trello_console_client.py create_column "колонка_name" - создать новую колонку.

python trello_console_client.py move "задача_name" "колонка_name" - переместить "задача_name" в указанную "колонку_name". Если таких задач несколько, будет предложенно выбрать id задачи, которую надо переместить.
