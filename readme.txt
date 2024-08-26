Dependencies of the django project is

1)Linux pc setup:

      a)Please install 'virtualenv' (virtualenvironmentwrapper) in your pc 
	//$ -symbol is prompt.
	install command :  $  pip3 install virtualenv

	Now make sure your in the project directory then to create virtualenv(command is given below),[change directory to the folder containing django_project folder]
	creation command :virtualenv env
	note - env is the virtualenvironment name

	To activate the virtualenv.
	run command: $ source env/bin/activate
	
	For more details:
	https://packaging.python.org/guides/installing-using-pip-and-virtual-environments/



      b)Install django in pc
	note:Please first create and run a virtualenv then install django.
	command : $ pip3 install django==3.1.1
	note : python version supported are 3.6 and above.
	django - version 3.1.1
	To check if installed run : $ django-admin --version
	output should be "3.1.1" or there might be some error in installtion process.
	
	For more details:
	https://docs.djangoproject.com/en/3.1/topics/install/

	now after activating virtualenv and installing django in pc we are going to install its neccessary dependencies.
	
	To install image handler.
	$ pip3 install Pillow
	For more details
	https://pillow.readthedocs.io/en/stable/installation.html	
	
	To install django_filters
	$ pip3 install django-filter
	For more details:
	https://django-filter.readthedocs.io/en/stable/guide/install.html	


      c)To run the django project
	change directory to the folder containing manage.py

	$ cd django_project/
	$ ls
	output:blog  db.sqlite3  django_project  manage.py  media   user
	
	run project command: $ python3 manage.py runserver
	
	Then if there are no errors from the above command then go to this link: http://127.0.0.1:8000/login/
	To go to admin panel enter this link : http://127.0.0.1:8000/admin/

	Admin user - admin
	Admin password - admin
	
	Normal user
	user - 
	password - 

2)Windows pc setup:

      a)To install virtual environment wrapper
	change directory to the folder containing django_project folder
	$pip install virtualenvwrapper-win
	To create virtualenv ....
	$ mkvirtualenv env
	note - env is the virtualenvironment name

	To install Django.
	$ pip install django==3.1.1
	
	To check if django is installed...
	$ django-admin --version
	output should be "3.1.1" or there might be some error in installtion process.
	
      b)To run the django project
	change directory to the folder containing manage.py

	$ cd django_project/
	$ DIR
	check if manage.py folder exsists.
	run project command: $ python3 manage.py runserver
	
	Then if there are no errors from the above command then go to this link: http://127.0.0.1:8000/login/
	To go to admin panel enter this link : http://127.0.0.1:8000/admin/

	Admin user - admin
	Admin password - admin
	
	Normal user
	user - 
	password - 

	


	
	


	
	
	





