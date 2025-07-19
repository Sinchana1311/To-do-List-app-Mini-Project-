
To-Do List Web Application

Introduction

The To-Do List App is a responsive and user-friendly web application built using Flask for the backend and HTML, CSS for the frontend. It enables users to manage their daily tasks—add new items, mark them as complete, and delete them with a single click. The app emphasizes clean design, intuitive UI, and real-time updates through route-based interactions.

Objective

The primary goal of this mini project is to demonstrate full-stack web development by integrating Python backend logic with a dynamic and stylish frontend. It also reinforces core concepts such as route handling, form submission, template rendering, and interface design.

Features
- Add new to-do tasks using a simple form
- Mark tasks as completed
- Delete tasks from the list
- Strike-through effect on completed tasks
- Responsive UI layout and mobile-friendly design
- Visually rich interface with hover effects, icons, and gradient styling

Technologies Used

Frontend:
- HTML5
- CSS3
- Google Fonts (Poppins)
- Emojis for icons

Backend:
- Python 3.x
- Flask micro web framework
- Jinja2 templating engine

Project Structure

todo_web_app/
├── app.py                  # Flask backend application
├── templates/
│   └── index.html          # Main HTML page rendered by Flask
├── static/
│   └── style.css           # Custom CSS for styling the UI
├── venv/                   # Virtual environment (not uploaded)

Implementation Details

Backend (Flask)
- Defines routes for rendering the main task list, adding a task via form submission, marking tasks as complete, and deleting tasks.
- Task data is stored temporarily in an in-memory list of dictionaries with unique IDs and status flags.

Frontend (HTML + CSS)
- HTML renders the task input form and dynamically displays the task list.
- CSS applies a pastel gradient background, a glass-style card layout, and modern fonts.
- Action icons (check and delete) allow task interactions and are styled with hover and scaling effects.

Styling Highlights
- Glassmorphism card with subtle shadow and blur
- Gradient “Add Task” button
- Smooth icon hover animation
- Font: Poppins via Google Fonts

How to Run the Project

1. Ensure Python 3.x is installed.

2. Create and activate a virtual environment:

Linux/macOS:
python3 -m venv venv
source venv/bin/activate

Windows:
python -m venv venv
venv\Scripts ctivate

3. Install Flask:
pip install flask

4. Run the app:
python app.py

5. Open your browser and go to:
http://127.0.0.1:5000

Future Enhancements
- Store tasks in a persistent SQLite database
- Add user login and authentication using Flask-Login
- Add categories or tags for tasks
- Enable due dates and reminders
- Enable drag-and-drop task reordering
- Add filtering options (e.g., show only incomplete tasks)

Conclusion

This To-Do List mini project showcases essential concepts of full-stack Python web development. It’s a practical and customizable starting point for learning Flask, HTML templating, and frontend styling. The application is both visually appealing and functionally useful, making it ideal for beginners and intermediate learners.
