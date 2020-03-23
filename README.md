# The People Search Application 

## Business Requirements <br>
* The application accepts search input in a text box and then displays in a pleasing style a list of people where any part of their first or last name matches what was typed in the search box (displaying at least name, address, age, interests, and a picture).  <br>
* Solution should either seed data or provide a way to enter new users or both. <br>
* Simulate search being slow and have the UI gracefully handle the delay. 
 
## Technical Requirements 
 
* A Web Application using WebAPI and a front-end JavaScript framework (e.g., Angular, React, etc.).  <br>
* Use an ORM framework to talk to the database. <br>
* Unit Tests for appropriate parts of the application. 

## Sample Screen Shot 

![picture alt](https://github.com/suneetkh/PeopleSearch/blob/master/PeopleSearch/images/ss1.png "Screen Shot 1")
![picture alt](https://github.com/suneetkh/PeopleSearch/blob/master/PeopleSearch/images/ss2.png "Screen Shot 2")


## Simulation of Slow Search
In order to simulate a slow search, I used Google Chrome's developer tools to throttle the connection speed.

The throttle settings are under the Network tab on the top right where it says "Offline" and "No throttling". I used the "Slow 3G" and "Offline" presets, but custom speeds and latency settings are also available. I first let the page load before throttling the connection, this way only the search operation is slowed.
