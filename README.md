# Rateaway
The app was designed to be a social media platform specifically for restaurant owners to advertise and for the general public to be able to find restaurants local to them. To create the app we opted to take a hybrid approach with HTML/CSS/JavaScript as opposed to using a native approach due to time constraints. To turn the functions of the code into a more app like style we employed Framework7, this made styling and traversal through the app much easier to implement. We also used Cordova to convert the HTML/CSS/JavaScript code into a deployable app for both Android and IOS. 

![Home Screen](/home_screen.jpg?raw=true "Home Screen")

One of the features on which the app was built is the login system (shown below). There are 2 possible accounts: a business account for any user who wishes to register restaurants and a regular user who wishes to find potential restaurants by viewing their videos. Business users can register an account and login with an email-password combination. Regular users can login with either Google or Facebook. This area of the app was my largest responsibility; I was responsible for all the backend validation associated with a registration and login feature, both on the client side via JavaScript and on the server side via PHP/SQL. I was also responsible for implementing the Facebook and Google login APIs and getting user information so that they can be queried with the database. 

![Login Screen](/login_screen.jpg?raw=true "Login Screen")

The other main feature that the app was built on was the scrolling video page where all the restaurant's videos would be shown to a user. A user can like/unlike a video which gives the restaurants feedback, and shortlist/unshortlist a video which allows the user to save a video for later viewing. I was responsible for the backend implementation of both features with regards to updating the database and visually indicating to the user that their action had been performed correctly. 

![Video Page](/video_page.jpg?raw=true "Video Page")

The page for the user to view their shortlisted videos was implemented as a grid which opens a scrolling video modal, similar to the video page, when a video is selected. I was responsible for gathering all of the video that user has shortlisted from the database. I was also responsible for handling the user unshortlisting a video while on the shortlist page. 

![Shortlist Page] (/shortlist_page.jpg?raw=true "Shortlist Page")

I was also responsible for handling the admin associated with putting the app on the Google Play Store in a closed testing capacity in addition to managing both the Google app console for the Google login feature and the Facebook app console for the Facebook login feature.


