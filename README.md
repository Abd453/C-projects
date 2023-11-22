# C++-projects
Hotel Management System using file concept. 
**Hotel Management System Readme**

# Introduction
This is a console-based Hotel Management System implemented in C++. The system is designed to manage reservations, room details, and services for a hotel. It allows users to reserve rooms, view room details, remove guests, and provides information about the system and its developers.

# Features
1. **User Authentication:**
   - The system begins with a login page to ensure user authentication.
   - Default login credentials are provided (username: abcd1@gmail.com, password: 123456).

2. **Room Reservation:**
   - Users can reserve a room by entering the room number.
   - The system checks if the room is available and takes customer information, food, drink, and service orders.

3. **View Room Details:**
   - Users can view detailed information about a specific room, including occupancy status, customer name, ordered food, drinks, and services.

4. **Remove Guest:**
   - Guests can be removed from a room, making it available for new reservations.

5. **File I/O:**
   - Room information is saved to a file (`hotel_data.txt`) to persist data between program runs.
   - Information is loaded from the file at the beginning to maintain the state of the rooms.

6. **Menu and Navigation:**
   - Users are presented with a menu to choose from different functionalities.
   - The system provides an option to clear the screen after each operation.

# How to Use
1. **Compilation:**
   - Compile the code using a C++ compiler (e.g., g++).

2. **Execution:**
   - Run the compiled executable.

3. **Login:**
   - Enter the provided default login credentials or use your own.

4. **Menu Options:**
   - Choose options from the menu (reserve room, view room details, remove guest, about system, developed by, exit).

5. **Room Reservation:**
   - Follow the prompts to reserve a room and provide necessary details.

6. **View Room Details:**
   - Enter the room number to view detailed information.

7. **Remove Guest:**
   - Enter the room number to remove a guest.

8. **About System:**
   - Get information about the hotel management system.

9. **Developed By:**
   - View details about the developers of the system.

10. **Exit:**
    - Save room information to the file and exit the system.

# Developers
- **Abdallah Abdurazak**
  - ID: 000000000000
  - Section: 4
  - Group: 7

- **Abel Bekele**
  - ID: 000000000000
  - Section: 4
  - Group: 7

# Note
- The system has a total of 400 rooms initially added to the list.
- Room information is saved to and loaded from the `hotel_data.txt` file.

Feel free to explore the functionalities of the Hotel Management System and enjoy managing the hotel's operations!
