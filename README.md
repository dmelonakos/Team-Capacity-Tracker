# Team-Capacity-Tracker

## Link
https://sites.google.com/view/fddcapacitytracker/full-page-embed

## Description
The Team Capacity Tracker was built to help my team manage workload. Previously, senior members would message junior members individually to find out who had availability for a new task. While we use a weekly capacity tracker in Excel, it is static and doesn't provide real-time information on who is available right now.

This web app serves as a live, interactive status board. Team members log their current workload, office, position, and a short note.

The visual bubble map and list view allow the team to see everyone's availability at a glance. Users can filter the team by office or role, click on an available member's bubble, and instantly generate an email to request assistance. In order to keep the board accurate, any status older than 48 hours is automatically removed.

## Key Tools
- React: Handles the user interface and keeps the screen updated as you change filters or views.
- D3.js: Powers the interactive bubble map, allowing you to drag, pan, and zoom.
- Tailwind CSS: Provides clean, FTI-branded styling.
- Google Firebase: Acts as the live database. It syncs everyone's screen instantly when a status changes and automatically deletes expired records to keep the system fast.
