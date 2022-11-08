Introduction
------------

This is a PHP Project entitled Sentiment Based Movie Rating System. This is a web-based application that calculates the success rating or review ratings of a movie. The project uses a simple sentiment-based analysis to identify or calculate the movie success rate. This has a simple user interface and easy-to-use. The application contains user-friendly functionalities and features.

About the Sentiment Based Movie Rating System
---------------------------------------------

I developed this project using the following:

-   [XAMPP v3.3.0](https://apachefreinds.org/) as my local webserver that has a PHP Version 8.0.7
-   PHP Language
-   MySQL Database
-   HTML
-   CSS
-   JavaScript
-   jQuery
-   Ajax
-   Bootstrap
-   AdminLTE
-   and some other plugins/libraries.

The Simple Sentiment Based Movie Rating System calculates the success rate or review rating using sentiment base analysis. The application has an Admin Panel that allows the management to populate the list of movies, genres, sentiment keywords, and etc. The Administrator users are in charge of the managing of listing the sentiment keywords (position or negative). Each sentiment keyword will be stored in the system database along with a score of the keyword.

### How does the System Calculate the Rating?

The system calculates the rates of each user's reviews in every movie. Each user is only allowed to submit a review/comment once in every movie. The system will extract each word in the user review's comment and searches the score of each word. The maximum rate in this system is 5.

Features
--------

### Management Side/Admin Panel

-   Secure Login and Logout
-   Dashboard
-   Manage Genres
    -   Add New Genre
    -   List All Genres
    -   Update Genre Details
    -   View Genre Details
    -   Delete Genre Details
-   Manage Sentiment keywords
    -   Add New keyword
    -   List All Sentiment Keywords
    -   Update Keyword Details
    -   Delete Keyword
-   Manage Movies
    -   Add New Movie
    -   List All Movie
    -   View Movie Details
    -   Update Movie Details
    -   List Movie Reviews/Comments
    -   Delete Movie
-   Manage Inquiries
    -   List All Inquiries
    -   View Inquiry Details
    -   Delete Inquiry
-   Manage Users list (CRUD)
-   Manage Account Details/Credentials
-   Manage System Information

### Public/User-Side

-   Login and Registration
-   Home Page*(displays the website's welcome content)*
-   List All Movies
-   List Movies by Genre
-   Search Movie
-   View Movie Details
-   Submit Review
-   Display/List Moview Reviews/Comments
-   Display About Us Content
-   Contact Us Page
-   Send Inquiry/Message
-   Logout

How to Run ??
-------------

Requirements

-   Download and Install any local web server such as XAMPP/WAMP.
-   Download the provided source code zip file. (*download button is located below*)

Installation/Setup

1.  Open your XAMPP/WAMP's Control Panel and start Apache and MySQL.
2.  Extract the downloaded source code zip file.
3.  If you are using XAMPP, copy the extracted source code folder and paste it into the XAMPP's "htdocs" directory. And If you are using WAMP, paste it into the "www" directory.
4.  Browse the PHPMyAdmin in a browser. i.e. http://localhost/phpmyadmin
5.  Create a new database naming msrps_db.
6.  Import the provided SQL file. The file is known as msrps_db.sql located inside the database folder.
7.  Browse the Sentiment Based Movie Rating System in a browser. i.e. http://localhost/msrps/
