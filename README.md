 1. Install all the necessary packages (best done inside of a virtual environment)

    > pip install -r requirements.txt
    
 2. Copy the file config.py.example and rename it to config.py in the instance folder
 
 3. Run the app

    > python runserver.py
    
 4. Initialize the db (the server must still be running, so open a new terminal window first)

    > python manage.py init_db 
    
 5. Install necessary JavaScript packages
    > npm install
    
 6. Bundle all the necessary files
    > gulp build 

 7. The site should be ready and running at http://localhost:5000/

