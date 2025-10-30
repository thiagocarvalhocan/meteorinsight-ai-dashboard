# 🚀 MeteorInsight – AI-Powered SaaS B2B Dashboard  

A full-featured **SaaS B2B Analytics Dashboard** built with **Angular 18+, Tailwind, RxJS, and PrimeNG**, integrating **OpenAI API** 
to generate real-time business insights through natural language.  

MeteorInsight helps teams visualize key performance metrics, explore data interactively, and receive AI-driven recommendations — all within a responsive,
scalable, and production-grade architecture.

---

## 🌟 Features

✅ **Modern SaaS Architecture** – Modular Angular setup with authentication, admin panel, and lazy loading.  
✅ **AI Integration** – Real-time insights powered by OpenAI API (GPT models).  
✅ **Interactive Dashboard** – Charts, KPIs, and analytics filters built with `ngx-charts` and `RxJS`.  
✅ **Responsive UI** – Built with Tailwind CSS and PrimeNG for enterprise-grade design consistency.  
✅ **Dark/Light Mode** – Accessible and adaptive layout with smooth transitions.  
✅ **Admin Panel** – Role-based access control, CRUD for users and plans.  
✅ **Deployed on Azure / Vercel** – Continuous deployment setup via GitHub Actions.

---

## 🏗️ Tech Stack

| Layer | Technology |
|--------|-------------|
| **Frontend Framework** | Angular 18+ |
| **Styling** | Tailwind CSS, PrimeNG |
| **State Management** | RxJS, Angular Signals |
| **Charts** | ngx-charts / Chart.js |
| **AI Integration** | OpenAI API / HuggingFace API |
| **Auth & Routing** | Angular Guards, Reactive Forms |
| **DevOps / Deploy** | Azure Static Web Apps / Vercel |
| **Version Control** | Git + GitHub |

---

## 📁 Project Structure
src/app/
├── core/ # Core services (Auth, API, Guards)
├── shared/ # Shared UI components, directives, and pipes
├── modules/
│ ├── auth/ # Login / Register / Forgot Password
│ ├── dashboard/ # KPI cards, charts, data filters
│ ├── ai-insights/ # AI prompt + chat response module
│ └── admin/ # Admin panel and CRUD operations
├── assets/ # Logos, themes, mock data
└── environments/ # Environment configs (API keys, endpoints)

---

## ⚙️ Setup Instructions

### 1️⃣ Clone the repository
```bash
git clone https://github.com/YOUR_USERNAME/MeteorInsight-ai-dashboard.git
cd MeteorInsight-ai-dashboard

2️⃣ Install dependencies
```bash
npm install

3️⃣ Configure environment variables
Create your .env or update environment.ts with your OpenAI key:
export const environment = {
  production: false,
  openaiKey: 'YOUR_API_KEY_HERE',
};

4️⃣ Run locally
```bash
ng serve

5️⃣ Build for production
```bash
ng build --configuration production
💬 Example AI Prompts

You can ask:

“Summarize sales performance in Q3.”

“Why did customer engagement drop last month?”

“Generate 3 strategies to increase conversion rate.”

“List top 5 clients by lifetime value.”

📸 Screenshots (coming soon)

Add here Figma mockups, UI previews or deployed app screenshots.

🌐 Live Demo (if deployed)

👉 https://MeteorInsight.vercel.app

(placeholder — replace with your real link)

🧭 Future Enhancements

🔐 OAuth2 Authentication

📊 Dynamic data from external REST APIs

💾 Firebase or Supabase backend

🧩 Multi-tenant support for SaaS scaling

🌍 i18n for multilingual users (English / French / Portuguese)

👨‍💻 About the Developer

Thiago Gusmão de Carvalho
Frontend Developer specialized in Angular, RxJS, and SaaS product architecture.
Fluent English (IELTS 7.0) • Canadian ECA Bachelor’s Degree
Focused on building scalable, responsive, and AI-driven web applications.

📫 LinkedIn

📧 thiagocarvalhocan@gmail.com

🏷️ Keywords

#Angular #AI #SaaS #Tailwind #RxJS #OpenAI #FrontendDeveloper #CanadaJobs
