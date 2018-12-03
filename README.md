# Flask-MySQL

This is a sample that demonstrates how to use Flask app to deal with MySQL. To run this application, install the requirements in a virtual environment, run `python app.py` and visit `https://localhost:5000`.

Install requirements:

    pip install flask-mysql openssl-python 

To generate CERT and KEY for using SSL, run:

    openssl req -x509 -newkey -nodes -out cert.pem -keyout key.pem -days 365
