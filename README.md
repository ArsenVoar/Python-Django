README (English)
Polls Application
This is a simple Django application for creating and managing polls. Users can view polls, vote on them, and see the results.

Installation
Clone the repository:

sh
Copy code
git clone <repository_url>
cd <repository_directory>
Create and activate a virtual environment:

sh
Copy code
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
Install the required dependencies:

sh
Copy code
pip install -r requirements.txt
Set up the database:

sh
Copy code
python manage.py migrate
Create a superuser:

sh
Copy code
python manage.py createsuperuser
Run the development server:

sh
Copy code
python manage.py runserver
Open your web browser and go to http://127.0.0.1:8000/polls/.

Usage
Home Page: Displays a list of recent polls.
Poll Detail Page: Shows the question and allows voting.
Poll Results Page: Shows the results of a specific poll.
Adding a Poll
Log in to the admin site at http://127.0.0.1:8000/admin/.
Add a new question under the Polls section.
Add choices to the question.
License
This project is licensed under the MIT License.

README (Russian)
Приложение Опросов
Это простое приложение Django для создания и управления опросами. Пользователи могут просматривать опросы, голосовать за них и видеть результаты.

Установка
Клонируйте репозиторий:

sh
Copy code
git clone <repository_url>
cd <repository_directory>
Создайте и активируйте виртуальную среду:

sh
Copy code
python -m venv venv
source venv/bin/activate  # В Windows используйте `venv\Scripts\activate`
Установите необходимые зависимости:

sh
Copy code
pip install -r requirements.txt
Настройте базу данных:

sh
Copy code
python manage.py migrate
Создайте суперпользователя:

sh
Copy code
python manage.py createsuperuser
Запустите сервер разработки:

sh
Copy code
python manage.py runserver
Откройте веб-браузер и перейдите по адресу http://127.0.0.1:8000/polls/.

Использование
Главная страница: Отображает список последних опросов.
Страница подробностей опроса: Показывает вопрос и позволяет голосовать.
Страница результатов опроса: Показывает результаты конкретного опроса.
Добавление опроса
Войдите на сайт администратора по адресу http://127.0.0.1:8000/admin/.
Добавьте новый вопрос в разделе Опросы.
Добавьте варианты ответов к вопросу.
Лицензия
Этот проект лицензирован по лицензии MIT.
