# Bonnier Publications Coding Challenge
This repository contains a [Laravel](https://laravel.com/docs/7.x) and [VueJS](https://vuejs.org/) starter application, which doesn't quite work.

There are specified tasks below, which needs to be solved to complete this coding challenge.

1. Don't fork the repository, please download/clone the source code instead.
2. Create a github public repository and push your solution to the repository master branch.
3. Send the repository URL to us. 

## Project description
Bob is a freelancer that wants to keep track of how much time he spends working on different projects.
At any given time he is working on different projects, giving each of them a unique name.
He needs to be able to log the date, the time he starts, and the time he stops working on a project, so that he knows how much time (hours, minutes, seconds) in total he has spent on it.
He needs to be able to start and stop the same project multiple times.
For a GUI, Bob does not need much, but he must be able to see an overview of the time spent on his projects, create new projects, and add entries to existing ones.

## Tasks:
These objectives are mandatory:

1. New user registration should be disabled. 
2. Implement database user seed with email:test@example.com, password:secret (for testing purpose).
3. If the user isn't logged in, all URLs should redirect to the login page.
4. Make auth middleware global, instead of in constructors of controllers.
5. Verify project name are unique and display error when submitting existing name.
6. Add functionality to support adding entries to projects.
7. Calculate total time (hours, minutes, seconds format) spent on a project and display it in the project overview.
8. It should be possible to delete entries and projects.
9. When adding or updating a project, make the project overview automatically update.
10. Make comments to the important part of your code and readme file of how to bootstrap (setup) your solution, so we can test it on a local machine.

## Bonus:
These objectives are optional:

11. Add unit tests to prove functionality.
12. Set Up Laravel, Nginx, and MySQL with Docker Compose for your solution.
