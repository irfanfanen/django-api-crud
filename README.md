# Django API Project

This project is an API built using Django and Django REST Framework (DRF). The goal of this project is to create an API that allows users to access and manage data.

## System Requirements

Make sure you have the following software installed before running the project:
- Python 3.10 or higher
- Django 5.1.4 or higher
- MySQL (or any other database you choose)

## Installation

Follow these steps to install the project on your local environment:

1. **Clone the Repository**
   Clone the repository to your local machine using the following command:
   ```bash
   git clone https://github.com/username/repository-name.git

   ```
2. **Navigate to the Project Directory**
   Change into the project directory:
   ```bash
   cd repository-name
   ```
3. **Create a Virtual Environment**
   Create and activate a virtual environment for the project:
   - On Windows:
     ```bash
     python -m venv env
     env\Scripts\activate
     ```
   - On Linux/Mac:
     ```bash
     python -m venv env
     source env/bin/activate
     ```
4. **Install Dependencies**
   Install all required dependencies using pip:
   ```bash
   pip install -r requirements.txt
   ```
5. **Configure the Database**
   Update the database settings in the `settings.py` file:
   - Ensure that MySQL or your chosen database is configured properly under the `DATABASES` section.

6. **Run Migrations**
   Run migrations to set up the database:
   ```bash
   python manage.py migrate
   ```

7. **Start the Server**
   Start the Django development server:
   ```bash
   python manage.py runserver
   ```

   Access the API at the following URL:
   ```bash
   http://localhost:8000/api/items/
   ```

## API Usage

Here are the available API endpoints:

- `GET /api/items/` - Get a list of all items.
- `POST /api/items/` - Add a new item.
- `GET /api/items/{id}/` - Get an item by its ID.
- `PUT /api/items/{id}/` - Update an item by its ID.
- `DELETE /api/items/{id}/` - Delete an item by its ID.

## Closing

For more information, visit the official Django documentation at [https://www.djangoproject.com/](https://www.djangoproject.com/).
