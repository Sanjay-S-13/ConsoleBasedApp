# Taxi Booking System

This is a console-based application for a taxi booking system, a common problem often asked in technical interviews.

## About the Project

This project simulates a taxi booking service where customers can book taxis and view the details of all bookings and taxi earnings. It's a classic example of an object-oriented programming (OOP) problem that tests a candidate's ability to model real-world entities like `Taxi` and `Booking` and manage their interactions.

A similar problem is frequently asked in interviews, including those at **Zoho**, especially in their **third technical round**, to assess problem-solving skills and code organization.

## Features

-   **Book a Taxi**: Customers can book a taxi by providing a pickup point, drop point, and pickup time.
-   **Taxi Allocation**: The system allocates the most suitable available taxi based on specific criteria:
    -   Availability at the requested time.
    -   Shortest distance from the customer's pickup point.
    -   If distances are equal, the taxi with the lowest total earnings is chosen to ensure fair distribution of trips.
-   **Calculate Fare**: The fare is calculated based on the distance traveled.
-   **Display Details**: Users can view a detailed breakdown of each taxi's bookings and total earnings.

## Structure

The project is structured into three main classes:

-   `Taxi.java`: Represents a single taxi with properties like ID, current location, total earnings, and a list of bookings.
-   `Booking.java`: Represents a single booking transaction, storing details like customer ID, pickup/drop points, times, and fare.
-   `TaxiBookingSystem.java`: The main class that handles the user interface, manages taxi allocation logic, and displays results.

## How to Run

1.  **Navigate** to the `TaxiBookingApp` directory.
2.  **Compile** the Java files: `javac *.java`
3.  **Run** the application: `java TaxiBookingSystem`
