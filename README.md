# Task manager

**Task Manager** is a simple web application built with Django 5.0 for managing tasks, workers and positions.

## Features

- **User Authentication**: The application allows users to create new accounts, log in, and log out.
- **Task Management**: Users can create, view, update, and delete tasks and task types. Additionally, there is a search function to look up tasks by name. 
- **Workers Management**: Users can search for other workers by username and view details of the workers and tasks they are assigned to.
- **Home page**: On the main page of the application, users can view the number of workers, positions, and task types currently created at their company.

## Installation

Run following code in terminal:

```shell
git clone https://github.com/loplicat/it-company-task-manager.git
cd it-company-task-manager
python3 -m venv venv
source venv/bin/activate
python manage.py runserver
```

After you can easily open the project in your browser.

# For testing

- Use the following command to load prepared data from fixture:

`python manage.py loaddata task_manager_db_data.json`

- After loading data from fixture you can use following superuser:
```
login: admin.user
password: 1qazcde3
```
# DB Structure
![image](https://github.com/loplicat/it-company-task-manager/assets/142423923/b7b74122-9ebb-4d1e-828a-fc2c41326c52)

Home page:
![image](https://github.com/loplicat/it-company-task-manager/assets/142423923/dd4b5a0f-208d-4b32-b738-cc49b260939b)

Task list:
![image](https://github.com/loplicat/it-company-task-manager/assets/142423923/6700e75f-afc5-4a60-9e74-dc07c550531e)
