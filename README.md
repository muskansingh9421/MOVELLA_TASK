# MOVELLA_TASK

Prerequisites
Running python file requires:

Python 3.7 (tested under Python 3.7.5)
futher need to have re
  pip install re
Coding Guidelines
All your Python resides in root.
The SQL file is also located in root.
Assignment
Write a command line program that simulates checking password strength based on certain rules.
Write a program that accepts a log file and writes 3 different log files - one for each type of log entry ( i.e. INFO log, DEBUG log and ERROR logs) containing those relevant type of log entries.
SQL QUERIES
Instructions
To Run the python files
$ python3 passwordChecker.py
same procedure for fileparsing.py
The output files are already in the repository to test the program you can delete output file (DEBUFlog.txt,INFOlog.txt & ERRORlog.txt)
You can also use your own log file but it should be copied into the root directory
Unit Test Cases
Password checker
```
python3 passwordChecker.py
>>> Enter Your Password =AbC
Password Strength LOW
Password should have atleast 8 characters
Password should contains atleast 2 special characters

python3 passwordChecker.py
>>>Enter Your Password =abcd@@
Password Strength AVERAGE
Password should have atleast 8 characters
Password should contains atleast 2 numbers

python3 passwordChecker.py
>>>Enter Your Password =abcde@&123
Password Strength VERY GOOD

```
File Parsing
```
python3 fileParsing.py
>>>Enter filename :abc
File Doesnt Exist

python3 fileParsing.py
>>>Enter filename :
Filename should not be Blank

python3 fileParsing.py
>>>Enter filename :log.txt  // will create file with required data
Process Done!

```
