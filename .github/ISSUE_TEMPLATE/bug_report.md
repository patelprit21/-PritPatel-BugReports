---
name: Bug report
about: Bug report for TaskMaster Application.
title: ''
labels: bug
assignees: patelprit21

---

Software:
TaskMaster (Version 3.0.2)

Bug Description:
The app poorly exhibits the due dates of tasks that continue into more than one month by sometimes summarizing the start and end dates when needed. This effectively describes a false representation of the deadline of user tasks, undermining users' scheduling. The problem likely lies in the faulty logic of parsing and formatting dates, which has to determine effectively between months and days. The application, therefore, has some inconsistencies, hence not reliable and usable in managing tasks. This should be worked on promptly to restore user confidence.

Steps to Reproduce:

Launch the TaskMaster app on your device.
Navigate to the "Tasks" or "To-Do List" section of the app.
Tap on the "+" or "Add Task" button to create a new task.
Enter the task details, including a title, description, and due date that spans across different months (e.g., from January 31st to February 5th).
Save the task and return to the task list view.
Observe that the newly created task appears in the list but displays an incorrect due date.
Instead of showing the correct date range (e.g., Jan 31 - Feb 5), the app displays an erroneous date (e.g., Jan 31 - Jan 5), causing confusion about the task's actual deadline.
Additional Information:

Device: Samsung Galaxy S22
Operating System: Android 13
App Language: English (United States)

Severity Label:
Medium
