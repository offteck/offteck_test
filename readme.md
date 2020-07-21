# Front End Application - A TO-DO app.
In this application you're asked to design and implement the following.
The application should be able to handle user login and user registration.
## Functional Requirement’s

### User Signup/Registration
1. Create a user signup form which intakes the user’s information such as name,
address, date of birth, phone number and username.
2. Only the phone number entered in the following format will be valid (i.e. 999-999-9090)
3. Date of birth can be inputted in any formats.
4. After successful entry and validation of this data the user should be created and
saved in the database. (For this purpose any in-memory database utilization will be accepted)

### User Login
1. Allow user to sign in to the application by validating the user’s username and
password

### Home Page (You can consider only 10-50 tasks will be created for the purpose of this test)
1. Upon successful login the user should be redirected to the homepage where he can
perform CRUD operations on the tasks.
    1. The user should be able to create a task. Such created tasks should be
displayed in a list view to the users.
    2. Every task should have small buttons to perform update and delete on
those respective tasks.
    3. Every task should be easily identifiable as a different task. Consider color
coding.
2. Status of the task could be created, in progress, completed. (Preferably distribute the tasks in different statuses.)
3. The home page will also have header and footer area.

### Branding feature. ( Theme Management ) (Bonus - Not required)
The application’s UI color coding should be easily configured. Consider a use case
where this platform could be distributed to different
vendors and they have the option to apply their own color coding to this application.
## Codebase Design Requirements
* We are looking for clean organization of code. We would be looking at what design
choices are made, how is the folder structure organized for files such as css, html, js, jsx etc.
* If using React, greater emphasis on reusable components, higher order functions will
be given.
## Deployment/Hosting (NO coding is required to implement CI/CD)
Please provide an explanation as to how you choose to deploy this web application and make it available to use. What strategies you would choose ?
## Notes ::
1. Use of any 3rd party packages, libraries is permitted. Ideally such libraries should be
stable, reliable, simple to integrate and smaller in size.
2. Feel free to use any technologies you choose, but React will be preferred choice.
Submission
* Please provide a link to the app if you host it. (Optional)
* Upload it on Github and provide us a link.
* Also, provide estimation before starting the test.