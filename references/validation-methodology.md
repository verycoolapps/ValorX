# VALIDATION METHODOLOGY — REFERENCE

> Validating assumptions before you build is cheaper than pivoting after.
> This reference guides the science of reducing product risk.

---

## THE VALIDATION PHILOSOPHY

**Validation is not about proving you're right.**
It is about finding out what's true as cheaply and quickly as possible.

The goal of validation is to KILL BAD HYPOTHESES before you invest heavily.

A good validator is happy to discover they were wrong early.
A bad validator tries to confirm what they already believe.

---

## HYPOTHESIS ARCHITECTURE

Before validating, structure your assumptions properly.

### The Riskiest Assumption Test (RAT)

Not all assumptions are equal. Focus on the ones that, if wrong, would kill the product.

```
RISKIEST ASSUMPTION IDENTIFICATION:

1. List every major assumption your product strategy makes
2. Assess: "If this is wrong, would we fundamentally change the product?"
3. Rank by: (Impact if wrong) × (Probability of being wrong)
4. Top 3 = your critical validation priorities

Common riskiest assumptions:
  - "This problem is painful enough that consumers will pay to solve it"
  - "This specific segment experiences this problem most intensely"
  - "Consumers will prefer our approach over their current solution"
  - "Consumers will change their current behavior to adopt this"
  - "They will pay X for this"
  - "They will find this through channel Y"
```

### Hypothesis Format

```
H[number]: We believe [SPECIFIC CLAIM ABOUT CONSUMER BEHAVIOR/REALITY]
            is true for [SPECIFIC SEGMENT] 
            because [SUPPORTING REASONING].

If correct: [WHAT DOES THIS MEAN FOR THE PRODUCT?]
If wrong: [HOW DOES THIS CHANGE OUR STRATEGY?]

Validation method: [HOW WILL WE TEST THIS?]
Success criteria: [WHAT OBSERVABLE OUTCOME CONFIRMS THIS?]
Failure criteria: [WHAT OBSERVABLE OUTCOME KILLS THIS?]
Time horizon: [HOW LONG TO COLLECT MEANINGFUL SIGNAL?]
Cost to validate: [TIME, MONEY, RESOURCES REQUIRED]
```

---

## VALIDATION METHODS LIBRARY

### Tier 1 — Cheapest (Highest Value per Dollar)

**Discovery Interviews**
- Purpose: Understand real customer behavior and priorities
- Format: 30-45 min 1:1 conversation, timeline-focused
- Sample size: 5-15 (look for pattern saturation)
- Strength: Rich insight, uncovers unknown unknowns
- Weakness: Small sample, potential interviewer bias
- Output: Job statements, pain ranking, switching triggers

**Competitor and Substitute Review Mining**
- Purpose: Understand what consumers complain about and love
- Format: Systematic analysis of 1-3 star reviews + praise patterns
- Sample size: 100+ reviews per competitor
- Strength: Real consumer voice, no recruitment needed
- Weakness: Existing products only, survivorship bias

**Concept Validation Survey**
- Purpose: Prioritize consumer preferences at scale
- Format: Max Diff, conjoint, or simple ranking questions
- Sample size: 50-200 (depending on segment size)
- Strength: Statistically significant preference data
- Weakness: Stated preference ≠ revealed preference

**Problem Interview (Pre-solution)**
- Purpose: Confirm the problem exists and its intensity
- Format: 20-30 min focused on exploring the problem space only
- Sample size: 10-20
- Rule: DO NOT mention your solution during this interview

---

### Tier 2 — Medium Investment

**Landing Page Experiment**
- Purpose: Test demand signal and value proposition messaging
- Format: Describe the product, offer to join waitlist or pre-order
- Sample size: 200+ unique visitors for statistical meaning
- Success signal: Conversion rate (industry-dependent, typically 5-15% for waitlist)
- Weakness: Measures interest, not behavior

**Prototype Testing (Low Fidelity)**
- Purpose: Validate core interaction model and information architecture
- Format: Paper/Figma prototype with 5-8 users
- Strength: Cheap to iterate, identifies major UX failures early
- Success signal: Users can accomplish core job without guidance

**Concierge MVP**
- Purpose: Deliver the product's value promise manually while building
- Format: Do manually what the product will automate
- Strength: Real consumer value with zero technical investment
- Weakness: Not scalable, doesn't test product UX
- Success signal: Consumers pay, return, refer

