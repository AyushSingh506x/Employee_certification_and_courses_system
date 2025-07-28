# EmployeeSkillHub – Course & Certification Manager

EmployeeSkillHub is a robust and modern web platform developed using the MERN Stack (MongoDB, Express, React, Node.js) designed to help organizations streamline the process of training, certifying, and managing their workforce. It simplifies assigning courses, monitoring certifications, and notifying employees about expiries – all under one roof.

---

## 🌟 Highlights

### Key Functionalities:
- Secure login with role-based access for Admins and Employees
- Manage training courses: add, update, delete, assign
- Maintain employee records and profiles
- Upload and track certification documents (PDFs)
- Receive automatic email alerts for expiring certifications
- Search and filter employees, courses, and certificates
- Clean dashboard with real-time stats for admins
- JWT-secured authentication system

---

## ⚙️ Tech Stack

| Component       | Technology             |
|----------------|------------------------|
| Frontend        | React.js + Tailwind CSS |
| Backend         | Node.js + Express.js    |
| Database        | MongoDB with Mongoose   |
| Authentication  | JWT                     |
| File Uploads    | Multer                  |
| Scheduler       | node-cron               |
| Emailing        | Nodemailer              |

---

## 📁 Project Structure

<pre> ```text EmployeeSkillHub/ ├── client/ │ └── src/ │ ├── views/ │ ├── components/ │ └── helpers/ ├── server/ │ ├── models/ │ ├── routes/ │ ├── controllers/ │ ├── middleware/ │ └── services/ ``` </pre>



---

## 🛠️ Getting Started

### Prerequisites:
- Node.js & npm
- MongoDB (local/cloud)
- Git

### 1. Clone the Repository
git clone https://github.com/YOUR_USERNAME/EmployeeSkillHub.git
cd EmployeeSkillHub
