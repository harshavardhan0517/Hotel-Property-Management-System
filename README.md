# Hotel-Property-Management-System
A full-stack Hotel Property Management System built with PHP, MySQL, and CSS. Supports user and admin roles for managing room bookings, staff data, and invoices. Includes role-based access, dynamic room updates, and automated billing through a responsive web interface.

To set up and run the Hotel Property Management System locally, follow these instructions:

1. Install XAMPP:

    Download and install XAMPP from the official website: https://www.apachefriends.org/
    
    Install it in the default directory, which is typically C:\xampp on Windows.

2. Clone or Copy the Project:

    After downloading or cloning your project, copy the entire project folder (e.g., Hotel-Management-System) into the htdocs directory within your XAMPP installation.
    
    The typical path would be: C:\xampp\htdocs\Hotel-Management-System\

3. Start XAMPP Services:

      Open the XAMPP Control Panel.
      
      Start both the Apache and MySQL services. You should see their status indicators turn green.

4. Set Up the Database:

      Open your web browser (e.g., Chrome, Firefox).
      
      Go to phpMyAdmin by typing the following URL: http://localhost/phpmyadmin/
      
      In phpMyAdmin, click on "New" in the left sidebar to create a new database.
      
      Name the new database hotelfinal.
      
      Once the database hotelfinal is created, select it from the left sidebar.
      
      Click on the "Import" tab in the top navigation bar.
      
      Click on "Choose File" and locate the hotelfinal.sql file within your project directory (C:\xampp\htdocs\Hotel-Management-System\hotelfinal.sql).
      
      Click the "Go" button at the bottom of the import page to import the database structure and sample data.

5. Run the Application:

      With the Apache and MySQL services running and the database set up, open your web browser again.
      
      Navigate to the following URL to launch the application: http://localhost/Hotel-Management-System/
