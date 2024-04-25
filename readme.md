<div align="center"><h1> Learning (backend) </h1> </div>


## Setup 

##### Step 1 -  The first thing to do is to clone the repository:

```sh
git clone https://github.com/sajibsd013/learning-backend.git
```


##### Step 2 - Create a virtual environment and activate it:

```sh
python -m venv myenv
myenv\Scripts\activate
```


##### Step 3 -Then install the dependencies:

```sh
cd learning-backend
pip install -r requirements.txt
```


##### Step 4 - create database:

```sh
python manage.py migrate
```


##### Step 5 - create admin username and password:

```sh
python manage.py createsuperuser
```


##### Step 6 - Then run your project:

```sh
python manage.py runserver
```

