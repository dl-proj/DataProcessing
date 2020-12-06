# DataProcessing

## Overview

This project is to parse and calcuate data in dat file and save the result into PostgreSQL database.

## Structure

- src

    The source code to save the data in dat file into the postgresql database, calculate the value in real time.

- utils
    
    * The source code to load the data, process time and date, delay.

- app

    The main execution file
    
- requirements

    All the dependencies for this project
    
- settings

    The several settings for this project

## Installation

- Environment
    Ubuntu 18.04, python 3.6 postgresql 12.0 
    
- To install dependencies, run following command in terminal

    ```
        pip3 install -r requirements.txt
    ```    

- Note: In Ubuntu 18.04, before installing dependencies, install libpq-dev for psycopg2

    ```
        sudo apt install libpq-dev python3-dev
    ```        

## Execution

- DAT_FILE_PATH is a absolute path to dat file. Please insert your dat file absolute path.

- In terminal, run the following command.

    ```
        python3 app.py
    ``` 
    
