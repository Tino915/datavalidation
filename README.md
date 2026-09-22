# Java Swing Registration System

## 1. Project Title

**Java Swing Registration System**

---

## 2. Project Overview

The Java Swing Registration System is a desktop application developed using **Java Swing**. The system allows a user to enter personal information into a registration form and checks whether the information entered is correct.

The application uses different validation methods to make sure that the user enters information in the correct format. It also displays the entered information in the **DATA** section after successful registration.

The system was developed as a school programming project to demonstrate the use of Java, Java Swing components, event handling, input validation, and graphical user interfaces.

---

## 3. Purpose of the Project

The main purpose of this project is to create a simple and user-friendly registration system.

The system is designed to:

* Collect user information.
* Validate information entered by the user.
* Display error messages when incorrect information is entered.
* Display successfully entered information.
* Allow the user to clear the form.
* Allow the user to exit the application.
* Provide help to the user.
* Demonstrate Java Swing programming.

---

## 4. Technologies Used

The following technologies were used to develop the system:

* **Java**
* **Java Swing**
* **NetBeans IDE**
* **JOptionPane**
* **Event Handling**
* **GUI Components**

Java Swing was used to create the graphical user interface, while Java was used to program the functionality of the system.

---

## 5. System Features

The system contains several features that make the registration process easier.

### 5.1 Name

The user enters their first name.

The system checks that the name contains valid characters.

Example error message:

> Invalid Name: Please enter letters only.

---

### 5.2 Surname

The user enters their surname.

The system checks that the surname is entered correctly and does not contain invalid characters.

---

### 5.3 Date of Birth

The user enters their date of birth.

The system uses the information provided to store the user's date of birth in the registration data.

---

### 5.4 Gender

The system allows the user to select their gender using radio buttons.

The radio buttons make it easier for the user to select one option.

---

### 5.5 Email Address

The user enters their email address.

The system checks whether the email has a valid format.

The email can contain:

* Letters
* Numbers
* Symbols such as `@` and `.`

Example error message:

> Invalid Email: Please enter a valid email address.

---

### 5.6 Contact Number

The user enters their contact number.

The system checks that the contact number contains valid characters and is entered in the correct format.

---

## 6. Data Validation

Validation is one of the most important parts of the system.

Validation prevents incorrect information from being accepted by the application.

For example, the system can check:

* Names contain letters.
* Surnames contain letters.
* Email addresses have a valid format.
* Contact numbers contain valid numbers.
* Required fields are not left empty.
* Gender is selected.

If incorrect information is entered, the system displays an error message to inform the user where the problem is.

---

## 7. Error Messages

The application uses error messages to help the user correct mistakes.

Examples include:

**Name:**

> Invalid Name: Please enter letters only.

**Email:**

> Invalid Email: Please enter a valid email address.

**Empty fields:**

> Please enter all required information.

These messages make the system easier to use because the user can understand what needs to be corrected.

---

## 8. Save / Submit Button

The **Save/Submit** button is used to process the information entered into the registration form.

When the user clicks the button, the system:

1. Gets the information entered into the form.
2. Checks whether the required fields are completed.
3. Validates the information.
4. Displays an error message if there is incorrect information.
5. Displays the information in the DATA section when the information is valid.

This prevents incorrect information from being displayed as valid registration data.

---

## 9. DATA Section

The **DATA** section displays the information entered by the user.

The information displayed can include:

* Name
* Surname
* Date of Birth
* Gender
* Email
* Contact Number

This allows the user to see the information they entered after completing the registration.

Example:

**DATA**

Name: John
Surname: Smith
Date of Birth: 15/05/2002
Gender: Male
Email: [john@gmail.com](mailto:john@gmail.com)
Contact Number: 0712345678

---

## 10. Clear Button

The **Clear** button is used to remove the information entered into the form.

When the user clicks **Clear**, the input fields are reset so that the user can enter new information.

This is useful when the user wants to start the registration process again.

---

## 11. Exit Button

The **Exit** button allows the user to close the application.

