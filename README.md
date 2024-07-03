Polls Application
This is a simple Django application for creating and managing polls. Users can view polls, vote on them, and see the results. The code of this application is straightforward, making it easy for any developer to understand and extend. The application uses PostgreSQL as the database.

Give a star to the repository, it will help us grow! Thanks!

Demo
A demo version of the project is available.


Mobile App
Link to the Polls Application mobile app for Android on Google Play: Mobile app

Development
Getting Started:
Open a terminal.
Navigate to the directory where you want to copy the project.
Clone the project with this command:
sh
Copy code
git clone <repository_url>
Go to the project directory:
sh
Copy code
cd polls-application
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
Start the development server and open http://127.0.0.1:8000/polls/ in your browser:
sh
Copy code
python manage.py runserver
Open Tasks
Implement user authentication.
Add more question types (e.g., multiple choice).
Improve the UI/UX for mobile devices.
License
This project is licensed under the MIT License.

README (Russian)
Приложение Опросов
Это простое приложение Django для создания и управления опросами. Пользователи могут просматривать опросы, голосовать за них и видеть результаты. Код этого приложения прост, что делает его легким для понимания и расширения любым разработчиком. Приложение использует PostgreSQL в качестве базы данных.

Поставьте звезду репозиторию, это поможет нам развиваться! Спасибо!

Демо
Демо-версия проекта доступна.


Мобильное Приложение
Ссылка на мобильное приложение для Android на Google Play: Мобильное приложение

Разработка
Начало Работы:
Откройте терминал.
Перейдите в директорию, куда хотите скопировать проект.
Клонируйте проект с помощью этой команды:
sh
Copy code
git clone <repository_url>
Перейдите в директорию проекта:
sh
Copy code
cd polls-application
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
Запустите сервер разработки и откройте http://127.0.0.1:8000/polls/ в вашем браузере:
sh
Copy code
python manage.py runserver
Открытые задачи
Реализовать аутентификацию пользователей.
Добавить больше типов вопросов (например, множественный выбор).
Улучшить UI/UX для мобильных устройств.
Лицензия
Этот проект лицензирован по лицензии MIT.
