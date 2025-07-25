# 📝 LearnLog – A Django-Based Personal Blogging Platform

**LearnLog** is a personal blogging platform built with Django. It allows users to post and manage blog entries categorized by topics and tagged for easier navigation. The platform is responsive, clean, and focused on sharing knowledge and learning resources.

🌐 **Live Demo:** [learnlog.pythonanywhere.com](https://learnlog.pythonanywhere.com)  
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
|-----------------|------------------------------------------|
| Backend         | Python, Django                           |
| Frontend        | HTML, CSS, Bootstrap, js                 |
| Database        | SQLite                                   |
| ORM             | Django ORM                               |
| Template Engine | Django Templates                         |
| Deployment      | PythonAnywhere                           |
| Version Control | Git, GitHub                              |

---

## 🚀 How to Run Locally

```bash
# Clone the repository
git clone https://github.com/MNR-Tushar/Blogs.git
cd Blogs

# Set up virtual environment
python -m venv venv
source venv/bin/activate
# For Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Apply migrations
python manage.py makemigrations
python manage.py migrate

# Create a superuser (for admin access)
python manage.py createsuperuser

# Start the development server
python manage.py runserver

Visit: http://127.0.0.1:8000/
Admin Panel: http://127.0.0.1:8000/admin/
```
---

## 👨‍💻 Author
# Md Naimur Rahman
🎓 Student, Department of Computer Science & Engineering
🏫 Daffodil International University, Bangladesh
📧 Email: rahman23105101275@diu.edu.bd
🔗 LinkedIn: linkedin.com/in/mdnaimurrahman36
