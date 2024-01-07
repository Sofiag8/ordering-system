# Pharmacy Drug Ordering System

This project involves the development of a simple Java application to simulate a drug ordering system from a pharmacy to a distributor. The primary goals of this project are to learn how to create a Java project, design a graphical interface using the Swing library, and handle debugging errors.

## Features

- **Name of the Medication:** Enter the medication name in an editable text box (`JTextField`).
- **Type of Medication:** Choose the type of medication from a drop-down menu (`JComboBox`).
- **Amount of Product:** Specify the quantity of the product in an editable text box (`JTextField`).
- **Pharmaceutical Distributor:** Select a distributor from three options: Cofarma, Empsephar, and Cemefar, using radio buttons (`JRadioButton`).
- **Pharmacy Branch:** Choose the pharmacy branch (Main and/or Secondary) using checkboxes (`JCheckBox`).
- **Buttons:**
  - **Delete:** Clears all the data from the form (`JButton`).
  - **Confirm:** Validates the entered data and opens a new window with the order summary if everything is correct (`JButton`).

## Data Validation

Before confirming the order, the application verifies the correctness of the entered data:

- Ensure the drug name contains alphanumeric characters.
- Check that a type of medication has been chosen.
- Validate that the quantity of the product is a positive integer.
- Verify that a distributor has been selected.
- Confirm that the pharmacy branch (Main and/or Secondary) has been chosen.

If any data is incorrect, the user will be notified of the error.

## Order Summary Window

Upon successful validation, a new window will appear with the order summary:

- **Window Title:** "Order to distributor D" (D is the selected distributor).
- **Medication Information:** Display the ordered medication as "X units of T M" (X is the number of units, T is the type of medication, and M is the name of the medication).
- **Pharmacy Address:** Display the pharmacy address as "For the pharmacy located in D" (D is the distributor's address).

## Order Shipment Simulation

The order summary window contains two buttons:

- **Cancel Order:** Closes the window.
- **Submit Order:** Simulates order shipment with a message on the screen ("Order sent") using `System.out.println`.

## NetBeans Project

The repository contains a complete NetBeans project with the implemented Java code. The project includes its own `main` method to test the system's operation.

Feel free to explore the code, run the project, and make improvements as needed. Happy coding!