When the button is clicked, the Java program closes the registration window.

This provides an easy way for the user to leave the system.

---

## 12. Help Button

The **Help** button provides information to assist the user when using the system.

It can display a message explaining how to complete the registration form.

For example:

> Please enter your information in the required fields. Make sure that your name contains letters and your email address is in a valid format.

The Help button makes the system more user-friendly.

---

## 13. JOptionPane

The system uses **JOptionPane** to display messages to the user.

JOptionPane can be used to display:

* Error messages
* Successful registration messages
* Help information
* Confirmation messages

For example, when an error occurs, the system can display a message box informing the user about the problem.

---

## 14. How the System Works

The system follows a simple process:

### Step 1: Open the Application

The user opens the Java Swing Registration System.

### Step 2: Enter Information

The user enters their personal information into the available fields.

### Step 3: Validate Information

The user clicks the Save/Submit button.

The system checks the information entered.

### Step 4: Display Errors

If there is incorrect information, an error message is displayed.

The user can then correct the information.

### Step 5: Display Data

If all information is correct, the information is displayed in the DATA section.

### Step 6: Clear or Exit

The user can either clear the information and enter new details or exit the application.

---

## 15. User Interface

The graphical user interface contains different components, including:

* Labels
* Text fields
* Radio buttons
* Buttons
* Data display area
* Message boxes

These components allow the user to interact with the application easily.

---

## 16. Event Handling

The application uses Java event handling to perform different actions when buttons are clicked.

For example:

* Save button → validates and displays information.
* Clear button → clears the form.
* Exit button → closes the application.
* Help button → displays help information.

Each button has an event that runs when the user interacts with it.

---

## 17. Testing

The system was tested using different types of information.

### Test 1: Correct Name

A valid name was entered.

**Expected Result:**
The name is accepted.

### Test 2: Incorrect Name

Numbers or invalid characters were entered in the name field.

**Expected Result:**
An error message is displayed.

### Test 3: Correct Email

A valid email address was entered.

**Expected Result:**
The email is accepted.

### Test 4: Incorrect Email

An invalid email address was entered.

**Expected Result:**
An error message is displayed.

### Test 5: Empty Fields

Some required fields were left empty.

**Expected Result:**
The system informs the user to complete the required information.

### Test 6: Clear Button

Information was entered and the Clear button was clicked.

**Expected Result:**
The fields are cleared.

### Test 7: Exit Button

The Exit button was clicked.

**Expected Result:**
The application closes.

---

## 18. Advantages of the System

The system has several advantages:

* Easy to use.
* Simple graphical interface.
* Reduces incorrect data entry.
* Provides clear error messages.
* Allows information to be displayed immediately.
* Allows users to clear information easily.
* Provides a Help option.
* Demonstrates practical Java programming skills.

---

## 19. Limitations

The current system is a basic desktop registration application.

Some limitations include:

* It does not use a database.
* Information may not be permanently stored after the application is closed.
* It is designed mainly for demonstration and learning purposes.
* It does not have online registration functionality.

---

## 20. Future Improvements

The system can be improved in the future by adding:

* A database such as MySQL.
* User login and registration.
* Permanent storage of user information.
* Edit and delete functions.
* Search functionality.
* Better error messages.
* Improved user interface design.
* Password protection.
* Report generation.

These improvements would make the system more suitable for a real-world application.

---

## 21. Project Structure

The project contains Java source code responsible for the different functions of the application.

The main components include:

* Registration form
* Input fields
* Validation code
* Button event handling
* Data display
* JOptionPane messages

The code is written using Java and Java Swing.

---

## 22. Conclusion

The Java Swing Registration System successfully demonstrates how a desktop application can be created using Java.

The system allows users to enter personal information, validates the information, displays appropriate error messages, and shows the entered information in the DATA section.

The project helped demonstrate important programming concepts such as **Java Swing, GUI design, event handling, input validation, conditional statements, and JOptionPane**.

Overall, the project provides a simple example of how Java can be used to create an interactive registration system.
