# Hostel Management System

This project is a simple command-line interface for managing hostel records using a MySQL database. It allows users to perform various operations such as admission, status checking, updating details, and more.

## Features

- **Admission Form**: Add new hostel records.
- **Status Checking**: Check records based on the department.
- **Update Details**: Update existing records.
- **Authorities Access**: Placeholder for authority access.
- **Exit**: End the program.

## Getting Started

To use this system, ensure you have MySQL installed and configured. Follow these steps:

### Prerequisites

- Python 3.x
- MySQL Server
- `mysql-connector-python` library

### Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/er-anubhavgoel/Hostel-Management.git
    cd Hostel-Management
    ```

2. **Install dependencies:**

    Install the required Python package using pip:

    ```bash
    pip install mysql-connector-python
    ```

3. **Setup MySQL Database:**

    - Create a database named `HOSTEL_MANAGEMENT`.
    - Create a table named `HOSTEL` with the following schema:

      ```sql
      CREATE TABLE HOSTEL (
          rgn_no INT PRIMARY KEY,
          name VARCHAR(20),
          address VARCHAR(100),
          room_no INT,
          dept VARCHAR(15),
          fees INT,
          bal INT
      );
      ```

### Usage

1. **Run the application:**

    ```bash
    python your_script_name.py
    ```

2. **Follow the on-screen prompts** to perform operations like adding records, checking statuses, and updating details.

### Example

Here's how the main menu looks:

```
WELCOME TO HOSTEL MANAGEMENT

MAKE YOUR PREFERENCE:
1. ADMISSION FORM
2. STATUS CHECKING
3. UPDATE DETAILS
4. AUTHORITIES
5. EXIT
```

### Code Overview

- **Database Connection**: Connects to the MySQL database.
- **AdmnForm()**: Handles new admissions.
- **StatusCheck()**: Checks records based on department.
- **UpdateDetails()**: Updates existing records.

### Contributing

Feel free to open issues or submit pull requests. Your contributions are welcome!

Anubhav Goel  
Email: anubhavgoel0520@hotmail.com  
LinkedIn: [Anubhav Goel](https://linkedin.com/in/er-anubhavgoel)  
GitHub: [er-anubhavgoel](https://github.com/er-anubhavgoel)  

GitHub Repository: [Hostel-Management](https://github.com/er-anubhavgoel/Hostel-Management)
