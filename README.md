# Rule-Based-battery-problem-Diagnosis
This project is a web-based application for diagnosing vehicle issues using an expert system and Flask. The application allows users to input symptoms their vehicle is experiencing, and based on predefined rules, it provides a diagnosis.

Expert System
Definition: An expert system is a computer program that mimics the decision-making abilities of a human expert. It uses predefined rules and a knowledge base to diagnose problems or provide solutions.

Components of Expert System
Knowledge Base: Contains domain-specific knowledge, in this case, rules for diagnosing issues with Bajaj vehicles.
Inference Engine: Applies logical rules to the knowledge base to deduce conclusions from the given facts (symptoms).
User Interface: Allows users to interact with the system, input their symptoms, and receive diagnoses.
Web Development with Flask
Definition: Flask is a lightweight web framework for Python. It allows developers to create web applications quickly and with minimal code.

Components Used in Code
Flask Application: The Flask object is initialized to create the application. Routes are defined using decorators to handle different URL endpoints.
Routes: The Home Route ('/') handles both GET and POST requests. The GET request displays a form where users can select symptoms, and the POST request processes the form data and displays the diagnosis.
HTML Template: Rendered using render_template_string, contains forms, checkboxes for symptoms, and buttons for submission. Displays the diagnosis result or the form based on the request type.
Running the Application: Runs the Flask application in debug mode.

how to run 
1.just download the file into your local system.
2.open with code editors like vscode(https://code.visualstudio.com/) or pycharm(https://www.jetbrains.com/pycharm/)
3.navigate to the location where file is present and run using the command : python filename.py(here in this case file name is battery_diagnoiser)
4.next you will find ip address like http://127.0.0.1:5000 in terminal like this just copy paste into the web browser you would see the hosted webpage from your local system.
5.check any two checkboxes and press diagnose you should see a diagnoisis result.
