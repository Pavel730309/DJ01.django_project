# Django App with /data and /test Pages

This is a sample Django project demonstrating how to handle two separate URL paths.

## Available URLs
- `/data/` — Returns a "DATA" page
- `/test/` — Returns a "TEST" page

## How to run
1. Create a virtual environment:
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

2. Install Django:
   ```
   pip install django
   ```

3. Run the server:
   ```
   python manage.py runserver
   ```

4. Visit:
   - http://127.0.0.1:8000/data/
   - http://127.0.0.1:8000/test/
