# project
##project topic: Бот-ежедневник с напоминаниями о предстоящих делах и событиях.
Какие инструменты ты будешь использовать в своем проекте?
 Из каких этапов будет состоять разработка проекта?
Продумай план реализации проекта!
function:
command /star- bot send all function
command /build_day_plan - input- time for end the task , name of the task output- table with all task and time when start the task and when end
command /show_day_plan- view full plan
command /send_me_message - input:  local time,message output: send message on the input time 
tools: 
visual studio code 
python
liberis:  
telebot
APScheduler
time 
datetime
files: 
bot.py - bot action, send messages and take the information from logic.py
logic.py- file where we do all math action and send to bot.py
config.py- bot token
database.- all information
action plan: 
register bot- get token and upload to config.py 
create bot actions 
create class Calendar (methods: add task, show all tasks,sum all time tasks)


