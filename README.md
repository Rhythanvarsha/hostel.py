# Hostel Management System

This project is a **Hostel Management System** built using Python and the Tkinter library. It provides a graphical user interface (GUI) for managing hostel-related operations such as adding students, managing rooms, tracking in/out times, handling visitor information, and processing leave applications.

## Features

- **Add Student**: Add new students with details like name, contact, address, and more.
- **Add Room**: Add new rooms for boys, girls, or others.
- **In/Out Time Management**: Track the in/out times of students with purpose and remarks.
- **Visitor Management**: Record visitor details and associate them with students.
- **View Information**: View all student information or filter by room.
- **Leave Applications**: Submit and manage leave applications for students.

## File Structure

- **`hostel.py`**: The main Python script containing the GUI and logic for the Hostel Management System.
- **Data Files**:
  - `inouttime.txt`: Stores in/out time records.
  - `leave_applications.txt`: Stores leave application details.
  - `room_info_boys.txt`: Stores room information for boys.
  - `room_info_girls.txt`: Stores room information for girls.
  - `room_info_others.txt`: Stores room information for others.
  - `student_info.txt`: Stores student details.
  - `visitor_info.txt`: Stores visitor information.

## Prerequisites

- Python 3.x
- Tkinter (comes pre-installed with Python)

## How to Run

1. Clone or download the project to your local machine.
2. Ensure all required data files (`.txt` files) are in the same directory as `hostel.py`.
3. Run the `hostel.py` script:
   ```bash
   python hostel.py
