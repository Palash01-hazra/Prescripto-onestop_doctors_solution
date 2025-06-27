# 🏥 Prescripto - One Stop Doctors Solution

**Prescripto** is a full-stack appointment booking system built for hospitals, clinics, and doctors. It supports three levels of authentication: **Patient**, **Doctor**, and **Admin**, enabling seamless management of appointments and medical profiles.

---

## 🔗 Live Links

- 🌐 **UI (Patient/Doctor View):** [prescripto-frontend](https://prescripto-onestop-doctors-solution-7oej-frontend.vercel.app/)
- 🛠 **Admin Dashboard:** [prescripto-admin](https://prescripto-admin-beta.vercel.app/)

---

## 📸 Screenshots

### UI Landing Page
![Landing Page](![Screenshot 2025-06-27 185629](https://github.com/user-attachments/assets/ea43a1b9-cd3a-4113-9316-65a0e75f5bf9)
)

### Admin Dashboard
![Admin Panel](![Screenshot 2025-06-27 184244](https://github.com/user-attachments/assets/1d99922d-b0b2-4c92-ad64-44c5a7906d4d)
)
### Doctors Dashboard
![Doctor Panel](![Screenshot 2025-06-27 184151](https://github.com/user-attachments/assets/fbbbf64d-4e8a-42a7-844a-cfb29d03ef72)
)

---

## 🚀 Features

### 👨‍⚕️ Patient Portal
- Browse doctors by specialty
- Book & cancel appointments
- View booking history

### 🩺 Doctor Dashboard
- Login and manage their profile
- View appointments and earnings

### 🛡 Admin Panel
- Add/update/delete doctors
- Manage all appointments
- Monitor patients & system stats

---

## 🛠 Tech Stack

| Category     | Tech                      |
|--------------|---------------------------|
| Frontend     | React, Tailwind CSS       |
| Backend      | Node.js, Express.js       |
| Database     | MongoDB                   |
| Auth         | JWT (Role-based)          |
| Hosting      | Vercel, Render            |

---

## ⚙️ Installation Guide

Clone the repo and install dependencies:


git clone https://github.com/Palash01-hazra/Prescripto-onestop_doctors_solution.git
cd Prescripto-onestop_doctors_solution
---
##🔧 Setup for Frontend
bash
Copy
Edit
cd frontend
npm install
npm run dev
---
##🔧 Setup for Backend
bash
Copy
Edit
cd backend
npm install
npm run dev
---
##🔐 Environment Variables

Create a .env file in the backend folder with:

env
Copy
Edit
PORT=3030
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret_key
---
##📂 Folder Structure
bash
Copy
Edit
Prescripto/
├── backend/          # Node.js + Express API
├── frontend/         # React.js + Tailwind UI
├── assets/           # Screenshots and design assets
└── README.md
---
##🙋‍♂️ Author
Palash Hazra
---
##📄 License
This project is licensed under the MIT License.
