# BlogNest

A full-featured Django web application for blogging and micro-posting (tweet-like) functionality.  
Users can register, log in, create posts, and view content from others in a clean interface.
---

## 🚀 Features

- User registration and authentication (login, logout, signup)
- Create, update, delete, and view blog/tweet posts
- Media upload support (images in posts)
- Admin panel for managing content
- Responsive UI using Django templates
- Organized project structure


## ⚙️ Installation

### 1. Clone the repository
git clone https://github.com/Lakshya3859/BlogNest.git
cd BlogNest
python3 -m venv .venv
source .venv/bin/activate   # For macOS/Linux
# OR
.venv\Scripts\activate      # For Windows
pip install -r requirements.txt
python manage.py makemigrations
python manage.py migrate
python manage.py runserver

Then visit:
📍 http://127.0.0.1:8000/tweet/

🧪 Tech Stack Used

Python 3.x
Django
SQLite3 (default, can be swapped)
Bootstrap (if used in templates)
HTML/CSS (Django templating)
