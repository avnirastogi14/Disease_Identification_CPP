# Disease Identification System (C++)

An intelligent healthcare solution for identifying potential diseases based on user symptoms, providing medication suggestions, and managing user data securely through file handling.

---

## 📖 Overview

This project is a C++ application designed to assist users in identifying diseases and suggesting treatments. It integrates symptom analysis, disease diagnosis, treatment recommendations, billing, and feedback functionalities. The system emphasizes user privacy by assigning a unique ID to each patient and securely storing information in files.

---

## 🚀 Features

- **Login/Registration System**:
  - Secure login using patient ID or mobile number.
  - Registration system with unique patient ID generation.
  - Password validation with multiple attempts.

- **Disease Identification**:
  - Analyze symptoms to identify probable diseases.
  - Suggest diagnostic tests for narrowing down results.
  - Provide treatments for the identified diseases.

- **Personal Information Management**:
  - View and manage personal details securely.

- **Billing and Payment**:
  - Generate bills based on services utilized.
  - Support for cash and online payment methods.
  - Automatic change calculation for cash payments.

- **Feedback System**:
  - Collect user feedback for improving the system.

---

## 🛠️ Tools and Libraries

This project utilizes the following C++ libraries:
- `<iostream>`: Input/Output operations.
- `<fstream>`: File handling.
- `<string>`: String manipulation.
- `<vector>`: Dynamic array operations.
- `<sstream>`: String stream operations.
- `<iomanip>`: Input/Output manipulators.
- `<ctime>`: Date and time utilities.
- `<algorithm>`: Sequence algorithms.
- `<unordered_set>`: Set container.
- `<cctype>`: Character classification functions.

---

## ⚙️ How It Works

1. **Welcome Window and Login**:
   - Displays a welcome message and prompts users to log in.
   - If login fails, users can opt to register.

2. **Main Menu**:
   - **View Personal Details**: Displays stored personal information.
   - **Identify Disease**:
     - User answers common and uncommon symptom prompts.
     - Identifies potential diseases and displays treatments/tests.
   - **Exit**: Exits the program.

3. **Billing and Payment**:
   - Generates bills based on actions (e.g., viewing diseases, tests).
   - Offers cash or online payment options.

4. **Feedback**:
   - Collects user feedback at the end of the session.

---

## 💻 Program Flow

1. **User Login**:
   - User logs in using credentials stored in `patients.txt`.
2. **Symptom Analysis**:
   - Users answer questions about common and uncommon symptoms.
   - The system matches these symptoms to diseases.
3. **Diagnosis and Treatment**:
   - Users can view disease details, treatments, and recommended tests.
4. **Billing**:
   - Calculates fees based on services availed.
   - Allows users to make payments via cash or online banking.
5. **Feedback Collection**:
   - Gathers user suggestions and ratings for system improvement.

---

## 🧑‍💻 Concepts Utilized

- **Data Structures**:
  - Structures for patients, diseases, and feedback.
- **File Handling**:
  - Read/write operations for patient data storage.
- **Standard Template Library (STL)**:
  - Use of `vector`, `unordered_set`, and algorithms.
- **Exception Handling**:
  - Validations for input errors and file operations.

---

## 📂 File Structure

- `patients.txt`: Stores patient records (ID, name, DOB, etc.).
- Source code files:
  - Implement login, registration, symptom analysis, and payment logic.
- Diagnostic data: Stores diseases, symptoms, and treatments.

---

## ✨ Future Enhancements

- Optimizing runtime and complexity.
- Summarizing diagnosis in a receipt format.
- Adding advanced access modes:
  - **Manager’s Window**: Record visits, track common symptoms, and update diseases.
  - **Patient Features**: Edit personal information and view past diagnoses.

---

## 📜 Authors

Developed by:
- Avni Rastogi 
- Anshika Aggarwal 
- Manayav Vatsal 
- Kohsheen Razdan 

---
