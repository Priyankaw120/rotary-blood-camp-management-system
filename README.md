# 🚑 Rotary Blood Camp Management System  
A full-stack system designed to help Rotary NGOs organize, monitor, and manage blood donation camps — from donor registration to allocation and reporting.

---

## 📌 Project Overview  
This application digitizes the entire workflow of a blood donation camp.  
Rotary Clubs and NGOs can use it to:

- Plan and schedule donation camps  
- Register donors and manage their profiles  
- Track every donation event  
- Maintain accurate blood inventory  
- Handle and approve blood requests  
- Allocate units intelligently  
- Generate admin-level reports  

The aim is to provide a **centralized, structured, and efficient platform** for NGO blood camp operations.

---

## 🧩 Core Features

### 🩸 Donor Management  
- Donor registration with blood type & eligibility  
- Donation history tracking  
- Unique donor profile management  

### 📅 Camp Management  
- Create, update, and manage blood donation camps  
- Track volunteers, slots, and session data  
- Link donations to specific camps  

### 🧬 Inventory Control  
- Track units by blood group  
- Auto-update after donation & allocation  
- Remove expired units  

### 🏥 Requests & Allocations  
- Handle requests from hospitals/NGOs  
- Approve/reject with notes  
- Allocate units based on availability  
- Audit trail for every action  

### 📊 Admin Dashboard  
- Key metrics: donors, units, camps  
- Open requests & pending approvals  
- Exportable reports (CSV/PDF)  

---

## 🛠️ Tech Stack

### **Frontend**
- React / JavaScript / HTML / CSS  
- Component-based UI  

### **Backend**
- Node.js  
- Express.js  
- JWT Authentication  

### **Database**
- PostgreSQL  

### **Tools**
- Git & GitHub  
- Postman     

---


## 🚀 Getting Started (Local Development)
---
### 1️⃣ Clone the repository
```bash
git clone https://github.com/Priyankaw120/rotary-blood-camp-management-system.git
cd rotary-blood-camp-management-system
```
---
### 2️⃣ Backend Setup
cd backend
npm install
cp .env.example .env    # Fill values
npm run dev
---
#### Backend will run at:

http://localhost:4000
---
#📡 API Summary
---
Complete API details: docs/api.md

Example endpoints:
---
- POST   /api/donors
- GET    /api/camps
- POST   /api/donations
- POST   /api/requests
- POST   /api/allocations


