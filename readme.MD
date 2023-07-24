# Habit Tracker App
This is a habit tracker app built using MongoDB, EJS, Node.js, and Express. The app allows users to define and track their habits on a daily basis.

## Features
Add Multiple Habits: Users can add multiple habits to track, such as reading a book, going to the gym, etc.

Track Habit Status: Each habit has three statuses:

Done: Mark the habit as done for a day.
Not done: Mark the habit as not done for a day.
None: User did not take any action on the habit for a day.
View All Current Habits: Users can see a list of all the habits they are tracking. An "Add" button allows users to add new habits to track.

Habit Tracking for 7 Days: The app displays the last 7 days for each habit, including today. Users can mark today's habit status and view the status of the previous 6 days.

Toggle Habit Status: Users can toggle between the three statuses (Done, Not done, None) for today's habit and any of the previous 6 days.

Default User and Habit Attachment: The app has one default user, and habits are attached to that user. There is no authentication required.

Data Storage: Habit and status data are stored in a MongoDB database.


##  Usage
On the homepage, you can view all the current habits and their respective status for the last 7 days. Click the "Add Habit" button to add a new habit to track.

Click on a habit to view its details. On the habit detail page, you can toggle the status for today and any of the previous 6 days.

To add a new habit, click the "Add Habit" button on the homepage. Enter the habit name and click "Save" to add it to the list of tracked habits.

