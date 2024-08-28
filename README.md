# Simple Attendance Tracker
# Overview

This Python-based system provides a convenient solution for tracking student attendance and sending timely reminders for excessive absences. 
By leveraging an Excel sheet and email notifications, it automates the process, saving time and effort for both students and staff.

# Features
* Automated attendance tracking: Automatically records student absences based on data entered into an Excel sheet.
* Personalized reminders: Sends email reminders to students when they approach their attendance limit for a particular subject.
* Notification system: Notifies both students and staff when a student exceeds the allowed absence limit.
* Efficient workflow: Streamlines the attendance tracking process, eliminating the need for manual paperwork.

# Requirements

* Python
* library (for reading and writing Excel files)
* smtplib and email libraries (for sending emails)

# Installation
Install the required libraries using pip or conda:

# Bash
pip install openpyxl smtplib email

# Usage
Prepare your Excel sheet: Create an Excel sheet containing the following columns:

* Roll number
* Student email ID
* Subject {1, 2, ..., N}

For this example, use the following subject codes:

* Machine Learning: 1
* Python: 2
* Data Analysis: 3

Run the Python script: Execute the script, providing the path to your Excel sheet as input.

Enter attendance data: When a student is absent, enter their roll number, subject code, and the date of absence into the script.

# How it works
The script reads the Excel sheet, updates the attendance records, and sends email reminders or notifications based on the defined absence limit.

# Customization
* Absence limit: Adjust the absence limit to suit your institution's policies.
* Email settings: Configure the email settings (sender address, password, SMTP server) to match your email provider.
* Subject and message templates: Customize the email subject and message content to fit your specific needs.

# Additional features
Consider adding features like attendance reports, integration with learning management systems, or real-time notifications.
* Note: Ensure that your email provider allows sending emails using SMTP and that you have the necessary authentication credentials.
