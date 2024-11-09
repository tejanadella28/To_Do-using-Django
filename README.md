# To-Do List App with Django

This is a simple To-Do List web application built using Django. The app allows users to add, update, and delete tasks, helping them to stay organized and manage their daily activities.

## Features

- **Task Management**: Add, update, delete, and mark tasks as completed.
- **Database Storage**: Tasks are stored in a database using Django’s ORM.

## Technologies Used

- **Django**: A high-level Python web framework.
- **SQLite**: Default database used for this app.
- **HTML/CSS**: For building the user interface.
- **Bootstrap**: For basic styling and responsive design.

## Setup & Installation

### Prerequisites

Ensure that you have Python and pip installed. You can check your Python version with:

```bash
python --version
```

You can install Django using pip if you don’t have it already:

```bash
pip install django
```

### Steps to Run the Project

1. **Clone the repository**:

    ```bash
    git clone https://github.com/tejanadella28/To_Do-using-Django.git
    cd To_Do-using-Django
    ```

2. **Create a virtual environment** (optional but recommended):

    ```bash
    python -m venv venv
    source venv/bin/activate  # For Windows use `venv\Scripts\activate`
    ```

3. **Apply database migrations**:

    ```bash
    python manage.py migrate
    ```

4. **Create a superuser** (optional, for accessing the Django admin panel):

    ```bash
    python manage.py createsuperuser
    ```

    Follow the prompts to create a user.

5. **Run the server**:

    ```bash
    python manage.py runserver
    ```

6. **Access the app**:

    Open your browser and go to [http://127.0.0.1:8000](http://127.0.0.1:8000) to start using the To-Do List app.

## Usage
1. **Add Task**: Click on the "Add Task" button to add a new to-do item.
2. **Update Task**: Mark tasks as completed or edit their details.
3. **Delete Task**: Remove tasks that are no longer needed.

## Folder Structure

```
todo-list-django/
├── manage.py
├── tasks/                # Main Django app
│   ├── migrations/
│   ├── __init__.py
│   ├── admin.py              # Admin panel setup
│   ├── apps.py
│   ├── models.py             # Database models
│   ├── tests.py
│   ├── views.py              # View functions
│   ├── urls.py               # URL routing
├── todo_list/templates/
│   ├── base.html             # Base HTML template
│   ├── index.html            # To-Do list page
├── todo_list/static/
│   ├── css/
│   └── js/
├── requirements.txt          # Project dependencies
└── db.sqlite3                # SQLite database
```

## Contributing

We welcome contributions! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.

---

Feel free to modify this README as needed. Happy coding!
