<p align="center">
  <a href="https://kayas-portfolio.vercel.app">
    <img src="banner.svg" alt="Ayan Salmani — Systems &amp; Full-Stack Software Engineer" width="100%" />
  </a>
</p>

<p align="right">
  <a href="https://kayas-portfolio.vercel.app"><b>Portfolio 🌐</b></a> &nbsp;•&nbsp;
  <a href="https://www.linkedin.com/in/ayan-salmani-aa8a9a27b/"><b>LinkedIn 🔗</b></a> &nbsp;•&nbsp;
  <a href="mailto:ayan.salmani.dev@gmail.com"><b>Email ✉️</b></a>
</p>

---

### Core Engineering Focus

- **Low-Latency Streaming Speech:** Hands-free voice agents, bidirectional WebSocket/PCM audio streams, schema-constrained function calling, and sub-50ms barge-in handling.
- **Autonomous Agent Loops:** ReAct execution runtimes, reasoning token isolation (`<think>`), multi-tier desktop perception fallbacks (UIA &rarr; OpenCV &rarr; OCR), and deterministic tool sandboxing.
- **Telemetry & Production Backends:** Non-blocking socket health monitors, SNI TLS verification, asynchronous event queues, and database-enforced metric retention policies.

---

### Shipped Systems & Open-Source

#### [Gymnos Voice Copilot](https://github.com/kayas881/gym-app)
*In-session hands-free voice copilot built for the Meta Global AI Developer Hackathon.*
- Architected an eyes-free voice pipeline transcribing spoken exercise updates into validated JSON schemas (exercise, weight, reps, RIR).
- Implemented human-in-the-loop "Confirm Card" safeguards to intercept and review agentic state changes prior to database commits.
- Built on Next.js, React, TypeScript, and Supabase with row-level security.

#### [Kayas Assistant](https://github.com/kayas881/kayas_Assistant)
*Autonomous desktop operating system agent driven by local model inference.*
- Engineered a deterministic ReAct planner in Python orchestrating a local 32B model (Qwen3-32B-AWQ via vLLM) and fine-tuned routing LoRA.
- Built a 3-tier visual perception fallback hierarchy: UI Automation (pywinauto) &rarr; OpenCV template matching &rarr; Tesseract OCR for resilient UI grounding.
- Designed isolated reasoning loops with `<think>` tag stripping and 15+ sandboxed OS tool executors.

#### [WanGP & ComfyUI Cloud GPU Tooling](https://github.com/kayas881/WanGP-Kaggle)
*Open-source generative video runtime orchestration on constrained cloud GPUs (34+ GitHub stars combined).*
- Automated multi-gigabyte model checkpoint redirection, CUDA VRAM offloading, and dependency patching on constrained T4/P100 hardware.
- Engineered one-click launch scripts providing authenticated Gradio tunnels with zero local installation overhead.

#### [Saral Watch](https://github.com/kayas881/kayas-watch)
*Self-hosted infrastructure and website telemetry platform.*
- Built concurrent socket health probes and SNI TLS certificate validation running on non-blocking 300-second cycles in Express and TypeScript.
- Implemented automated rolling 7-day metric retention policies in MySQL via Prisma ORM to bound database storage footprint.

#### [Race-OS](https://github.com/kayas881/Race-OS)
*Financial and operational workflow engine for independent creators.*
- Integrated live banking feeds via Plaid API, automated income/expense categorization rules, and quarterly tax calculation engines.
- Designed clean relational schemas with multi-tenant access controls and exportable financial audits.

---

### Technical Stack

| Domain | Technologies |
| :--- | :--- |
| **Languages** | Python (Asyncio), TypeScript, JavaScript, SQL, C++, Bash |
| **Agentic & Audio** | ReAct Loops, Structured Schemas (Pydantic/Zod), WebSockets, WebRTC, vLLM, Whisper, OpenCV, pywinauto |
| **Backend & Telemetry** | Node.js, Express, FastAPI, Prisma ORM, RESTful APIs, Cron Jobs, Socket Probes |
| **Databases** | PostgreSQL, MySQL (InnoDB), Supabase, SQLite, Redis |
| **Frontend** | React, Next.js, Tailwind CSS, HTML5, CSS Modules |
| **Cloud & DevOps** | Google Cloud (GCP), Microsoft Azure, Docker, Linux (Ubuntu), Nginx, PM2, Git, GitHub Actions |
