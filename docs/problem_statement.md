# Problem Statement — Acture AI

## 1. Context

Engineering leaders in growth-stage companies operate across multiple tools: Jira (tasks), GitHub (code), and Slack (communication).  
To ensure predictable delivery, they need a clear and real-time understanding of what is happening across teams.

Today, this visibility is fragmented and typically **24–48 hours outdated**, which leads to delayed decision-making and missed risks.

---

## 2. ICP (Ideal Customer Profile)

**Company:**
- B2B SaaS / tech startups  
- 50–200 employees  
- 15–80 engineers  
- 2–6 parallel teams  

**Tech stack:**
- Jira  
- GitHub  
- Slack  

**Roles:**
- CTO / VP Engineering  
- Head of Engineering  
- Tech Leads  

---

## 3. Core Problem

**I am:**  
An engineering leader responsible for delivery across multiple teams  

**I’m trying to:**  
Maintain predictable delivery and understand execution in real time  

**But:**  
Data is fragmented across Jira, GitHub, and Slack  

**Because:**  
Signals (commits, PRs, tasks, communication) are not connected and require manual aggregation  

**This results in:**
- 24–48h delay in visibility  
- missed blockers and hidden risks  
- 5–10 hours/week spent on synchronization  
- decisions based on incomplete or outdated data  

---

## 4. JTBD (based on survey)

Detailed JTBD analysis: [JTBD](./JTBD_final)

### JTBD #1 — Maintain real-time visibility (HIGH)

**When:** managing multiple teams and parallel projects  
**I want to:** see what is actually happening across teams  
**So that:** I don’t lose control or miss risks  

---

### JTBD #2 — Explain engineering impact to business (HIGH)

**When:** leadership asks for results and ROI  
**I want to:** translate engineering work into business impact  
**So that:** I can justify decisions and secure resources  

---

### JTBD #3 — Reduce coordination overhead (MEDIUM)

**When:** running sync meetings and reports  
**I want to:** eliminate manual aggregation  
**So that:** I can focus on decision-making  

---

## 5. How teams solve it today

- Jira → task tracking  
- GitHub → code  
- Slack → communication  
- Standups → alignment  
- Manual reports → leadership updates  

Result: fragmented and outdated understanding  

---

## 6. Workarounds

Detailed breakdown: [Workarounds](./Workarounds.md)

**Key approaches:**
- Manual sync (PM/Lead aggregates data)  
- Jira as source of truth (comment-driven)  
- Internal scripts + LLM pipelines  
- Metrics dashboards (LinearB, Jellyfish)  
- Standup bots  
- AI on top of Jira  

All approaches provide partial visibility but not full understanding  

---

## 7. Competitive Landscape

Full analysis: [Competitive Analysis](./Competitor_research.md)

**Market structure:**
- Metric tools → provide data, not meaning  
- Task tools → manage workflows, not execution  
- Narrative tools → summarize, but lack depth  

---

## 8. Key Insight

The core problem is not lack of data —  
it is lack of **contextual interpretation across systems**.

Engineering leaders today act as a **human integration layer**, manually connecting signals and interpreting them.

---

## 9. Quantified Impact

- 5–10 hours/week spent on synchronization  
- 24–48h delay in visibility  
- delayed risk detection  
- low confidence in data  

---

## 10. Desired Outcome

A solution should:

- reduce sync time by ≥50%  
- provide near real-time visibility (<1 hour delay)  
- connect code, tasks, and communication  
- explain:
  - what is happening  
  - why it is happening  
  - what it means for delivery  
