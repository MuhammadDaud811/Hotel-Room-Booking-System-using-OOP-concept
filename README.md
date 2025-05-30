# Hotel-Room-Booking-System-using-OOP-concept
**Project Summary:**

This C++ project is based on Hotel Management System designed to manage hotel room bookings and customer data. It includes two main types of users: 
Admins and Customers. Admins have the ability to log in using predefined credentials and perform tasks such as adding, updating, deleting, viewing, and searching for rooms. Customers can sign up for an account, log in, view available rooms, search by type or number, book rooms, and cancel their bookings. Each room has details like room number, type (Single, Double, Suite), availability status, and price per night.
The system uses the concept of Object-Oriented Programming (OOP). The User class is an abstract base class, from which Admin and Customer are derived. The project describes inheritance, polymorphism through overriding login functions, and encapsulation by keeping data private and accessible through methods. 
All data is saved to and loaded from external files (rooms.txt and customers.txt), allowing data to be stored by the software in between iterations. It also includes input validation to ensure that users enter valid data.
This system is useful for understanding the concepts of OOP and also applying them to create software, especially in managing structured data. 

**1. Introduction:**

This project is a simple Hotel Management System coded in C++. It is 
designed to help manage hotel rooms, bookings, and user accounts. The 
system consists of two types of users: Admin and Customer. Admins can 
manage rooms (add, update, delete), while Customers can sign up, log in, 
view rooms, book rooms, and cancel bookings.

**2. Objectives:**

-The objective of this project is to design and implement a real-world Hotel 
Management System using Object-Oriented Programming in C++.
- Support admin and customer functionalities.
- Allows data to be stored by the software in between iterations.

**3. Main Features:**
- Admin login with pre-defined credentials.
- Customer signup and login system.
- Room management (add, update, delete, view, search).
- Booking and cancellation by customers.
- File handling for saving and loading data.
- Input validation and error handling.

**4. System Design:**

The system is built using OOP concepts like inheritance, polymorphism, 
encapsulation, and abstraction. The main classes are:
- User (Base class): Contains username and password.
- Admin & Customer (Derived from User): Represent different users.
- Room Class: Represents a hotel room with details like number, type, price, 
availability.
- Booking Class: Stores info of customer and booked room.
- HotelManagement Class: Main class that controls the system's logic and 
menus.

**5. Code Explanation:**

• Key Classes of the Project:
User Class (Base Class)
- Abstract base class with virtual login().
**Admin and Customer Class**
- Inherited from User Class.
- Have login() defined differently.
**Room Class**
- Contains room details.
- Has getter/setter methods and a static counter.
**Booking Class**
- Simple class for storing bookings.
**HotelManagement Class**
- Central class managing all logic (menus, files, operations).

**6. How the System Works:**

Following are the steps how system works:
1. Admin logs in and manages rooms.
2. Customers sign up or log in.
3. Customers can view/search rooms.
4. Customers can book or cancel rooms.
5. Data is saved in text files (rooms.txt, customers.txt).
6. File Handling & Data Storage:
Room and customer data is stored in text files. The system reads from these 
files on startup and writes to them on updates.

**7. **Input Validation & Error Handling:****

The system uses input validation in various functions to prevent invalid data 
(such as non-numeric input, empty usernames, etc.). It also uses 
'cin.clear()' and 'cin.ignore()' to handle incorrect inputs.
