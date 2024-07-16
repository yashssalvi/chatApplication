Project Title:
ChatApp

Prerequisites:
Anaconda navigator
VS Code
Python (3.9)
Node.js (16.15.0 or later)
npm
pip
Django
Django REST Framework
React

Setup:
Backend Setup (Django)
Clone the repository:
git clone https://github.com/yashssalvi/chatApplication.git

cd your-repo-name/Server/myserver
Create and activate a virtual environment:
python3 -m venv env
source env/bin/activate

Install the required packages:
pip install -r requirements.txt

Run migrations and create a superuser:
python manage.py migrate
python manage.py createsuperuser

Start the Django development server:
python manage.py runserver

Frontend Setup (React)
Navigate to the frontend directory:
cd ../UI/myapp

Install the required packages:
npm install

Start the React development server:
npm start

Connecting Frontend and Backend
Configure the frontend to communicate with the backend API:

In your React app, set up the base URL for your API requests. For example, create a file src/global.js and configure the base URL:

Start the Django development server:
cd Server/myserver
source env/bin/activate
python manage.py runserver

Start the React development server:
cd ../UI/myapp
npm start

Open your browser and navigate to:
http://localhost:3000
This will load your React application, which will communicate with the Django backend running at http://localhost:8000.

Feel free to modify this template according to the specifics of your project.
