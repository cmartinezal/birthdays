# birthdays
Webpage built using Flask. CS50 Problem Set 9.

<img width="1250" alt="Screenshot 2024-03-12 at 18 41 49" src="https://github.com/cmartinezal/birthdays/assets/84383847/1b8597e6-f952-4508-ae92-b537c5668415">



## Problem to Solve

Create a web application to keep track of friends’ birthdays.

## Implementation Details

Complete the implementation of a web application to let users store and keep track of birthdays.

- When the `/` route is requested via `GET`, your web application should display, in a table, all of the people in your database along with their birthdays.
  - First, in `app.py`, add logic in your `GET` request handling to query the birthdays.db database for all birthdays. Pass all of that data to your index.html template.
  - Then, in `index.html`, add logic to render each birthday as a row in the table. Each row should have two columns: one column for the person’s name and another column for the person’s birthday.
- When the `/` route is requested via `POST`, your web application should add a new birthday to your database and then re-render the index page.
  - First, in `index.html`, add an HTML form. The form should let users type in a name, a birthday month, and a birthday day. Be sure the form submits to `/` (its “action”) with a method of post.
  - Then, in `app.py`, add logic in your `POST` request handling to `INSERT` a new row into the birthdays table based on the data supplied by the user.

Optionally, you may also:

- Add the ability to delete and/or edit birthday entries.
- Add any additional features of your choosing!

  <img width="1290" alt="Screenshot 2024-03-12 at 18 41 33" src="https://github.com/cmartinezal/birthdays/assets/84383847/da9f610f-e060-462f-9ca1-48dbc958b806">


  
