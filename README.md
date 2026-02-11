<div align="center">
  <h1>Hi there, I'm Atakan Bıyıkoğlu 👋</h1>
  <h3>Backend & AI Developer</h3>
  <p>Building scalable web architectures, AI-integrated automations, and secure database systems.</p>
  
  <a href="https://linkedin.com/in/atakanbiyikoglu">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin" alt="LinkedIn" />
  </a>
  <a href="mailto:atakanbiyikoglu.dev@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact_Me-c14438?style=for-the-badge&logo=gmail" alt="Email" />
  </a>
</div>

<br />

### 🚀 About Me
I am a developer focused on **Node.js & Python** ecosystems. I specialize in modernizing legacy infrastructures, designing relational database schemas (PostgreSQL), and integrating LLMs (OpenAI, Claude) into real-world applications without over-engineering.

- 🔭 I’m currently working on **AI-Assisted SaaS Platforms**.
- ⚡ **Core Philosophy:** "Clean code, scalable database, reliable API."

<br />

### 🛠️ Technical Arsenal

| Domain | Technologies |
| :--- | :--- |
| **Backend** | ![NodeJS](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) ![Express](https://img.shields.io/badge/Express.js-000000?style=flat&logo=express&logoColor=white) |
| **AI Integrations** | ![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white) ![Claude](https://img.shields.io/badge/Anthropic_Claude-D97757?style=flat&logo=anthropic&logoColor=white) ![Gemini](https://img.shields.io/badge/Google%20Gemini-8E75B2?style=flat&logo=googlegemini&logoColor=white) |
| **Database** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat&logo=postgresql&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat&logo=supabase&logoColor=white) ![Neon](https://img.shields.io/badge/Neon-00E599?style=flat&logo=postgresql&logoColor=black) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white) |
| **Tools & ORM** | ![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat&logo=prisma&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white) ![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat&logo=vercel&logoColor=white) ![n8n](https://img.shields.io/badge/n8n-FF6584?style=flat&logo=n8n&logoColor=white) |

<br />

### 💼 Engineering Experience

#### 1. Ashera - Legacy System Modernization (Private Repo)
*Revived a legacy codebase with no documentation and transformed it into a production-ready platform.*

* **Infrastructure Recovery:** The production database was missing. I reverse-engineered the data structure solely from **Prisma ORM** schema definitions and re-initialized a **PostgreSQL (Neon)** instance.
* **CI/CD Pipeline:** Replaced manual processes with an automated deployment pipeline connecting **GitHub** to **Vercel**, managing environment secrets and domain configurations.
* **Cost Optimization:** Designed a pre-processing logic that summarizes user inputs before sending them to the AI model, reducing token consumption.
* **Security:** Engineered an **idempotent verification flow** and rate limiting to prevent bot spam during user registration.

#### 2. Badi (Diyojen) - AI Chatbot & Automation SaaS
*A multi-tenant AI assistant platform for enterprise clients.*

* **Fault-Tolerant AI System:** Built a **3-layer fallback system** that automatically switches providers (**Gemini → OpenAI → DeepSeek**) in case of API outages to ensure uptime.
* **Embeddable Widget:** Developed a lightweight `chatbubble.js` widget using **Shadow DOM**, allowing clients to inject the chatbot into any website without CSS conflicts.
* **Database Security (RLS):** Implemented **PostgreSQL Row Level Security (RLS)** policies on Supabase to securely isolate User, Partner, and Admin data.
* **Document AI (File Search):** Integrated **OpenAI Assistants API (File Search)** to allow users to upload PDF/Docx files, enabling the chatbot to answer questions based on custom knowledge bases.
* **Automation:** Connected the platform to **n8n** workflows for cross-platform messaging and task automation (WhatsApp/Instagram).

<br />

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=atakanbiyikoglu&show_icons=true&theme=dark&hide_border=true&bg_color=000000" alt="Atakan's GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=atakanbiyikoglu&layout=compact&theme=dark&hide_border=true&bg_color=000000" alt="Top Languages" />
</div>
