# MY README

### STEPS
- update app/requirements.txt  
    ```
    from: SQLAlchemy>=1.3.0,<2  
    to: SQLAlchemy>=1.3.0,<1.4.0  
    ```
- set environment
    ```sh
    export FLASK_CONFIG=development
    ```
- pip install -r requirements.txt
- invoke app.run    

### TEST
Browse: http://127.0.0.1:5000/api/v1/
