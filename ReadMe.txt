Перед запуском программы заполните следующие данные:

auth_params = {    
    'key': "Enter your key !!!",    
    'token': "Enter your token !!!", }  
  
board_id="Enter your board_id"

Команды для консоли:

python trello.py - Для просмотра всех задач

python trello.py create "задача_name" "колонка_name" - создать "задачу_name" в "колонке_name"

python trello.py create_column "колонка_name" - создать новую колонку

python trello.py move "задача_name" "колонка_name" - переместить "задача_name" в указанную "колонку_name". Если таких задачь несколько, будет предложенно выбрать id задачи, которую надо переместить
