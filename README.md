# Mathnasium-Auto-Reminder
A terminal based GUI that uses a headless version selenium to send text messages to parents. The message is usually about a student being late/not showing up.

# The task
Automatically send messages to the parents of kids that are late to their Mathnasium tutoring session.

# Why is this important?
Sometimes there are a lot of students that are late or do not show up to their online or in person tutoring session.
Identifying the phone number of the parent and then texting them could take some time.
Making a system that can easily text parents with a few clicks of a button will save a lot of time.

# Problem!
How was I going to make a system to easily text our student's parents?

# Solution
Using the [Textfree](https://textfree.us/) service I was able to use a headless version of [Selenium](https://www.selenium.dev/) for this project.

# Nice Features
Let's say there is a new student added to our roster. How could could anyone from any computer (that works at Mathnasium) put their information in a file for the program to read? 
### Solution
Everytime the program is run it fetches the most up to date data using [PyDrive](https://pythonhosted.org/PyDrive/) from a google spread sheet. Any employee can add a student's name, and their parents phone number to this google sheet, so the program can read it. 

# Description
Please install the necessary modules/packages below in your command prompt by typing in the commands below.
If you do not have pip installed please install it here: https://pip.pypa.io/en/stable/installation/
The only file that is needed that is NOT generated by this program is the client_secret.txt file
This file contains important authentication data to verify our identity.

requests - pip install requests
time - pip install time
datetime - pip install datetime
bs4 - pip install bs4
re - pip install re
pandas - pip install pandas
pydrive - pip install pydrive
numpy - pip install numpy
selenium - pip install selenium

Enjoy!

And... yes this program was tested and successfully put to use in the workplace. 
