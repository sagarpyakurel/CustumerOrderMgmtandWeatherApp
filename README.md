# CustumerOrderMgmt and WeatherApp
Open Source Project
Steps to run this Project: 
1) Clone the repo:
      git clone https://github.com/sagarpyakurel/CustumerOrderMgmtandWeatherApp.git
2) Navigate to project folder:
      cd crm1
3) Create a virtual environment:
      python3 -m venv venv
4) Activate virtual environment:
      source venv/bin/activate (macOS/Linux)
      venv\Scripts\activate (Windows)
5) Install dependencies:
      pip install -r requirements.txt
6) Apply migrations:
      python manage.py migrate
7) Create a superuser (optional):
      python manage.py createsuperuser
8) Run the server:
      python manage.py runserver
9) Visit the site:
      http://127.0.0.1:8000/
