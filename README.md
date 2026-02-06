# longterm-investor-agent
The agent’s goal is to continuously identify, evaluate, and recommend long-term equity investments, subject to user risk profile, investment horizon, and regulatory constraints, while optimizing for risk-adjusted returns and decision consistency. 

## Problem Statement
Long-term investors struggle to make consistent, data-driven equity decisions due to fragmented financial data, delayed insights, and heavy reliance on manual interpretation. Investment decisions are often influenced by short-term noise, emotional bias, and incomplete analysis of fundamentals, macro trends, and company-specific events.

This project proposes an **agentic AI system** that continuously evaluates long-term equity opportunities and portfolios in a structured, explainable, and disciplined manner.

---

## Problem Context
Long-term retail investors, wealth managers, and research analysts typically rely on quarterly reports, analyst notes, spreadsheets, and news articles. This approach is manual, slow, and error-prone. Continuous monitoring of fundamentals and macro signals is difficult, leading to inconsistent outcomes and delayed actions.

An intelligent agent-based system can improve decision quality by automating analysis, tracking key signals, and providing explainable recommendations aligned with long-term investment objectives.

---

## Primary Goal
To design an agentic system that:
- Identifies and evaluates long-term equity investments
- Aligns recommendations with user risk profile and investment horizon
- Optimizes decision consistency and risk-adjusted returns
- Provides explainable insights and monitoring guidance

---

## Scope and Boundaries

### Agent is allowed to:
- Analyze financial statements and earnings
- Track long-term business fundamentals and macro indicators
- Generate equity recommendations with rationale
- Monitor portfolios and suggest rebalancing
- Provide scenario-based and explainable insights

### Agent must ask a human before:
- Executing trades or placing orders
- Changing user risk profile or investment horizon
- Acting on ambiguous or conflicting signals

### Out of Scope:
- Trade execution without approval
- Short-term or intraday trading strategies
- Personalized tax or legal advice

---

## User Types
- Long-term retail investors
- Wealth managers / financial advisors
- Research analysts

---

## High-Level Agent Architecture
The system follows a **Perceive → Plan → Act** framework supported by multiple specialized agents:
- Perception Agent
- Fundamentals Analysis Agent
- Macro & Industry Agent
- Qualitative & Governance Agent
- Portfolio & Allocation Agent
- Compliance Guard Agent
- Orchestrator Agent

---

## Repository Structure
```
tree here

longterm-investor-agent/
│
├── README.md                  # Project overview and architecture
│
├── prompts/                   # Perceive–Plan–Act prompt design
│   ├── perceive.md
│   ├── plan.md
│   └── act.md
│
├── agents/                    # Specialized agent roles
│   ├── orchestrator.md
│   ├── fundamentals_agent.md
│   ├── macro_agent.md
│   ├── qualitative_agent.md
│   ├── portfolio_agent.md
│   └── compliance_guard.md
│
├── memory/                    # Agent memory and state
│   ├── schema.md
│   ├── user_profile.json
│   ├── watchlist.json
│   └── decisions_log.json
│
├── tools/                     # Open-source tools used
│   └── README.md
│
├── models/                    # Model assumptions
│   └── model_registry.md
│
└── docs/                      # Documentation and samples
    ├── architecture.md
    └── conversation_samples.md'''

