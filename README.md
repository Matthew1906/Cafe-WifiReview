# Cafe-Wifi Review Website

Hello there, welcome to my Cafe-Wifi Review Website 

My name is Matthew Adrianus Mulyono, and this is my project website

This is a  Mock website that contains reviews about cafe (I have no desire to promote or criticize any cafes included in this website)

The design of this website is partly from the course, since I simply improved an existing project from 100 Days of Python Course

### Steps of Running the website
1. Clone this repository
2. Set up a virtual environment by typing 'python -m venv env' in the command line
3. Set your interpreter path to the virtual environment path
4. Download all the dependencies (modules) by typing 'python -m pip install -r requirements.txt'
5. Before starting the application, you need to create the database locally (using sqlite) in the python script (and comment them afterwards)
6. You also need to add an admin and the initial data 
- The initial code to be run and initial data is available in the [init]('init') , all you need to do is paste the code from extra code snippet text file to the paste uncommented code section in the cafe_wifi.py
7. Lastly, don't forget to setup SECRET_KEY, ADMIN_NAME, ADMIN (username), and PASSWORD in .env file so that the program can start
8. Start the application by running the code, and then go to http://127.0.0.1:5000/
