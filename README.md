# Hotel Management System

## Overview
The Hotel Management System is designed to address the operational challenges faced by small to mid-sized hotels. It offers a robust, user-friendly software solution for handling bookings, room availability, staff shift management, and inventory. This application provides essential features typically available to larger hotel chains but tailored for independent and smaller hotels seeking to improve their management processes.

Developed with **Java** using **NetBeans IDE** and following the **Entity-Control-Boundary (ECB) design pattern**, this system is cross-platform and scalable for future enhancements.

## Key Features
### User Roles
- **Guests**: View room availability, reserve rooms, and make payments.
- **Staff**: Manage room availability, view and request shift changes, and update inventory.
- **Admin**: Assign shifts, manage room availability, and approve or deny shift change requests.

### Functionalities
1. **Login System**:
   - User-specific interface based on role (Guest, Staff, Admin).
2. **Room Reservations**:
   - Guests can view available rooms and book them based on type and price.
3. **Room Availability Management**:
   - Staff and Admin can toggle room availability for cleaning or other needs.
4. **Shift Management**:
   - Admin assigns shifts and approves staff shift change requests.
   - Staff can view, request changes to, and confirm shift assignments.
5. **Inventory Management** (Staff only):
   - Staff can add, update, and display inventory items and their prices.

## Project Timeline
| Date            | Milestone                                         |
|-----------------|---------------------------------------------------|
| April 27, 2024  | Initial project setup with ECB pattern and core classes (`AdminUI`, `StaffUI`, `GuestUI`, etc.). |
| April 28, 2024  | Added Shift Management features and integrated text file handling for shift data. |
| May 2, 2024     | Completed GUI for Shift Management in Admin and Staff UIs using Java Swing. |
| May 5, 2024     | Added Room Availability Management functionality. |
| May 6, 2024     | Finalized features for Inventory Management and refined error handling. |
| Nov 11, 2024    | Transfering project details to this GitHub. |

## Installation
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/hotel-management-system.git

## Folder Structure
```
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
```

## Testing
The application has undergone rigorous testing, including:

1. Unit Tests:
   - Ensured room reservation, shift assignment, and inventory updates work as intended.
2. Integration Tests:
   - Verified seamless interaction between room management, shift management, and inventory.
3. End-to-End Tests:
 -Simulated complete workflows from booking a room to confirming shifts and updating inventory.

## Contributing
1. Fork the Repository
 - Create a Branch: git checkout -b feature/YourFeature
2. Commit Changes: git commit -m 'Add Your Feature'
 - Push Changes: git push origin feature/YourFeature
3. Submit Pull Request


## License
This project is licensed under the MIT License - see the LICENSE file for details.
This version should be ready for direct copying and pasting into a `README.md` file. Let me know if you need any more customizations!


