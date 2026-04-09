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

<table>
<tr>
<td width="50%">

**Production & Planning**
| Module | What it does |
|---|---|
| [MES Dashboard](https://github.com/Andrey2Ch/isramat-dashboard) | Kanban planning, order management, role-based views |
| [Machine Monitor](https://github.com/Andrey2Ch/mtconnect-core) | Real-time FOCAS + Modbus, 18 machines 24/7 |
| [Backend API](https://github.com/Andrey2Ch/machine-logic-service) | FastAPI business logic, lot lifecycle, QC workflow |

</td>
<td width="50%">

**Interfaces & Tools**
| Module | What it does |
|---|---|
| [Telegram Bot](https://github.com/Andrey2Ch/IsramatBot) | Operator & machinist daily interface |
| [Metrology Tracker](https://github.com/Andrey2Ch/metrology-tracker) | Calibration management + AI certificate parsing |
| WhatsApp Integration | Role-based alerts with AI translation (RU→HE) |

</td>
</tr>
</table>

**Also built into the ecosystem:** Warehouse & Materials (batch traceability, OCR intake), Program Vault (CNC program revisions), AI Advisor (Text2SQL over production data), QC Workflow (process gates), Time Tracking (geolocation attendance).

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
