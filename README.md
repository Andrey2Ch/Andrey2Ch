<h1 align="center">Hi, I'm Andrey</h1>

<p align="center">
<strong>COO who codes</strong> — I run a CNC turning factory and built its entire software ecosystem from scratch.
</p>

<p align="center">
<a href="https://liveshopfloor.com">liveshopfloor.com</a> &nbsp;|&nbsp;
<a href="https://www.linkedin.com/in/andreycherniak/">LinkedIn</a>
</p>

---

### LiveShopFloor — Manufacturing Ecosystem

I spent 15+ years managing production with Excel, WhatsApp, and clipboards. Then I taught myself to code and built the system I always wanted.

**LiveShopFloor** is a 9-module ecosystem running a real factory — 18 CNC machines, 6M+ parts tracked, 3+ years in daily production use.

| Module | What it does |
|---|---|
| MES Dashboard | Kanban planning, order management, role-based views (9 roles) |
| Machine Monitor | Real-time FOCAS + Modbus, 18 machines 24/7, TV Mode |
| Backend API | FastAPI business logic, lot lifecycle, QC workflow |
| Telegram Bot | Operator & machinist daily interface, zero app adoption |
| Warehouse & Materials | Batch traceability, OCR intake, process gates |
| Program Vault | CNC program revisions, immutable history |
| AI Advisor | Natural language queries over production data (Text2SQL) |
| QC Workflow | Quality control with gates and approvals |
| WhatsApp | Role-based alerts with AI translation (RU→HE) |
| Time Tracking | Geolocation-based attendance via Telegram |
| Metrology Tracker | Calibration management + AI certificate parsing |

> See the full ecosystem at **[liveshopfloor.com](https://liveshopfloor.com)**

---

### The Core Idea: Process Gates

The system doesn't just track data — it enforces continuity:

```
No material issued     →  Setup can't start
No program uploaded    →  QC won't receive it
No QC approval         →  Production can't begin
```

Steps can't be skipped. Data can't be lost. The factory runs itself.

---

### Tech Stack

```
Frontend    Next.js 15 · TypeScript · Material-UI · React Query · Recharts
Backend     FastAPI · SQLAlchemy · PostgreSQL · Prisma
Bot         Python · aiogram · Telegram Bot API
Monitoring  Node.js · FOCAS · Modbus TCP · MTConnect/SHDR
AI          Claude API · Text2SQL · OCR · Auto-translation
Deploy      Railway · Docker · Edge Gateway (offline-first)
```

---

<p align="center">
<a href="https://liveshopfloor.com"><strong>Live Demo</strong></a> &nbsp;&nbsp;|&nbsp;&nbsp;
<a href="https://www.linkedin.com/in/andreycherniak/">Connect on LinkedIn</a>
</p>
