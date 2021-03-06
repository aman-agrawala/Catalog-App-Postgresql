# Item Catalog Project
The following code will allow you to create a local webserver that lists categories
and the items in each of them. This project includes the ability to login using 
Google+ and create, edit and delete your specific items. You can only view items that
other people have made. This project will be expanded to eventually include Facebook and 
better web design.

In order to get this code up and running, it is expected that you are familiar with Python, SQLAlchemy, and Flask. Please see
https://www.python.org/ for more information on installing and setting up python by yourself. Please see http://docs.sqlalchemy.org/en/rel_1_0/core/tutorial.html for setting up SQLAlchemy. Please see http://flask.pocoo.org/docs/0.10/quickstart/ for quickly setting up Flask. 
Furthermore, it is advised to install vagrant on your own machine to get all additional programs quickly intsalled. Please see this link for more details on this process: https://www.udacity.com/wiki/ud197/install-vagrant.

## Instructions

1. Open up terminal/Git Bash and cd to you vagrant folder.

2. Type `vagrant up` and, after the virtual machine is turned on, type `vagrant ssh` to login

3. Type `cd /vagrant` to go to common directory and then cd into your Item Catalog Project folder.

4. Now type `python application.py` and hit enter.

5. The server should be running locally at `localhost:8000` and you can view it yourself by typing `localhost:8000` into your browser url bar.

You can now edit, delete, or create new items in their respective categories. If you would like to select a different port for your website, then open up the application.py file and scroll all the way to the last line. By changing the value of port in `app.run(host='0.0.0.0', port=8000)` you can select any port you prefer. 

To add your own styling, open up the static folder and change the styles.css file as desired. Remember to include the styling link in your header if you add any new templates or change the styling.css name.

Feel free to add your own styling and launch your website publically! 