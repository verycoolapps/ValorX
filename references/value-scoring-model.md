# VALUE SCORING MODEL — REFERENCE

> A transparent, explainable scoring methodology for consumer value analysis.
> Scores are analytical tools, not empirical measurements. Label everything.

---

## CORE PRINCIPLES

1. **Transparency** — Every score is explained, not just stated
2. **Evidence labeling** — Every score is tagged with its evidence type
3. **Relative meaning** — Scores gain meaning through comparison, not absolute value
4. **Intellectual honesty** — Uncertainty is stated, not hidden
5. **Actionability** — Scores exist to guide decisions, not impress

---

## EVIDENCE TAXONOMY

Before scoring anything, classify your evidence:

| Label | Symbol | Definition | Weight |
|-------|--------|-----------|--------|
| Measured Data | 📊 | From direct measurement, A/B test, or controlled research | 1.0 |
| Research Finding | 📰 | From published research, industry reports, surveys | 0.8 |
| Consumer Verbatim | 💬 | From actual consumer reviews, interviews, forum posts | 0.7 |
| Expert Judgment | 🎓 | From domain expert assessment | 0.6 |
| Inference | 💡 | Logically derived from other verified facts | 0.5 |
| Hypothesis | 🔮 | Educated guess requiring validation | 0.3 |

**Usage:** When scoring, cite your highest-quality evidence and apply the appropriate confidence weight.

---

## VALUE GAP SCORING

### Step 1: Score Consumer Importance

For each TCV dimension and sub-dimension:

```
SCALE: 1-10

1-2  = Negligible importance — consumers rarely think about this
3-4  = Low importance — nice to have, rarely drives decisions
5-6  = Moderate importance — considered, one of many factors
7-8  = High importance — frequently mentioned, often decisive
9-10 = Critical importance — almost always the primary decision factor
```

**How to score:** Based on evidence of how often this dimension appears in:
- Consumer complaints when absent
- Consumer praises when present
- Switching reasons
- Purchase decision explanations

---

### Step 2: Score Current Market Satisfaction

How well do existing solutions (including competitors) satisfy this dimension?

```
SCALE: 1-10

1-2  = Severely underserved — consumers universally frustrated
3-4  = Underserved — significant gaps, notable consumer pain
5-6  = Adequately served — basic needs met, meaningful gaps remain
7-8  = Well served — consumers largely satisfied, minor gaps
9-10 = Overserved — saturated, further improvement brings minimal value
```

---

### Step 3: Calculate Value Gap

```
VALUE GAP = Consumer Importance - Current Market Satisfaction

Interpretation:
  > +5  = Major unmet need — high strategic priority
  +3 to +5 = Significant opportunity — worth targeting
  +1 to +3 = Moderate opportunity — depends on strategic position
  -1 to +1 = Equilibrium — market is roughly meeting expectations
  < -1  = Overserved — consumers have more than they need here
```

---

## OPPORTUNITY SCORE ENGINE

### Ulwick's Opportunity Algorithm (Adapted)

```
BASE OPPORTUNITY = Importance + (Importance - Satisfaction)

This double-weights importance because:
- High importance = consumer cares
- High gap = market isn't serving it
- Both together = maximum opportunity

If Base Opportunity > 15: Overserved — reduce complexity
If Base Opportunity 10-15: Table stakes — meet, don't differentiate
If Base Opportunity < 10: Underserved — PRIORITIZE
```

### ValorX Enhanced Opportunity Score

For more nuanced prioritization:

```
ENHANCED OPPORTUNITY = (
  Importance × 0.30 +
  Value_Gap × 0.25 +
  Urgency × 0.15 +
  WTP_Signal × 0.15 +
  Feasibility × 0.10 +
  Market_Size × 0.05
) × Evidence_Confidence

Where Evidence_Confidence = 0.3 to 1.0 (from evidence taxonomy above)

Normalize to 0-100:
  Multiply raw score by (100 / max_possible_score)
```

**Definition of each factor:**

| Factor | What to score | Scale |
|--------|--------------|-------|
| Importance | How much consumers care | 1-10 |
| Value_Gap | Importance minus satisfaction | 0-9 |
| Urgency | How time-sensitive the need is | 1-10 |
| WTP_Signal | Signals of willingness to pay | 1-10 |
| Feasibility | Your ability to address it | 1-10 |
| Market_Size | How many consumers have this need | 1-10 |

---

## FEATURE PRIORITIZATION MATRIX

