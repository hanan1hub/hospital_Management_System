

# 🏥 Hospital Management System (Java and Javafx)

## 📌 Project Overview

The **Hospital Management System (HMS)** is a desktop-based JavaFX application designed to streamline and digitize hospital operations. This system supports three types of users—**Admin**, **Doctor**, and **Patient**—and provides a robust interface for managing patient data, appointments, feedback, and more. The application connects with a **MySQL database** to ensure persistent and reliable storage of hospital data.

---

## 🚀 Features

### 🔐 Authentication
- Role-based login (Admin, Doctor, Patient)
- User data managed in the database

### 🛠 Admin Dashboard
- Add/View/Delete patients and doctors
- Monitor appointments and feedback
- View system statistics and logs
- generate reports

### 👨‍⚕️ Doctor Dashboard
- Access patient vitals and medical history
- Schedule and view appointments
- Submit feedback and prescriptions
- Real-time messaging and video chat with patients
- view stats

### 🧑‍🤝‍🧑 Patient Dashboard
- Upload vitals and documents
- View prescriptions and doctor feedback
- Request appointments with available doctors
- Live text and video chat options
- view stats

### 🧩 Additional Functionalities
- Responsive and styled JavaFX GUI
- Real-time chat and communication system
- Data validation and input checking
- CSV export/import for reports and vitals

---

## 🛠️ Technologies Used

- **JavaFX** – GUI framework for Java
- **Java 17**
- **MySQL** – Relational database

---

## 🗂️ Project Structure
```
/src
├── AdminDashboard.java
├── DoctorDashboard.java
├── PatientDashboard.java
├── PatientService.java
├── AppointmentService.java
├── ChatService.java
└── ...
/resources
├── images
├── background.jpg
└── icons/
```
## ⚙️ Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/hanan1hub/hospital_Management_System.git

2. Set up your MySQL database:

3. Import hospital_management_schema.sql using a tool like phpMyAdmin or MySQL Workbench

4. Update the database credentials in DatabaseConfig.java

5. Launch the project from your IDE (e.g., IntelliJ or Eclipse)

6. Ensure JavaFX SDK is properly configured

7. Use Java 17 or compatible JDK

how to deploy project::

first of all install any java sported IDE(IntelliJ recommended) 
then
open the (project_oop) project from the jaavfx_complete project folder zip in IDE
then
import javafx library in project through files attached(from libraries to import folder)
then
 import my sql-connector file in project (from libraries to import folder)
then
 import Jakarta files in project available in (from libraries to import folder)
then 
in my sql workbench add the sql script provided in zip and run segment by segment

and you are good to go to view my hospital management system oop project


📷 Screenshots
(https://github.com/hanan1hub/hospital_Management_System/blob/main/Outcome_images.pdf))

## 👥 Authors

- **Hanan Majeed**  

# 📄 License
This project is licensed under the MIT License.


