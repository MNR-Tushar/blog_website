# 📝 LearnLog – A Django-Based Personal Blogging Platform

**LearnLog** is a personal blogging platform built with Django. It allows users to post and manage blog entries categorized by topics and tagged for easier navigation. The platform is responsive, clean, and focused on sharing knowledge and learning resources.

🌐 **Live Demo:** [learnlog.pythonanywhere.com](https://learnlog.pythonanywhere.com)  
📁 **GitHub Repository:** [github.com/MNR-Tushar/Blogs](https://github.com/MNR-Tushar/Blogs)

---

## 🔥 Features

- 📝 Create, view, and manage blog posts
- 🗂 Categorize posts (e.g., Tech, Education, Career)
- 🏷 Add and filter by tags
- 📅 Display posts by publication date
- 🔎 Search functionality
- 🎨 Clean, responsive UI using Bootstrap
- 🔐 Django Admin panel for post management
- 🧠 Built with Django ORM for database operations

---

## 🛠️ Technologies Used

| Area            | Technologies                             |
|------------------|------------------------------------------|
| Backend         | Python, Django                           |
| Frontend        | HTML, CSS, Bootstrap                     |
| Database        | SQLite (can be replaced with MySQL)      |
| ORM             | Django ORM                               |
| Template Engine | Django Templates                         |
| Deployment      | PythonAnywhere                           |
| Version Control | Git, GitHub                              |

---

## 📚 Categories Available

- 📘 Learning & Education  
- 💻 Programming & Tech  
- 🚀 Career & Skills  
- 🌱 Self-Development  
- 💡 Lifestyle & Motivation  

---

## 🏷 Tags (Examples)

`Django`, `Python`, `HTML`, `CSS`, `Web Development`, `Bootstrap`, `Tutorial`, `Motivation`,  
`Career`, `Projects`, `Learning`, `ORM`, `Education`, `Database`, `Technology`, `Blogging`

---

## 🚀 How to Run Locally

```bash
# Clone the repository
git clone https://github.com/MNR-Tushar/Blogs.git
cd Blogs

# Set up virtual environment
python -m venv venv
source venv/bin/activate       # For Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Apply migrations
python manage.py makemigrations
python manage.py migrate

# Create a superuser (for admin access)
python manage.py createsuperuser

# Start the development server
python manage.py runserver
