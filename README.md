# jukin_pytest
Clone the jukin_pytest project from Github to your machine.
Ensure that Python is installed on your machine and that python environment variable is set correctly in path.
Ensure that grails application server is running.
Goto the project folder and run command 'venv\scripts\activate.bat' in order to activate the virtual environment (for windows machines) and for linux or mac use (source venv/bin/activate)
Now the vertualenv is activated. Run command (pytest --browser chrome --url "http://localhost:8080/WhatChaMaCallIt/login"  --html=./report/report.html)
my framework currently support three browser connfiguration namely chrome, firefox and iexplorer (just replace the chrome with other options)
After test execution, please navigate to report directory and open the report.html
this report contains all the details related to this execution that is number of testcases passed and failed with detailed explaination.
