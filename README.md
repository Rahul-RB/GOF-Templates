# GOF Templating Application

[![Build Status](https://travis-ci.org/ganesh-k13/GOF-Templates.svg?branch=master)](https://travis-ci.org/ganesh-k13/GOF-Templates) [![licensebuttons by-sa](https://licensebuttons.net/l/by-sa/3.0/88x31.png)](https://creativecommons.org/licenses/by-sa/4.0)

Provides pattern templates based on user requirements 

### Check our live demo right [here!](https://spryion.pythonanywhere.com/)

## Prerequisites

* Python version 3.6 or higher
* Flask version 0.12.2 or higher
* Astyle version 3.1

install prerequisites:
```
sudo pip3 install -r requirements.txt
brew install astyle
```

## Running

1. Clone this repository.
2. Run these instructions from the repository's root:
```bash
virtualenv -p python3 venv
source venv/bin/activate
./venv/bin/pip3 -r requirements.txt
export FLASK_APP=run.py
export FLASK_ENV=development

flask run
```
3. Site should be live in `http://localhost:5000/`

## Built With

* [Python](https://docs.python.org/3/)
* [Flask](http://flask.pocoo.org/)

## Authors

* **Ganesh K.** - [ganesh-k13](https://github.com/ganesh-k13)
* **Hardik Mahipal Surana** - [hardiksurana](https://github.com/hardiksurana)
* **Rahul R Bharadwaj** - [Rahul-RB](https://github.com/Rahul-RB)


## Acknowledgments

* This is developed as a project for Design Patterns course.
