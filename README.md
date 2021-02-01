# 5-day-planner

## 05 Third-Party APIs: Work Day Scheduler

A project to introduce the concept of third party api's through the implementation of a day planner.


## Purpose and Scope

The purpose of this website is to allow a user to view their schedule for the current day and edit it as needed. 

This project is limited in scope. It only displays the current day and does not have an option to schedule anything beyond the current day nor reference past days. 


## Installation

No installation is required. This is a web-based ap. Click here to access it:
https://lasettebrown.github.io/5-day-planner/

## Instructions

When the site loads the user will be presented with a scheduler for the day. The page will display today's date at the top and list blocks of time in units of one hour. The scheduler starts at 7:00am and ends at 7:00pm. 

![Day Scheduler](./assets/images/lasettebrown.github.io_5-day-planner_.png)

The user may click into the text area within any hourblock listed in order to add text to that space. Clicking the 'SAVE' button to the right of each hourblock will save any text entered into the user's local storage so that the text remains even if they refresh the page or navigae away from it.

The color of the timeblock indicates whether that hour is in the past, present or future. Grey indicates that the timeblock is in the past. Red indicates the current hour. Green indicates future hours.

## Built with

The HTML and CSS were provided for this project. I used JavaScript and Jquery to create the dynamic elements on the page. I used Luxon to access and format dates and times for this project. 

Find more information about Luxon here:
  * [Luxon](https://moment.github.io/luxon/)

## Authors

The HTML and CSS for this page were provided by the instruction team at the University of Denver Full Stack Web Development Coding Bootcamp. JavaScript and Jquery were written by Lasette Brown.


## License

The content of this website is copyrighted. Please do not use the content without permission.
© 2021 Lasette Brown. All Rights Reserved.









