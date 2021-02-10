# angkacaa Project

## Setup

The first thing to do is to clone the repository:

```sh
$ git clone \https://github.com/yaumialfadha/angkacaa.git
$ cd angkacaa or open angkaca directory
```

Create a virtual environment to install dependencies in and activate it:

For windows
```sh
$ py -m venv env
$ env\Scripts\activate.bat
```

For Linux
```sh
$ virtualenv env
$ source env/bin/activate
```


Then install the dependencies:
```sh
$ pip install -r requirements.txt
```


Once `pip` has finished downloading the dependencies:
```sh
$ python manage.py runserver
```

And navigate to `http://127.0.0.1:8000` or open your browser and search  http://127.0.0.1:8000
