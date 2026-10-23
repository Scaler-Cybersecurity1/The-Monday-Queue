# The-Monday-Queue

**Topic:** Alert triage / signal vs. noise · **Time:** 25–35 min

**Scenario.** You start your SOC shift and the overnight queue has **12 alerts**.
Most are noise. One host is genuinely compromised, and the signal is split across a
few related alerts.

**Your task.** For every alert, set a **Verdict** and a **Priority** from the
dropdowns, based on its evidence:
- **Verdict:** False positive (not real) · Benign (real but no threat, e.g. an attack
  that was blocked) · Suspicious (needs a look) · Malicious (confirmed bad).
- **Priority:** P1 (critical, act now) → P4 (informational).

You cannot advance until the alerts that make up the real intrusion are correctly
marked Malicious. Then recover the facts and make the escalation call.

**You must find:**
1. Which host is compromised.
2. The command-and-control (C2) domain.
3. The alert ID that shows the initial code execution.
