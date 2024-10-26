Contact Managment System

A simple python program that allows the user to manage contacts.

Upon running the file, a welcome screen will be displayed with the following options:
1. Add contact
2. Edit contact
3. Delete contact
4. Search contacts
5. Display contacts
6. Export contacts to text file
7. Import contacts from file
8. Quit

1. Add contact will ask the user for input for the following fields: "name", "phone", "email", and "city" .
 Regex is used to validate user inputs for the phone and email fields. As of now, the phone number format is just 10 digits, without dashes or spaces, but I plan to expand that.

2. Edit contact asks the user for the field they would like to update, based on a "idenitifier_phone" variable which is the phone number provided by the user input.
The individual fields can then be accessed and updated.

3. Delete contact simply erases the contact from the dictionary.

4. Search contacts will look up a user by the phone number, and display the information for that contact.

5. Display contacts will print out the entire dictionary of contacts.

6. Export contacts sends the contacts dictionary to a text file.

7. Import contacts brings in contacts from a text file.

8. Quit to exit the program.



9. 
10. 
11. 
