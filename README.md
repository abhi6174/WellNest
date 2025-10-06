# WellNest - Blockchain-based Electronic Health Records (EHR) Management System

WellNest is a secure, decentralized Electronic Health Records management system built on Hyperledger Fabric blockchain technology. The system provides secure, private, and patient-centered healthcare data management with tamper-proof records and controlled access mechanisms.

## 🏗️ Architecture

The project consists of three main components:

- **Blockchain Network**: Hyperledger Fabric network with 2 organizations (Org1MSP for doctors, Org2MSP for patients)
- **Backend API**: Spring Boot application providing REST APIs for blockchain interaction
- **Frontend**: React.js web application for user interface

## 👥 User Roles & Organizations

### Organization 1 (Org1MSP) - Healthcare Providers
- **Role**: Doctors and medical staff
- **Capabilities**: Create, update, and access patient records
- **Default Admin**: admin:adminpw

### Organization 2 (Org2MSP) - Patients
- **Role**: Patients and healthcare consumers
- **Capabilities**: View their own records, grant/revoke access permissions
- **Default Admin**: admin:adminpw