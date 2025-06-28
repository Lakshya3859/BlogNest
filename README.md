BlogNest 📝
A full-featured Django web application for blogging and micro-posting with tweet-like functionality. BlogNest provides a clean, intuitive platform where users can share their thoughts, stories, and media content with the community.
✨ Features
User Authentication System
User registration and login/logout functionality
Secure session management
Profile management
Content Management
Create, read, update, and delete blog posts
Tweet-like micro-posting capabilities
Rich text content support
Media upload support (images in posts)
User Experience
Responsive UI design using Django templates
Clean and intuitive interface
Real-time content updates
Mobile-friendly design
Admin Features
Django admin panel for content management
User management capabilities
Content moderation tools
![Screenshot 2025-06-25 at 6 48 32 PM](https://github.com/user-attachments/assets/652c426b-b9e9-446a-a545-9f1199a96706)

![Screenshot 2025-06-28 at 11 02 25 AM](https://github.com/user-attachments/assets/902937eb-4c77-486e-96e8-886f73ec8d48)




🛠️ Tech Stack
Backend: Python 3.x, Django
Database: SQLite3 (default, easily configurable for PostgreSQL/MySQL)
Frontend: HTML5, CSS3, Django Templates
Styling: Bootstrap (responsive design)
Media Handling: Django's built-in file handling

📋 Prerequisites
Before you begin, ensure you have the following installed:

Python 3.7 or higher
pip (Python package installer)
Git

⚙️ Installation & Setup
1. Clone the Repository
git clone https://github.com/Lakshya3859/BlogNest.git
cd BlogNest

2. Create Virtual Environment
# For macOS/Linux
python3 -m venv .venv
source .venv/bin/activate

# For Windows
python -m venv .venv
.venv\Scripts\activate


3. Install Dependencies
pip install -r requirements.txt

4. Database Setup
python manage.py makemigrations
python manage.py migrate

5.Run the Development Server
python manage.py runserver

6. Access the Application
Open your web browser and visit: http://127.0.0.1:8000/tweet/


🚀 Usage
For Regular Users:

Sign Up: Create a new account on the registration page
Login: Access your account using your credentials
Create Posts: Share your thoughts via blog posts or quick tweets
Upload Media: Add images to enhance your posts
Explore: View and interact with content from other users

For Administrators:

Access the admin panel at /admin/
Manage users, posts, and site content
Monitor and moderate user-generated content