**Fake Door Test**
- Purpose: Measure demand for a specific feature before building
- Format: Show the button/link; track clicks; deliver "coming soon" message
- Strength: Behavioral signal (click) > stated preference
- Weakness: Slight consumer deception requires careful handling

---

### Tier 3 — Significant Investment

**MVP with Usage Metrics**
- Purpose: Validate core loop, retention, and product-market fit
- Sample size: 100-1000 active users
- Key metrics: Activation rate, Day 7/30/90 retention, NPS
- Success signal: Retention above category benchmark

**A/B Testing**
- Purpose: Test specific product decisions against baseline
- Requirements: Sufficient traffic, clear metric, single variable
- Weakness: Requires scale, long duration for significance

**Pilot Program**
- Purpose: Controlled validation in real-world conditions
- Format: Select 20-50 high-fit consumers for structured trial
- Strength: Rich feedback, controlled conditions
- Weakness: Time-intensive, Hawthorne effect possible

---

## VALIDATION DESIGN RULES

### The One Metric Rule
Each experiment tests ONE primary hypothesis with ONE primary metric.
Multi-hypothesis experiments produce ambiguous results.

### The Pre-Mortem Rule
Before running an experiment:
> "If we get a negative result, what will we do?"
If you can't answer clearly, you're not ready to run the experiment.

### The Anti-Confirmation Bias Rule
Document failure criteria BEFORE seeing results.
Never move goalposts after results come in.

### The Minimum Viable Evidence Rule
What is the minimum evidence that would change your strategy?
Only run experiments that can generate that level of evidence.

---

## VALIDATION EVIDENCE LADDER

```
WEAKEST ←———————————————————————————→ STRONGEST

EXPERT OPINION       → "Experts say this market needs X"
ANALOGOUS EVIDENCE   → "Similar products succeeded in this space"  
INTERVIEW SIGNALS    → "10 consumers expressed this pain strongly"
SURVEY PREFERENCE    → "70% selected this feature as most important"
WAITLIST CONVERSION  → "15% of visitors joined the waitlist"
USAGE BEHAVIOR       → "80% of users completed core task in first session"
PAYMENT              → "Users paid before the product was fully built"
RETENTION            → "60% returned after 30 days"
REFERRAL             → "Users spontaneously recommended to peers"
```

Higher on the ladder = stronger evidence, more investment required.
Match evidence tier to decision stakes.

---

## VALIDATION ROADMAP TEMPLATE

```
VALIDATION ROADMAP: [Product Name]
Analysis date: [Date]
Overall confidence before validation: [%]

PHASE 1 — RISKIEST ASSUMPTIONS (Weeks 1-4)
  Budget: [Time and money]
  
  Experiment 1.1:
    Hypothesis: [H1]
    Method: [From library above]
    Success criteria: [Specific, measurable]
    Failure criteria: [Specific, measurable]
    Timeline: [X days]
    Responsible: [Who runs this?]
    
  Experiment 1.2:
    [Same structure]

PHASE 2 — SECONDARY ASSUMPTIONS (Weeks 4-8)
  Conditional on: [Phase 1 outcome]
  [Same structure]

PHASE 3 — SCALING VALIDATION (Weeks 8-12)
  Conditional on: [Phase 2 outcome]
  [Same structure]

GO/NO-GO DECISION POINT:
  After Phase 1, we will decide: [Build / Pivot / Kill]
  Decision criteria: [Specific outcomes that determine each path]
```

---

## COMMON VALIDATION MISTAKES

| Mistake | Consequence | Prevention |
|---------|------------|------------|
| Validating with friends and family | Biased positive results | Recruit from real target segment |
| Testing your solution too early | Miss the real job/pain | Problem-first, solution-second |
| Moving goalposts after bad results | Confirm bias | Pre-commit to success/failure criteria |
| Sample too small | False patterns | Calculate minimum sample before starting |
| Survey-only validation | Stated ≠ revealed preference | Combine surveys with behavioral tests |
| Long time between experiments | Slow learning, expensive | Rapid iteration loops |
| Testing everything at once | Ambiguous results | One hypothesis per experiment |
| Ignoring failure signals | Expensive pivot later | Pre-mortem every experiment |
