#  LoanGuard AI — Intelligent Loan Risk Analyzer

> **An AI-powered fintech platform that transforms complex loan agreements into clear, actionable financial insights.**

---

## What is LoanGuard AI?

LoanGuard AI is a next-generation **AI-driven financial contract intelligence system** that helps users:

* Understand dense loan agreements instantly
* Detect hidden financial risks
* Estimate real-world monetary impact
* Compare multiple loan offers
* Make confident borrowing decisions

---

## Why This Project is Impressive

Unlike basic projects, LoanGuard AI is a **complete decision system**, not just a parser.

### What makes it stand out:

* **AI-first architecture** (LLM-based understanding, not regex)
* **Clause-level financial reasoning**
* **Real monetary impact estimation in ₹**
* **Plain-English explanations of legal clauses**
* **Loan comparison engine**
* **Decision-ready report generation**

---

## Core Features

### 1. Intelligent Document Ingestion

Upload any loan agreement PDF → AI extracts and understands content automatically.

### 2. Financial Risk Clause Detection

Detects critical clauses like:

* Prepayment penalties
* Foreclosure charges
* Hidden charges
* Auto-debit mandates
* Late payment penalties

### 3. Plain Language Interpretation

Converts complex legal text into simple, user-friendly explanations.

### 4. Clause-Level Risk Scoring

Each clause is categorized as:

* 🔴 High Risk
* 🟡 Medium Risk
* 🟢 Low Risk

### 5. Monetary Impact Estimation

Calculates actual cost in ₹:

> Example: “Closing early may cost ₹20,000”

### 6. Overall Loan Risk Assessment

Generates:

* Risk Score (0–100)
* Risk Level (Low → Critical)
* Clear summary

### 7. Decision-Ready Report

Structured report with:

* Clauses
* Risks
* Costs
* Recommendations

### 8. Loan Comparison Engine

Compare multiple loans side-by-side and identify the **best option instantly** 

---

##  Tech Stack

* LLM: Qwen2.5-0.5B-Instruct (Transformers)
* Backend: Flask
* PDF Processing: PyMuPDF
* API Exposure: Ngrok
* Frontend: HTML, CSS, JavaScript

---

## Setup Instructions

###  Step 1: Install Dependencies

```bash
pip install flask flask-cors pyngrok pymupdf transformers torch accelerate sentencepiece
```

---

### Step 2: Run Backend (GPU Recommended)

Make sure you are using a GPU environment (Colab / local GPU).

```bash
python app.py
```

👉 This will:

* Load AI model
* Start Flask server
* Generate a public backend URL (via ngrok)

---

### Step 3: Copy Backend URL

After running backend, you’ll see:

```bash
 Public URL: https://xxxx.ngrok-free.app
```

Copy this URL.

---

### Step 4: Connect Frontend

In your frontend file (`index.html`), update:

```javascript
const API_URL = "https://xxxx.ngrok-free.app/analyze";
```

---

### Step 5: Open Frontend

Simply open:

```bash
index.html
```

in your browser.

---

##  How It Works

```text
PDF Upload → AI Extraction → Risk Detection → Cost Estimation → Scoring → Report
```

---

##  Example Output

* Risk Score: **100/100 (Critical)**
* Hidden Cost: **₹44,164**
* Key Issues:

  * ₹20,000 prepayment penalty
  * Hidden charges
  * Auto-debit mandate

---

## Real Impact

LoanGuard AI helps users:

* Avoid hidden financial traps
* Understand legal terms easily
* Choose the safest loan
* Save thousands of rupees

---

## Why This Matters

> Most people sign loan agreements without understanding them.

LoanGuard AI solves this by turning:

> ❌ Legal complexity → ✅ Financial clarity

---

## Developed By

**Vaishnavi Sriyaa Narasimhadevara**
---

## Final Note

This project is not just a demo —
It is a **real-world fintech product prototype** with strong practical value.

---

🔥 *If you found this interesting, consider starring the repo!*
