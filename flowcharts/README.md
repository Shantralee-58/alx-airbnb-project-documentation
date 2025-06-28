# 🔁 User Registration Flowchart – Airbnb Clone Backend

This flowchart visualizes the backend process for **User Registration** in the Airbnb Clone system. It maps out each logical step from form submission to account creation, validation, and notification.

## 📋 Process Overview

1. **Form Submission**  
   A new user fills out the registration form with their name, email, and password.

2. **Validation**  
   The submitted data is checked for completeness and accuracy. If invalid, the process logs the error and halts.

3. **Account Creation**  
   If the input is valid, a new user account is created in the database.

4. **Email Notification**  
   A confirmation email is sent to verify the user's account.

5. **Error Logging**  
   If validation fails, the error is recorded for debugging or user feedback.

## 🧩 Related Tables (Represented in dbdiagram.io)

- `RegistrationForm`: Stores raw form data submitted by users.
- `ValidationCheck`: Stores results of input validation.
- `Users`: Stores registered user accounts.
- `ConfirmationEmail`: Tracks whether confirmation was sent.
- `ErrorLog`: Records validation failures or errors.

## 🛠️ File Included

- `data-flow-diagram.png`: A visual flowchart representing the process.
- `flowchart-schema.sql`: SQL code compatible with dbdiagram.io to recreate the diagram.

## 💡 How to Use

1. Open [https://dbdiagram.io/d/data-flow-diagram-68603b68f413ba350853d7fc]
2. Paste the SQL from `flowchart-schema.sql` into the editor
3. View and export the generated flowchart
4. Use this visualization to understand and refine your backend logic

---

> This diagram is part of the **ALX Airbnb Clone Project Documentation** for the **ProDev Back-End** track.

