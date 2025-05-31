# Student Enrollment Form

![Project Logo](https://img.icons8.com/ios-filled/100/000000/student-center.png)

> A simple and interactive student enrollment form that stores student data based on Roll No as the primary key. The form enables adding new records, updating existing records, and resetting the form. Built using plain HTML and JavaScript.

---

## About

This project implements a **Student Enrollment Form** that allows users to enter data into a hypothetical school database (`SCHOOL-DB`) in the `STUDENT-TABLE` relation. The primary key for this table is **Roll No**.

The form works dynamically by enabling/disabling controls based on user input and database availability of records:

- On page load or reset, only the Roll No field is enabled for input.
- If Roll No does not exist, the user can fill in the rest of the fields and **save** a new record.
- If Roll No exists, the form shows the existing data and lets the user **update** fields (except Roll No).
- Proper input validation is done to ensure no empty data is saved or updated.
- Three control buttons: **Save**, **Update**, and **Reset** manage form data and state.

---

## Features
- Input fields for Roll-No, Full Name, Class, Birth Date, Address, and Enrollment Date.
- The Roll No field acts as the primary key for identifying student records.
- On page load or reset, only the Roll No field is enabled for input.
- If the Roll No entered does not exist in the database, users can enter other student details and save the record.
- If the Roll No entered exists, the form is populated with existing data, and users can update it.
- Buttons:
  - **Save**: Saves new student records.
  - **Update**: Updates existing student records.
  - **Reset**: Clears the form and resets the state.
- Form validation ensures no empty fields during save or update.
- The cursor focuses on the Roll No field on load and reset.

---

## Demo

![Demo Screenshot](https://i.imgur.com/2zGF0JS.png)

*Note: This is a static mockup. The included form uses a mock database in JavaScript.*

---

## Technologies Used
- HTML
- JavaScript
- 
---

## How to Use
1. Open the `index.html` file in a modern web browser.
2. Enter the Roll No in the first input field.
3. If the Roll No does not exist, enter the student details and click **Save**.
4. If the Roll No exists, the form will display the student data. Edit the fields as needed and click **Update**.
5. Use the **Reset** button to clear the form and start over.

---

## Notes
- The current implementation includes a mock database for demonstration purposes. The data is stored only temporarily in the script and will be reset upon page reload.
- For real database integration, backend scripts or API endpoints should be implemented.

---

## Future Enhancements
- Connect with a real database for persistent storage.
- Add server-side validation.
- Improve UI styling and responsiveness.
- Add search functionality for students.

---

## File Structure
- `index.html` : Contains the Student Enrollment Form with inline CSS and JavaScript.

---

## License
This project is open-source and free to use.

---

Feel free to customize or expand this project as needed.
