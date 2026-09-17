# GitHub Profile README Design Specification

- **Date:** 2026-09-17
- **Author:** Sheharyar Nadeem (@SheyBoiCarti)
- **Status:** Approved by User
- **Target File:** `README.md` in `SheyBoiCarti/SheyBoiCarti`

---

## 1. Overview & Objective

Transform the personal GitHub profile repository (`SheyBoiCarti/SheyBoiCarti`) into a modern, visually engaging, and tech-stack-focused profile. It highlights technical proficiencies, AI/ML expertise, backend/full-stack systems, featured projects, and GitHub metrics while intentionally omitting traditional workplace experience.

---

## 2. Structure & Sections

### 2.1. Header & Dynamic Intro
- **Greeting:** `Hi, I'm Sheharyar 👋` with center alignment.
- **Dynamic Typing Animation:** Using `readme-typing-svg` with high-contrast neon/cyan accents (`#00E5FF` / `#7928CA` or matching GitHub dark theme):
  - `"Software Developer & AI Engineer"`
  - `"AI/RAG, Scalable Backends & Full-Stack Systems"`
  - `"C++ | Python | C# | TypeScript | Rust/Go enthusiast"`
  - `"Building Intelligent, High-Performance Software"`
- **Technical Summary (Bullet Points):**
  - Focus on building intelligent applications, RAG pipelines, scalable APIs, and immersive software.
  - Core areas of interest: AI Engineering, Large Language Models, Distributed Backend Systems, and Game/XR Tech.
  - Active GitHub contributor open to open-source collaboration.

### 2.2. Tech Stack & Ecosystem (Badges)
Organized into themed categories using standardized `shields.io` badges with `style=for-the-badge` (or `flat-square` for dense elegance), branded logos, and clean hex colors:

1. **Programming Languages:**
   - Python, C#, C++, TypeScript, JavaScript, Java, SQL
2. **AI, Machine Learning & Data:**
   - PyTorch, LangChain, Llama 3 / NVIDIA AI, RAG, ChromaDB, TorchSharp, CNNs
3. **Backend & Frameworks:**
   - FastAPI, .NET / ASP.NET Core, Node.js, Express, GraphQL, REST APIs, OAuth 2.0
4. **Frontend & Mobile:**
   - Next.js, React, React Native, Tailwind CSS, Angular, HTML5/CSS3
5. **Databases & Cloud:**
   - PostgreSQL, Supabase, MongoDB, MySQL, Vector Search
6. **DevOps & Tooling:**
   - Docker, Git, GitHub Actions, Azure DevOps, Linux / Bash
7. **Game Dev & Spatial Tech:**
   - Unreal Engine 5, Unity, C++, ARCore

### 2.3. Featured Projects Showcase
A structured markdown table or clean card list presenting the technical implementation of flagship projects:
- **CVRAG:** Retrieval-Augmented Generation chatbot with semantic search, SSE streaming, per-session memory, and evaluation metrics (FastAPI, Next.js, LangChain, ChromaDB, Llama 3.3 70B, Docker).
- **CCTV Deep Learning Classifier:** End-to-end image classification pipeline with TorchSharp, CNNs, and ResNet reaching 92.52% accuracy.
- **PRIMED Dashboard:** Real-time analytics, automated team and review allocation platform (React, Supabase, Tailwind CSS).
- **UNI_FEVER:** Document management and repository system with AI chatbot integration (ASP.NET).

### 2.4. GitHub Analytics & Activity Cards
Center-aligned dark-mode widgets configured for user `SheyBoiCarti`:
- **GitHub Stats Card:** `github-readme-stats` with `theme=tokyonight` (or `radical`), showing total stars, commits, PRs, and issues.
- **Streak Card:** `github-readme-streak-stats` showing current and longest streaks.
- **Top Languages Card:** Visual breakdown of primary languages across repositories.

### 2.5. Connect & Social Links
Polished social badges linking to:
- **LinkedIn:** `https://linkedin.com/in/sheharyar-nadeem/`
- **Email:** `mailto:Sheharyarnadeem45@gmail.com`
- **GitHub:** `https://github.com/SheyBoiCarti`

---

## 3. Style & Quality Guidelines
- **Responsive & Centered:** Use semantic HTML wrappers (`<div align="center">`) where appropriate for headers, badges, and stats cards.
- **Dark Mode Friendly:** Ensure all badges and SVG cards render crisply on GitHub's dark and light backgrounds.
- **Zero Broken Links:** Verify all badge URLs, SVGs, and profile links are active and correctly formatted.
- **No External Work Experience:** Keep strictly to technologies, projects, engineering topics, and metrics.
