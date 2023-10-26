# JeffersonCountyLibrary

## Setup
* Fork and Clone this repository
* Run `update-database`

## Exercise (12 points)

Check out a new branch and complete the following tasks **in order**:
* 2 points - There is a bug in our authentication!  Identity looks like it is set up, but we can't register users.  Find and fix this bug! (Hint: this should only take one line of code)
* 2 points - Right now, anyone can 'check out' a book.  Update the application so that only a logged in user can check out a book.
* 4 points - In this application, we have the ability to create new books.  Improve this functionality by:
  * Add a link from the nav-bar to add a book
  * Make sure only Librarians can add a book
* 2 points - Create a descriptive pull request and merge this branch into main
* 2 points - Take a screenshot of a database query result from pgAdmin that clearly shows which users in your database are librarians.  Update this README to include your screenshot below:

   <img width="332" alt="image" src="https://github.com/Eli-J-Paris/Launch_Mod5Week3Assessment/assets/130601227/1704ce50-aef8-46c4-9782-37894f7393df">


  

## Questions (6 points)

Answer the questions below in this README.  Answer these questions as if you are in an interview!

1. What are roles and claims as they relate to Authentication and Authorization?
"First I'd like to define the difference between authentication and authorization. Authentication is asking the question does this User belong here by verify that they are who they say they are. Authroization on the other hand is asking the question what level of access does a User have. Both roles and claims can be used to bolster levels different levels of authorization. When thinking about roles I often think of a role of an Admin. These Admins typically have more access to areas of a program than say a typical user would. Admins could have the ability to say delete a users message on a message board or delete a users account while a typical user might not even know about this functionality. One thing to note about Roles is they typically stay the same for a particular user and are often changed manually a database. Claims on the other hand are a bit more dynamic and can change more often. These changes usually happend based on users attributes. For instance an application could have different subscription levels based on how much a user is willing to pay. A user could have a claim to one subcription level one day and decide to pay more for a higher subscription level the next. If that was the case that user would then have a claim to that higher subcription level."

3. How do cookies play a role in authentication and authorization?

 "Cookies allow a browser to remember a specfic user and because a specfic user can have roles and or claims in an application the cookies tell the application what level of access a user has. One really common example is when you log into a website and check the remember me box. This is creating a cookie that is being stored in your browser that rembers you when you come back to that website at a later date. All that being said, cookies play a large part in authetication by automatically checking if a user is who they say they say they are."

5. If asked to implement Auth in a new .NET application, would you use the Identity framework?
"As it stands right now, I have more experience handrolling authentican into my applications. I peronally enjoy designing and implmenting things such as password validation, and adding verifaction to applcations to see if a username already exsistis in a database and if so a new account can't be created with that same username. That being said, in the time I have spent working with Identity framework not only offers more robust authentican and authrization, it saves me the time and energy of designing, implmenting and testing my own handrolled versions. So while I do feel comfortable hand rolling auth I feel like using identity framework is a standard that I will use going forward."
## Rubric

This assessment has a total of 18 points.  Earning 12 or higher is a pass!
