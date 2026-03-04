<div align="center">
```
███████╗███████╗███╗   ██╗████████╗██╗███╗   ██╗███████╗██╗      ██╗  ██╗
██╔════╝██╔════╝████╗  ██║╚══██╔══╝██║████╗  ██║██╔════╝██║      ╚██╗██╔╝
███████╗█████╗  ██╔██╗ ██║   ██║   ██║██╔██╗ ██║█████╗  ██║       ╚███╔╝ 
╚════██║██╔══╝  ██║╚██╗██║   ██║   ██║██║╚██╗██║██╔══╝  ██║       ██╔██╗ 
███████║███████╗██║ ╚████║   ██║   ██║██║ ╚████║███████╗███████╗ ██╔╝ ██╗
╚══════╝╚══════╝╚═╝  ╚═══╝   ╚═╝   ╚═╝╚═╝  ╚═══╝╚══════╝╚══════╝ ╚═╝  ╚═╝
```

### ⚡ Stop Fraud Before It Breathes. ⚡
**Real-time. Intelligent. Relentless.**

---

![Team](https://img.shields.io/badge/Team-Dev%20Spark-blueviolet?style=for-the-badge)
![Theme](https://img.shields.io/badge/Theme-Future%20Finance%20Innovation-informational?style=for-the-badge)
![Speed](https://img.shields.io/badge/Detection%20Speed-<300ms-success?style=for-the-badge)
![Status](https://img.shields.io/badge/Hackathon-Active-orange?style=for-the-badge)

</div>

---

## 🧠 The Problem We're Solving

> *"By the time your bank sends you an SMS, the money is already gone."*

In India's blazing-fast digital payments ecosystem — UPI, IMPS, NEFT — transactions settle in **milliseconds**. But fraud detection? It's still playing catch-up.

Here's the uncomfortable truth:

| What Exists Today | What Actually Happens |
|---|---|
| Rule-based fraud filters | Get defeated by AI-driven schemes like **Salami Attacks** |
| Post-transaction analysis | Fraud is caught *after* money is lost |
| IP/device monitoring | Too slow to act within a single transaction window |
| Rigid block lists | Frustrates real users → High **False Positive** rates |

The gap between payment speed and fraud intelligence is where criminals live. **Sentinel-X closes that gap.**

---

## 🛡️ What is Sentinel-X?

**Sentinel-X** is a lightning-fast, three-layered fraud prevention engine that doesn't just *detect* fraud — it *intercepts* it. Instead of asking "was that fraudulent?", it asks **"should this even be allowed?"** — all within **300 milliseconds**.

It analyzes every transaction like a behavioral lie detector:
- 🧬 Your typing rhythm
- 📍 Your location trajectory
- 📱 Your device fingerprint
- 🕐 The *time* you transact
- 💸 The *pattern* of what you spend

---

## 🏗️ Architecture: The Three-Layer Defense

```
                    💳 TRANSACTION INITIATED
                            │
                            ▼
         ┌──────────────────────────────────────┐
         │   LAYER 1: THE INGESTION GATE        │
         │   ⚙️  Java Multithreading Engine     │
         │   ─────────────────────────────────  │
         │   • Handles 1,000+ signals/second    │
         │   • Acts as the Traffic Cop          │
         │   • Peak-time resilience guaranteed  │
         └──────────────────┬───────────────────┘
                            │
                            ▼
         ┌──────────────────────────────────────┐
         │   LAYER 2: THE INTELLIGENCE BRAIN    │
         │   🐍 Python + Isolation Forest ML    │
         │   ─────────────────────────────────  │
         │   • Spots anomalies, not just        │
         │     "known" fraud patterns           │
         │   • Risk Score: 0.0 → 1.0           │
         │   • Scored in under 100ms            │
         └──────────────────┬───────────────────┘
                            │
                            ▼
         ┌──────────────────────────────────────┐
         │   LAYER 3: BEHAVIORAL FINGERPRINT    │
         │   🔍 The Identity Layer              │
         │   ─────────────────────────────────  │
         │   • Passive biometric profiling      │
         │   • Geo-velocity detection           │
         │   • Device hash + hardware ID        │
         └──────────────────┬───────────────────┘
                            │
                  ┌─────────┴──────────┐
                  ▼                    ▼
           ✅ LOW RISK           ⛔ HIGH RISK
        Transaction clears    Transaction FROZEN
           in < 300ms        + XAI Report generated
```

---

## 🚀 The 300ms Loop — How It Actually Works

```
[ USER initiates ₹20,000 payment to new merchant ]
          ↓
[ Java Engine ingests signal instantly ]
          ↓
[ Python Brain scores behavior vs. history + global fraud trends ]
          ↓
     ┌────┴────┐
  Score < 0.5  Score 0.5–0.8   Score > 0.9
     │            │                │
  ✅ Pass     🔐 Step-Up       🚨 Kill Switch
  (instant)   (Face ID/OTP)   (Freeze + Report)
```

---

## ✨ Feature Breakdown

### 🧠 Core Detection Engine
- **Isolation Forest Anomaly Detection** — Hunts outliers, not just "known bad" patterns
- **Real-Time Risk Scoring** — Every transaction scored `0.0–1.0` in under 100ms
- **Dynamic Thresholding** — Heightened security during high-risk windows (e.g., 2 AM, known phishing waves)
- **Velocity Tracking** — Catches Salami Attacks: 10 × ₹10 in 10 seconds? Flagged.

### 🔬 Behavioral Biometrics *(The Secret Sauce)*
- **Passive Interaction Profiling** — Typing rhythm, scroll speed, micro mouse movements
- **Geo-Velocity Alerts** — Bangalore → London in 10 minutes? Physically impossible. Blocked.
- **Device Fingerprinting** — Tracks browser hashes + hardware IDs; detects Device Farm switches

### ⚔️ The Sentinel Response System
| Risk Score | Action Taken |
|---|---|
| `0.0 – 0.49` | ✅ Transaction approved instantly |
| `0.5 – 0.79` | 🔐 Step-up: Face ID or OTP challenge |
| `0.8 – 0.89` | ⚠️ Flagged for review + user notified |
| `0.9 – 1.0` | 🚨 Automated Kill-Switch: transaction frozen |

### ⚡ Performance Infrastructure
- **Java Multithreaded Gateway** — 1,000+ TPS with zero degradation
- **Redis Hot Memory Cache** — Instant recall of a user's last 5 minutes of activity
- **Explainable AI (XAI) Reports** — Every block comes with a human-readable reason
  > *e.g., "Blocked: Behavioral mismatch + Unknown VPN detected"*
- **Tamper-Proof Security Audit Trail** — Full forensic log for every decision made

---

## 🛠️ Tech Stack

```
Backend Logic       →  Java (Multithreaded Ingestion Engine)
ML / AI Core        →  Python + Isolation Forest Algorithm
Caching Layer       →  Redis (Sub-millisecond hot memory)
Behavioral Layer    →  Custom Passive Biometrics Engine
Explainability      →  XAI Report Generator
```

---

## 🏆 Why Sentinel-X Wins

| Traditional Fraud Detection | Sentinel-X |
|---|---|
| Reacts *after* fraud occurs | **Prevents** before money moves |
| Flags known patterns only | Detects **unknown** anomalies |
| One-size-fits-all rules | **Personalized** behavioral baseline per user |
| High false positives | **Dynamic thresholds** = fewer blocks on real users |
| Slow, batch processing | **Sub-300ms** real-time decision engine |

---

## 👥 Team

| Role | Name |
|---|---|
| **Team Leader** | Chandrashekar Azad D |
| **Team Name** | Dev Spark |
| **Hackathon Theme** | Future Finance Innovation Platforms |

---

## 📌 Hackathon Submission

> This project was built as part of a hackathon under the theme **"Future Finance Innovation Platforms"**.  
> Sentinel-X represents a paradigm shift — from reactive fraud reporting to proactive, behavioral-intelligence-driven fraud *prevention*.

---

<div align="center">

*"Don't just detect fraud. Strangle it at birth."*

**⭐ Star this repo if Sentinel-X made you feel safer. ⭐**

</div>
