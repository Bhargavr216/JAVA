

# VBR Bus Bookings

## Table of Contents
1. [Introduction](#introduction)
2. [Features](#features)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Tools Used](#tools-used)
6. [Classes and Methods](#classes-and-methods)
7. [Screenshots](#screenshots)
8. [Future Enhancements](#future-enhancements)
9. [Credits](#credits)

## Introduction
The VBR Bus Bookings system is a Java Swing application designed to facilitate the booking of bus tickets. It allows users to input customer names, select seats, choose travel dates, calculate the ticket price, and check existing tickets.

## Features
- **Customer Name Input:** Field to input the name of the customer.
- **Seat Selection:** Users can select available seats.
- **Date Picker:** Calendar control to choose the date of travel.
- **Price Calculation:** Displays the ticket price.
- **Ticket Checking:** Button to check existing tickets.
- **Booking:** Button to finalize the booking.

## Installation
1. **Prerequisites:**
   - Java Development Kit (JDK) installed.
   - NetBeans IDE installed.

2. **Setup:**
   - Clone or download the project repository.
   - Open the project in NetBeans IDE.
   - Ensure all necessary libraries are included.

## Usage
1. **Running the Application:**
   - Open the project in NetBeans IDE.
   - Click on the 'Run' button or press `Shift + F6`.

2. **Booking a Ticket:**
   - Enter the customer name in the provided field.
   - Select a seat from the available options.
   - Choose the date of travel using the calendar.
   - The price field will display the calculated ticket price.
   - Click the 'Book' button to finalize the booking.

3. **Checking Tickets:**
   - Enter the date for which you want to check tickets.
   - Click the 'Search' button to view existing bookings for that date.

## Tools Used
1. **NetBeans IDE:**
   - Integrated Development Environment (IDE) used for developing the Java Swing application.
   - Provides a comprehensive set of tools for building desktop applications in Java.

2. **Java Swing:**
   - GUI toolkit used to create the graphical user interface of the application.
   - Part of the Java Foundation Classes (JFC).

3. **Java Development Kit (JDK):**
   - Provides the necessary tools to develop and run Java applications.
   - Includes the Java Runtime Environment (JRE), an interpreter/loader (Java), a compiler (Javac), an archiver (Jar), a documentation generator (Javadoc), and other tools.

## Classes and Methods
### Main Class: `VBRBusBookings`
- **Methods:**
  - `main(String[] args)`: Entry point of the application.
  - `initComponents()`: Initializes all components in the form.
  - `calculatePrice()`: Calculates the ticket price based on selected options.
  - `resetFields()`: Resets all input fields to their default values.
  - `bookTicket()`: Finalizes the booking process.
  - `checkTickets()`: Displays existing bookings.

### Ticket Checking Class: `CheckTickets`
- **Methods:**
  - `searchTickets()`: Searches and displays tickets for the specified date.
  - `initComponents()`: Initializes all components in the ticket checking form.

## Screenshots
### Main Booking Interface
![VBR Bus Bookings Main Interface](path/to/main_booking_image.png)

### Ticket Checking Interface
![VBR Bus Bookings Check Tickets Interface](path/to/check_tickets_image.png)

## Future Enhancements
- **Database Integration:** Store booking information in a database.
- **User Authentication:** Add login functionality for users.
- **Payment Integration:** Integrate payment gateways for online ticket booking.
- **Enhanced UI:** Improve the user interface with modern design elements.

- **IDE:** NetBeans

---**VBR**
