# Decision Automation for Capability & Training Prioritisation

Designing a logic-driven decision system to reduce ad-hoc judgment, cognitive load, and inconsistency in skill development decisions within complex organisations.

---

## Context

In a large engineering consultancy environment, I worked within a multidisciplinary team consisting of two distinct role groups:

- Technical engineers responsible for analysis, design, and coordination  
- Digital delivery specialists responsible for translating intent into detailed outputs  

Each role required a different mix of skills, depth, and progression expectations.  
At the time, the team size was ~50 and growing.

---

## The Problem

The organisation maintained a detailed skill matrix:
- ~30 skills spanning multiple domains
- Self-rated proficiency (1–5 scale)
- Role grades defining expected competency levels

However, **training allocation during downtime** was largely:
- Ad-hoc
- Dependent on individual line manager judgement
- Inconsistent across teams
- Not systematically aligned to role, grade, or skill criticality

This resulted in:
- Repetitive manual evaluation
- Missed critical skill gaps
- Training effort not always aligned to highest impact areas

This was not a motivation issue — it was a **decision-structuring problem**.

---

## Why Traditional Approaches Didn’t Scale

Common approaches proved insufficient:
- Manual spreadsheet reviews were time-consuming and inconsistent
- Static templates broke under role and grade variation
- Checklists lacked contextual nuance
- Human judgement varied widely across managers

The organisation had data — but lacked **repeatable reasoning** applied to that data.

---

## Core Insight

> If training decisions rely on repeated logic, the thinking itself can be systematised.

Rather than asking managers to repeatedly reason from scratch, the decision logic could be:
- Made explicit
- Encoded once
- Applied consistently at scale

This opened the door to automation and, eventually, AI-assisted decision workflows.

---

## The System I Built

I designed a **logic-driven decision system** using Python, supported by AI-assisted reasoning during development.

### Key components:
- Explicit role classification (technical vs digital)
- Skill segmentation by role relevance
- Identification of essential vs non-essential skills
- Grade-based competency thresholds
- Automated evaluation across individuals and skills

Each individual was evaluated against expectations derived from:
- Their role
- Their grade
- Skill criticality

The system generated a **visual heat map** highlighting:
- Individual training needs
- Group-level training patterns
- High-impact skill gaps

---

## Role of AI

AI (via ChatGPT) was used as a **thinking partner** to:
- Validate decision logic
- Surface edge cases
- Refine rules and thresholds
- Accelerate iteration

AI was not used to replace judgement, but to **reduce repetitive cognitive effort** and improve consistency.

---

## What Changed

Although the system was not rolled out organisation-wide, it demonstrated that:
- Training decisions can be standardised without removing human oversight
- Manager cognitive load can be significantly reduced
- The same framework can scale across teams and practices with minimal changes

Even with partial adoption, the system validated the **multiplier effect** of structured decision-making.

---

## Learnings

- High-impact problems often exist outside formal role boundaries
- Repetitive thinking is a strong signal for automation
- AI is most valuable when it reduces cognitive load, not when it replaces judgement
- Organisational adoption is as important as technical correctness

---

## Why This Matters Beyond Engineering

The same principles apply directly to product and AI work:
- Feature prioritisation
- Capability mapping
- Internal tooling
- Decision-support systems
- AI-assisted workflows under real-world constraints

This experience shaped how I approach problems — by identifying leverage, structuring ambiguity, and designing systems for long-term impact.

---

## What I Would Improve Next

If building this today:
- Introduce scenario-based reasoning instead of fixed thresholds
- Improve explainability for non-technical stakeholders
- Design for adoption earlier in the process
- Extend the framework using AI to generalise across domains
