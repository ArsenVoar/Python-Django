Polls Application
This is a simple Django application for creating and managing polls. Users can view polls, vote on them, and see the results. The code of this application is straightforward, making it easy for any developer to understand and extend. The application uses PostgreSQL as the database.

Give a star to the repository, it will help us grow! Thanks!

Demo
A demo version of the project is not available.

Development
Getting Started:
Open a terminal.
Navigate to the directory where you want to copy the project.

Clone the project with this command:
git clone <repository_url>

Go to the project directory:
cd polls-application

Create and activate a virtual environment:
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

Install the required dependencies:
pip install -r requirements.txt

Set up the database:
python manage.py migrate

Create a superuser:
python manage.py createsuperuser

Start the development server and open http://127.0.0.1:8000/polls/ in your browser:
python manage.py runserver

License
This project is licensed under the MIT License.

Приложение Опросов
Это простое приложение Django для создания и управления опросами. Пользователи могут просматривать опросы, голосовать за них и видеть результаты. Код этого приложения прост, что делает его легким для понимания и расширения любым разработчиком. Приложение использует PostgreSQL в качестве базы данных.

Поставьте звезду репозиторию, это поможет нам развиваться! Спасибо!

Демо
Демо-версия проекта пока не доступна.

Разработка
Начало Работы:
Откройте терминал.
Перейдите в директорию, куда хотите скопировать проект.

Клонируйте проект с помощью этой команды:
git clone <repository_url>

Перейдите в директорию проекта:
cd polls-application

Создайте и активируйте виртуальную среду:
python -m venv venv
source venv/bin/activate  # В Windows используйте `venv\Scripts\activate`

Установите необходимые зависимости:
pip install -r requirements.txt

Настройте базу данных:
python manage.py migrate

Создайте суперпользователя:
python manage.py createsuperuser

Запустите сервер разработки и откройте http://127.0.0.1:8000/polls/ в вашем браузере:
python manage.py runserver

Лицензия
Этот проект лицензирован по лицензии MIT.
