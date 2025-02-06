# Bus Reservation System

## Overview
This **Bus Reservation System** is a C-based program that allows users to:
- Login with a valid username and password.
- Book tickets for available buses.
- Cancel booked tickets.
- Check the status of a specific bus, including available seats and fare details.

## Features
- Supports multiple users with authentication.
- Allows ticket booking and seat assignment.
- Enables ticket cancellation.
- Displays real-time bus status including source, destination, total seats, available seats, and fare.

## Installation & Compilation
To compile and run this program, use the following commands:
```sh
gcc bus_reservation.c -o bus_reservation
./bus_reservation
```

## Usage
1. **Run the program** and select the login option.
2. **Enter valid login credentials.**
3. **Once logged in, you can:**
   - Book a ticket by selecting a bus and providing passenger details.
   - Cancel a booked ticket by providing passenger details.
   - Check the status of a bus, including seat availability and fare.
   - Logout when done.

## Example Output
```sh
=== Bus Reservation System ===
1. Login
2. Exit
Enter your choice: 1

Enter Username: user1
Enter Password: password1
Login successful. Welcome, user1!

=== User Menu ===
1. Book a Ticket
2. Cancel a Ticket
3. Check Bus Status
4. Logout
Enter your choice: 1
Enter Bus Number: 101
Enter Passenger Name: Alice
Enter Passenger Age: 25
Ticket booked successfully!
```


## Created By
**Diyansi Chaudhary**

