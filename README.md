# Linux Terminal Replica with User Database

This project is a small replica of a Linux terminal, allowing users to interact with it through a Python script (`useradd_mid.py`). The project also includes a MySQL database setup using a script (`project_database.sql`). Users and their information are stored in the database, creating a basic user management system.

## Linux Terminal Overview

The Linux terminal, also known as the command line or shell, is a text-based interface for interacting with the operating system. It allows users to execute commands, navigate the file system, and perform various tasks efficiently.

## Instructions

### Step 1: Run the Python Script

1. Ensure you have Python installed on your system.

2. Open a terminal.

3. Navigate to the directory containing `useradd_mid.py`.
    ```bash
    cd /path/to/project
    ```

4. Run the Python script.
    ```bash
    python useradd_mid.py
    ```

5. Follow the on-screen prompts to interact with the Linux terminal replica.

### Step 2: Set Up MySQL Database

1. Install MySQL on your system if not already installed.

2. Open a terminal.

3. Navigate to the directory containing `project_database.sql`.
    ```bash
    cd /path/to/project
    ```

4. Log in to MySQL using the command below, replacing `username` and `password` with your MySQL credentials.
    ```bash
    mysql -u username -p
    ```

5. Create the database by running the script.
    ```bash
    source project_database.sql
    ```

6. The script will create a database named `project_database` and tables required for the project.

7. Exit MySQL.
    ```bash
    exit
    ```

## Project Details

- The Python script `useradd_mid.py` provides a user interface resembling a Linux terminal.

- The MySQL script `project_database.sql` sets up a database and tables to store user information.

- Users and their data are managed within the MySQL database, creating a simple user management system.

**Note:** Ensure to customize MySQL credentials and paths based on your system configuration.

