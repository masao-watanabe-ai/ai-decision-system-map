# AI Decision System Map (Contract-first)

This repository is the **map** of my design references for building
**AI-driven decision systems that survive beyond PoC**.

Instead of "end-to-end magic", I focus on:
- **Contract-first design** (schemas / interfaces / auditability)
- Clear **decision boundaries** (where to cut smooth computation with logic)
- **Human-in-the-loop** review gates
- Reproducible and explainable decision pipelines

---

## System Map (by layer)

### 1) Event & Data Foundation
Preserve behavior as factual events and support time-aware reality (bitemporal models).
- **User behavior as events:** `user-behavior-event-design`
- **Time-aware / bitemporal data:** `time-aware-data-for-ai`

### 2) Social Context & Inference
Infer relationships, context, and intent as inputs to decision making.
- `social-context-inference`

### 3) Metrics & Evaluation
Metrics that connect AI analysis to real allocation and decisions.
- `decision-metric-design`

### 4) Decision Pipeline (Contract-first)
How to design decision flows that remain auditable and maintainable.
- `decision-pipeline-reference`

### 5) Orchestration & Agents
Readable multi-agent orchestration + LLM agent design principles.
- `multi-agent-orchestration-design`
- `llm-agent-design-notes`

### 6) View / Human Decision Interface
View layers that transform AI outputs into human decisions.
- `ai-decision-visualization`

### 7) Value & Local Infrastructure
Local currency as distributed decision infrastructure.
- `multi-agent-local-value-system`

---

## Reading Path (recommended)

1. Start here: `decision-pipeline-reference`
2. Data reality: `user-behavior-event-design` → `time-aware-data-for-ai`
3. Meaning & people: `social-context-inference`
4. Evaluation: `decision-metric-design`
5. Execution & scaling: `multi-agent-orchestration-design` + `llm-agent-design-notes`
6. Human interface: `ai-decision-visualization`
7. Economic layer (optional): `multi-agent-local-value-system`

---

## Contact
- Email: masao.watanabe.ai@proton.me
- LinkedIn: https://www.linkedin.com/in/masao-watanabe-ai

## Writings / Background

My long-form thoughts, design notes, and experiments are archived on my personal blog
(approx. 1500 posts, written over many years):

Blog: https://deus-ex-machina-ism.com/?lang=en
