# Coffee-Shop Full-Stack

Coffe Shop is new digitally enabled coffee shop where students can order drinks, socialize, and study.
This application is a full stack flask/Angular/Ionic web application that demonstrates my understanding of writing flask api's, consumming the api's in the frontend.
It also demonstrates strong understanding of JWT, Authentication and Access Control and the use of third party authentication (Auth0) and how to set up User Authorization using Auth0.

## Overview

The apllication must:

1. Display graphics representing the ratios of ingredients in each drink.
2. Allow public users to view drink names and graphics.
3. Allow the shop baristas to see the recipe information.
4. Allow the shop managers to create new drinks and edit, delete existing drinks.


## Setup instructions

In order to setup and run the CoffeeShop application on your local machine, follow the following instructions

Fork the repository from my [github page](https://github.com/muhammedctgr/CoffeeShop-FullStack.git). The repository will appear on your list of repositories.

Clone this repository into your local machine from your command prompt with following command

`git clone https://github.com/muhammedctgr/CoffeeShop-FullStack.git`

Run `cd CoffeeShop` to navigate to the project directory

In the project directory, there are two main subfolders

`backend`

`frontend`

### Backend setup instructions

- Run `cd backend` to navigate into the backend project directory

- Create a python virtual environment with the following command

`python -m venv venv`

- Run `source venv/bin/activate` to activate the virtual environment. Use `deactivate` command to deactivate your virtual environment.

**Note** *Be sure to install the following Flask, SQLAlchemy, jose*

- Assumming that pip is installed in your system, install python packages to be used by flask app.

`pip install -r requirements.txt`

- After all requirements are installed, run

`FLASK_APP=src/api.py FLASK_DEBUG=1 flask run` to start the application.


### Frontend setup instructions

**Note** *Be sure that both Angular version from 13 above and ionic 6 or above are installed globally in your local machine*

- Run `cd frontend` command to navigate to the frontend directory

- Run `npm install` to install all application dependencies/libraries

- Start the frontend server with `ionic serve`


