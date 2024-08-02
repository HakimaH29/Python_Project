# Python Database Connection Project

## Overview

This project showcases my capabilities in Python, including connecting to a database, handling user input through a web form, and displaying data on a webpage. CSS used for styling. HTML on the front-end. 

## Features

- User input form
- Database connectivity
- Data display on a webpage
- Simple and intuitive user interface

## Files and Directories

- `create_table_schema_sql.txt`: SQL schema for creating the `user_info` table.
- `home.html`: Homepage of the application with navigation links.
- `data.html`: Page for displaying user data from the database.
- `my_form.html`: Page containing the user input form.
- `display_data.py`: Python script for managing data display logic.

## Database Schema

The `user_info` table is defined with the following schema:

```sql
CREATE TABLE `user_info` (
  `user_name` varchar(100) DEFAULT NULL,
  `user_age` int DEFAULT NULL,
  `user_city` varchar(100) DEFAULT NULL,
  `user_hobby` varchar(300) DEFAULT NULL
);
