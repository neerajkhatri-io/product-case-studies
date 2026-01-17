# Decision Support for Design Change Impact in Complex Projects

A structured decision-support system to classify, prioritise, and reason about late-stage design changes under time, cost, and delivery constraints.

---

## Overview

Large engineering and infrastructure projects frequently experience design changes — often late in the delivery cycle and under significant time pressure. While teams are good at *logging* and *communicating* these changes, they struggle to quickly understand **which changes truly matter** and which can be safely absorbed.

This case study explores a **decision-support product concept** designed to help teams **classify and prioritise design changes early**, reducing reactive decision-making, rework, and downstream cost and schedule risk.

Although inspired by experiences in Architecture, Engineering, and Construction (AEC), the underlying problem — *making fast, high-stakes decisions under uncertainty* — is common across many complex, multi-stakeholder engineering environments.

---

## Context & Background

In complex projects such as large buildings, airports, and infrastructure assets:

- Design teams are multidisciplinary (architecture, structures, MEP, fire, BIM, etc.)
- Stakeholders include consultants, clients, regulators, and operators
- Design changes originate from evolving requirements, coordination issues, or regulatory feedback

Having worked in delivery-focused engineering environments, I’ve repeatedly seen design changes introduced **late and under compressed timelines**. Teams often absorb these changes reactively — not due to lack of competence or intent, but because they lack fast, structured decision support at the moment it matters most.

---

## The Core Problem

> **When design changes are introduced in complex engineering projects, teams lack a fast and reliable way to classify and prioritise their downstream impact. As a result, changes are handled reactively, leading to inefficient use of time, manual effort, and increased cost and schedule risk.**

---

## Why Existing Solutions Fall Short

Current tools and processes typically fail because:

- They capture *what* changed, but not *what it means* for downstream disciplines, coordination effort, or risk.
- Prioritisation is subjective and discipline-centric; what feels critical to one team may be low-impact to another.
- Projects involve multiple organisations with different tools and ways of working, resulting in no shared framework for impact assessment.
- Teams rely heavily on senior intuition and manual judgement under time pressure, increasing the risk of rework and late surprises.

The gap is not a lack of information — it is a lack of **decision clarity**.

---

## Users & Decision Ownership

**Primary User**
- **Design Manager / Project Design Lead**  
  Owns early prioritisation decisions under time pressure.

**Secondary Users**
- Discipline leads (structures, MEP, fire, etc.)
- BIM and coordination teams
- Cost and planning teams (as consumers of early signals)

**Stakeholders**
- Client representatives
- Architects and regulatory teams

**Key Insight**
Risk ownership shifts by project stage, but **early prioritisation almost always sits with the design manager**, who must decide whether to absorb, defer, or escalate a change.

---

## Product Vision

> Enable project teams to quickly understand the downstream impact of design changes so they can prioritise the right actions early — before risk is absorbed by delivery teams.

### What This Product Is Not
- A design tool
- A BIM viewer
- A reporting dashboard
- An automated approval system

### What This Product Enables
- Faster, calmer decision-making
- Structured prioritisation under uncertainty
- Better conversations earlier in the lifecycle

---

## MVP Scope (3-Month Focus)

### What the MVP Does

The MVP focuses on **early impact classification**, not prediction or automation.

**Core capabilities**
- Accepts unstructured change inputs (email text, meeting notes, copied messages)
- Normalises inputs into a structured format
- Classifies change impact as **Low / Medium / High**
- Highlights affected disciplines
- Surfaces clear reasoning behind each classification

The objective is **speed and confidence**, not perfect accuracy.

---

### What the MVP Deliberately Does Not Include

To maintain focus and adoption, the MVP excludes:

- Cost modelling and programme simulation
- Dashboards and executive reporting
- Deep BIM or scheduling tool integrations
- Automated decision-making or approvals

These may be explored later, but they are not required to validate core value.

---

## Role of AI (Support, Not Replacement)

AI acts as a **supporting intelligence**, not a decision-maker.

**How AI Helps**
- NLP interprets messy, unstructured change descriptions
- Pattern recognition highlights similarities to past high-risk changes
- Confidence and uncertainty signals guide attention

**What AI Does Not Do**
- Replace engineering judgement
- Calculate exact cost or schedule impacts
- Make contractual or approval decisions

> Final decisions remain with experienced professionals.

---

## Risks & Trade-offs

### Key Risks

1. **Adoption & Behaviour Change**  
   Engineering teams operate under established workflows and time pressure. If the product adds friction or feels like extra work, users may revert to existing habits.

2. **Trust in AI-Assisted Outputs**  
   NLP-based interpretation is not error-free. Inaccurate or opaque recommendations could erode trust or lead to over-reliance.

### Mitigation Strategy

- Design for minimal input effort and fast outputs
- Make classifications explainable and transparent
- Position the product as an aid, not a replacement
- Pilot with a small group of design managers before scaling

---

## What I’d Explore Next

If validated, future exploration could include:
- Deeper integrations with coordination and delivery tools
- Cross-project learning and benchmarking
- Organisation-specific tuning of impact signals

---

## Closing Note

This case study reflects how I approach product problems:
- Grounded in real delivery constraints
- Focused on decisions, not features
- Respectful of domain expertise
- Intentional about where AI adds value

The goal is not to eliminate complexity — but to help teams navigate it better.
