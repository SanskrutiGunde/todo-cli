# Task Tracker CLI

## Overview

The Task Tracker CLI is a command-line interface (CLI) application built using Python and SQL to help users manage and track their tasks efficiently. This tool provides a simple and intuitive way to add, view, update, and delete tasks directly from the command line.

## Features

Task Management: Add, view, update, and delete tasks seamlessly.
SQL Database: Utilizes a SQL database to store and manage task data.

## Prerequisites

Python 3.x
SQL Database (e.g., SQLite)

### Installation

Clone the repository:
git clone https://github.com/SanskrutiGunde/todo-cli
cd todo-cli

### Install dependencies:

pip install -r requirements.txt

### Set up the database:

#### Create a new SQL database (e.g., SQLite).

Update the database configuration in config.py with your database details.
Usage

py .\ido.py --help

#### View Tasks:

py .\ido.py show

#### Add a Task:

python ido.py add "Jogging" "Sports"

#### Update a Task:

py ido.py update --help
py ido.py add "task" "cat"

#### Delete a Task:

python ido.py delete 3

#### Mark the task as complete

python ido.py complete 1

### Configuration

In the config.py file, you can customize the database connection parameters.

### License

This project is licensed under the MIT License - see the LICENSE file for details.

### Acknowledgments

Thanks to [Author Name] for the inspiration and guidance.
Contact
For any inquiries or issues, please contact me.
