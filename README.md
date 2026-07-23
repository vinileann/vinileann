<h1 align="center">Olá! Eu sou o Vinicius Leandro 👋</h1>

<p align="center">
  Desenvolvedor full-stack — construo produtos de ponta a ponta: front, back serverless,
  banco com segurança em nível de linha e a regra de negócio num pacote só.
</p>

---

## 🔭 O que estou construindo agora

Plataforma de **educação médica** (repos privados): um **portal do aluno** e um **app de gestão**
que compartilham a mesma regra de negócio através de um **pacote de domínio puro em TypeScript**
(versionado com SemVer + changelog) — *uma regra, um lugar*.

- 🧱 **Arquitetura**: 2 apps React + NestJS (serverless na Vercel) · pacote de domínio compartilhado
- 🔐 **Dados**: PostgreSQL com **Row-Level Security** e particionamento · **Redis** com invalidação de cache cruzada entre os apps
- 🔌 **Integrações**: webservices REST/SOAP de ERP acadêmico, pagamentos (PIX/cartão), geocodificação
- 🕵️ **Observabilidade**: access log completo com redação de dados sensíveis (LGPD)
- 🚀 Minha startup: [SmartBid](https://smartbid.tech/)

## 🛠️ Ferramentas e tecnologias do trabalho

**Linguagens**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)

**Web — HTML & CSS**

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

**🤖 IA & Agentes de código**

![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=for-the-badge&logo=claude&logoColor=white)
![Codex](https://img.shields.io/badge/Codex-000000?style=for-the-badge&logo=openai&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Angular](https://img.shields.io/badge/Angular_17+-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Radix UI](https://img.shields.io/badge/Radix_UI-161618?style=for-the-badge&logo=radixui&logoColor=white)
![shadcn/ui](https://img.shields.io/badge/shadcn/ui-000000?style=for-the-badge&logo=shadcnui&logoColor=white)

**Backend & Integrações**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)
![Vercel](https://img.shields.io/badge/Serverless_·_Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![REST/SOAP](https://img.shields.io/badge/APIs_REST_·_SOAP-5A29E4?style=for-the-badge&logo=postman&logoColor=white)

**Bancos & Cache**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL_(RLS)-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase_·_Firestore-DD2C00?style=for-the-badge&logo=firebase&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

**Testes & Qualidade**

![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=for-the-badge&logo=vitest&logoColor=white)
![Jest](https://img.shields.io/badge/Jest-C21325?style=for-the-badge&logo=jest&logoColor=white)
![Testing Library](https://img.shields.io/badge/Testing_Library-E33332?style=for-the-badge&logo=testinglibrary&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

**Fundamentos (nível inicial)**

![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)

## ⚙️ Como eu trabalho

- **Entendo o problema antes da solução** — converso com quem usa, mapeio o fluxo real e só depois desenho a arquitetura;
- **Planejo antes de codar** — todo projeto começa com um documento de planejamento (veja a seção abaixo), que vira o contrato do que será entregue;
- **Domínio no centro** — a regra de negócio vive num pacote puro e testado; apps são camadas finas em volta dela;
- **TDD onde importa** — política nova nasce com teste antes do código, principalmente no domínio e nas integrações críticas;
- **IA como par de trabalho** — uso Claude Code e Codex no dia a dia para acelerar implementação, revisão e refatoração, mantendo a decisão de arquitetura comigo;
- **Privacidade por padrão** — RLS no banco, redação de dado sensível em log e LGPD desde o design, não como remendo.

## 🗺️ Como eu planejo um projeto

Antes de qualquer commit, escrevo um **documento de planejamento** da plataforma/projeto
(ex.: `PLATAFORMA_LM.html` no domínio da plataforma de educação médica), que cobre:

- **Visão & escopo** — o problema, quem usa, o que entra e o que explicitamente fica de fora;
- **Arquitetura & contratos** — diagrama dos apps, do pacote de domínio e das integrações; toda mudança que cruza apps vira um *plano por app* antes do código;
- **Modelo de dados** — entidades, relacionamentos, particionamento e políticas de RLS definidos junto com o domínio;
- **Fases & entregas** — quebra em versões incrementais (SemVer), cada uma com critérios de aceite claros;
- **Riscos & dependências** — integrações externas (ERP, pagamentos), pontos de falha e plano B;
- **Rastreabilidade** — changelog do que mudou e por quê, ligando decisão → versão → código.

> O documento é vivo: evolui junto com o projeto e serve de fonte única de verdade para o time (e para os agentes de IA que trabalham comigo).

## 📊 GitHub

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=vinileann&show_icons=true&count_private=true&locale=pt-br" alt="Estatísticas do GitHub" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=vinileann&layout=compact&locale=pt-br" alt="Linguagens mais usadas" />
</p>

## 📫 Contato

- ✉️ vinileann@gmail.com
- 💼 [LinkedIn](https://www.linkedin.com/in/vinicius-leandro-37b5102a9/)
- 🚀 [SmartBid](https://smartbid.tech/)
