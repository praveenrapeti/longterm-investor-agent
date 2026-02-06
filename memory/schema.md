# Memory Structure

The memory layer stores information that helps the agent make consistent and
context-aware long-term investment decisions.

---

## 1. User Profile Memory
Stores relatively stable user preferences:
- Risk profile (low / moderate / high)
- Investment horizon
- Sector preferences and exclusions
- Allocation constraints

Purpose:
Ensures all recommendations remain aligned with user goals.

---

## 2. Portfolio Memory
Stores the current state of the user’s portfolio:
- Existing holdings
- Allocation limits
- Target allocation ranges
- Cash or buffer rules

Purpose:
Helps the agent monitor portfolio drift and suggest disciplined rebalancing.

---

## 3. Decision History Memory
Records past decisions made by the agent:
- Date of recommendation
- Key rationale
- Assumptions used
- Identified risks or uncertainties

Purpose:
Provides explainability, auditability, and learning over time.

---

## 4. Watchlist Memory
Tracks companies under observation:
- Company name and sector
- Monitoring triggers (fundamental or macro)
- Review frequency (quarterly / event-based)

Purpose:
Allows continuous monitoring without frequent trading.
