# railwayTicketReservationConsoleApplication-usingJava

#### Description : 
The "Railway Ticket Reservation Console Application" project entails the creation of a Java-based system with two main classes: "Train" and "Main." The "Train" class manages train-specific information, including available seats and passenger data, while the "Main" class serves as the program's entry point, enabling users to book tickets or exit via a console menu. The application allows users to specify the number of tickets they want to book, input passenger details, and updates available seat counts accordingly. Error handling is implemented, and the program can be compiled and executed to facilitate railway ticket reservations.


**Problem Statement:**
Design and implement a simple railway ticket reservation system that allows users to book tickets for a train.

Steps:

Step 1: Create a Train class

Define a class called Train to represent a train.
Include instance variables such as trainName (String) and availableSeats (int) as private and passName (String []), passAge (int []) and count variable as public.
Note: Count value starts from 1. 
Implement a constructor to initialize the passName[], passage[].
Include getter methods to retrieve the trainName and availableSeats.
Implement a bookTicket method that takes no argument and updates the availableSeats accordingly.

Step 2: Create the Main class

Define a class called Main class.
Implement the main method inside the Main class.
Use the Scanner class to read user input from the console.
Create an instance of the Train class, passing the train name and available seats to the constructor.
Display a menu with options to book a ticket or exit the application.
Prompt the user to enter their choice and use a switch statement to handle different options.
If the user chooses to book a ticket:
Prompt the user to enter the number of tickets they want to book.
Get the Trainer name and number of Tickets, passenger name and age.
Call the bookTicket method of the Train object to book the tickets.
If the user chooses to exit the application, display a goodbye message and exit the program.
Handle any invalid choices with an appropriate error message.

Step 3: Compile and run the program

Compile the Java source code.
Execute the program to test the functionality.

