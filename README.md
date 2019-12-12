# Recommendo
Prerequisites:
- Python 3.5 or higher

- Anaconda - A free and open-source distribution of the Python and R programming languages for scientific computing, that aims to simplify package management and deployment. Package versions are managed by the package management system conda.

- Xampp - A free and open-source cross-platform web server solution stack package developed by Apache Friends, consisting mainly of the Apache HTTP Server, MariaDB database, and interpreters for scripts written in the PHP and Perl programming languages 

Packages:
- Flask 
- Flask-MySQLdb
- jinja2
- WTForms
- mysqlclient
- numpy
- pandas 
- sklearn

Steps:
- Download or clone the source code from github.

- Install latest version of Anaconda, this will install Jupyter Notebbok will be used for editing and managing the ipynb files.

- Install Xampp web server and make sure atleast mysql database is installed. This is the database which will connect to the project. Everytime you need to use the database you must start the server. 

- Install python 3.5 or higher. 

- Install the packages on your enviroment, you can use pip if you're using the command line or follow the instrustions of your respective IDE.

- After everything is set. Run the main.py file. 

File Descriptions:
- create.py - Contains the code for the machine learning model testing.

- main.py - Contains main code which uses the other modules and runs the project.

- data.csv - Dataset for the project.

- preprocessing - Contains code to read data.csv and extract relevant information and machine learning model training.                   

