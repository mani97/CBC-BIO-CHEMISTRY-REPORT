# 🏥 Hospital Laboratory Report Generator

A comprehensive **Hospital Laboratory Information System (LIS)** built with **Java Spring Boot**, **Hibernate**, and **PostgreSQL**.  
This backend solution streamlines patient data management, laboratory reporting, billing, and secure record retrieval.

---

## ✨ Key Features
- **[Report Generation](ca://s?q=Hospital_lab_report_generation)** → Create lab reports from simple input fields.  
- **[Billing System](ca://s?q=Hospital_billing_system)** → Integrated billing for tests and procedures.  
- **[Patient Data Maintenance](ca://s?q=Hospital_patient_data_management)** → Store, update, and retrieve patient records.  
- **[Report Access](ca://s?q=Hospital_patient_report_access)** → Secure retrieval of patient reports.  
- **[Registration Number & Timestamp](ca://s?q=Hospital_registration_number_generation)** → Auto‑generate unique patient IDs with timestamps.  

---

## 🧪 Supported Laboratory Reports
- **CBC (Complete Blood Count)**  
- **Biochemistry Reports**  
  - Widal Test  
  - Liver Function Test (LFT)  
  - Renal Function Test (RFT)  
  - Lipid Profile  
  - Glucose Test (FBS/PPBS)  
- **Urine Analysis**  
- **Serum Calcium Level**  
- **Card Tests**  
  - HBsAg  
  - HIV 1/2  
  - Malaria IgG/IgM  
- *(Extensible for additional tests)*

---

## 🛠️ Tech Stack
- **Backend:** Java, Spring Boot  
- **ORM:** Hibernate  
- **Database:** PostgreSQL  
- **Authentication:** Spring Security (JWT)  
- **Architecture:** RESTful APIs, Microservices ready  

---

## 📂 Database Schema Highlights
- **Patients** → Registration number, demographics, contact info  
- **Reports** → CBC, LFT, RFT, etc. linked to patient ID  
- **Billing** → Test charges, invoices, payment tracking  
- **Pharmacy Integration** → Drug stock, prescriptions, ADR tracking  
- **Employee Management** → Doctors, lab technicians, staff roles  

---

## 🚀 Getting Started
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/hospital-lab-report-generator.git
