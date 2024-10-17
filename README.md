# Real-Estate Property Management System

![Homepage Screenshot](Images/2024-10-17(5).png)

## Overview

The **Real-Estate Property Management System** is a web application designed to simplify and automate the process of managing rental properties. It provides functionality for property listings, tenant management, rental payments, and maintenance requests. This system helps landlords, property managers, and real estate professionals efficiently handle their properties and tenants.

## Features

- **Property Listings**: Add, view, and manage property details, including images, descriptions, rental prices, and availability.
- **Tenant Management**: Track tenant information, leases, and rental agreements.
- **Rental Payments**: Manage rental payments, track overdue payments, and generate payment receipts.
- **Maintenance Requests**: Tenants can submit maintenance requests which can be tracked and resolved by property managers.
- **User Roles**: Admin, Property Agent, Customer, and Saller with different levels of access and functionality.
- **Notifications**: Automated email notifications for rent due, maintenance request updates, and lease expirations.
- **Reporting**: Generate reports for rental income, occupancy, and maintenance costs.

## Technologies Used

- **Backend**: ASP.NET Core MVC
- **Frontend**: Razor Pages, HTML5, CSS3, Bootstrap
- **Database**: Microsoft SQL Server, Entity Framework Core for ORM
- **Authentication**: ASP.NET Identity for user authentication and role management
- **IDE**: Visual Studio

## Installation

### Prerequisites

- .NET 8.0 SDK
- Microsoft SQL Server
- Visual Studio 2022 (or newer)

### Steps to Install

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/Real-Estate-Property-Management-System.git
    ```

2. **Navigate to the project directory**:
    ```bash
    cd Real-Estate-Property-Management-System
    ```

3. **Set up the database**:
    - Open the project in Visual Studio.
    - Update the `appsettings.json` file with your database connection string.
    - Run the following command to apply migrations:
      ```bash
      Update-Database
      ```

4. **Run the project**:
    - In Visual Studio, click on the “Run” button or press `F5` to start the application.


## Usage

1. **Admin**: Admin users can add sellers, manage properties, and access all system reports.
2. **Sellers**: Sellers can add and manage their own properties, track inquiries, and handle property listings.
3. **Customers**: Customers can view property details, submit inquiries, and schedule property visits.



