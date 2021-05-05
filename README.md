# hotel_reservation_system_sap
## General Info
***
Hotel reservation system checks for the available slots based on the start and end days.

## Technologies
***
A list of technologies used within the project:
* C#
* Console application within .net core framework.
* MS Unit testing framework.

## Installation
***
A little intro about the installation. 
1. Download the zip file, extract and click the solution - "Hotel_Reservation_System.sln".
2. Build the solution and launch the application.

## Application Walkthrough
***
A little intro about validating the test cases. 
1. On successfully running the application, A prompt message asks us to enter the Room Number in the Console Window.
  e.g. input 3 via keyboard and press "Enter" through keyboard.( Room number can have a rangefrom 1 to 1000 ).
2. After successfully entering the room number, the system will prompt to enter the start/end days, Please enter the start day / end day
    in the specified format and press "Enter".
   Note: Please enter the values as "startday,endday" which for e.g., "2,5" where 2 is the start day and 5 is the end day.
3. After successfully entering the "startday,endday", a message will be prompt as "Accept" or "Decline" where Accept defines the reservation can be done and Decline defines
    reservation is not possible.
4. Navigate to the HotelReservationUnitTest.cs and run the unit tests.
