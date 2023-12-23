Instructions for Running Samwise Executables


Overview: 
Part A: nodejs, mySql, and the Samwise source code need to be installed first. 
Part B: db database need to be created either in MySQL Shell Terminal or in MySQL Workbench.
Part C: run commands in the Samwise source code folder.
Part D: access the Samwise webpage. 




Part A: nodejs, mySql, and the Samwise source code installations.
1. Install nodejs from: https://nodejs.org/en/download
2. Install mySql from: https://dev.mysql.com/downloads/installer/
3. Install the Samwise source code from the current Iteration from github: https://github.com/GITyannie/samwise


Part B: Create db database with MySQL Shell Terminal or in MySQL Workbench.
1. Run command MySQL Shell terminal: CREATE DATABASE db


OR


2. Open MySQL Workbench.
2.1. Connect to your local instance.
2.2. In the upper left hand navigation panel, click “Create a new schema in the connected server”. It is the database 2.3 symbol with a (+) sign.
2.3. Specify the name of the schema as: db
2.4. Click apply.
2.5. Click apply again.
2.6. Click finish. 


Part C: Run a Command Terminal in the Samwise source code's folder:
1. Open the folder you wish to open the command prompt window from where the Samwise source code is located.
2. Type cmd into the location bar at the top of the window and tap enter.
3. The command prompt will now be opened in the desired location.
4. Run the following commands in the command prompt window:
        4.a. npm install -i
        4.b. node index.js


Part D: Access the Samwise web page locally.
1. Open a web browser.
2. Type into the url bar: http://localhost:3000/