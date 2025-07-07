# std-mgmt_gui-system-mysql

A Python-based Student Management System with a graphical user interface (GUI) and MySQL database integration.

## References
Python Mega Course Guided Coding

## Features

- Add, update, delete, and view student records
- User-friendly GUI built with Python (PyQt)
- Persistent data storage using MySQL
- Search and filter student information
- Error handling and input validation

## Requirements

- Python 3.x
- MySQL Server
- Python packages:
    - `mysql-connector-python`
    - GUI library (PyQt5)

## Setup

1. **Clone the repository:**
     ```bash
     git clone https://github.com/yourusername/std-mgmt_gui-system-mysql.git
     cd std-mgmt_gui-system-mysql
     ```

2. **Install dependencies:**
     ```bash
     pip install mysql-connector-python
     # If using PyQt6:
     pip install PyQt6
     # If using Tkinter, it is included with most Python installations.
     ```

3. **Configure MySQL:**
     - Create a database and user for the application.
     - Update the database connection settings in the source code as needed.

4. **Run the application:**
     ```bash
     python main.py
     ```

## Usage

- Launch the application.
- Use the GUI to manage student records.
- All changes are saved to the MySQL database.

## License

This project is licensed under the MIT License.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## Contact

For questions or support, please open an issue on the repository.