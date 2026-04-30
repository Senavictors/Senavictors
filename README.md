# Hi, I'm Victor Sena 👋

💻 Full Stack Developer at Allcom Telecom <br>
🎓 Degree in Systems Analysis and Development

🌐 [Access my Portfolio](https://portifolio-victor-sena.vercel.app/)

Backend Developer focused on PHP/Laravel with full-stack experience in Next.js and TypeScript. I specialize in developing REST APIs, transactional domain modeling, authentication, authorization, and complex business logic. In my personal projects, I have delivered a CRM with 9 operational fronts, a financial system with atomic transfers, a clinical SaaS for physiotherapists, and an open-source SVG widget engine for GitHub READMEs.

---

## 🚀 Projects

### [GitWidgets](https://github.com/gitwidgets-org/gitwidgets)
An open-source TypeScript engine to generate dynamic SVG widgets for GitHub READMEs (stats, streak, languages, activity graph), featuring a unified theme and hybrid delivery (API + GitHub Action).

`TypeScript` `Cloudflare Workers` `Hono` `Next.js 16`

- Public API + GitHub Action + dashboard with playground.
- Multi-layer caching (CDN → KV → D1) ensuring fast cached responses.
- Typed theme system (no hard-coded colors).
- Optimized GitHub API usage with ETag + token pooling.
- Smart fallback: always returns an SVG, never an error on the README.

---

### [Watch CRM](https://github.com/Senavictors/watch-crm)
Full-stack CRM to centralize catalog, orders, shipping, after-sales, and commercial goals for a watchmaking operation.

`Laravel 12` `Next.js 16` `MySQL` `Docker`

- 9 operational fronts consolidated into a single system.
- Multi-item orders with automatic total calculation and sales rep linking.
- 4 access roles with 50+ permissions, record-level policies, and ownership.
- After-sales module with warranties, exchanges, returns, and reshipping queue.
- Sales goals with catalog filters and real-time progress tracking.

---

### [Finance Controller](https://github.com/Senavictors/Finance-Controller)
Full-stack personal finance management system to centralize accounts, transactions, recurring bills, and analytics.

`Next.js 16` `TypeScript` `PostgreSQL` `Prisma 7` `Tailwind CSS`

- Layered architecture: Route Handlers → Use Cases → Domain Rules → Repositories.
- Atomic transfers between linked accounts via `transferId`.
- Recurring transactions with idempotent application and execution logs.
- Customizable dashboard with drag-and-drop and user-persisted layout.
- 25 route handlers covering auth, finance, analytics, and dashboard.

---

### [PhysioFlow](https://github.com/Senavictors/PhisioFlow)
A clinical management SaaS for physiotherapists that centralizes the entire workflow:
Registration → Consultation → Progress Notes → Documentation → Billing.

`Next.js 16` `TypeScript` `PostgreSQL` `Prisma` `Tailwind CSS` `Zod`

- Layered multi-tenant architecture (UI → Route Handlers → Use Cases → Domain → Repositories) with total isolation via `userId` in all queries.
- SOAP notes, evolution timeline, and on-demand PDF report generation via `@react-pdf/renderer`.
- Clinical multi-modality: treatment plans by area/specialty with single or package billing.
- Integrated finance: payments with `expectedFee` snapshots, received vs. projected dashboard, time series, and breakdowns by location/area.
- Native integrations: Gmail (App Password with AES-256-GCM) for notifications/reports and Google Calendar (OAuth) with session sync.

---

## 📊 GitHub Stats

<table align="center">
  <tr>
    <td align="center">
      <img width="95%" src="https://github-readme-stats.vercel.app/api?username=senavictors&show_icons=true&theme=tokyonight" />
    </td>
    <td align="center">
      <img width="95%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=senavictors&layout=compact&theme=tokyonight" />
    </td>
    <td align="center">
      <img width="95%" src="https://streak-stats.demolab.com?user=senavictors&theme=tokyonight&locale=en" />
    </td>
  </tr>
</table>

## 🛠️ Main Stack

### **Backend**
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)&nbsp;
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)&nbsp;
![Python](https://img.shields.io/badge/python-3670A0?logo=python&logoColor=ffdd54&style=for-the-badge)&nbsp;
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)&nbsp;
![Hono](https://img.shields.io/badge/Hono-E36002?style=for-the-badge&logo=hono&logoColor=white)&nbsp;

### **Frontend**
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)&nbsp;
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)&nbsp;
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)&nbsp;
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)&nbsp;

### **Database & DevOps**
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)&nbsp;
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)&nbsp;
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)&nbsp;
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)&nbsp;
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)&nbsp;

---

## 📫 Contact Me

<div>
  <a href="https://www.linkedin.com/in/senavictors/" target="_blank">
    <img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white">
  </a>
  <a href="mailto:victorsena760@gmail.com">
    <img src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white">
  </a>
  <a href="https://www.instagram.com/senavictors" target="_blank">
    <img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white">
  </a>
</div>
