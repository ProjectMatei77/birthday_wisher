This Python script automatically sends a personalized birthday email to people listed in a birthdays.csv file. It selects a random letter template, replaces the recipient's name, and sends an email using an SMTP server.

Features

    Reads birthday data from birthdays.csv
    
    Checks if today matches any birthdays
    
    Selects a random letter template from letter_templates
    
    Sends a personalized email using Gmail SMTP

Requirements

    Python 3.x
    
    pandas for handling CSV files
    
    smtplib for sending emails
