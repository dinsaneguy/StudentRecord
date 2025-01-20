# Student Marks Tracker - User Guide

## Introduction

Welcome to the **Student Marks Tracker**! This is a simple and easy-to-use web application that allows you to track student marks by class. You can add student details, calculate their total marks, and delete records as necessary. All the data is saved directly in your browser’s local storage, ensuring it persists even after a page refresh.

## Features

- **Add Student Data**: Enter the student's name, class, and marks.
- **Automatic Total Marks Calculation**: The system automatically calculates the total marks based on the provided values.
- **Group Students by Class**: Students are organized into separate tables based on their class.
- **Delete Student Records**: Easily delete student records when needed.
- **Data Persistence**: All data is saved in your browser’s local storage, ensuring it persists after page refreshes.

## How to Use

### 1. Add a New Student

- **Student Name**: Type the name of the student.
- **Class**: Specify the class the student belongs to (e.g., "10A", "12B").
- **Marks**: Enter the marks scored by the student. You can use spaces, `+`, `*`, `-`, or commas to separate the marks. Here are some example inputs:
  - `10 5 8 9`
  - `6+4+8`
  - `3,5,7`

Once you’ve filled out the details, click on the **Add Student** button to save the information.

### 2. View Student Data

After adding a student, their information will appear in tables grouped by class. For each class, you'll see a table with the following columns:

- **Student Name**: The name of the student.
- **Total Marks**: The sum of the marks entered for that student.
- **Action**: The option to delete a student's record.

### 3. Delete a Student's Record

If you want to remove a student’s record, click on the **Delete** button next to their name in the table. This will remove the student’s data from both the table and the local storage.

### 4. Persistent Data

- The data is saved in your browser’s local storage. This means that even if you refresh the page or close and reopen the browser, your data will be preserved.
- You can access your student data anytime as long as it’s stored in the same browser.

## Example Walkthrough

1. **Adding a Student**:
   - **Student Name**: *John Doe*
   - **Class**: *10A*
   - **Marks**: *10 5 8 9*

   After clicking **Add Student**, the student will be displayed in the "10A" class table with the total marks calculated.

2. **Deleting a Student**:
   - To delete *John Doe*'s record, simply click the **Delete** button next to their name in the table. The student will be removed from the table, and their data will be erased from local storage.

## Troubleshooting

- **Data not saving**: Make sure that your browser’s local storage is enabled. If it is disabled, the data will not persist.
- **Data disappears after refresh**: If the data disappears after refreshing, ensure that your browser is not set to clear local storage upon closing. Using private/incognito browsing mode may also prevent data from being saved.

## Feedback

If you have any questions or suggestions, please contact the website administrator.

---

Thank you for using the **Student Marks Tracker**!
