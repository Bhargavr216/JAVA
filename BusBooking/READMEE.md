
# VBR Bakery Management

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
The VBR Bakery Management system is a Java Swing application designed to manage a bakery shop. It allows users to select bakery items through clickable images, input quantities, view the list of selected items along with their quantities and total price, and save the bill as a PDF.

## Features
- **Clickable Item Images:** Images of bakery items that users can click to add to their order.
- **Quantity Input:** Prompt for users to input the quantity of the selected item.
- **Order Summary:** Displays a list of items added, their quantities, and the total price.
- **Print Button:** Saves the bill as a PDF when clicked.

## Installation
1. **Prerequisites:**
   - Java Development Kit (JDK) installed.
   - NetBeans IDE installed.
   - iText library for PDF generation.

2. **Setup:**
   - Clone or download the project repository.
   - Open the project in NetBeans IDE.
   - Ensure all necessary libraries (e.g., iText) are included.

## Usage
1. **Running the Application:**
   - Open the project in NetBeans IDE.
   - Click on the 'Run' button or press `Shift + F6`.

2. **Adding Items to the Order:**
   - Click on the image of the bakery item you wish to add.
   - Input the quantity of the selected item.
   - The item and its quantity will be added to the order summary.

3. **Viewing the Order Summary:**
   - The order summary section displays the list of items added, their quantities, and the total price.

4. **Saving the Bill as PDF:**
   - Click the 'Print' button to save the bill as a PDF file.

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

4. **iText Library:**
   - Used for generating PDF documents.
   - Provides tools for creating and manipulating PDF files in Java.

## Classes and Methods
### Main Class: `VBRBakeryManagement`
- **Methods:**
  - `main(String[] args)`: Entry point of the application.
  - `initComponents()`: Initializes all components in the form.
  - `addItemToOrder(String itemName, int quantity)`: Adds the specified item and quantity to the order.
  - `updateOrderSummary()`: Updates the order summary with the current items and total price.
  - `saveBillAsPDF()`: Generates and saves the bill as a PDF file.

## Screenshots
### Main Interface
![VBR Bakery Management Main Interface]![image](https://github.com/user-attachments/assets/3a913fad-8903-495c-96ac-1d9b51772cf7)


## Future Enhancements
- **Database Integration:** Store order information in a database.
- **User Authentication:** Add login functionality for users.
- **Payment Integration:** Integrate payment gateways for online orders.
- **Enhanced UI:** Improve the user interface with modern design elements.

- **IDE:** NetBeans

--- **VBR**
