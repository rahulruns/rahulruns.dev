# rahulruns.dev — Personal Developer Portfolio

This is the source code for my personal website **rahulruns.dev** — a modern developer portfolio showcasing my work in **AI Engineering, Automation, Python Development, FastAPI, LangChain, and LangGraph**.

The site is built with **Next.js**, styled with **Tailwind CSS**, and deployed on **Vercel**.  
It features my projects, experience, skills, and professional profile.

---

## 🚀 Tech Stack

- **Next.js (App Router)**
- **TypeScript**
- **Tailwind CSS**
- **Vercel Deployment**
- **Server & Client Components**

---

## 📁 Project Structure

```
rahulruns.dev/
├── app/
│   ├── layout.tsx
│   ├── page.tsx                  # Home page
│   ├── about/page.tsx            # About Me
│   ├── projects/page.tsx         # Featured Projects
│   ├── contact/page.tsx          # Contact Section
│   └── components/
│       ├── Nav.tsx
│       ├── Footer.tsx
│       └── ProjectCard.tsx
├── public/
│   └── images/                   # Profile + project screenshots
├── styles/
│   └── globals.css
├── LICENSE
├── package.json
└── README.md
```

---

## 🧪 Branching Strategy

This repo uses a professional Git branching workflow:

- `main` → Production (Vercel deploys from this branch)  
- `dev` → Integration / Staging  
- `feature/*` → Feature branches for individual site sections

Example:

```
feature/initial-structure
feature/home-hero
feature/about-section
feature/projects-page
```

---

## 🔧 Running Locally

```bash
git clone https://github.com/YOUR_USERNAME/rahulruns.dev
cd rahulruns.dev
npm install
npm run dev
# open http://localhost:3000
```

---

## 🌐 Deployment

This site is deployed on **Vercel**.

### Production  
Anything merged into `main` automatically goes live at:

👉 **https://rahulruns.dev**

### Preview  
All other branches (e.g., `dev`, `feature/*`) receive automatic preview deployments.

---

## 📬 Contact

You can reach me at:

- **LinkedIn:** https://www.linkedin.com/in/rahulranjan  
- **GitHub:** https://github.com/YOUR_USERNAME  
- **Email:** YOUR_EMAIL  

---

## 📄 License

This project is licensed under the **MIT License**.
