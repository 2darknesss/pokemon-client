# Pokemon Client App

This is a simple console application created to practice Object-Oriented Programming (OOP) in Python. The main idea of this project is to learn how to fetch data from external sources and wrap it into Python classes. 

In this code, I used the requests library to connect to the PokeAPI. I created a client class to handle the connection and a separate class to represent the Pokemon itself and display its name. 

For package management, this project uses uv. It is a modern tool that helps to run the code quickly without manually creating virtual environments.

## Setup Instructions

First, you need to make sure you have uv installed on your system. You can install it using the standard Python package manager:

pip install uv

## Running the Application

To run the app, you just need to open your terminal inside the project folder and use the following command. It will automatically download all necessary dependencies and run the script:

uv run main.py
