Hotel Booking System

Problem Statement
To Develop a simple Hotel Booking System using Python that allows different types of users (Guest, Receptionist, and Hotel Manager) to interact with the system.

The system should support:
- User registration and login
- Room management
- Room booking for specific dates
- Booking tracking and invoice generation
- 
Actors
1. Guest
a,View available rooms
b,Book a room for specific dates
2. Receptionist
a,View all bookings
b,Generate invoice for a booking
3. Hotel Manager
a,Add new rooms
b,View all rooms

System Attributes
Rooms
1,Room Number
2,Type (AC / Non-AC)
3,Floor
4,Rate
5,Status (Available / Booked)

Bookings
1,Booking ID
2,Guest ID
3,Room Number
4,Check-in Date
5,Check-out Date
6,Status

Logic Used
The system is implemented using:
1,Dictionary which to store users
2,List of dictionaries to store rooms and bookings
3,While loops for user interaction
4,Conditional statements for role-based access

Core Logic:
1. User registers with role (guest/receptionist/manager)
2. Login validates user credentials
3. Based on role:
   a,Guest books room
   b,Receptionist views bookings & generates invoice
   c,Manager adds rooms
4. Booking updates room status from available to booked
5. Invoice is calculated based on room rate
