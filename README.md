## Flask-Todo-App

### Overview 

A Simple Todo web App developed using `Flask`,`SQLAlchemy` and `Bootstarp` and deployed on Heroku to get the basic idea about the flask web framework.
**Todo web App** : [](https://todo-app-astha.herokuapp.com/) 
The App basically follow the CRUD operation where you can add, update and delete todo items.


### Motivation behind learning Flask 

As being a Data and ML enthusiast I have tried many different projects related to the subject but what i have realised is that Deploying your machine learning model is a key aspect of every ML and Data science project. Everthing thing I had studied or been taught so far in my Data science and ML journey had mostly focused defining problem statement followed by Data collection and preparation, model building and evaluation process which is ofcourse base for every ML project but what if i want different people to interact with my models, how can i make my model available for end-user? I can't send them jupyter notebooks right! 
To Address this problem I started exploring and then come to know about `Flask`.

### About Flask 

Flask is a micro web application framework written in Python. It has multiple modules that make it easier for a web developer to write applications without having to worry about the details like protocol management, thread management, etc.
*To know more follow the given link :* [](https://pythonbasics.org/what-is-flask-python/)

### Technical Aspects 

This App is created using Python3 programming language. 
- Project consist `app.py` script which is used to run the application and is engine of this app. It connects with database and all operations on database are held there.
- templates folder contains three files `index.html`, `base.html` and `update.html` which describe the structure of the app and the way this web application behaves. These files are connected with Python via Flask framework. 
- static folder contains file `style.css` which adds some styling and enhance the look of the appication.

### Installation

The Code is written in Python 3.8. If you don't have Python installed you can find it [here](https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after cloning the repository:

``` pip install -r requirements.txt ```

*To clone the repo*
``` git clone https://github.com/asthasharma98/Flask-Todo-App.git ```





