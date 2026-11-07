# Hi, I'm Cheng-Peng

**AI Engineer** building agentic systems, LLM tooling, and computer vision models.<br>
M.S. in Computer Science @ NTUST (GPA 4.0) · Based in Taipei · **Open to relocating to the U.S.**

[LinkedIn](https://www.linkedin.com/in/cheng-peng-huang) · [Email](mailto:chengpong1127@gmail.com)

---

## Highlights

### Via: Multimodal Journey Planner · [`chengpong1127/Via`](https://github.com/chengpong1127/Via)
Plans door-to-door trips across Taiwan by combining **public transit, bike-share, and walking**, with a Rust routing server and an iOS app.
- Two-phase routing: a **RAPTOR-style round-based transit search** finds candidate corridors, then each is evaluated against **realtime transit timing and live bike-share availability**
- Builds its transit network from GTFS data, pulls realtime data from TDX, and uses **Valhalla** for street routing
- `Rust` `iOS` `GTFS` `Valhalla` `RAPTOR`

### Mindify AI: Contextual Ads for AI Agents · *Technical Co-Founder*
Designed the ad-serving system from scratch. It uses conversation context and user intent to retrieve and rank ads by predicted performance and advertiser bids.
- Built the backend: campaign budgeting, a **double-entry ledger**, publisher settlement, and **Stripe payments and payouts**, running as stateless services
- Launched **10+ live ads reaching 100+ users** on the Cortex agent platform
- `TypeScript` `NestJS` `Fastify` `PostgreSQL` `Redis` `Stripe` `Terraform` `GCP`

### Generalizable AI-Generated Image Detection · *Master's thesis, paper under review*
End-to-end deep learning research at **Academia Sinica**: data processing, model training, and rigorous evaluation.
- **92.2% average accuracy**, state-of-the-art across **6 public and in-the-wild benchmarks**, with strong cross-generator generalization
- `PyTorch` `DINOv3` `Vision Transformers` `LoRA` `Contrastive Learning`
- *Code will be released after publication.*

### CURA: Agentic Software Engineering System · [`mindify-ai/CURA`](https://github.com/mindify-ai/CURA)
A test-driven coding agent built in LangGraph. It **writes tests before fixing code**, runs them in **Docker sandboxes**, and **replans when tests fail**.
- Repository-aware retrieval improved GPT-4o-mini issue resolution by **+5 percentage points on SWE-bench Verified**
- `Python` `LangGraph` `LangChain` `ReAct` `RAG` `Chroma` `Docker`

### Conversational Analytics Assistant · *Data Scientist Intern @ Taboola, Los Angeles*
Built a chat-based analytics assistant for Sales and Account Management, with **5 AI workflows** that turn ad data into insights and automated reports.
- Integrated DataHub semantic metadata into an internal database **MCP** tool for more accurate LLM-driven data retrieval
- `Python` `OpenAI Agents SDK` `MCP` `PostgreSQL` `Kubernetes`

### NTUAI Club Website · [ntuai.dev](https://ntuai.dev/)
Full-stack site built from scratch for **100+ members**, with **600+ monthly visitors** and **4K+ monthly page views**. A CMS with **MCP integration** lets AI agents manage content.
- `Next.js` `React` `Payload CMS` `Playwright` `Tailwind CSS` `Vercel`

### GPA-Extension: Course GPA Insights for NTUST · [`chengpong1127/GPA-Extension`](https://github.com/chengpong1127/GPA-Extension)
Chrome extension that adds historical GPA stats and grade histograms to NTUST's course search page, helping students pick courses.
- Published on the Chrome Web Store with **250+ users**
- `JavaScript` `Chrome Extension` `Vite` `Tailwind CSS`

---

## Open-source projects

| Project | What it does |
|---|---|
| [**arc**](https://github.com/chengpong1127/arc) | One command for a working NVIDIA GPU environment (Rust CLI) |
| [**MyTorch**](https://github.com/chengpong1127/MyTorch) | A PyTorch-like deep learning framework with autograd, built from scratch in NumPy |
---

## Tech stack

- **Languages:** Python · TypeScript · JavaScript · SQL · Rust
- **AI/ML:** PyTorch · Computer Vision · Vision Transformers · LLMs · RAG · AI Agents · LangGraph · MCP
- **Backend & Infra:** Next.js · PostgreSQL · Redis · Docker · Kubernetes · Terraform · GCP · Vercel
