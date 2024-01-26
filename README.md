# Hotel Management System

This is a simple hotel management system implemented in Python using file handling for data storage and MySQL database for storing persistent data. The system allows users to perform various tasks related to managing hotel operations such as booking rooms, checking availability, adding customers, etc.

## Features

- **Room Booking**: Users can book available rooms for specified dates.
- **Check Availability**: Users can check the availability of rooms for specific dates.
- **Customer Management**: Add, view, and manage customer details.
- **Billing**: Generate bills for customers based on their bookings.
- **Admin Panel**: Access control for administrators to manage rooms, customers, and bookings.

## Prerequisites

- Python 3.x
- MySQL Server
- `mysql-connector-python` library (install using `pip install mysql-connector-python`)

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/hotel-management-system.git
   ```

2. Navigate to the project directory:

   ```bash
   cd hotel-management-system
   ```

3. Create a virtual environment (optional but recommended):

   ```bash
   python3 -m venv env
   source env/bin/activate   # For Unix/Linux
   ```

4. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

5. Set up the MySQL database:
   
   - Create a MySQL database named `hotel_management`.
   - Execute the SQL script `database.sql` to create the necessary tables.

6. Update database credentials:
   
   - Open `config.py` and update the MySQL database connection details.

7. Run the application:

   ```bash
   python main.py
   ```

## Usage

- Follow the on-screen instructions to navigate through the application.
- Use the admin credentials to access the admin panel.

## Contributors

- [Rohit kumar](https://github.com/RohitKumar-tech)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Feel free to customize this README according to your project's specifics, adding more details or sections as needed. This README serves as a starting point to help users understand your project and how to set it up and use it.
