# 🎧 Customer Service Case Automation — Case Study

> Automated case creation, categorisation, routing, SLAs and escalations in Dynamics 365 Customer Service, aimed at reducing manual triage and average handling time (AHT).

![Case Study](https://img.shields.io/badge/Type-Case%20Study-0F766E?style=for-the-badge)
![Dynamics 365 Customer Service](https://img.shields.io/badge/Dynamics%20365%20Customer%20Service-002050?style=for-the-badge)
![Power Automate](https://img.shields.io/badge/Power%20Automate-0066FF?style=for-the-badge)

---

## 🧩 Business problem

Customer requests arriving by **email and web forms** had to be triaged by hand: someone had to create the case, decide what it was about and send it to the right team. Manual triage slows down first response and pushes up **average handling time (AHT)**.

## 💡 Solution overview

Use **Dynamics 365 Customer Service** with **Power Automate** to:

- **Automatically create cases** from email and web forms
- **Categorise cases with rules** and **route them to queues**
- Apply **SLAs** and **escalation rules** so nothing is missed
- Support agents with **knowledge articles**

## 🏗️ Workflow / architecture

```mermaid
flowchart LR
    E[📧 Email] --> C[🗂️ Case auto-created]
    W[🌐 Web form] --> C
    C --> R{Rule-based<br/>categorisation}
    R --> Q1[Queue A]
    R --> Q2[Queue B]
    R --> Q3[Queue C]
    Q1 & Q2 & Q3 --> S[⏱️ SLA timers applied]
    S --> A[👩‍💻 Agent works case<br/>+ knowledge articles]
    S -. SLA at risk .-> X[🚨 Escalation rule]
    X --> A
    A --> D[✅ Case resolved]
```

## ✨ Key features

- Automatic case creation from **email** and **web forms**
- **Rule-based categorisation** and **routing to queues**
- **SLAs** to track response and resolution commitments
- **Escalation rules** for cases at risk
- **Knowledge articles** to help agents resolve cases consistently

## 👩‍💼 My role

- Designed the case automation approach in Dynamics 365 Customer Service and Power Automate

## 📈 Outcomes

- Designed to **reduce manual triage** and **average handling time (AHT)**.

## 🖼️ Screenshots

> _Screenshots coming soon._

| Case form | Routing rules | SLA / escalation |
|---|---|---|
| _placeholder_ | _placeholder_ | _placeholder_ |

## 🧠 Key learnings

- Good categorisation rules are the foundation — routing, SLAs and reporting all depend on them.
- SLAs and escalations work best when they match how each team actually works.
- Knowledge articles help agents resolve cases consistently.

---

<sub>Built by [Mubeena M E](https://github.com/mubeename) · [LinkedIn](https://www.linkedin.com/in/mubeename)</sub>
