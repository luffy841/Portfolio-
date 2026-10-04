# Soumya Khandelwal — Personal Portfolio Website

A modern, high-performance, and responsive personal portfolio built with **React**, **Vite**, and **Tailwind CSS**. Designed for B.Tech students and tech enthusiasts with an emphasis on AI, Web Development, and Digital Productivity.

## 🚀 Features

- **Single-Page Smooth Scrolling:** Fluid navigation between Hero, About, Education, Skills, Projects, Achievements, and Contact.
- **Mobile-First & Fully Responsive:** Hamburger navigation drawer on mobile with glassmorphism backdrop blur.
- **Centralized Data File:** All personal details, links, education history, skills, projects, and achievements are organized in `src/data/portfolioData.js`.
- **Interactive Micro-Animations:** Subtle hover lift effects, glowing highlights, and interactive preview modals.
- **Click-to-Copy Email:** Instant copy-to-clipboard for `khandelwalsoumya59@gmail.com` with feedback badge.
- **Deployable to Vercel:** Zero-config Vercel configuration (`vercel.json` included).

---

## 🛠️ Tech Stack

- **Framework:** [React 18](https://react.dev/) + [Vite](https://vitejs.dev/)
- **Styling:** [Tailwind CSS](https://tailwindcss.com/)
- **Icons:** [Lucide React](https://lucide.dev/)
- **Fonts:** [Outfit](https://fonts.google.com/specimen/Outfit) & [Plus Jakarta Sans](https://fonts.google.com/specimen/Plus+Jakarta+Sans)
- **Deployment:** [Vercel](https://vercel.com/)

---

## 💻 Quick Start

### 1. Install Dependencies
```bash
npm install
```

### 2. Run Locally in Development Mode
```bash
npm run dev
```
Open [http://localhost:3000](http://localhost:3000) in your browser.

### 3. Build for Production
```bash
npm run build
```

### 4. Preview Production Build
```bash
npm run preview
```

---

## 📝 Customization Guide

All data can be customized in a single file:
👉 **`src/data/portfolioData.js`**

1. **LinkedIn & GitHub URLs:**
   Update `personal.linkedinUrl` and `personal.githubUrl`.
2. **Projects:**
   Add or edit projects in `projects: [...]` with your own GitHub repos and live demo links.
3. **Achievements:**
   Add new certifications, hackathons, or awards to `achievements: [...]`.
4. **Skills:**
   Add, remove, or modify skills in `skills: [...]`.

---

## ☁️ Deploy to Vercel

### Option 1: Via Vercel CLI
```bash
npm i -g vercel
vercel
```

### Option 2: Via GitHub & Vercel Dashboard
1. Push this repository to GitHub.
2. Go to [vercel.com/new](https://vercel.com/new).
3. Import your GitHub repository.
4. Framework preset will automatically detect **Vite**.
5. Click **Deploy** — your portfolio is live in under 60 seconds!
