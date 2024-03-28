# Finica
# Finica: Personal Finance Tracker

Finica is a web application built using Django that allows users to manage their personal finances. It provides features for tracking income, expenses, and visualizing financial data through graphs. Here's how you can set up and run the project:

## Installation and Setup

1. **Install Django**:
    - Make sure you have Python installed (version > 3.5.x).
    - Create a virtual environment (optional but recommended).
    - Install Django using pip:
        ```bash
        pip install django
        ```

2. **Create the Project and App**:
    - Start a new Django project named "Finica":
        ```bash
        django-admin startproject Finica
        cd Finica
        ```
    - Create an app named "FinApp":
        ```bash
        python manage.py startapp FinApp
        ```

3. **Configure Settings**:
    - Add the "FinApp" to the `INSTALLED_APPS` list in `settings.py`:
        ```python
        INSTALLED_APPS = [
            # ...
            'FinApp',
        ]
        ```


        ```

4. **Run the Server**:
    - Start the development server:
        ```bash
        python manage.py runserver
        ```
    - Access the application at [http://localhost:8000](http://localhost:8000).

## Contributing
Contributions are welcome! Feel free to open issues or submit pull requests.

