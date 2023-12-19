# GST Billing Software

Welcome to the Simplest GST Billing app repository! This open-source solution allows you to streamline your invoicing process, manage inventory, and keep track of balances with ease.

## Features

* Easily create invoices
* Manage inventory
* Keep books and track balances

## Getting Started

Follow these steps to set up the GST Billing app on your local machine:

1. Create a virtual environment:
   ```bash
   virtualenv -p python3 venv
   ```

2. Activate the virtual environment:
   ```bash
   source venv/bin/activate
   ```

3. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run database migrations:
   ```bash
   python manage.py migrate
   ```

5. Start the development server:
   ```bash
   python manage.py runserver
   ```

Now you're ready to explore and use the GST Billing app locally!

Feel free to contribute, report issues, or suggest improvements. Happy billing!