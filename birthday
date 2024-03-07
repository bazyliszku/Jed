import datetime

# Prompt the user for their name
name = input("Enter your name: ")

# Prompt the user for their date of birth
dob = input("Enter your date of birth (YYYY-MM-DD): ")

# Convert the input string to a datetime object
dob_date = datetime.datetime.strptime(dob, '%Y-%m-%d')

# Get today's date
today_date = datetime.datetime.now().date()

# Check if today is the user's birthday
if dob_date.month == today_date.month and dob_date.day == today_date.day:
    ("Happy birthday, {}!".format(name))
else:
    ("Hello, {}! Today is not your birthday.".format(name))
