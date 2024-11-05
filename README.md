Hotel Management System
Overview
The Hotel Management System is designed to address the operational challenges faced by small to mid-sized hotels. It offers a robust, user-friendly software solution for handling bookings, room availability, staff shift management, and inventory. This application provides essential features typically available to larger hotel chains but tailored for independent and smaller hotels seeking to improve their management processes.

Developed with Java using NetBeans IDE and following the Entity-Control-Boundary (ECB) design pattern, this system is cross-platform and scalable for future enhancements.

Key Features
User Roles
Guests: View room availability, reserve rooms, and make payments.
Staff: Manage room availability, view and request shift changes, and update inventory.
Admin: Assign shifts, manage room availability, and approve or deny shift change requests.
Functionalities
Login System:
User-specific interface based on role (Guest, Staff, Admin).
Room Reservations:
Guests can view available rooms and book them based on type and price.
Room Availability Management:
Staff and Admin can toggle room availability for cleaning or other needs.
Shift Management:
Admin assigns shifts and approves staff shift change requests.
Staff can view, request changes to, and confirm shift assignments.
Inventory Management (Staff only):
Staff can add, update, and display inventory items and their prices.

Project Timeline
Date	Milestone
April 27, 2024	Initial project setup with ECB pattern and core classes (AdminUI, StaffUI, GuestUI, etc.).
April 28, 2024	Added Shift Management features and integrated text file handling for shift data.
May 2, 2024	Completed GUI for Shift Management in Admin and Staff UIs using Java Swing.
May 5, 2024	Added Room Availability Management functionality.
May 6, 2024	Finalized features for Inventory Management and refined error handling.

Installation
Clone the Repository:
bash
Copy code
git clone https://github.com/yourusername/hotel-management-system.git
Open in NetBeans:
Open NetBeans and navigate to File > Open Project.
Select the cloned folder and open the project.
Run the Project:
Click the green play button in NetBeans or run the main class HotelManagement.


Usage
Login: Launch the application to access the LoginGUI. Enter your credentials to proceed to your respective role interface.
Guests: Use the GuestUI to view room options, reserve a room, and proceed to payment.
Staff: Manage room availability, check shift assignments, request changes, and update inventory.
Admin: View and assign shifts, manage room availability, and respond to shift change requests.
Folder Structure
perl
Copy code
hotel-management-system/
├── src/                           # Source code
│   ├── AdminUI.java               # Admin interface
│   ├── StaffUI.java               # Staff interface for room and shift management
│   ├── GuestUI.java               # Guest interface for room reservations
│   ├── Shift.java                 # Handles shift assignments and requests
│   ├── Inventory.java             # Manages inventory functionality
│   └── RoomAvailability.java      # Room availability management
├── shift_assignments.txt          # Stores shift details
├── Availability.txt               # Room availability data
├── README.md                      # Project README
└── LICENSE                        # License information


Testing
The application has undergone rigorous testing, including:
Unit Tests:
Ensured room reservation, shift assignment, and inventory updates work as intended.
Integration Tests:
Verified seamless interaction between room management, shift management, and inventory.
End-to-End Tests:
Simulated complete workflows from booking a room to confirming shifts and updating inventory.
Contributing
Fork the Repository
Create a Branch: git checkout -b feature/YourFeature
Commit Changes: git commit -m 'Add Your Feature'
Push Changes: git push origin feature/YourFeature
Submit Pull Request

License
This project is licensed under the MIT License - see the LICENSE file for details.

