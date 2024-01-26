# Server Buddy
It's an app that would help banquet servers take orders.

### Features

- Secure Login - (TODO) - AZURE
- Create Orders.
- Create Events per room.
- Generate table order summary.
- Dashboard for management with tables order summary.

# Front-End Enviroment & Set-up

- React
- JS
- Node.js

## Scaffold the App

Create a new React app within this project folder. You must perform this within this front-end project folder.

```bash
$ npx create-react-app
```

# Back-End Environment & Set-up

### Setup

The goal for setup is to cover all of the setup needed at the beginning of this project, which includes:

1. Forking and cloning
1. Managing dependencies
1. Setting up development and test databases
1. Setting up a `.env` file

### Requirements

### Fork and Clone

1. Fork this project repo to your own personal account
1. Clone this new forked project

### Managing Dependencies

Create a virtual environment:

```bash
$ java
```

## Setting Up Development and Test Databases

Create a database:

1. A development database named `your_database_name`

### Creating a `.env` File

Create a file named `.env`.

Create two environment variables that will hold your database URLs.

1. `SQLALCHEMY_DATABASE_URI` to hold the path to your development database
1. [OPTIONAL] `SQLALCHEMY_TEST_DATABASE_URI` to hold the path to your development database

Your `.env` may look like this:

```
SQLALCHEMY_DATABASE_URI=postgresql+psycopg2://postgres:postgres@localhost:5432/your_database_name
```


