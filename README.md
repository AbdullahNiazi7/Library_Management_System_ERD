# Library_Management_System_ERD

This repository contains an Entity Relationship Diagram (ERD) for a team management and library system. The diagram illustrates the core entities, their attributes, and the relationships between them, providing a clear overview of the data structure.

Overview
The ERD is designed to model a system that manages books, users, staff, reservations, and related operations. It is suitable for a library or team management application, supporting features such as book borrowing, user management, staff roles, and event organization.

Key Entities
Book: ISBN, Title, Author Name, Price, Publisher, Year of Publication

User: User ID, First Name, Middle Name, Last Name, Email, Phone Number

Staff: Staff ID, Name, Manages, Reports

Publisher: Publisher ID, Name

Reservation: Reserve Date, Return Date

Login System: Login ID, Password

Additional Entities (Optional)
Library Branch: Branch ID, Name, Address, Phone, Manager ID

Book Copy: Copy ID, ISBN, Branch ID, Status, Purchase Date

Fine: Fine ID, User ID, Copy ID, Amount, Issue Date, Paid Date

Department: Department ID, Name, Head Staff ID, Location

Event: Event ID, Title, Description, Date, Location, Organizer Staff ID

Relationships
One-to-Many (1:N): A user can have many reservations; a book can have many copies.

Many-to-Many (N:M): Events can have many attendees; users can attend many events.

One-to-One (1:1): A staff member can manage one branch; a book copy can have one reservation.

How to Use
The ERD is provided in PDF format for easy viewing.

You can use this diagram as a reference for database design or as a starting point for developing a library or team management system.

Contributing
Feel free to suggest improvements, add new entities, or clarify relationships. Pull requests and issues are welcome!

