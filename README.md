# 📊 Admin Dashboard App

An enterprise-style dashboard application built with **Angular** and **Angular Material**, featuring role-based access, reactive forms, charts, and state management. Ideal for demonstrating UI architecture, stateful logic, and scalable component design within a corporate or admin-style interface.

## 🛠 Tech Stack

- **Frontend:** Angular, Angular Router, Angular Reactive Forms
- **Styling:** Tailwind CSS *(or SCSS if preferred)*
- **State Management:** Angular Services with BehaviorSubjects (MVP)
- **Auth:** Simple local auth or Azure AD B2C (optional)
- **Charts:** ng2-charts (Chart.js wrapper)
- **Backend (Optional):** Azure Functions for dynamic features
- **Hosting:** Azure Static Web Apps

## 🚀 Features

| Feature                     | Description                                                                 |
|-----------------------------|-----------------------------------------------------------------------------|
| 🔐 Login Form               | Basic login form (hardcoded or Azure B2C optional integration)             |
| 🧭 Role-Based Routing        | Angular Router separates admin/user views with route guards                |
| 👥 User Management Table    | Full CRUD with Angular Material Table and Dialogs                          |
| 📊 Dashboard Charts         | Visualize sample metrics using `ng2-charts`                                |
| 📝 Reactive Forms           | Angular Reactive Forms with dynamic validation                             |
| 🔄 Shared State             | Global state managed via Services and BehaviorSubjects                     |
| ⚙️ Optional Backend          | Azure Functions for APIs or server-side logic                              |
| ☁️ Azure Deployment         | Hosted via Azure Static Web Apps                                           |

## 📦 Folder Structure

admin-dashboard-app/  
├── src/  
│   ├── app/  
│   │   ├── auth/  
│   │   ├── admin/  
│   │   ├── user/  
│   │   ├── services/  
│   │   └── shared/  
│   └── assets/  
├── environments/  
├── angular.json  
├── tailwind.config.js *(or styles.scss)*  
├── .env  
└── README.md  

## ⚙️ Setup Instructions

1. **Clone the repo**  
   `git clone https://github.com/yourusername/admin-dashboard-app.git && cd admin-dashboard-app`

2. **Install dependencies**  
   `npm install`

3. **Start dev server**  
   `ng serve`

4. **Configure Azure (Optional)**  
   - Azure AD B2C settings for login  
   - Azure Functions for backend APIs

5. **Deploy to Azure**  
   Use Azure Static Web Apps for deployment. Connect repository and follow portal instructions.

## 🧪 Optional Enhancements

- Full auth integration with Azure AD B2C
- Backend API routes with Azure Functions
- Dark mode and theme toggling
- Export user reports as CSV/PDF

## 📸 Screenshots

_Add screenshots of login, admin dashboard, and user table views._

## 📄 License

MIT — use freely for learning, enterprise demos, or production scaffolds.
