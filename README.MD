# Full Stack Employee Management System (EMS)

A complete **Full Stack Employee Management System** built with modern technologies, designed to handle real-world organizational workflows like employee management, attendance tracking, leave handling, and payslip generation.

---

## 🌐 Live Demo  
👉 [Click here to explore the app](https://employee-management-system-theta-six.vercel.app/login)

---

## ✨ Features

* 🔐 **Role-Based Authentication**

  * Separate access for Admin and Employees

* 📅 **Attendance Management**

  * Employees can mark attendance
  * Admin can monitor records

* 📝 **Leave Management**

  * Apply for leave
  * Admin approval/rejection system

* 💰 **Payslip Generation**

  * Automated salary slip generation

* 🌐 **REST API**

  * Built using Node.js & Express

* 🗄️ **Database Integration**

  * MongoDB for efficient data handling

* ⚙️ **Background Jobs**

  * Managed using Inngest

* 🤖 **AI Code Review**

  * Integrated with CodeRabbit

* 📧 **Email Notifications**

  * SMTP-based email system for alerts and communication

---

## 🛠️ Tech Stack

**Frontend:**

* React.js / Next.js
* Tailwind CSS / Bootstrap

**Backend:**

* Node.js
* Express.js

**Database:**

* MongoDB

**Other Tools:**

* Inngest
* CodeRabbit

---

## 📁 Project Structure

```
FullStack-EMS/
│── frontend/
│── backend/
│── README.md
```

---

## ⚙️ How to Run This Project

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Deepanshi-05/Employee-Management-System.git
cd Employee-Management-System
```

---

### 2️⃣ Setup Backend

```bash
cd backend
npm install
```

Create a `.env` file inside the `backend` folder and add:

```
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key

# Inngest Configuration
INNGEST_EVENT_KEY=your_inngest_event_key
INNGEST_SIGNING_KEY=your_inngest_signing_key

# SMTP Email Configuration
SMTP_HOST=smtp.gmail.com
SMTP_USER=your_email@example.com
SMTP_PASS=your_email_password
```

Run backend:

```bash
npm start
```

---

### 3️⃣ Setup Frontend

Open a new terminal:

```bash
cd frontend
npm install
npm run dev
```

---

### 4️⃣ Open in Browser

```
http://localhost:3000
```

---

## 🔑 Roles & Access

* **Admin**

  * Manage employees
  * Approve/reject leaves
  * View attendance

* **Employee**

  * Mark attendance
  * Apply for leave
  * View payslip

---

## 📌 Future Improvements

* 📊 Advanced Dashboard & Analytics
* 🔔 Real-time Notifications
* 📱 Improved Mobile Responsiveness
* 📈 Performance Optimization

---

## 🤝 Contributing

Feel free to fork the repository and submit pull requests.

---

## 📫 Contact

📧 **[sabrandeepanshi23@gmail.com](mailto:sabrandeepanshi23@gmail.com)**


