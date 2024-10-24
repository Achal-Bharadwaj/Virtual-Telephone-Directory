Virtual Telephone Directory

**Description:**

The Virtual Telephone Directory is a simple Python application built using the Tkinter library for creating a graphical user interface (GUI) and SQLite for database management. This application allows users to manage contacts by adding, updating, and deleting them from a database.

**Features:**

1.Add New Contact: Users can add new contacts by providing their first name, last name, gender, age, address, and contact number.
2.Update Contact: Existing contacts can be updated by selecting them from the displayed list. Users can modify the contact details and save the changes.
3.Delete Contact: Users can delete existing contacts by selecting them from the list and confirming the deletion.
4.View Contacts: The application displays a list of contacts stored in the database, including their member ID, first name, last name, gender, age, address, and contact number.

**File Structure:**

1.contact_list.py: This file contains the main Python script for the application.

2.pythontut.db: This SQLite database file stores contact information.

**Requirements:**

Python 3.x
Tkinter library (usually included in Python standard library)
SQLite database

**Setup:**

1.Ensure you have Python installed on your system.
2.Install Tkinter library if not already installed. You can do this using pip:
3.Copy code
4.pip install tk
5.No additional setup is required for the SQLite database as it's managed within the application.

**Usage:**

1.Run the contact_list.py script.
2.The application window will open, displaying the list of contacts if any exist in the database.
3.Use the buttons provided to add new contacts, update existing contacts, or delete contacts.
4.Double-click on a contact in the list to update its details.
5.Fill in the required information in the entry fields and click the "Save" or "Update" button to apply changes.
6.Confirm deletion by clicking the "DELETE" button after selecting a contact from the list.

**Contributors:**

Developed by Achal S Bharadwaj.

Notes:

1.Ensure that the pythontut.db file is in the same directory as the contact_list.py script for proper database access.
2.This application is a simple example and may be extended with additional features such as search functionality, sorting, and more robust error handling as needed.





