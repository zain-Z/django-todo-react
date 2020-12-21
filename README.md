# django-todo-react

# Backend

- python
- pipenv
- django / djangorestframework
- django-cors-headers

# Frontend

- javascript
- nodejs
- npm
- create-react-app
- yarn
- bootstrap
- reactstrap
- axios

## Getting started

To start project without getting any errors:

1. Clone the project to your machine `[git clone https://github.com/zain-Z/django-todo-react.git]`
2. Install pipenv by command: `[python install pipenv]` or `[pip install pipenv]`
3. run `[pipenv shell]`
4. run `[pipenv install]`
5. run `[pipenv install django]`
6. run `[pipenv install djangorestframework]`
7. run `[pipenv install django-cors-headers]`
8. run `[npm install]` for installing all frontend dependencies
9. run `[python manage.py runserver]`
10. run `[yarn start]` if you installed yarn or you can use `[npm start]`

## Run the application

You will need two terminals pointed to the frontend and backend directories to start the servers for this application.

1. Run this command to start the backend server in the `[backend]` directory: `[python manage.py runserver]` (You have to run this command while you are sourced into the virtual environment)
2. Run this command to start the frontend development server in the `[frontend]` directory: `[npm install]` (This will start the frontend on the adddress [localhost:3000](http://localhost:3000))

## Creator Credit

This demo app was originally built for a scotch.io (acquired in 2020 by DigitalOcean) article by [Jordan Irabor](https://github.com/Jordanirabor/django-todo-react)
