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

The screen shots attached are from Safari browser. However, this application runs on all browser (IE, Edge, Mozilla, Chrome etc.).

![picture alt](https://github.com/suneetkh/PeopleSearch/blob/master/PeopleSearch/images/ss1.png "Screen Shot 1")
![picture alt](https://github.com/suneetkh/PeopleSearch/blob/master/PeopleSearch/images/ss2.png "Screen Shot 2")

## Application Tooling

### API / Service / Data Access
* Application created with Visual Studio Community for Mac (I tested on a Windows 10 machine using Visual Studio 2017.
* The design/architectural pattern used is Model-View-Controller (MVC).
* The web technology I used for front end is JavaScipt.
* .NET Core 2
* Microsoft SQL Server

### How to start the Web API:
* Install Visual Studio 2017 if you havn't already.
* Open the PeopleSearch.snl with Visual Studio.
* Click the 'Run' button on the Visual Studio tool bar.
* This should open a browser window pointed to http://127.0.0.1:8080

Note: I did my best to make sure the solution would load, build and run without any problems. If you face any issue loading, building or running the project, please email me at srk.suneet@gmail.com and I'd be happy to correct the issue.

## Simulation of Slow Search
In order to simulate a slow search, I used Google Chrome's developer tool to throttle the connection speed.

The throttle settings are under the Network tab on the top right where it says "Offline" and "No throttling". I used the "Slow 3G" and "Offline" presets, but custom speeds and latency settings are also available. I first let the page load before throttling the connection, this way only the search operation is slowed.
