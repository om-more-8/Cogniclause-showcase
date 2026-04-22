# ⚖️ CogniClause — AI Contract Intelligence System

> Transform contracts into **structured risk intelligence, ranked insights, and optimized clauses** using a multi-stage AI pipeline.

---

## 🚀 Live Demonstration

🎥 **Demo Video:**
👉 *(Paste your video link here — YouTube / LinkedIn / Drive)*

> This demo shows full workflow: upload → analysis → risk scoring → clause optimization

---

## 📸 Screenshots

### 📄 Upload Interface

![Upload](./assets/upload.png)

### 📊 Risk Analysis Dashboard

![Dashboard](./assets/dashboard.png)

### ⚠️ Clause Risk Breakdown

![Risk](./assets/risk-analysis.png)

### ✍️ AI Optimization Output

![Optimization](./assets/optimization.png)

---

## 🧠 What CogniClause Does

CogniClause is not a simple AI wrapper.

It is a **multi-stage contract intelligence system** that:

* Extracts clauses from raw legal documents
* Classifies legal components semantically
* Quantifies risk using scoring logic
* Ranks clauses by importance
* Generates optimized legal suggestions

---

## ⚙️ End-to-End Workflow

```text
User Upload (PDF/DOCX/Text)
        ↓
Clause Segmentation Engine
        ↓
Embedding Generation (Semantic Representation)
        ↓
Vector Similarity Matching
        ↓
Clause Classification
        ↓
Risk Evaluation Engine
        ↓
Importance Ranking System
        ↓
LLM Optimization Engine
        ↓
Structured Output (UI + JSON)
```

---

## 🧩 Core Analytical Components

### 1. Clause Segmentation Engine

* Breaks contracts into atomic legal units
* Preserves semantic boundaries
* Handles noisy formatting

---

### 2. Semantic Similarity Engine

* Uses embeddings to understand clause meaning
* Matches clauses with known legal patterns
* Avoids keyword-based limitations

---

### 3. Risk Evaluation Engine

Risk is computed using:

```text
Risk Score = f(similarity_score, clause_weight, contextual_severity)
```

Factors:

* Clause type (liability, indemnity, termination)
* Semantic similarity
* Legal impact severity

---

### 4. Importance Ranking System

Prioritizes clauses based on:

* Risk severity
* Legal impact
* Contract relevance

---

### 5. AI Optimization Engine

For each risky clause:

* Identifies issue
* Explains risk
* Suggests improved clause

---

## 📊 Example Output

```json
{
  "summary": "High risk due to liability imbalance",
  "risk_score": 3.1,
  "top_clauses": [
    {
      "type": "Liability",
      "risk": "High",
      "issue": "Unlimited liability exposure",
      "suggestion": "Introduce liability cap..."
    }
  ]
}
```

---

## 🏗️ System Architecture

| Layer       | Responsibility             |
| ----------- | -------------------------- |
| Frontend    | UI & visualization         |
| Backend API | Pipeline orchestration     |
| AI Engine   | Semantic + reasoning logic |
| Database    | Storage + access control   |

---

## ⚡ Key Design Decisions

| Decision              | Reason                    |
| --------------------- | ------------------------- |
| Pipeline architecture | Modular & scalable        |
| Embeddings over rules | Better generalization     |
| LLM at final stage    | Cost efficiency           |
| Backend-driven logic  | Prevent frontend exposure |

---

## 🔐 Security Model

* Row Level Security (RLS) enforced
* User-level data isolation
* Backend-controlled processing
* No direct database exposure

---

## 🛠️ Tech Stack

### Frontend

* React + Vite
* Tailwind CSS
* Framer Motion

### Backend

* FastAPI
* Async processing

### AI Layer

* Sentence Transformers
* OpenRouter / Groq / Ollama

### Database

* Supabase (PostgreSQL + RLS)

---

## 🧠 What Makes This System Non-Trivial

* Multi-stage processing pipeline
* Hybrid AI system (embeddings + rules + LLM)
* Risk quantification logic
* Structured output generation
* Modular architecture design

---

## 🔮 Future Enhancements

* Full contract rewriting engine
* Export as formatted legal document (PDF/DOCX)
* Clause dependency graph
* Multi-contract comparison

---

## 👨‍💻 Author & Ownership

**Om More**
AI & Data Science Engineer

> CogniClause is an independently designed and developed system.
> All architecture, pipeline design, and implementation originate from this work.

---

## ⚠️ License

All rights reserved.
Unauthorized use, reproduction, or distribution is prohibited.
