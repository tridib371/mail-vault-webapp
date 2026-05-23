# 📬 Mailbox App

A modern SaaS-style mailbox management web application built with **Next.js** and **Tailwind CSS**, featuring responsive design, authentication flows, and a customer dashboard experience.

---

## 🚀 Tech Stack

- ⚛️ Next.js (App Router)
- 🎨 Tailwind CSS
- 📱 Responsive Design (Mobile + Web)
- 🔗 Mock APIs (Dummy JSON structure)
- 🧩 Component-based UI architecture

---

## 📌 Project Overview

Mailbox App is designed as a SaaS-style email/messaging dashboard platform. It includes both **public-facing pages** and a **secure customer dashboard**.

The project follows a modular UI approach with reusable components and scalable folder structure.

---

## 🌐 Pages Included

### 🟢 Public Pages
- 🏠 Home (`/`)
- 💰 Pricing (`/pricing`)
- 📞 Contact (`/contact`)
- 📄 Terms & Conditions (`/terms`)
- 🔒 Privacy Policy (`/privacy-policy`)
- 📬 How It Works (`/how-it-works`)

---

### 🔐 Authentication Pages
- 📝 Signup (`/signup`)
- 🔑 Login (`/login`)
- 🔁 Forgot Password (`/forgot-password`)

---

### 📊 Customer Dashboard
- 📁 Dashboard Home (`/dashboard`)
- 📩 My Mail (`/dashboard/mail`)
- 💳 Subscription (`/dashboard/subscription`)
- 👤 Profile Settings (`/dashboard/profile`)

---

## 🎯 Key Features

- 📱 Fully responsive UI (Mobile + Desktop)
- 🧪 Mock API integration using dummy JSON
- 🎨 Clean and modern UI design
- 🧩 Reusable components (Navbar, Footer, Cards)
- ⚡ Fast performance with Next.js
- 🔐 Authentication flow UI (frontend only)

---


app/
┣ (auth)/
┃ ┣ login/
┃ ┣ signup/
┃ ┗ forgot-password/
┣ (public)/
┃ ┣ pricing/
┃ ┣ contact/
┃ ┣ terms/
┃ ┣ privacy-policy/
┃ ┗ how-it-works/
┣ dashboard/
┃ ┣ mail/
┃ ┣ subscription/
┃ ┗ profile/
┣ components/
┃ ┣ Navbar.tsx
┃ ┣ Footer.tsx
┃ ┗ Sidebar.tsx
┗ layout.tsx


---

## 🛠️ Setup Instructions

### 1️⃣ Clone the repository
```bash
git clone https://github.com/tridib371/mailbox-app.git
cd mailbox-app

## 📂 Folder Structure (Planned / Recommended)

2️⃣ Install dependencies
npm install

3️⃣ Run development server
npm run dev

📦 Build for Production
npm run build
npm start

📌 Notes for Developers
1. 🧪 All data is currently using mock JSON structures
2. 🔌 API layer is simulated for frontend development
3. 🎯 Focus is on UI/UX and responsive layout
4. 🧱 Code is structured for future backend integration

🤝 Contribution

This project is currently under active development as part of an internship assignment. Contributions and improvements will be added progressively.

📜 License

This project is for educational and internship purposes.

✨ Author

Built with 💻 by Tridib Sarkar

---

If you want next upgrade, I can also:
- :contentReference[oaicite:0]{index=0}
- or :contentReference[oaicite:1]{index=1}
- or :contentReference[oaicite:2]{index=2}

Just tell me 👍
