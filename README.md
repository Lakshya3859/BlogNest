# BlogNest 📝

A full-featured Django web application for blogging and micro-posting with tweet-like functionality. BlogNest provides a clean, intuitive platform where users can share their thoughts, stories, and media content with the community.

## ✨ Features

### User Authentication System
- User registration and login/logout functionality
- Secure session management
- Profile management

### Content Management
- Create, read, update, and delete blog posts
- Tweet-like micro-posting capabilities
- Rich text content support
- Media upload support (images in posts)

### User Experience
- Responsive UI design using Django templates
- Clean and intuitive interface
- Real-time content updates
- Mobile-friendly design

### Admin Features
- Django admin panel for content management
- User management capabilities
- Content moderation tools

- ![Screenshot 2025-06-25 at 6 48 32 PM](https://github.com/user-attachments/assets/d5ac1295-8b9e-4a8a-8ce0-c036f0a945b4)

- ![Screenshot 2025-06-28 at 11 02 25 AM](https://github.com/user-attachments/assets/f1b272f2-db62-4c25-bea8-29dcf8a93660)



## 🛠️ Tech Stack

- **Backend:** Python 3.x, Django
- **Database:** SQLite3 (default, easily configurable for PostgreSQL/MySQL)
- **Frontend:** HTML5, CSS3, Django Templates
- **Styling:** Bootstrap (responsive design)
- **Media Handling:** Django's built-in file handling

## 📋 Prerequisites

Before you begin, ensure you have the following installed:

- Python 3.7 or higher
- pip (Python package installer)
- Git

## ⚙️ Installation & Setup

### 1. Clone the Repository
```bash
git clone https://github.com/Lakshya3859/BlogNest.git
cd BlogNest
```

### 2. Create Virtual Environment
```bash
# For macOS/Linux
python3 -m venv .venv
source .venv/bin/activate

# For Windows
python -m venv .venv
.venv\Scripts\activate
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Database Setup
```bash
python manage.py makemigrations
python manage.py migrate
```

### 5. Create Superuser (Optional)
```bash
python manage.py createsuperuser
```

### 6. Run the Development Server
```bash
python manage.py runserver
```

### 7. Access the Application
Open your web browser and visit: **http://127.0.0.1:8000/tweet/**


## 🚀 Usage

### For Regular Users:

1. **Sign Up:** Create a new account on the registration page
2. **Login:** Access your account using your credentials
3. **Create Posts:** Share your thoughts via blog posts or quick tweets
4. **Upload Media:** Add images to enhance your posts
5. **Explore:** View and interact with content from other users

### For Administrators:

1. Access the admin panel at `/admin/`
2. Manage users, posts, and site content
3. Monitor and moderate user-generated content

## 🔧 Configuration

### Database Configuration
By default, BlogNest uses SQLite3. To use PostgreSQL or MySQL:

1. Install the appropriate database adapter:
   ```bash
   pip install psycopg2-binary  # For PostgreSQL
   # OR
   pip install mysqlclient      # For MySQL
   ```

2. Update `settings.py`:
   ```python
   DATABASES = {
       'default': {
           'ENGINE': 'django.db.backends.postgresql',  # or mysql
           'NAME': 'your_database_name',
           'USER': 'your_username',
           'PASSWORD': 'your_password',
           'HOST': 'localhost',
           'PORT': '5432',  # or 3306 for MySQL
       }
   }
   ```

### Media Files Configuration
Ensure your `settings.py` includes:
```python
MEDIA_URL = '/media/'
MEDIA_ROOT = os.path.join(BASE_DIR, 'media')
```

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 🔮 Future Enhancements

- [ ] User profile pages with bio and avatar
- [ ] Comment system for posts
- [ ] Like/heart functionality
- [ ] Follow/unfollow users
- [ ] Real-time notifications
- [ ] Search functionality
- [ ] Tag system for posts
- [ ] Email verification for registration
- [ ] Password reset functionality
- [ ] API endpoints for mobile app integration
