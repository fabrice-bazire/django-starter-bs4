# django-starter-bs4

Django example project with bootstrap 4 templates 
2 small apps with simple models, django forms and BS4 templating

## Installation

- create a virtualenv : `virtualenv -p python3 venv`
- activate : `source venv/bin/activate`
- migrate : `./manage.py migrate`
- install  static dependencies :
    - `cd static ` (at root level)
    - `npm i`

## Run server

Just do:

`./manage.py runserver`


## Available routes 

```bash
admin/

lesTaches/home/<param> [name='home']
lesTaches/listing [name='listing']

contacts/ [name='contact']
contacts/detail/<int:cid> [name='detail']
contacts/edit/<int:pers_id> [name='edite']
contacts/del/<int:pers_id> [name='delete']
contacts/list [name='listing'] 
```