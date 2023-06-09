Example Readme
================================================================================
This is a readme file.

# Heading1
## Heading2
### Heading3
#### Heading4
##### Heading5
###### Heading6

## List
* Item1
* Item2

```bash
use ```bash``` to make a bash
dir
cd dir_name
cd.
```

## image

image in readme - you can also use any image of your repo in the readme.
![image](images/git-github.png)


## Links

you can also use this built in website to built readme file.
-[https://readme.so/](https://readme.so/)

## API PROJECT  
===
_cscapp - application for countries, states, cities api_
---

#### How to run project

clone repository

```bash
python -m venv env
.\env\scripts\activate

cd apiproject
pip install -r requirements.txt
```

create a database 'apidatabase'
upload countries.sql , states.sql , cities.sql (from countries-states-cities-database-master\sql folder into your apidatabase)

```bash
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
```
