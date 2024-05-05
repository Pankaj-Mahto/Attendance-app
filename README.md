**Attendanceapp**

This project is build using the html,css,javascript,php and mysql
This application is designed to streamline the process of managing attendance records. With Attendanceapp, you can easily create, update, and manage attendance data.You can also export the attendence in csv form.

### Requirements
Before getting started with Attendanceapp, make sure you have the following prerequisites installed on your system:
- XAMPP: You'll need XAMPP to run a local server environment for hosting the application and the database.
- Visual Studio Code (or any other code editor of your choice): You'll need a code editor to view and modify the source code.

### Installation
Follow these steps to set up Attendanceapp on your local machine:

1. **Clone the Repository**: 
   ```
   git clone https://github.com/yourusername/Attendanceapp.git
   ```

2. **Create Database**:
   - Open XAMPP and start the Apache and MySQL services.
   - Navigate to `http://localhost/phpmyadmin` in your web browser.
   - Create a new database named `att_db`.

3. **Run the SQL Script**:
   - Inside the `Attendanceapp` directory, navigate to `database` folder.
   - Execute the `createtables.php` file to create the necessary tables in the `att_db` database.

4. **Configure Database Connection**:
   - Open `database.php` file located in the `database` directory.
   - Update the database connection settings (hostname, username, password, database name) according to your XAMPP configuration.

5. **Start Using Attendanceapp**:
   - Open the application in your web browser by navigating to `http://localhost/Attendanceapp`.
   - You're now ready to use Attendanceapp to manage attendance records!

### Features
- User-friendly interface for managing attendance records.
- Create and manage multiple events or classes.
- Easily add, update, or delete attendance records.
- View detailed reports and statistics.

### Support
Thank you for choosing Attendanceapp for your attendance management needs! We hope it helps streamline your workflow and makes attendance tracking a breeze.
