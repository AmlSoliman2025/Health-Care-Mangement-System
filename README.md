# Health-Care-Mangement-System
SQL-based hospital management database system to track patients, appointments, doctors, and billing. Includes an ER diagram and SQL scripts for schema creation, data queries, and reports.


## 📚 Key Entities
- **Patients**: Stores patient details and medical history
- **Doctors**: Contains doctor information and specialization
- **Appointments**: Manages patient-doctor scheduling
- **Billing**: Tracks financial records for treatments


## 🗂️ Database Schema
![image](https://github.com/user-attachments/assets/8f773994-c3ef-40f4-a21d-ee6e6d67c822)

The database consists of 4 interconnected tables:
- `patients(patient_id, name, gender, dob, contact_number, address, medical_history)`
- `doctors(doctor_id, name, specialization, contact_number, email)`
- `appointments(appointment_id, patient_id, doctor_id, appointment_date, appointment_time, status)`
- `billing(bill_id, patient_id, doctor_id, bill_date, amount, status)`

## 🧩 Relationships
- Each appointment links a **patient** to a **doctor**
- Each billing entry is associated with a **patient** and a **doctor**
- One-to-many relationships:
  - A patient can have many appointments and bills
  - A doctor can attend multiple appointments and issue bills

## 🛠️ Features
- Schedule and track patient appointments
- Maintain billing history
- Store patient records with medical history
- Query doctor availability and patient interactions

## 📁 Repository Structure

The database consists of 4 interconnected tables:
- `patients(patient_id, name, gender, dob, contact_number, address, medical_history)`
- `doctors(doctor_id, name, specialization, contact_number, email)`
- `appointments(appointment_id, patient_id, doctor_id, appointment_date, appointment_time, status)`
- `billing(bill_id, patient_id, doctor_id, bill_date, amount, status)`

## 🧩 Relationships
- Each appointment links a **patient** to a **doctor**
- Each billing entry is associated with a **patient** and a **doctor**
- One-to-many relationships:
  - A patient can have many appointments and bills
  - A doctor can attend multiple appointments and issue bills

## 🛠️ Features
- Schedule and track patient appointments
- Maintain billing history
- Store patient records with medical history
- Query doctor availability and patient interactions


