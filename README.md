Flight Reservation System Demo
This Demo project is designed to showcase an Object-Oriented Programming approach for managing a regional airline. It establishes a class structure to handle the main entities involved in flight booking. People are separated into Employees and Passengers, both inheriting from an abstract Person class. Flights are composed of multiple Seats. Passengers can create a Reservation, which belongs to a specific Flight.

Functionality
The program allows for the basic administration of the airline system, including:

Registering new passengers and employees.

Creating and managing flights with seat capacities.

Processing flight reservations (confirming and canceling).

It consists of a menu with initial options and runs entirely on the console.

Considerations
The program only runs in the console and is built using standard C++, meaning it is compatible with all operating systems.

compile with: "g++ main.cpp Person.cpp Passenger.cpp Employee.cpp Flight.cpp Seat.cpp Reservation.cpp"

run in linux: "./a.out"

run in windows: "a.exe"
