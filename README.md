# Library Management System
A simple flask app to manage users along with mysql service

![Libray Management App - Flask](https://github.com/varuni7/BookFlow)

 

# User Management Flask App with MySQL Service

 
This is a simple Flask web application designed for user management, utilizing a MySQL database as its backend storage. The application allows you to perform basic user management tasks such as creating, reading, updating, and deleting user records. It serves as a foundation for understanding how to integrate Flask with a MySQL database for managing user data.

## Features

- User Registration: Register new users with their basic information.
- User Login: Allow registered users to log in securely.
- User Profile: Display user details and profile information.
- User Update: Enable users to update their profile information.
- User Deletion: Admins can delete user records if needed.
- Data Persistence: User data is stored in a MySQL database for durability.

## Installation

1. Clone the repository:

   ```bash
   git clone git@github.com:varuni7/BookFlow.git
   ```

2. Navigate to the project directory:

   ```bash
   cd user-management-flask-mysql
   ```

3. Create a virtual environment (optional but recommended):

   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```

4. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

5. Configure MySQL Database:

   - Create a MySQL database named `user_management_db`.
   - Update the `config.py` file with your MySQL credentials.

6. Run the application:

   ```bash
   python app.py
   ```

7. Open your web browser and go to `http://localhost:5000` to access the application.

## Usage

1. Register as a new user with your details.
2. Log in with your registered credentials.
3. Update your profile information if needed.
4. Administrators can manage user records and delete users if necessary.

## Contributing

Contributions are welcome! Feel free to submit issues or pull requests for improvements, bug fixes, or new features.

 
 
