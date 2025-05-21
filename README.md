# 💼 Personal Portfolio Website

A simple personal portfolio built with Django. This website showcases my work, skills, and contact information.

## 🚀 Features

- Responsive landing page
- Clean HTML and CSS layout
- Built with Django
- Easily customizable and extendable

## 🛠️ Tech Stack

- **Backend:** Django 5.2.1
- **Frontend:** HTML5, CSS3
- **Database:** SQLite (default with Django)

## 📂 Project Structure

portfolio_site/

├── main/

│ ├── migrations/

│ ├── static/

│ │ └── style.css

│ ├── templates/

│ │ └── index.html

│ ├── init.py

│ ├── admin.py


│ ├── apps.py

│ ├── models.py

│ ├── tests.py

│ └── views.py

├── portfolio_site/

│ ├── init.py

│ ├── settings.py

│ ├── urls.py

│ └── wsgi.py

├── db.sqlite3

├── manage.py

├── requirements.txt

└── README.md


## 🧑‍💻 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/portfolio_site.git
cd portfolio_site

2. Set Up a Virtual Environment
python -m venv venv
# Activate the virtual environment:
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate

3. Install Dependencies
pip install -r requirements.txt

4. Run the Development Server
python manage.py runserver
Then open your browser and go to: http://127.0.0.1:8000

📦 Deployment
You can deploy this site using platforms like:

Railway

Render

Heroku

Or host it on your own server

Let me know if you want deployment help!

📄 License
This project is open-source and available under the MIT License.
