# Railway-Reservation-System
This project was a team effort of myself Hariharan A and my friends Girish and Kaarthik Shrinivaas

We have created a database “LOGIN” and created some schemas.
They are:
BOOKINGHISTORY
PASSENGERDETAILS 
TRAINS
USERS

index.php is the starting page of our project. So after creating the database run the project with index.php as the first page
We have divided the project into modules that will use the above relationship schemas to perform the required operations

The following modules are:
Index.php-login page 
loginProcess.php-checking whether the user exits
SignupPage.php-first time user access
SignupProcess.php-inserting user details into database
Available.php-train details
Ticketbooking.php-enable user to book tickets
TicketDetails.php-to store/show the ticket details
Canceltickets.php- to cancel the tickets
Bookinghistory.php-to view and book tickets from the previous ticket details
FinalBooking.php- filling the ticket details




RELATIONSHIP SCHEMA
BOOKING HISTORY 
Attributes:
bid(primary key)
UserID(foreign key)
TrainNumber(foreign key)
DateOfJourney
NoOfTickets
Purpose: To store the booking details of the user

PASSENGERDETAILS 
Attributes:
PID(primary key)
UserID(foreign key)
TrainNumber(foreign key)
DateofJourney
PassengerName
PassengerAge
Purpose: To store the ticket details of passengers

TRAINS
Attributes:
TrainNumber(primary key)
TrainName
FromPlace
ToPlace
Arrival
Departure
NumberOfSeats
DateOfJourney

Purpose:
To store the details of trains

USERS 
Attributes:
ID(primary key)
Username
Email
Password

Purpose: To store the details of the user

SOFTWARE REQUIRED
MySQL- Structured Query Language from Microsoft.
XAMPP -For implementing PHP and running a website locally on my laptop.
PhpMyAdmin -To connect the database to PHP and HTML.
Brackets -For implementing code

PROGRAMMING LANGUAGES USED
Structured Query Language (SQL)
Personal Home Page(PHP)
Hyper Text Mark-up Language(HTML)
Cascading Style Sheets(CSS)

--------------------
NOTE:
Kindly modify and create database according to the code
