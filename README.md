Product Inventory Management System

*Abstract
In the fast-paced world of retail and business management, maintaining an efficient and organized inventory is crucial. The Product Inventory Management System is a Single Page Application (SPA) developed using Angular for the front-end and a JSON server for the back-end. This system empowers businesses by streamlining inventory tracking, product categorization, and stock management.

The solution enables users to perform essential CRUD (Create, Read, Update, Delete) operations, ensuring seamless product handling. Additionally, administrators can securely log in, manage inventory, and monitor stock levels in real-time, making it an effective tool for modern businesses.


*Problem Statement
Businesses often struggle with manual inventory tracking, leading to inefficiencies and errors. This application aims to address these challenges by providing a digital platform that simplifies inventory management. It allows users to:

-Add, update, delete, and list products
-Organize products by categories
-Update stock quantities
-Manage product details such as descriptions, prices, and manufacturers
-Enable secure administrator login for controlled access

With this system, businesses can enhance operational efficiency, reduce manual errors, and optimize inventory handling.


*System Features & Functionalities
1. User Authentication
Users can register and log in securely.
Only logged-in users can manage inventory operations.
Authentication is handled via stored credentials in the JSON server (db.json file).
2. Product Management
View Products: Displays a list of all available products.
Add Products: Users can add new products by entering necessary details.
Edit Products: Allows modification of product attributes like name, price, and stock.
Delete Products: Users can remove unwanted products from the inventory.
Search Products: A search bar is available to filter products based on keywords.
3. User Roles
Admin: Has full control over inventory, including product management.
Registered Users: Can view and interact with products but require authentication for modifications.
4. Navigation & UI
The application includes a Welcome Page with key navigation links:
Products Page: Displays all listed products.
About Page: Provides details about the system.
Sign In & Register: Allows user authentication.
Logout: Ends the user session and redirects to the welcome page.
The UI is responsive and includes proper form validations to ensure data integrity.
5. Business Logic & Constraints
All required fields must be completed with valid data.
The system enforces tab-based navigation for ease of access.
Proper error handling and validation messages for incorrect inputs.
Users cannot access product management features unless authenticated.


*Technical Overview
-Front-End: Angular for building a dynamic and user-friendly interface.
-Back-End: JSON Server acting as a lightweight REST API to store product data.
-Routing: Angular’s built-in RouterModule for seamless navigation.
-Data Storage: Products and user credentials are stored in db.json for easy retrieval.
-Validation & Error Handling: Implemented at both form and API levels to ensure smooth operation.


*Conclusion
The Product Inventory Management System provides a structured and efficient way to handle product listings, stock updates, and inventory tracking. Its user-friendly interface and seamless CRUD operations make it a valuable tool for businesses looking to digitize their inventory management processes.