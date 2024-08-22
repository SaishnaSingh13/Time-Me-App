#Time-Me

##Description

Time-Me is an Android application designed to help users efficiently manage their time by logging 
work hours, setting daily work goals, and viewing progress through visual reports. The app also 
includes a to-do list feature for task management. All data is stored in an online database using 
Firebase.

##Motivation

Time management is crucial for productivity and work-life balance. Time-Me aims to provide users 
with an easy-to-use tool to track their work hours, set goals, and visualize their progress, 
helping them stay on top of their tasks and improve their efficiency.

##Features 

User Authentication: Log in using a username and password.
Category Creation: Create categories for timesheet entries.
Timesheet Entries: Log entries with date, start and end times, description, and category.Optionally add photos.
Goal Setting: Set minimum and maximum daily work hour goals.
Entry Viewing: View a list of timesheet entries for a selectable period.
Photo Access: Access photos attached to entries.
Time Tracking Reports: View total hours spent on each category over a selectable period.
Graphical Reports: Visualize hours worked each day and compare with set goals.
Weekly Reports: Access detailed weekly reports.
To-Do List: Manage tasks with a built-in to-do list feature.

##Security Features

Data Encryption: All data transferred between the app and Firebase is encrypted.
Authentication: Secure user authentication via Firebase Authentication.
Access Control: Users can only access their own data.

##Key Elements

MainActivity: Handles user authentication and navigation.
CategoryActivity: Manages category creation and display.
TimesheetActivity: Manages creation and listing of timesheet entries.
EntryDetailActivity: Displays details of a specific timesheet entry, including the photo.
SettingsActivity: Allows setting of daily work hour goals.
ReportActivity: Generates and displays reports and graphs, including weekly reports.

##Installation

Prerequisites:
Android Studio installed on your computer.
A Firebase account with a project set up.

Setup Steps:
Clone the Time-Me repository to your local machine.
Open the project in Android Studio.

Configure Firebase:
Add the google-services.json file from your Firebase project to the app directory.
Ensure Firebase dependencies are added to build.gradle files.
Sync the project with Gradle files.

Dependencies:
Firebase Authentication
Firebase Firestore
Firebase Storage
MPAndroidChart for graphing
AndroidX libraries

##Usage

Logging In:
Open the app and log in using your username and password.
If you do not have an account, create one using the Register option.

Creating Categories:
Navigate to the Categories section.
Add a new category by entering a name and saving it.

Creating a Timesheet Entry:
Go to the Timesheet section.
Click on 'Add Entry' and fill in the required details (date, start time, end time, description, category).
Optionally, add a photo to the entry.
Save the entry.

Setting Goals:
In the Goals section, set your minimum and maximum daily work hour goals.

Viewing Entries and Reports:
View all entries for a selected period in the Timesheet section.
Access photos attached to entries from the list.
View total hours spent on each category and graphical reports in the Reports section.
Access detailed weekly reports in the Reports section.
