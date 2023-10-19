# expense-tracking-tool
This repository contains the Python code for an expense tracking tool that tracks income, spendings, budget and other metrics, based on the user's needs. It also sends alerts based on how the user is doing with respect to budget.
This is done by first setting up a database to store the income, expense, budget data and set up user settings. I'm using SQLite for this project. 
I then implement functions for data entry, ensuring proper data validation and insertion into the database. 
After that, I create functions for sending alerts based on the user's budget status. Here I use a Python email library called smtplib to send email alerts.
