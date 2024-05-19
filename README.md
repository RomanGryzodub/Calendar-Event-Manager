Calendar Event Manager

This Google Apps Script project is designed to manage calendar events by reading a schedule from a Google Sheets document, grouping same-day events, and creating corresponding events in a Google Calendar. It also includes functionality to fetch existing calendar events and update the spreadsheet.

Features
Clear Calendar Events: Deletes all events from the specified Google Calendar for the current year.
Create Calendar Events: Reads events from a Google Sheets document, groups same-day events with the same title, and creates calendar events.
Fetch Calendar Events: Fetches events from the specified Google Calendar and updates the Google Sheets document.
Setup
Google Sheets Setup:

Create a Google Sheets document.
Set up the sheet with the following columns:
DATE: The date of the event.
DAY: The day of the week.
TIME: The time range for the event (e.g., 7-8).
ACTIVITY TERM: The title of the event.
Google Apps Script Setup:

Open the Google Sheets document.
Go to Extensions > Apps Script.
Copy and paste the script provided into the script editor.

Instructions
Replace YOUR_CALENDAR_ID with the ID of your Google Calendar.
Save the script in the script editor.
Run the functions createCalendarEvent and fetchCalendarEvents as needed.

License
This project is licensed under the MIT License - see the LICENSE file for details.
