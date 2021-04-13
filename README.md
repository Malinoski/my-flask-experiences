# My Flask experiences
This project ios an experiment using Flask [tutorial](https://flask.palletsprojects.com/en/1.1.x/tutorial/) (version 1.1).

### Install
```
cd $PROJECT_ROOT
python3 -m venv venv
. venv/bin/activate
pip install -e .
pip list
```

### Test:
```
cd $PROJECT_ROOT
pytest -v
coverage run -m pytest
coverage report
```

### Start:
```
cd $PROJECT_ROOT
export FLASK_APP=flaskr
export FLASK_ENV=development
flask init-db
flask run
```



### Use:
[http://127.0.0.1:5000/auth/register](http://127.0.0.1:5000/auth/register)