# POP Brute Force
A Python Program that uses **poplib** module to brute force POP3 (Post Office Protocol).
## Requirements
Language Used = Python3<br />
Modules/Packages used:
* poplib
* datetime
* optparse
* colorama
* multiprocessing
* time
<!-- -->
## Arguments
* '-s', "--server" : Target POP Server
* '-p', "--port" : Port of Target POP Server (Default=995)
* '-u', "--users" : Target Users (seperated by ',') or File containing List of Users
* '-P', "--password" : Passwords (seperated by ',') or File containing List of Passwords
* '-c', "--credentials" : Name of File containing Credentials in format ({user}:{password})
* '-w', "--write" : CSV File to Dump Successful Logins (default=current data and time)