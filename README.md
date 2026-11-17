Vehicle & Fleet Management System

Version: 2.1
Language: Python
Storage: CSV files
Platform: Python-compatible environments, including Pydroid 3

Project Overview

The Vehicle & Fleet Management System is a Python-based application designed to help manage vehicle records, driver information, trip activities, fuel usage and fleet maintenance alerts.

It uses CSV files to store records, allowing information to remain available after the application closes.

Main Features

- Fleet dashboard with vehicle, driver and trip summaries
- Vehicle registration and record management
- Driver registration and record management
- Trip recording and trip history
- Editing and deletion of trip records
- Vehicle service alerts
- Driver licence compliance alerts
- Monthly fuel and trip reports
- CSV data backup
- CSV backup discovery and restoration interface

Data Storage

The system uses three main CSV files:

File| Purpose
"vehicles.csv"| Vehicle records
"drivers.csv"| Driver records
"trips.csv"| Trip and fuel records

Backups are stored in the "fleet_backups" directory.

Running the Application

1. Install Python or use a compatible Python environment such as Pydroid 3.
2. Open the project Python file.
3. Run the application.
4. Select an operation from the main menu.
5. Follow the prompts to manage fleet records.

Testing Status

The following operations have been tested successfully using runtime outputs:

- Application initialization
- Dashboard
- Vehicle and driver registration and viewing
- Trip recording and viewing
- Vehicle, driver and trip editing
- Trip deletion
- Service and licence alerts
- Monthly reports
- CSV backup creation
- Backup listing and cancellation
- Data persistence after restarting the application

Actual backup restoration, vehicle deletion and driver deletion have not yet been fully tested.

Project Objective

This project demonstrates practical Python programming concepts, including:

- Functions
- Lists and dictionaries
- File handling
- CSV data processing
- Input validation
- Record management
- Data verification
- Error handling

Future Development

Possible future improvements include:

- More comprehensive automated testing
- Improved reporting
- A graphical user interface
- More advanced fleet performance analysis

Author

Stanly Philip

A practical Python project focused on fleet administration, record keeping and inventory-style data management.
