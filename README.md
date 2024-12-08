# Setting Up Django Project
# Create a virtual environment
python3 -m venv myenv
source myenv/bin/activate  # On Windows use 'myenv\Scripts\activate'

# Install Django
pip install django

# Start a new Django project
django-admin startproject restaurant_price_predictor

# Create an app within the project
cd restaurant_price_predictor
python manage.py startapp predictor
# Install required packages in python
# Set up the UPI Calls, Then keep the entire set up from above files.
# Run the Django Server
python manage.py runserver
# Goto http://127.0.0.1:8000/ in your browser to see the page.
