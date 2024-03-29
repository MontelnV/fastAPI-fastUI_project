## FAST-API + FAST-UI Project
## Description
Веб-приложение "Event Aggregator", создано с использованием Python и фреймворков FAST-API (backend) и FAST-UI (frontend). Приложение представляет собой агрегатор мероприятий, который позволяет пользователям изучать и просматривать разнообразные события.

На главной странице приложения пользователи могут легко просмотреть доступные мероприятия, ознакомиться с их деталями, такими как дата проведения, место, описание и т.д. Интуитивно понятный интерфейс позволяет пользователям фильтровать мероприятия и находить наиболее подходящий вариант.

Для администраторов предусмотрен личный кабинет, где они могут вносить изменения в информацию о мероприятиях, добавлять новые события и удалять устаревшие. Пользователи с правами администратора имеют полный контроль над содержимым приложения и могут эффективно управлять всеми аспектами мероприятий.
P.S. Приложение находится еще в разработке и имеет неполный функционал)
### build
```
python -m venv venv
.\venv\Scripts\activate
pip install -r requirements.txt
```
### run
```
uvicorn app.main:app --reload
```
### screenshots
![image](https://github.com/MontelnV/fastAPI-fastUI_project/assets/139653630/5dce50bd-37cd-40d8-86f3-7e403d36a1b9)
![image](https://github.com/MontelnV/fastAPI-fastUI_project/assets/139653630/3f92665e-4338-4bd6-9f75-277817734254)
