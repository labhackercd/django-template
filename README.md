![python3-badge](https://img.shields.io/badge/python-django-green.svg) ![license-badge](https://img.shields.io/badge/license-GPLv3-blue.svg)

# How to use this template

```
django-admin startproject projectname --template=https://github.com/labhackercd/django-template/archive/master.zip --extension py,yml,json,md --name Dockerfile
```

Don't forget to add `--extension` and `--name` parameters!

# {{ project_name }}
> Description of {{ project_name }} project

## Installation
First of all, you need to install [pipenv](https://pipenv.readthedocs.io/en/latest/install/#installing-pipenv) and [npm](https://www.npmjs.com/get-npm). After install these dependencies you can run the follow commands:

```
pipenv install
npm install
```

## Running

```
pipenv run src/manage.py migrate
pipenv run src/manage.py runserver
```

## Support

Fell free to create any issue on this repository and contact the team responsible to maintain this project here on GitHub (@msfernandes, @erivanio, @cfviotti and @pettalves) or via email: labhacker@camara.leg.br.

## Contributing
1. Fork of this repository
2. Write your code
3. Create a Pull Request
4. Our team will review your PR and merge as soon as possible!

## License
This project is under GPLv3 License

