# Olá, eu sou o Victor Sena 👋

💻 Desenvolvedor Full Stack na Allcom Telecom <br>
🎓 Formado em Análise e Desenvolvimento de Sistemas

🌐 [Acesse meu Portifolio](https://portifolio-victor-sena.vercel.app/)

Desenvolvedor Backend com foco em PHP/Laravel e experiência full stack com Next.js e TypeScript. Atuo no desenvolvimento de APIs REST, modelagem de domínios transacionais, autenticação, autorização e regras de negócio. Nos projetos pessoais, entreguei um CRM com 9 frentes operacionais, um sistema financeiro com transferências atômicas, um SaaS clínico para fisioterapeutas e um engine open-source de SVG widgets para GitHub READMEs.

---

## 🚀 Projetos


### [GitWidgets](https://github.com/gitwidgets-org/gitwidgets)
Engine open-source em TypeScript para gerar widgets SVG dinâmicos em READMEs do GitHub (stats, streak, linguagens, activity graph), com tema unificado e entrega híbrida (API + GitHub Action).

`TypeScript` `Cloudflare Workers` `Hono` `Next.js 16`

- API pública + GitHub Action + dashboard com playground
- Cache multi-layer (CDN → KV → D1) com respostas rápidas em cache
- Sistema de temas tipado (sem cores hard-coded)
- Uso otimizado da API do GitHub com ETag + pool de tokens
- Fallback inteligente: sempre retorna SVG, nunca erro no README

---

### [Watch CRM](https://github.com/Senavictors/watch-crm)
CRM full stack para centralizar catálogo, pedidos, envios, pós-venda e metas comerciais de uma operação de relojoaria.

`Laravel 12` `Next.js 16` `MySQL` `Docker`

- 9 frentes operacionais consolidadas em um único sistema
- Pedidos multi-itens com cálculo automático de totais e vínculo por vendedor
- 4 papéis de acesso com 50+ permissões, policies por registro e ownership
- Pós-venda com garantias, trocas, devoluções e fila de reenvio
- Metas de vendas com filtros por catálogo e progresso em tempo real

---

### [Finance Controller](https://github.com/Senavictors/Finance-Controller)
Sistema full stack de gestão financeira pessoal para centralizar contas, transações, recorrências e analytics.

`Next.js 16` `TypeScript` `PostgreSQL` `Prisma 7` `Tailwind CSS`

- Arquitetura em camadas: Route Handlers → Use Cases → Domain Rules → Repositories
- Transferências atômicas entre contas vinculadas por transferId
- Recorrências com apply idempotente e logs de execução
- Dashboard customizável com drag-and-drop e layout persistido por usuário
- 25 route handlers cobrindo autenticação, finanças, analytics e dashboard

---

### [PhysioFlow](https://github.com/Senavictors/PhisioFlow)
SaaS de gestão clínica para fisioterapeutas que centraliza todo o fluxo
Cadastro → Atendimento → Evolução → Documentação → Cobrança.

`Next.js 16` `TypeScript` `PostgreSQL` `Prisma` `Tailwind CSS` `Zod`

- Arquitetura multi-tenant em camadas (UI → Route Handlers → Use Cases → Domain → Repositories) com isolamento total por `userId` em todas as queries
- Registro SOAP, timeline de evolução e geração on-demand de laudos PDF via `@react-pdf/renderer`
- Multi-modalidade clínica: planos de tratamento por área/especialidade com cobrança avulsa ou em pacote
- Financeiro integrado: pagamentos com snapshot `expectedFee`, dashboard de recebido vs previsto, série temporal e quebras por local/área
- Integrações nativas: Gmail (App Password com AES-256-GCM) para envio de avisos/laudos e Google Calendar (OAuth) com sync por sessão

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
      <img width="95%" src="https://streak-stats.demolab.com?user=senavictors&theme=tokyonight&locale=pt_BR" />
    </td>
  </tr>
</table>

## 🛠️ Principais Tecnologias

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

### **Banco de Dados & DevOps**
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)&nbsp;
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)&nbsp;
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)&nbsp;
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)&nbsp;
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)&nbsp;

---

## 📫 Contato

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