After generating Opportunity Scores, use this matrix:

```
                    HIGH OPPORTUNITY SCORE
                              │
                              │   INVEST & BUILD
         RESEARCH &           │   (high opportunity,
         VALIDATE             │   high feasibility)
         (high opportunity,   │
          low feasibility)    │
                              │
LOW ————————————————————————————————————————— HIGH
FEASIBILITY                   │                FEASIBILITY
                              │
         DEPRIORITIZE         │   QUICK WINS
         (low opportunity,    │   (low opportunity,
          low feasibility)    │   high feasibility)
                              │
                    LOW OPPORTUNITY SCORE
```

---

## TCV DIMENSION SCORING TEMPLATE

Complete this for each analysis:

| Dimension | Importance | Satisfaction | Value Gap | Opportunity | Evidence | Priority |
|-----------|-----------|-------------|-----------|-------------|----------|----------|
| Functional | /10 | /10 | | /100 | 📊/📰/💡/🔮 | 🔴/🟡/🟢/💎 |
| Social | /10 | /10 | | /100 | 📊/📰/💡/🔮 | 🔴/🟡/🟢/💎 |
| Emotional | /10 | /10 | | /100 | 📊/📰/💡/🔮 | 🔴/🟡/🟢/💎 |
| Epistemic | /10 | /10 | | /100 | 📊/📰/💡/🔮 | 🔴/🟡/🟢/💎 |
| Conditional | /10 | /10 | | /100 | 📊/📰/💡/🔮 | 🔴/🟡/🟢/💎 |
| Economic | /10 | /10 | | /100 | 📊/📰/💡/🔮 | 🔴/🟡/🟢/💎 |

**Priority Key:**
- 💎 Diamond (Opportunity Score 75+): Strategic priority, differentiation potential
- 🟢 Green (50-74): Strong opportunity, worth significant investment
- 🟡 Yellow (25-49): Moderate opportunity, worth addressing
- 🔴 Red (<25): Low opportunity, maintain parity only

---

## COMPETITIVE VALUE BENCHMARKING

For head-to-head comparison, score each player on each dimension:

| Dimension | Your Product | Competitor A | Competitor B | Market Best | Your Gap vs Best |
|-----------|-------------|-------------|-------------|-------------|-----------------|
| Functional | | | | | |
| Social | | | | | |
| Emotional | | | | | |
| Epistemic | | | | | |
| Conditional | | | | | |
| Economic | | | | | |
| **TOTAL** | | | | | |

**Interpretation:**
- Positive gap vs. best = you're ahead — defend and amplify
- Neutral gap = parity — monitor, don't invest heavily
- Negative gap = you're behind — close gap or concede dimension

---

## VALIDATION CONFIDENCE SCORING

How confident are we in our analysis?

```
OVERALL CONFIDENCE SCORE:

Weighted average of evidence confidence across all scored dimensions.

If Overall Confidence < 40%:
  "HYPOTHESIS-DRIVEN ANALYSIS — Extensive validation required before major investment"

If Overall Confidence 40-70%:
  "INFERENCE-DRIVEN ANALYSIS — Targeted validation of key assumptions recommended"

If Overall Confidence > 70%:
  "EVIDENCE-DRIVEN ANALYSIS — Foundation solid, refine with ongoing feedback"
```

---

## ANTI-GAMING RULES

Scores are analytical tools. These rules prevent gaming:

1. **Never round up to look impressive** — Report 6.2 as 6.2, not 7
2. **Never inflate opportunity scores to justify pre-decided builds** — The score should inform the decision
3. **Never suppress negative findings** — Weak scores are valuable intelligence
4. **Always show the formula** — Don't deliver a final score without the components
5. **Always date your analysis** — Consumer preferences and markets change
6. **Always note key assumptions** — What would change if assumption was wrong?

---

## SCORE INTERPRETATION CAUTIONS

| Situation | Warning |
|-----------|---------|
| All dimensions scored high | 🚨 Likely optimism bias — recalibrate with harder questions |
| All dimensions scored low | 🚨 Likely pessimism — ensure sufficient market research |
| Opportunity Score > 95 | 🚨 Requires 📊 Measured Data evidence — extraordinary claims need extraordinary evidence |
| Evidence all 🔮 Hypothesis | 🚨 This is not an analysis — it's a guess with structure |
| No negative gaps found | 🚨 Product needs deeper analysis — perfect scores don't exist |
