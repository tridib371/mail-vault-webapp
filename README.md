<div align="center">

# 📬 MailVault

**A modern SaaS-style mailbox management platform built for speed, scale, and simplicity.**

[![Next.js](https://img.shields.io/badge/Next.js-15-black?style=for-the-badge&logo=next.js)](https://nextjs.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3-06B6D4?style=for-the-badge&logo=tailwindcss)](https://tailwindcss.com/)
[![License](https://img.shields.io/badge/License-Educational-orange?style=for-the-badge)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Active_Development-brightgreen?style=for-the-badge)]()

[📖 View Demo](https://mail-vault-webapp.netlify.app) · [🐛 Report Bug](https://github.com/tridib371/mailbox-app/issues) · [✨ Request Feature](https://github.com/tridib371/mailbox-app/issues)

</div>

---

## 📌 Table of Contents

- [Overview](#-overview)
- [Tech Stack](#-tech-stack)
- [Features](#-features)
- [Pages & Routes](#-pages--routes)
- [Folder Structure](#-folder-structure)
- [Getting Started](#-getting-started)
- [Scripts](#-scripts)
- [Developer Notes](#-developer-notes)
- [Contributing](#-contributing)
- [Author](#-author)
- [License](#-license)

---

## 🧭 Overview

**MailVault** is a full-featured SaaS-style email and messaging dashboard built with modern web technologies. It provides a clean, responsive interface for managing mailboxes, subscriptions, and user profiles — with both public-facing marketing pages and a secure authenticated dashboard experience.

> ⚠️ **Note:** This project is currently in active development as part of an internship assignment. The frontend is fully functional with mock API data; backend integration is planned for future iterations.

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| ⚛️ **Next.js (App Router)** | React framework with server-side rendering & routing |
| 🎨 **Tailwind CSS** | Utility-first CSS for rapid, consistent UI styling |
| 🔗 **Mock APIs (Dummy JSON)** | Simulated backend for frontend development |
| 📱 **Responsive Design** | Mobile-first layout supporting all screen sizes |
| 🧩 **Component Architecture** | Reusable, modular UI components |

---

## ✨ Features

- 🔐 **Authentication Flow** — Signup, Login, and Forgot Password UI (frontend-only)
- 📊 **Customer Dashboard** — Personalized mail, subscription, and profile management
- 📱 **Fully Responsive** — Optimized for both mobile and desktop viewports
- 🧪 **Mock API Integration** — Simulated data layer using structured dummy JSON
- 🧩 **Reusable Components** — Shared Navbar, Footer, Cards, and layout wrappers
- ⚡ **Optimized Performance** — Leveraging Next.js App Router for fast page loads
- 🌐 **Public Marketing Pages** — Home, Pricing, Contact, and more

---

## 🌐 Pages & Routes

### 🟢 Public Pages

| Route | Page |
|---|---|
| `/` | 🏠 Home |
| `/pricing` | 💰 Pricing |
| `/contact` | 📞 Contact |
| `/how-it-works` | 📬 How It Works |
| `/terms` | 📄 Terms & Conditions |
| `/privacy-policy` | 🔒 Privacy Policy |

### 🔐 Authentication Pages

| Route | Page |
|---|---|
| `/signup` | 📝 Sign Up |
| `/login` | 🔑 Login |
| `/forgot-password` | 🔁 Forgot Password |

### 📊 Customer Dashboard

| Route | Page |
|---|---|
| `/dashboard` | 🏠 Dashboard Home |
| `/dashboard/mail` | 📩 My Mail |
| `/dashboard/subscription` | 💳 Subscription |
| `/dashboard/profile` | 👤 Profile Settings |

---

## 📂 Folder Structure

```
mailbox-app/
├── app/                          # Next.js App Router
│   ├── (public)/                 # Public-facing pages
│   │   ├── page.tsx              # Home
│   │   ├── pricing/page.tsx
│   │   ├── contact/page.tsx
│   │   ├── how-it-works/page.tsx
│   │   ├── terms/page.tsx
│   │   └── privacy-policy/page.tsx
│   ├── (auth)/                   # Authentication pages
│   │   ├── login/page.tsx
│   │   ├── signup/page.tsx
│   │   └── forgot-password/page.tsx
│   └── dashboard/                # Protected dashboard pages
│       ├── page.tsx              # Dashboard home
│       ├── mail/page.tsx
│       ├── subscription/page.tsx
│       └── profile/page.tsx
├── components/                   # Reusable UI components
│   ├── Navbar.tsx
│   ├── Footer.tsx
│   └── ui/                       # Shared UI elements (Cards, Buttons, etc.)
├── data/                         # Mock API / Dummy JSON data
├── public/                       # Static assets (images, icons)
├── styles/                       # Global styles
├── tailwind.config.ts
├── next.config.ts
└── package.json
```

---

## 🚀 Getting Started

### Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/) `v18+`
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)

### Installation

**1. Clone the repository**

```bash
git clone https://github.com/tridib371/mailbox-app.git
cd mailbox-app
```

**2. Install dependencies**

```bash
npm install
# or
yarn install
```

**3. Start the development server**

```bash
npm run dev
# or
yarn dev
```

**4. Open in your browser**

```
http://localhost:3000
```

---

## 📦 Scripts

| Command | Description |
|---|---|
| `npm run dev` | Start local development server |
| `npm run build` | Build the app for production |
| `npm start` | Start the production server |
| `npm run lint` | Run ESLint for code quality checks |

---

## 🧑‍💻 Developer Notes

- 🧪 **Mock Data** — All API responses are currently simulated using local dummy JSON structures. No real backend is connected.
- 🔌 **API Layer** — The data-fetching layer is abstracted to make backend integration straightforward in future iterations.
- 🎯 **UI/UX Focus** — The primary focus of this phase is clean, accessible, and responsive interface design.
- 🧱 **Backend-Ready Architecture** — Folder structure and component design are prepared for seamless backend integration (e.g., REST API or Next.js Route Handlers).
- 🔐 **Auth Guards** — Dashboard routes include frontend-level route protection placeholders, ready for real session management.

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/your-feature-name`
3. Commit your changes: `git commit -m "feat: add your feature"`
4. Push to the branch: `git push origin feature/your-feature-name`
5. Open a Pull Request

Please follow [Conventional Commits](https://www.conventionalcommits.org/) for commit messages.

---

## 👤 Author

<div align="center">

**Tridib Sarkar**

Built with 💻, ☕, and a passion for clean UI

[![GitHub](https://img.shields.io/badge/GitHub-tridib371-181717?style=flat&logo=github)](https://github.com/tridib371)

</div>

---

## 📜 License

This project is developed for **educational and internship purposes** only. Not intended for commercial use.

---

<div align="center">

⭐ **If you found this project helpful, consider giving it a star!** ⭐

</div>
