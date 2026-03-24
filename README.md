# 🗳️ Django Poll App (Dockerized)

A full-featured Django-based Poll Application where users can register, create polls, vote, and view results.  
This project has been enhanced with Docker to simulate real-world DevOps workflows.

---

## 🚀 Features

- User Authentication (Register/Login)
- Create, Update, Delete Polls
- Add and Manage Choices
- Vote on Polls (One vote per user)
- View Poll Results
- Search & Filter Polls
- Pagination Support
- Poll Ownership Control (Only creator can modify)
- Poll Expiry (Ended polls cannot be voted)

---

## 🛠️ Tech Stack

- **Backend:** Django (Python)
- **Containerization:** Docker
- **Database:** SQLite (default)
- **Server:** Django Dev Server (can be upgraded to Gunicorn)

---

## 🏗️ Architecture
Developer → Django App → Docker Container → Browser

<h1>Getting Started</h1>
<p>These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.</p>

<h2>Prerequisites</h2>
<code>python== 3.5 or up and django==2.0 or up</code>

<h2>🔹 Clone Repository</h2>
<code>git clone https://github.com/Naushad1767/Django-poll-app.git</code><br><br>
<code>cd Django-poll-app</code><br><br>

<h2>🔹 Install Dependencies</h2>
<code>pip install -r requirements.txt</code><br>

<h2>🔹 Apply Migrations</h2>
<code>python manage.py makemigrations
python manage.py migrate</code><br>

<h2>🔹 Create Superuser</h2>
<code>python manage.py createsuperuser</code><br>

<h2>🔹 Run Server</h2>
<code>python manage.py runserver</code><br>

<h2> 🌐 Access Application</h2>
<h2> Open in browser:</h2>
<h2> http://127.0.0.1:8000 </h2>

<h2>Project snapshot</h2>
<h3>Home page</h3>
<div align="center">
    <img src="https://user-images.githubusercontent.com/19981097/51409444-0e40a600-1b8c-11e9-9ab0-27d759db8973.jpg" width="100%"</img> 
</div>

<h3>Login Page</h3>
<div align="center">
    <img src="https://user-images.githubusercontent.com/19981097/51409509-36c8a000-1b8c-11e9-845a-65b49262aa53.png" width="100%"</img> 
</div>

<h3>Registration Page</h3>
<div align="center">
    <img src="https://user-images.githubusercontent.com/19981097/51409562-5cee4000-1b8c-11e9-82f6-1aa2df159528.png" width="100%"</img> 
</div>

<h3>Poll List Page</h3>
<div align="center">
    <img src="https://user-images.githubusercontent.com/19981097/51409728-d423d400-1b8c-11e9-8903-4c08ba64512e.png" width="100%"</img> 
</div>

<h3>Poll Add Page</h3>
<div align="center">
    <img src="https://user-images.githubusercontent.com/19981097/51409796-fe759180-1b8c-11e9-941b-c1202956cca4.png" width="100%"</img> 
</div>

<h3>Polling page</h3>
<div align="center">
    <img src="https://user-images.githubusercontent.com/19981097/51409843-1e0cba00-1b8d-11e9-9109-cceb79a6a623.png" width="100%"</img> 
</div>

<h3>Poll Result Page</h3>
<div align="center">
    <img src="https://user-images.githubusercontent.com/19981097/51409932-60ce9200-1b8d-11e9-9c83-c59ba498ca8b.png" width="100%"</img> 
</div>

<h3>Poll Edit Page</h3>
<div align="center">
    <img src="https://user-images.githubusercontent.com/19981097/51410008-92dff400-1b8d-11e9-8172-c228e4b60e28.png" width="100%"</img> 
</div>

<h3>Choice Update Delete Page</h3>
<div align="center">
    <img src="https://user-images.githubusercontent.com/19981097/51410442-dc7d0e80-1b8e-11e9-8f8e-18e6d7bb70fb.png" width="100%"</img> 
</div>


<div align="center">
    <h3>========Thank You !!!=========</h3>
</div>
