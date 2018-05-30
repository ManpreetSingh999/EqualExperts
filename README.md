# EqualExperts
Hotel Booking System
Project version: HotelBooking_v1.0
# Technology used - 
Behaviour Driven Development approach using Cucumber - Gherkin
Selenium Webdriver
Maven build automation tool
JUnit as a Test Runner
# This Automation Framework consists of the following Packagaes and classes-
'broswerObject' package containing 'BrowserFactory.java' class: This class initialises the Browsers and their drivers to be called in the tests.
'features' package containing 'Booking.feature' file: This file contains the features, scenario outlines and scenaorios to be tested including the Examples tables which contains the data to be called by the test scripts
'runner' package containing 'TestRunner.java' class: This class contains the scripts which initiates the tests using JUnit as a Test Runner
'stepDefinitions' package containing 'CreateBooking.java' and 'DeleteBooking.java' classes: These classes are the test cases for the creation and deletion of the booking on the Hotel Booking system.
All the dependencies have been added in the pom.xml file which in turn adds the required JAR files to the project
# RUNNING THE PROJECT:
In order to run the project, kindly import the HotelBooking_v1.0.jar in the Workspace using an IDE.
Navigate to the 'TestRunner.java' class and run the code using JUnit. This will automatically create 2 bookings in the system as well as delete a recently created booking.
