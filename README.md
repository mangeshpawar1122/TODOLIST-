# TODOLIST-
# Django To-Do List App

A simple To-Do List web application built with Django that allows users to create, update, delete, and manage tasks efficiently.

## Features

* Add new tasks
* Edit existing tasks
* Delete tasks
* Mark tasks as completed/incomplete
* Store task descriptions
* Track task creation date and time
* Responsive Bootstrap UI

## Technologies Used

* Python
* Django
* SQLite3
* HTML
* Bootstrap 5

## Project Structure

```text
todolist/
│
├── todo/
│   ├── migrations/
│   ├── templates/
│   │   └── todo/
│   │       ├── base.html
│   │       ├── task_list.html
│   │       ├── task_form.html
│   │       └── task_confirm_delete.html
│   ├── admin.py
│   ├── models.py
│   ├── urls.py
│   └── views.py
│
├── todolist/
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
│
├── db.sqlite3
├── manage.py
└── README.md
```

## Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/django-todolist.git
cd django-todolist
```

### 2. Create Virtual Environment

```bash
python -m venv venv
```

Activate the environment:

#### Windows

```bash
venv\Scripts\activate
```

#### Linux / macOS

```bash
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install django
```

### 4. Apply Migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

### 5. Run Development Server

```bash
python manage.py runserver
```

Open your browser and visit:

```text
http://127.0.0.1:8000/
```

## Usage

### Create Task

* Click **Add Task**
* Enter title and description
* Save the task

### Update Task

* Click **Edit**
* Modify task details
* Save changes

### Complete Task

* Click **Mark**
* Task status changes to completed

### Delete Task

* Click **Delete**
* Confirm deletion

## Database

The application uses SQLite as the default database.

Database file:

```text
db.sqlite3
```

## Future Improvements

* User authentication
* Task priorities
* Due dates
* Search and filtering
* Pagination
* REST API integration
* Dark mode

## Author

Developed using Django and Bootstrap.

## License

This project is open-source and available under the MIT License.
