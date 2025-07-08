# 📊 Admin Dashboard App

A modern, enterprise-style admin dashboard built with **React** and styled using **ShadCN UI** (Tailwind + Radix UI). This app features role-based views, reactive forms, CRUD functionality, charts, and centralized state management—perfect for showcasing scalable frontend architecture.

---

## 🛠 Tech Stack

- **Frontend:** React, React Router, React Hook Form
- **Styling:** ShadCN UI (Tailwind CSS + Radix UI)
- **State Management:** Context API or Zustand (BehaviorSubject-like)
- **Auth:** Simple local auth or Azure AD B2C (optional)
- **Charts:** React Chart.js or Recharts
- **Backend (Optional):** Azure Functions
- **Hosting:** Azure Static Web Apps

---

## 🚀 Features

| Feature                  | Description                                                               |
|--------------------------|---------------------------------------------------------------------------|
| 🔐 Login Form            | Basic local login or optional Azure B2C integration                       |
| 👥 Role-Based Views      | Conditional rendering and route protection based on user role             |
| 🧾 User Management Table | List, create, update, delete users with modals and confirmation dialogs    |
| 📊 Dashboard Charts      | Visualize metrics using Chart.js or Recharts                              |
| 📝 Reactive Forms        | Add/edit forms with validation using React Hook Form                      |
| 🔄 Shared State          | Global state using Zustand or Context with custom hooks                   |
| ☁️ Azure Deployment      | Hosted with Azure Static Web Apps + Functions (if needed)                 |

---

## 📦 Folder Structure

admin-dashboard-app/  
├── public/  
├── src/  
│   ├── components/ (ShadCN UI)  
│   ├── pages/  
│   ├── routes/  
│   ├── context/ or stores/  
│   ├── lib/ (auth, API helpers)  
│   ├── charts/  
│   └── App.tsx  
├── shadcn.config.ts  
├── tailwind.config.ts  
├── .env  
└── README.md  

---

## ⚙️ Setup Instructions

1. **Clone the repo**  
   ```bash
   git clone https://github.com/yourusername/admin-dashboard-app.git && cd admin-dashboard-app
   ```

2. **Install dependencies**  
   ```bash
   npm install
   ```

3. **Run the dev server**  
   ```bash
   npm run dev
   ```

4. **(Optional)** Set up Azure AD B2C and Azure Functions

5. **Deploy to Azure**  
   - Use Azure Static Web Apps  
   - Optionally deploy Azure Functions for backend logic

---

## 🧪 Optional Enhancements

- Dark mode toggle with ShadCN theming
- JWT-based auth with refresh token logic
- Export table data to CSV or PDF
- Admin audit logs and analytics

---

## 📸 Screenshots

_Add screenshots of login screen, dashboard charts, and user management table._

---

## 📄 License

MIT — feel free to fork, expand, and use as a base for internal tools.
