**SRM Gym Management System**

**Overview:**

This program implements a simple gym management system using C++. It allows users to join the gym, quit the gym, edit their profiles, and view fitness tips. Additionally, it provides administrative functionalities such as adding, displaying, searching, editing, and deleting member records.

**Files:**

1. **gym_management.cpp:** This file contains the source code for the gym management system.

2. **README.md:** This file provides instructions and information about the gym management system.

**How to Run:**

To run the gym management system:

1. Compile the source code using a C++ compiler. For example, you can use g++:

   ```
   g++ -o gym_management gym_management.cpp
   ```

2. Execute the compiled program:

   ```
   ./gym_management
   ```

3. Follow the on-screen instructions to navigate through the user or admin mode and perform desired actions.

**Features:**

1. **User Mode:**
   - Join the gym: Users can join the gym by providing necessary details such as member number, name, contact, preferred class (gold or silver), and preferred timings.
   - Quit the gym: Users can quit the gym by deleting their member record.
   - Edit profile: Users can edit their profile details, including contact information, class type, and preferred timings.

2. **Admin Mode:**
   - Administrative login: Admins can log in using predefined admin codes.
   - Manage members: Admins can perform various operations related to member management, including creating new member records, displaying all records, searching for specific records, editing member details, and deleting member records.

**Functionality:**

- **Save Member:** Adds a new member to the system by creating a member record and saving it to a file.
- **Show All:** Displays all existing member records stored in the file.
- **Search Record:** Searches for a specific member record based on the member number.
- **Edit Member:** Allows admins to modify the details of an existing member record.
- **Delete Member:** Enables admins to remove a member record from the system.
- **Fitness Tips:** Provides users with fitness tips from a text file.

**Note:**

- Ensure that you have a C++ compiler installed on your system to compile and run the program.
- Users can navigate through different options in both user and admin modes using the provided menu.
- Admins need to log in with valid credentials to access administrative functionalities.
- The program stores member records in a file named "newdata2.dat" and reads from it for various operations.

**Enjoy Managing Your Gym!**
