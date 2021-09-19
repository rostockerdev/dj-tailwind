**Django Boilerplate for Tailwind CSS**
----------------------------------------

## Objectives ##

Setup Django Boilerplate for django project with Tailwind CSS

## Setup ##
```
git clone https://github.com/rostockerdev/dj-tailwind.git
cd dj-tailwind
python -m venv venv
python -m pip install -r requirements/dev.txt

```

## Configure Tailwind ##

Set the tailwind-compatible 'theme' as app

```
python manage.py tailwind init theme

```
Set the settings file

```
LOCAL_APPS = [ "theme",]
THIRDPARTY_APPS = [ "tailwind",]
TAILWIND_APP_NAME = 'theme'
```

Set the node path 

```

NPM_BIN_PATH = r"C:\Program Files\nodejs\npm.cmd"

```

Install the Tailwind CSS dependencies 

```
python manage.py tailwind install

```
Start Tailwind in development mode 

```
python manage.py tailwind start

```