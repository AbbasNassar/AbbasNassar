<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=280&section=header&text=Hi%20there%20👋&fontSize=90&fontAlignY=35" alt="Header" />
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=AbbasNassar&label=Profile%20Views&color=0e75b6&style=flat-square&logo=github" alt="Profile Views" />
</p>

<h1 align="center">👋 Hello, I'm Abbas Nassar</h1>

<p align="center">
  <em>Backend Developer & IoT Enthusiast building scalable and efficient systems.</em>
</p>

---

## 🚀 About Me

- 💻 Passionate about **Backend Development**, **System Architecture**, and **IoT**
- 🤖 Passionate about **automation and workflow engineering** using **n8n**
- 🔄 I enjoy turning repetitive tasks into automated, reliable workflows
- 🧑‍💻 Proud **vibe coder** — I build, experiment, break things, and figure them out along the way
- 📚 Constantly learning and improving my skills in Software Engineering
- 🧠 Interested in scalable systems, APIs, databases, queues, and automation
- 📫 Reach me at **abbasnassar212@gmail.com**
- ⚡ The sky is the limit fr

---

## 🌐 Connect with Me

<p align="left">
  <a href="https://linkedin.com/in/abbas-nassar-581277274" target="_blank">
    <img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="LinkedIn" height="40" width="50" />
  </a>
</p>

---

## 🛠️ Languages & Tools

<p align="left">
  <a href="https://www.cprogramming.com/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="C" width="50" height="50" /></a>
  <a href="https://www.w3schools.com/cpp/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="C++" width="50" height="50" /></a>
  <a href="https://www.java.com" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="Java" width="50" height="50" /></a>
  <a href="https://www.python.org" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="Python" width="50" height="50" /></a>
  <a href="https://www.mysql.com/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="MySQL" width="50" height="50" /></a>
  <a href="https://www.w3.org/html/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="HTML" width="50" height="50" /></a>
  <a href="https://www.w3schools.com/css/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="CSS" width="50" height="50" /></a>
  <a href="https://n8n.io/" target="_blank"><img src="https://cdn.simpleicons.org/n8n/EA4B71" alt="n8n" width="50" height="50" /></a>
</p>

---

## 🤖 Automation & n8n

One of the things I'm especially passionate about is **automation**.

I enjoy using **n8n** to connect services, automate repetitive processes, and build workflows that allow systems to work together with minimal manual intervention.

### What I Like Building with Automation

- 🔄 Automated workflows between APIs and services
- 📧 Automated email notifications and processing
- 💬 WhatsApp and messaging automations
- 🗄️ Database-driven workflows
- 🔔 Event-based notifications
- 🌐 API integrations
- ⚙️ Background processes and scheduled jobs
- 🤖 AI-powered automation workflows
- 📊 Data processing and synchronization

> If a computer can reliably do it for me, I probably want to automate it. ⚡

---

## 🏗️ Current Project Architecture

I'm currently building a **full-stack application** using a **monorepo architecture** with a focus on scalability, type safety, clean separation of concerns, and automation.

### 📦 Monorepo

- 📁 Plain **npm workspaces** for managing the entire project
- 🔗 Shared packages allow the frontend and backend to use the same validation schemas, enums, and permissions

```text
├── apps/
│   ├── api/          # NestJS backend
│   └── web/          # Next.js frontend
│
├── packages/
│   └── types/        # Shared types, schemas & permissions
│
└── package.json      # npm workspaces
```

### ⚙️ Backend — `apps/api`

- 🚀 **NestJS** for the backend API
- 🗄️ **Prisma** as the ORM
- 🐘 **PostgreSQL** as the primary database
- ⚡ **Redis** for caching
- 🔄 **BullMQ** for notification job queues

### 🌐 Frontend — `apps/web`

- ⚡ **Next.js 15** with the App Router
- 🛍️ One application powering both the **storefront** and **admin dashboard**
- 🎨 **Tailwind CSS** for styling
- 🌍 **next-intl** for internationalization
- 🇸🇦 Arabic + 🇬🇧 English support
- ↔️ Full **RTL** support for Arabic

### 📦 Shared Code — `packages/types`

Shared code between the API and web application:

- ✅ **Zod** validation schemas
- 🔢 Shared enums
- 🔐 Centralized permission list
- 🔄 Consistent validation and types across the stack

### 🐳 Infrastructure

Development infrastructure runs with **Docker**:

- 🐘 PostgreSQL
- ⚡ Redis
- 🪣 **MinIO** for local image/object storage

Production image storage is planned to use **Cloudflare R2**.

### 🔌 External Services

- 📧 **Resend** for email delivery
- 💬 **Meta WhatsApp Cloud API** for WhatsApp messaging
- 🤖 **n8n** for workflow automation and service integrations
- 🔒 External services are disabled by default in development where applicable

### 🧪 Testing

- ⚡ **Vitest** for API testing
- 🧪 Unit tests
- 🔄 End-to-end tests
- 🗄️ Tests run against a separate test database

---

## 💡 Fun Facts

- 🔥 I love working on backend systems and algorithmic problems
- 🤖 I love finding ways to automate repetitive work with n8n
- 🧑‍💻 I'm a vibe coder — ideas first, implementation second, debugging third 😎
- 🏗️ I enjoy designing APIs, databases, queues, and scalable architectures
- 🌍 I like building applications that work across Arabic and English
- ⚡ I believe good automation can turn complicated workflows into simple ones
- 🎯 My goal is to become a top-notch backend engineer

---

## 🎯 Projects & Repositories

### 🐦 X (Twitter) Clone
Backend-focused implementation exploring APIs, architecture, authentication, and core social-media functionality.

### 🍽️ Restaurant Cashier System
A desktop point-of-sale system built with **Java & JavaFX**.

### 🛒 E-Commerce Course Website
A frontend e-commerce project built with **HTML, CSS, and JavaScript**.

### 🚀 Current Full-Stack Project
A scalable monorepo application featuring:

| Area | Technologies |
|---|---|
| Backend | NestJS · Prisma · PostgreSQL |
| Frontend | Next.js 15 · App Router · Tailwind CSS |
| Queues & Cache | Redis · BullMQ |
| Infrastructure | Docker · MinIO |
| Shared | Zod shared schemas |
| Localization | Arabic & English · RTL support |
| Integrations | Resend · WhatsApp Cloud API · n8n |
| Testing | Vitest |

📌 Check out more projects on my [GitHub Repositories](https://github.com/AbbasNassar?tab=repositories)!

---

## ⚡ What I'm Into

```text
Backend Engineering     ████████████████████
System Architecture     ██████████████████
Automation / n8n        ███████████████████
IoT                     ███████████████
APIs & Integrations     ███████████████████
Databases               █████████████████
Vibe Coding             ████████████████████
```

---

<p align="center">
  ⭐ <em>Keep coding, keep learning, automate everything you can, and never stop exploring!</em> 🚀
</p>

<p align="center">
  <em>Built with code, automation, caffeine, and a little bit of vibe coding.</em> ☕🤖💻
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=150&section=footer" alt="Footer" />
</p>
