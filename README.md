# Employee Tracker

## Description

The Employee Tracker is a command-line application built with Node.js that allows users to manage a company's employee database. It provides functionalities to add, view, and update employee information, making it an essential tool for HR departments and managers who need to keep track of employee records efficiently.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Video](#video)
- [Repo](#repo)
- [License](#license)

## Features

- Add new employees, roles, and departments.
- View existing employees, roles, and departments.
- Update employee roles and manager assignments.
- Delete employees, roles, or departments as needed.
- Generate reports on employee data.

## Technologies Used

- **Node.js**: Backend runtime for the application.
- **Inquirer.js**: For interactive command-line prompts.
- **PostgreSQL**: To store and manage employee data.
- **Console.table**: To display data in a table format in the console.

## Installation

Clone this repository:

```bash
git clone https://github.com/briansotolago/Employee-Tracker.git
```

To install the necessary dependencies for this application, run the following command:

```bash
npm install
```

Setup your PostgreSQL database credentials:

```bash
USER_NAME=your_db_username
PASSWORD=your_db_password
DB_NAME='employees_db'
```

Run the following command to set up the database:

```bash
cd db
psql -U postgres
\i schema.sql
\i seeds.sql
\i query.sql
```

## Usage

To use the Employee Tracker, follow these steps:

- Clone the repository to your local machine.
- Navigate to the project directory in your terminal.
- Set up the MySQL database using the provided schema and seed files.
- Run the following command:

```bash
node index.js
```

- Follow the prompts to manage employee data.

## Video

This video demonstrates the functionality of the Employee Tracker, including adding, viewing, and updating employee records.

[![video](https://i.sstatic.net/Vp2cE.png)](https://drive.google.com/file/d/1Hgo3pychOfSzdTiky9IaoQsUNIofjdMQ/view)

## Repo

[GitHub Repo](https://github.com/briansotolago/Employee-Tracker)

## License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
