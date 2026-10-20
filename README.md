# Hi, I'm Arpit 👋

**AI developer** · Computer Science Engineering student at Guru Gobind Singh Indraprastha University (IPU), Delhi

I build LLM applications that run in production: agents, retrieval (RAG) and document AI, with deterministic checks and evaluation sets so I can show how accurate a model's output is, not just that it works in a demo.

I'm looking for **AI / ML engineering and full stack AI internships**.

## 🚀 Featured project

### [InvoiceIQ](https://github.com/arpittts/invoiceiq): an AI agent for Indian GST invoices

Reads invoice photos, scans and PDFs with a vision LLM, validates every field with deterministic GST rules, suggests HSN/SAC codes via hybrid RAG over 22,609 official codes, routes doubtful invoices to human review, answers ledger questions in plain English through guarded text-to-SQL, and reconciles books against the GST portal's GSTR-2B.

- **LangGraph agent** that re-reads only the fields that fail a check, within a token and cost budget
- **Hybrid retrieval**: pgvector (HNSW) + Postgres full-text, fused with reciprocal rank fusion
- **Evaluation in CI**: 60-invoice held-out test set, **99.8% field accuracy**, **100% auto-approve precision**, 98.1% of injected misreads caught, 8/8 adversarial SQL prompts blocked
- **MCP server** that exposes the same services as tools for Claude and other MCP clients
- Runs entirely on free tiers: FastAPI on Render, Postgres on Neon, React on Vercel, Gemini

🔗 [Live demo](https://invoiceiq-teal.vercel.app) · [Releases](https://github.com/arpittts/invoiceiq/releases) · `Python` `FastAPI` `LangGraph` `pgvector` `React` `TypeScript`

## 🛠 Other projects

**[HireBoard](https://github.com/arpittts/hireboard)**: job and internship tracker with a drag-and-drop Kanban board, analytics dashboard, JWT auth and email follow-up reminders. React, Node.js, Express, PostgreSQL. 🔗 [Live demo](https://hireboard-mu.vercel.app)

**[Aether Weather](https://github.com/arpittts/weather-app)**: React 19 weather dashboard on the OpenWeatherMap API with geolocation, 5-day forecasts, city-local times and saved cities. 🔗 [Live demo](https://weather-app-nine-black-40.vercel.app)

## 🧰 Tech stack

**AI / LLM:** LangGraph, RAG, pgvector, embeddings (fastembed), structured output, text-to-SQL, MCP, LLM evaluation, Gemini and Claude APIs, Langfuse  
**Languages:** Python, TypeScript, JavaScript, SQL, Java  
**Backend:** FastAPI, Pydantic, SQLAlchemy, Alembic, Node.js, Express, REST APIs, JWT auth  
**Frontend:** React, Vite, Tailwind CSS, TanStack Query  
**Data:** PostgreSQL, pgvector, MySQL  
**Tools:** Git, GitHub Actions, Docker, pytest, Vercel, Render, Neon

## 📚 Relevant coursework

Database Management Systems · Data Structures & Algorithms · Statistics & Probability · Computer Networks · Object-Oriented Programming (Java) · Theory of Computation

## 📫 Reach me

[LinkedIn](https://www.linkedin.com/in/arpitsingh14/) · [arpit.singh1485@gmail.com](mailto:arpit.singh1485@gmail.com)
