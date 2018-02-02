# iBot
POST form to a third-party site (ca.gov) and then display as well as store response (in db).

# Install and execute
Download and exract the zip folder. Open command promt and navivate to project directory. The first command to execute once inside the main project directory (the one that contains 'index.js'), is 'npm install'. This command will install the required dependencies to run the project.
Once the previous step has finished installing. Type 'node index.js' into command prompt. At this point, the command prompt will listen on port 8080 and will be unresponsive to further commands unless you terminate current command ('Ctrl + c').

# Viewing the results of the program
While the program is running, a front-end visualization will be viewable on your http:\\localhost:8080. The output data is also stored in a database that is in the json format. The database file is in the main project directory and it is named - 'db.json'. The response from the form is saved in that file and can be viewed via a text editor.
