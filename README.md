#  Bus Ticket Management System in C

A simple **Bus Ticket Management System** developed using the **C programming language**. The system allows users to view available buses, book tickets, display booking information, and manage passenger records.

## Features

* View available buses
* View bus routes and schedules
* Book a bus ticket
* Enter passenger information
* Generate a ticket
* View booked tickets
* Search booking information
* Cancel a ticket
* Calculate ticket prices
* Simple menu-driven interface

##  Technologies Used

* **Programming Language:** C
* **Compiler:** GCC
* **Platform:** macOS / Linux / Windows
* **Interface:** Command Line / Terminal

##  Project Structure

```text
bus-ticket/
│
├── main.c
├── README.md
└── bus_ticket
```

##  How to Run

### 1. Clone or download the project

Open your terminal and move to the project directory:

```bash
cd bus-ticket
```

### 2. Compile the program

Using GCC:

```bash
gcc main.c -o bus_ticket
```

### 3. Run the program

On macOS/Linux:

```bash
./bus_ticket
```

On Windows:

```bash
bus_ticket.exe
```

##  Example Operations

When the program starts, users can select options such as:

```text
=================================
     BUS TICKET SYSTEM
=================================

1. View Buses
2. Book Ticket
3. View Tickets
4. Search Ticket
5. Cancel Ticket
6. Exit

Enter your choice:
```

##  Passenger Information

During booking, the system may request:

* Passenger name
* Phone number
* Bus number
* Destination
* Travel date
* Seat number

##  Ticket Information

A successful booking can display information such as:

```text
=================================
          BUS TICKET
=================================
Passenger : John Doe
Bus No.   : BUS-101
Route     : Dar es Salaam - Arusha
Seat No.  : 15
Price     : TZS 35,000
=================================
```

##  Purpose

The purpose of this project is to demonstrate fundamental C programming concepts, including:

* Variables and data types
* `if` statements
* `switch` statements
* Loops
* Functions
* Arrays
* Structures
* String handling
* File handling
* Input and output

##  Future Improvements

Possible future features include:

* Login system for administrators
* Database integration
* Online ticket booking
* Payment integration
* Automatic seat allocation
* Printable tickets
* Customer account management
* Improved user interface

##  Author

**Bus Ticket Management System**

Developed as a C programming project.
by eDDie

##  License

This project is intended for educational and learning purposes.
