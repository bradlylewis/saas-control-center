# 🧩 SaaS Control Center

An enterprise-style admin dashboard built with **Angular** and **Azure**, designed to manage users, roles, and key metrics for a SaaS platform. Includes role-based access, charts, forms, and structured component architecture.

## 🛠 Tech Stack

- **Frontend:** Angular, Angular Router, Angular Reactive Forms
- **Styling:** Tailwind CSS (or SCSS)
- **State Management:** Services with BehaviorSubjects (MVP)
- **Auth:** Simple local auth or Azure AD B2C (optional)
- **Charts:** ng2-charts (Chart.js wrapper)
- **Backend (Optional):** Azure Functions for dynamic features
- **Hosting:** Azure Static Web Apps

## 🚀 Features

| Feature                | Description                                                     |
|------------------------|-----------------------------------------------------------------|
| 🔐 Role-Based Access    | Admin vs User views using route guards                          |
| 👥 User Management      | CRUD operations on a user table                                 |
| 📊 Dashboard Charts     | Line/bar/pie charts using dummy or real data                    |
| 🧾 Reactive Forms        | Validated forms for adding/editing users                        |
| 📦 Shared State          | Lightweight state via services and BehaviorSubjects            |
| ☁️ Azure Deployment      | Hosted using Azure Static Web Apps and optionally Functions     |

## 📦 Folder Structure

saas-control-center/  
├── src/  
│   ├── app/  
│   │   ├── components/  
│   │   ├── pages/  
│   │   ├── services/  
│   │   ├── guards/  
│   │   ├── models/  
│   │   └── app.module.ts  
│   ├── assets/  
│   └── environments/  
├── angular.json  
├── README.md  
└── ...  

## ⚙️ Setup Instructions

1. **Clone the repo**  
   `git clone https://github.com/yourusername/saas-control-center.git && cd saas-control-center`

2. **Install dependencies**  
   `npm install`

3. **Run the app locally**  
   `ng serve`

4. **Deploy to Azure**  
   Follow Azure Static Web Apps CLI or GitHub Actions setup.

## 🌐 Optional Azure Services

- **Azure AD B2C** — for enterprise-ready authentication  
- **Azure Functions** — to handle real-time chart data or event logs  
- **Azure Monitor** — for app telemetry and health tracking  

## 📸 Screenshots

_Add screenshots for the dashboard, charts, and user management pages._

## 📄 License

MIT — customize and expand as needed.
