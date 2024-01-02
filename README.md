**Library Management System:**
Welcome to the Library Management System project! This system is designed to efficiently manage library operations with a robust and secure architecture. Below are the key components and technologies used in this project.

**Technologies Used:**
Frontend: Angular 17
Backend: .NetCore Web API
Database: MySQL Server

**Backend Architecture:**
The backend utilizes a secure API approach, ensuring that users are shielded from the underlying queries and backend code. MySQL Server has been chosen for its traditional reliability and efficient database management, especially in cases where cloud services are not available.

**Authentication and Authorization:**
JWT (JSON Web Token) has been implemented for secure login and user authorization. The system has an admin user who has the authority to approve new user registrations. The admin can also add and delete books, as well as introduce new book categories.

**User Functionalities:**
Admin User
-Approve new user registrations
-Add and delete books
-Manage book categories
-Accept returned books and view fines

Regular Users
-Order books
-View total returns and pending returns

Return books within 10 days to avoid fines
Accumulate fines for overdue books

**Usage:**
Admin Panel
-Log in as the admin user.
-Approve new user registrations.
-Manage the library inventory by adding, deleting books, and creating new book categories.
-Accept returned books and check fines associated.

Regular User
-Log in as a regular user.
-Order books from the available inventory.
-Keep track of total returns and pending returns.
-Ensure books are returned within 10 days to avoid fines.

Note:
For secure and efficient library management, it is recommended to adhere to the defined roles and functionalities for both admin and regular users. Explore the comprehensive features offered by this Library Management System to streamline your library operations.
