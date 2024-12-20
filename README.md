
![Снимок 11 12 2024 в 19 56](https://github.com/user-attachments/assets/4a364887-fbcd-4b26-96c1-5a2d9377b049)

WhatToWatch

WhatToWatch — это приложение для добавления и просмотра отзывов о фильмах. Пользователи могут делиться своими мнениями о фильмах, а также читать отзывы других людей. 

Функции:
	•	Добавление отзыва: пользователи могут оставлять отзывы о фильмах, указывая название, текст отзыва и ссылку на фильм.
	•	Просмотр отзывов: каждый фильм имеет свой список отзывов, которые можно просматривать.
	•	Поиск фильма: пользователи могут найти фильм по названию и получить доступ к отзывам.

Технологии:
	•	Flask — веб-фреймворк для создания бэкенда.
	•	SQLAlchemy — ORM для работы с базой данных.
	•	SQLite — база данных для хранения информации о фильмах и отзывах.
	•	Jinja2 — шаблонизатор для отображения HTML-страниц.
	•	HTML/CSS/Bootstrap — фронтенд для пользовательского интерфейса.


### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone 
```

```
cd what_to_watch
```

Cоздать и активировать виртуальное окружение:

```
python3 -m venv venv
```

```
source venv/bin/activate
```
или для пользователей Windows

```
source env/Scripts/activate
```

Установить зависимости из файла requirements.txt:

```
python3 -m pip install --upgrade pip
```

```
pip install -r requirements.txt
```

Запустить проект:

```
flask run
```
