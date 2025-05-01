
# 👨‍💻 Jaya Krishna Sri — Portfolio Website

This repository contains the **source code for my personal portfolio website**, created to highlight my technical expertise, projects, and career journey as a **Generative AI Engineer**.

> 🛠️ This code was **generated using the Lovable application** and deployed using **Vercel**.

### 🔗 Live Demo  
🌐 [Visit Portfolio](https://sorting-visualizer-kgz8.onrender.com)

---

## 📁 Website Sections

- **Home** – Introduction and quick overview  
- **Skills** – Technologies and tools I’m proficient in  
- **Work** – Highlights of projects and accomplishments  
- **Experience** – Summary of my professional journey  
- **Information** – Contact info and background  
- **Resume** – Downloadable or viewable resume  
- **Portfolio** – My curated set of works  

---

## 🙋‍♂️ About Me

**Hello, I'm Jaya Krishna Sri**  
A passionate and creative **Generative AI Engineer** with hands-on experience in developing intelligent applications and tools. I specialize in:

- Building LLM-powered solutions with LangGraph and LangChain  
- Designing Retrieval-Augmented Generation (RAG) pipelines  
- Developing fast, scalable APIs using FastAPI  
- Creating elegant frontends using React + Vite  

I'm driven by the desire to make AI approachable and impactful in real-world use cases.

---

## ⚙️ Tech Stack Used

- ⚛️ **React** (built with Vite)  
- 🎨 **Tailwind CSS** (utility-first CSS framework)  
- 🧩 **Lovable** (for generating the project structure and components)  
- 🚀 **Vercel** (for hosting and deployment)  

---

## 🛠️ Local Development Setup

```bash
# 1. Create a Vite-powered React project
npm create vite@latest my-portfolio -- --template react
cd my-portfolio

# 2. Install dependencies
npm install

# 3. Add Tailwind CSS
npm install -D tailwindcss @tailwindcss/vite

# 4. Configure Tailwind + Vite in vite.config.js
import { defineConfig } from "vite";
import react from "@vitejs/plugin-react";
import tailwind from "@tailwindcss/vite";

export default defineConfig({
  plugins: [react(), tailwind()],
});

# 5. Setup Tailwind in your CSS
@import "tailwindcss";
html { scroll-behavior: smooth; }

# 6. Run your dev server
npm run dev
```

---

## 🌍 Deployment

This portfolio website is deployed using **Vercel**, ensuring fast, global delivery with zero-config continuous deployment.

---

## 📌 Purpose

This portfolio serves as a dynamic representation of my professional identity and technical capabilities. It’s designed not only to showcase my work but also to demonstrate real-world application of frontend technologies and deployment strategies.
