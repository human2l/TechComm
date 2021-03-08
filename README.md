# TechComm
A social network app for developers.

Using ReactJS, NodeJS, Express and MongoDB

To view the production please click this link: https://warm-everglades-50194.herokuapp.com/  
Just register a make up username & password and everything is ready to go!

## Landing Page
A brief introduction of TechComm App, provide two buttons: Login and Register

## Authentication Page (Register && Login)
### Register Page
Provide register form
|Form Content
|---
|Name
|Email Address
|Password
|Confirm Password

### Login Page
Provide login form
|Form Content
|---
|Email Address
|Password

After register or login success, direct to dashboard page

## Dashboard Page
#### If new user:
provide "create profile" button
#### Else:
* show 3 options(button): "Edit Profile", "Add Experience" and "Add Education"
* show user's Experience Credentials & Education Credentials
If user click Edit Profile, show form:
|Form Content
|---
|Professional Status
|Company
|Company Website
|Location
|Skills
|Github Username
|Social Links

If user click Add Experience, show form:
|Form Content
|---
|Job Title
|Company
|Location
|From Date
|Current Job `or` To Date
|Job Description

If user click Add Education, show form
|Education Content
|---
|School or Bootcamp
|Degree or Certificate
|Field of Study
|From Date
|Current School `or` To Date
|Program Description

## Developers Page
LIST: List all of the users registered on this app with their brief intro 
Provide "View Profile" button on each list item 
If "View Profile" button clicked  
Show selected person's detailed info including all of experience and education  
Using Github api get latest 5 of selected person's repository info(name, stars, watchers, forks)  

## Posts Page
Provide a textfield for user to create a new post  
LIST: List all users' posts down below  
If user click "Submit" button, the new post will add to LIST below  
|List Item
|---
|avatar
|name
|post content
|"like" button
|"unlike" button
|"Discussion" button (with discussion counts showed)

If user click "Discussion" button show "Leave Comment" Component:  

### Leave Comment
Show selected post  
Provide a textfield for user to leave a comment to current post
LIST: list all comments of selected post
If user click "Submit" button, the new comment will add to LIST below
|List Item
|---
|avatar
|name
|comment content
|comment date


