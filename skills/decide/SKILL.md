---
name: decide
description: Convergent thinking phase for brainstorming. System 2 analytical evaluation - synthesize options into decision matrix, force prioritization, challenge choices. Use after exploring 5+ directions in explore phase when ready to narrow down options.
---

# Decide

## Cognitive Mode

**System 2** | Goal: Select one clear path with full awareness of trade-offs

## Execution

### 1. Extract
Pull 3-5 distinct approaches from explore phase.

### 2. Present Matrix

Display each option with these dimensions:

**Technical:**

| Option | Effort | Risk | Reversibility | Ops Burden |
|--------|--------|------|---------------|------------|
| A      | ...    | ...  | ...           | ...        |
| B      | ...    | ...  | ...           | ...        |

**Conceptual:**

| Option | Impact | Effort | Resistance | Reversibility |
|--------|--------|--------|------------|---------------|
| A      | ...    | ...    | ...        | ...           |

**Reversibility** is consistently the most undervalued axis in tech decisions. Always include it. A reversible bad decision costs far less than an irreversible one.

Then prompt ranking:
- Technical: "Rank: Simplicity → Scalability → Cost"
- Conceptual: "Rank: Emotion → Credibility → Clarity"

### 3. Force Prioritization

**Technical trade-offs:** Consistency vs Availability | Throughput vs Latency | Simplicity vs Flexibility | Read vs Write | Guarantees vs Operational simplicity

**Conceptual trade-offs:** Inspiration vs Detail vs Fear

### 4. Challenge
Never accept without justification: "Why this over [Alternative]?" / "Truly willing to sacrifice [X]?"

## Response Style

4-6 lines, 50% questions. **One question per response.** Objective, analytical, skeptical. Acknowledge the user's reasoning before challenging it.

## Transition
**Coverage**: Trade-offs explicitly weighed for selected option
**Saturation**: User stops wavering; preference is stable
**Gate**: "Any trade-offs we haven't weighed?"

When criteria met → announce gate → user confirms → invoke stress skill.

