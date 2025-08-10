
Personal Contact Management System (CMS)
A Contact Management System (CMS) is a Python-based application that allows users to manage their contacts. The system is built using core Python data structures such as lists, dictionaries, and sets to efficiently store, retrieve, and manipulate contact information.

Features
The CMS provides the following functionalities:

Add a New Contact: Users can add new contacts with their name, phone number, and email address. The system prevents the addition of duplicate contacts by checking if the phone number already exists.

View All Contacts: This feature allows users to see a list of all saved contacts.

Search a Contact: Users can search for a contact using either their name or phone number.

Update Contact Details: Existing contact information (name, phone, and email) can be updated. The system validates that a new phone number is not already in use by another contact.

Delete a Contact: Users can remove a contact from the system by providing their phone number.

Prevent Duplicate Contacts: The system utilizes a set to store phone numbers, which ensures that no two contacts can have the same phone number.

Key Concepts Used
The project demonstrates the use of several key Python concepts:

Classes and Objects: The system is structured using a Contact class and a ContactManagementSystem class to encapsulate data and functionality.
Lists: A list is used for dynamic storage of Contact objects.
Dictionaries: Dictionaries are used to structure the data for each individual contact.
Sets: A set, specifically phone_index, is used to maintain a collection of unique phone numbers to prevent duplicates.
Menu-driven program: The system provides a user-friendly, menu-driven interface for easy interaction.
String Manipulation and Input Validation: The code includes logic for handling user input and performing searches that are not case-sensitive.
