# Hotel Management System

## Overview
The **Hotel Management System** is a console-based application built using **Java**, **JDBC**, and **MySQL**. It allows hotel staff to efficiently manage room reservations, customer information, and payments. The system provides several functionalities such as making a reservation, viewing existing reservations, retrieving room numbers, updating and deleting reservations, and processing payments.

## Features
- **Reserve a Room**: Allows users to make a new reservation by providing guest details and room number.
- **View Reservations**: Displays all the current reservations with their details.
- **Get Room Number**: Retrieves the room number for a specific reservation by ID and guest name.
- **Update Reservation**: Allows updating reservation details like guest name, room number, and contact information.
- **Delete Reservation**: Deletes a reservation by its ID.
- **Make Payment**: Processes payments using the guest's account number and PIN, updating the account balance.

## Technologies Used
- **Java**: Programming language used to develop the system.
- **JDBC**: Java Database Connectivity for connecting the application to the MySQL database.
- **MySQL**: Relational database for storing reservation and account information.
- **Scanner**: Used for taking input from the user through the console.

## Database Schema
The system uses the following tables:

### 
1. **accounts**
2. **reservation**
3. **users**
