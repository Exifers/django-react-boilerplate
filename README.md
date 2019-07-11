A minimalist boilerplate for Django and React, using Webpack.

# Features
- python 3
- Django 2.2
- Django extensions
- Webpack
- Webpack Dev Server
- React
- basic deployment on heroku

# Getting started
## Setup Django development server
Clone this repository, then run the following commands in the root directory:
```shell
pip3 install -r requirements.txt
python3 manage.py makemgigrations
python3 manage.py migrate
python3 manage.py runserver
```
Note: it is recommended to use virtualenv to manage your python packages.

Go to your favorite browser at http://localhost:8000, you should see the welcome page.

## Setup React
To start developping in React, go to ```/frontend/```, then run :
```shell
npm install
```
You can edit ```/frontend/src/index.js``` to start coding with React.
### Compiling React code
Compile and watch for changes :
```shell
npm run watch
```
Compile for production :
```
npm run build
```
Run webpack dev server :
```
npm run start
```
Webpack Web Server will show you only the React part of the project, parts will be missing if you use Django to render some pages or html components.

# Todo
- support for PostGreSQL for deployment on Heroku

# Licence
GPL
