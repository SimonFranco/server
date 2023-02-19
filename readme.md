For my milestone project, i decided to work on a simple version of a social media site. The purpose of working on this site was to learn how to implement certain features onto sites such as adding friends, making posts, dark and light mode and also liking posts.


Technalogies used for this app are Material UI, Redux Toolkit, React Router,React Dropzone ,Formik, and Google Fonts on the front end. Node,MongoDB ,Mongoose JsonWebToken, MulterGridFS-Storage and   Yup on the backend.


Bugs that i have found so far are that sometimes an image  isnt supported so post doesnt get uploaded. Also, when adding or removing a friend the friend count on current user isnt updated until you do a refresh. 


To use the site, you must make an account which will take you to a home page containing all users posts. From there you have thw option to add and remover friends, make and delete posts, and also switch from light and dark mode by using the dark/light mode icon in the upper right hand corner.













TableName- user 
id - String
firstname - string 
lastname - string 
friends - Array <Object>
email - string 
password - string 
picturepath - string ref
location string 
occupation - string 
Views - number
impressions - number



Tablename Post
id - string     
userid string 
firstname - string 
lastname - string 
location - string 
description - string 
userpicturepath - string ref
picture path - string  ref
likes 
comments - array <string>


tablename friends
id -string 
firstname - string 
lastname -string 
picturepath -string ref
occupaton -string 
location-string 


