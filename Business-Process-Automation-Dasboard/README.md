# ⚡ AutoSphere | Enterprise Business Process Automation Dashboard

[![Project Sub-domain](https://img.shields.io/badge/Sub--Domain-Process%20Automation-blue.svg)](https://github.com)
[![Project Type](https://img.shields.io/badge/Project%20Type-Individual%20Capstone-emerald.svg)](https://github.com)
[![Duration](https://img.shields.io/badge/Duration-8--12%20Weeks-purple.svg)](https://github.com)
[![Architecture](https://img.shields.io/badge/Architecture-Control%20Plane%20Topology-cyan.svg)](https://github.com)
[![License](https://img.shields.io/badge/License-MIT-gray.svg)](https://github.com)

> **A bird's-eye enterprise control plane and observability dashboard for automated scripts, RPA bots, and background microservices across the entire enterprise.**

---

## 📌 Executive Summary

Modern enterprises automate thousands of routine workflows across Finance, Human Resources, IT, Logistics, and Customer Support using a patchwork of scripts (Python, PowerShell, Node.js, SQL ETL pipelines). However, **companies lose visibility into what is running where, when processes fail, and whether SLAs are breached.**

**AutoSphere** eliminates this operational blind spot by delivering:
1. **Centralized Visibility**: A single glassmorphic control pane tracking all automation assets regardless of language, host machine, or schedule.
2. **Real-Time Outage Triage**: Immediate detection of failures with root-cause stack traces and one-click self-healing remediation.
3. **Interactive Workflow Topology**: Step-by-step DAG visualization with simulated runtime payloads and telemetry SLAs.
4. **Quantitative ROI & Labor Savings**: Continuous tracking of recaptured employee hours, cost savings, and Full-Time Equivalent (FTE) labor multipliers.

---

## 🎯 Capstone Project Alignment

| Parameter | Project Details |
| :--- | :--- |
| **Project Title** | Business Process Automation Dashboard (AutoSphere) |
| **Sub-Domain** | Process Automation & Enterprise Orchestration |
| **Project Type** | Individual Capstone |
| **Duration** | 8–12 Weeks |
| **Evaluation Criteria** | **Innovation, Practicality, Completeness, Presentation Quality** |
| **Deliverables** | **1. Code / Tool** &nbsp;•&nbsp; **2. Prototype** &nbsp;•&nbsp; **3. Technical Documentation** |

---

## 🚀 Key Functional Capabilities

### 1. 📊 Enterprise Overview & Live Telemetry
- **Fleet KPIs**: Active Bots (4/6 online), Enterprise Process Success Rate (97.4%), Monthly Recaptured Hours (608 hrs), Realized Monthly Cost Savings ($23,800).
- **Cluster Worker Gauges**: Real-time worker CPU load, memory heap consumption, and queue message throughput.
- **Live Event Stream**: Real-time activity ticker logging bot transitions, trigger events, and health probes.
- **Fleet Diagnostics & Data Export**: Immediate diagnostic health check dispatches and one-click CSV / JSON audit report exports.

### 2. 🤖 Enterprise Bot Registry
- **Multi-Department Filtering**: Filter bots across **Finance**, **HR & IT**, **Customer Service**, **Supply Chain**, and **Marketing**.
- **Real-Time Search**: Search instantly by process ID (`BOT-101`), bot name, or owner lead.
- **Operational Controls**: Immediate manual execution trigger (`▶ Run Now`), schedule pause/resume toggle (`⏸ Pause`), console log drawer, and workflow inspector.
- **Bot Registration Modal**: Register new automated scripts with custom schedules, owner leads, and projected ROI.

### 3. 🔄 Visual Workflow Pipeline Topology
- **Interactive DAG Pipeline Flowchart**: Step-by-step visual graph (e.g. Ingestion → OCR Extraction → GL Code Matcher → ERP Sync).
- **Interactive Step Simulation**: Step-by-step execution simulation animating transitions from *pending* to *running* to *completed*.
- **Payload & Telemetry Inspector**: Click any pipeline node to inspect simulated JSON input/output contracts, worker node identifiers, execution latency, memory peaks, and AES-256 security tokens.

### 4. ⚠️ Incident Management & Self-Healing Center
- **Outage Severity Triage**: Real-time outage banner with active incident counts and SLA breach risk indicators.
- **Root-Cause Diagnostics**: Clear categorization of error codes (e.g. `ERR_STRIPE_RATE_LIMIT_429`), failing step locator, and formatted stack trace snippets.
- **Automated Remediation**: One-click **Auto-Retry & Remediate** executing exponential backoff and idempotency regeneration.
- **Operator Incident Resolution**: Mark incidents resolved to clear outage flags and restore fleet health.

### 5. ⏰ Enterprise Scheduler & Cron Engine
- **Tabular Schedule Manager**: Complete schedule matrix across all bots with cron syntax (`*/15 * * * *`, `0 8 * * 1-5`, etc.).
- **Human Cadence Translation**: Real-time translation to readable English (*"Every 15 minutes"*, *"Mon-Fri at 08:00 AM"*).
- **Live Countdown Timer**: Real-time projection of upcoming scheduled runs.

### 6. 📈 Quantitative ROI & Business Analytics
- **Execution Throughput Bar Visualizer**: Daily run counts (Monday–Sunday) tracking successful vs. failed runs.
- **Departmental Hours Breakdown**: Percentage and hour distribution across enterprise departments.
- **Interactive Labor Cost ROI Calculator**: Real-time slider adjusting average employee wage ($20–$120/hr) to calculate monthly and annualized value realization.

### 7. 📖 Integrated Documentation & SDK Hub
- In-app tabbed technical reference covering system topology, multi-language SDKs (Python, PowerShell, Node.js), security and RBAC specifications, and the 8–12 week roadmap.

---

## 🛠️ Technology Stack & Architecture

- **Front-End Architecture**: Modern Vanilla ES6+, Semantic HTML5, Glassmorphism CSS Design System.
- **Typography & Icons**: Plus Jakarta Sans, JetBrains Mono, SVG Vector Badges.
- **Zero-Dependency Runtime**: Operates completely standalone with **zero npm/Node/Python install requirements** — double-click `index.html` to run in any browser.
- **State & Storage**: Dynamic reactive in-memory state engine with `localStorage` persistence and fallback demo seeding.
- **Telemetry Protocols**: Unified JSON schema supporting REST `/api/v1/telemetry/*` and WebSocket event streams.

---

## 📂 Project Directory Structure

```text
Business-Process-Automation-Dasboard/
│
├── index.html                   # Production-Grade Dashboard Application & Tool
├── README.md                    # Executive Project Overview & Guide (This File)
├── TECHNICAL_DOCUMENTATION.md   # Comprehensive Technical Architecture & Design Report
├── ROADMAP_AND_MILESTONES.md    # 8-12 Week Implementation Plan & Review Checkpoints
├── PROJECT_PRESENTATION.md      # Capstone Defense Presentation Deck & Speaking Script
│
└── data/
    └── mockData.js              # Enterprise Bot Seed Data & Telemetry Fixtures
```

---

## 🚦 Quick Start Guide

You do **not** need to install Node.js, Python, or npm to run this prototype.

### Launch in Browser
1. Navigate to the project directory:
   ```powershell
   c:\Users\JOY AJITH\OneDrive\Desktop\Business-Process-Automation-Dasboard
   ```
2. Double-click **`index.html`** or open it using Google Chrome / Microsoft Edge.
3. The dashboard will launch immediately with full interactive capability!

---

## 📑 Capstone Deliverables Index

- 💻 **Code / Tool**: Fully functional, zero-error web application in [`index.html`](file:///c:/Users/JOY%20AJITH/OneDrive/Desktop/Business-Process-Automation-Dasboard/index.html).
- 🖥️ **Interactive Prototype**: Dynamic glassmorphic control plane with 7 views, interactive simulations, and state persistence.
- 📘 **Technical Documentation**: Comprehensive 10-page equivalent architecture document in [`TECHNICAL_DOCUMENTATION.md`](file:///c:/Users/JOY%20AJITH/OneDrive/Desktop/Business-Process-Automation-Dasboard/TECHNICAL_DOCUMENTATION.md).
- 🗓️ **Roadmap & Milestones**: Detailed 8–12 week breakdown in [`ROADMAP_AND_MILESTONES.md`](file:///c:/Users/JOY%20AJITH/OneDrive/Desktop/Business-Process-Automation-Dasboard/ROADMAP_AND_MILESTONES.md).
- 🎤 **Presentation Deck**: Defense slides and executive script in [`PROJECT_PRESENTATION.md`](file:///c:/Users/JOY%20AJITH/OneDrive/Desktop/Business-Process-Automation-Dasboard/PROJECT_PRESENTATION.md).

---

## 👨‍💻 Project Information

- **Developer**: Joy Ajith
- **Sub-domain**: Process Automation
- **Evaluation Criteria**: Innovation, Practicality, Completeness, Presentation Quality
