<div align="center">
  <h1>Hi there, I'm Atakan Bıyıkoğlu 👋</h1>
  <h3>Backend & AI Developer</h3>
  <p>Architecting scalable microservices, fault-tolerant AI agents, and secure SaaS infrastructures.</p>
  
  <a href="https://linkedin.com/in/atakanbiyikoglu">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin" alt="LinkedIn" />
  </a>
  <a href="mailto:atakanbiyikoglu.dev@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact_Me-c14438?style=for-the-badge&logo=gmail" alt="Email" />
  </a>
</div>

<br />

### 🚀 About Me
I am a developer focused on bridging the gap between **Robust Backend Systems** and **Generative AI**. I specialize in reverse-engineering legacy systems, designing multi-tenant databases, and building resilient AI pipelines that don't break under pressure.

- 🔭 I’m currently working on **Enterprise RAG Systems & Microservices**.
- ⚡ **Core Philosophy:** "If it's not scalable, it's not finished."

<br />

### 🛠️ Technical Arsenal

| Domain | Technologies |
| :--- | :--- |
| **Backend** | ![NodeJS](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white) |
| **AI & ML** | ![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white) ![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=chainlink&logoColor=white) ![Gemini](https://img.shields.io/badge/Google%20Gemini-8E75B2?style=flat&logo=googlegemini&logoColor=white) ![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=flat&logo=pinecone&logoColor=white) |
| **Data & Infra** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat&logo=postgresql&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat&logo=supabase&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white) |
| **Tools** | ![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white) ![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat&logo=vercel&logoColor=white) ![n8n](https://img.shields.io/badge/n8n-FF6584?style=flat&logo=n8n&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black) |

<br />

### 💼 Engineering Experience (Key Projects)

#### 1. Ashera - Legacy Infrastructure Modernization (Private Repo)
*Revived a dormant, undocumented legacy codebase and transformed it into a production-ready SaaS platform.*

* **Infrastructure Recovery (Reverse Engineering):** The production database was missing. I reverse-engineered the entire data schema solely from **Prisma ORM** definitions and re-initialized a scalable **PostgreSQL (Neon)** instance with zero data loss concepts.
* **DevOps & Automated CI/CD:** Replaced manual deployments with a fully automated pipeline using **GitHub Actions** and **Vercel**, managing environment secrets and domain DNS configurations from scratch.
* **Cost-Optimized AI Architecture:** Designed a pre-processing middleware that summarizes user prompts before sending them to the LLM. This strategy significantly reduced token consumption costs and latency.
* **Security & Anti-Abuse:** Engineered an **idempotent verification flow** and IP-based rate limiting to prevent bot spam, securing the authentication process without compromising UX.

#### 2. Badi (Diyojen) - AI Chatbot SaaS & Widget Architecture
*A multi-tenant, embeddable AI assistant platform for enterprise clients.*

* **Fault-Tolerant AI Orchestration:** Built a robust **3-layer fallback system** that automatically switches providers (**Gemini → OpenAI → DeepSeek**) in case of API outages, ensuring 99.9% service uptime.
* **Embeddable Widget (Shadow DOM):** Developed a lightweight `chatbubble.js` widget using **Shadow DOM** for style isolation, allowing clients to inject the chatbot into any website with a single line of code without CSS conflicts.
* **Database Security (RLS):** Implemented **PostgreSQL Row Level Security (RLS)** policies and SQL Triggers on Supabase to strictly isolate User, Partner, and Admin data in a complex multi-tenant schema.
* **RAG Pipeline:** Architected the document ingestion service that chunks PDF/Docx files, generates vector embeddings, and executes semantic search for custom-trained bots.
* **Performance Engineering:** Managed the migration to **Next.js 15**, optimizing bundle sizes by downgrading React versions (19 to 18) for stability and implementing Shadcn/ui for a high-performance UI.

<br />

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=atakanbiyikoglu&show_icons=true&theme=dark&hide_border=true&bg_color=000000" alt="Atakan's GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=atakanbiyikoglu&layout=compact&theme=dark&hide_border=true&bg_color=000000" alt="Top Languages" />
</div>
