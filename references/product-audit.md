# PRODUCT AUDIT METHODOLOGY — REFERENCE

> For Mode B: Existing Product Intelligence.
> The systematic investigation of what a product actually delivers vs. what it claims.

---

## THE AUDIT PHILOSOPHY

**A product audit is not a feature list review.**

It is a deep investigation into:
- What VALUE was promised (marketing, positioning, claims)
- What VALUE was delivered (actual consumer experience)
- Where the gap lives (by TCV dimension)
- What VALUE is being DESTROYED (negative value)
- What VALUE is MISSING (unaddressed consumer needs)
- What VALUE could be AMPLIFIED (underutilized strengths)

---

## AUDIT STRUCTURE

### Phase 1: Promise Audit

Document the product's value claims across all channels:

```
VALUE PROMISE INVENTORY:

Marketing promises:
  - [Specific claim 1] → Dimension: [Functional/Social/Emotional/Epistemic/Conditional/Economic]
  - [Specific claim 2] → Dimension: [...]

Onboarding promises:
  - [What users are told they'll get]

Feature descriptions promises:
  - [What specific features claim to deliver]

Pricing page promises:
  - [What each tier claims to offer]

Support documentation promises:
  - [Implied reliability and response standards]
```

---

### Phase 2: Delivery Audit

Investigate what the product actually delivers:

```
Evidence sources to investigate:
  - User reviews (App Store, Google Play, G2, Trustpilot, Capterra)
  - Forum discussions (Reddit, community forums, Quora)
  - Social media sentiment (Twitter/X, LinkedIn)
  - Support tickets / FAQ patterns (if accessible)
  - Influencer/review content
  - Personal use testing (when possible)
  - Return/refund rate signals

For each TCV dimension, assess:
  FUNCTIONAL DELIVERY:
    Performance: [Actual vs. promised]
    Reliability: [Uptime, failure patterns, edge cases]
    Feature completeness: [What works, what's broken, what's missing]
    Usability: [Real-world friction points]
    
  SOCIAL DELIVERY:
    Brand perception: [How users are actually perceived using this]
    Community quality: [Active, helpful, toxic, non-existent?]
    Status signal actual vs. intended: [Is it conferring desired status?]
    
  EMOTIONAL DELIVERY:
    Trust level: [Do users feel safe relying on this?]
    Satisfaction sentiment: [Overall emotional experience]
    Frustration triggers: [What consistently disappoints?]
    Delight moments: [What exceeds expectations?]
    
  EPISTEMIC DELIVERY:
    Learning curve reality: [Steeper or flatter than promised?]
    Discovery depth: [Is there depth to explore?]
    Innovation cadence: [How often does the product genuinely improve?]
    
  CONDITIONAL DELIVERY:
    Performance in peak use cases: [Does it excel when it matters most?]
    Performance in edge cases: [How does it fail in non-ideal conditions?]
    
  ECONOMIC DELIVERY:
    Total cost reality: [Hidden costs discovered after purchase?]
    ROI delivery: [Actual value created vs. price paid?]
    Price fairness perception: [Do users feel fairly treated?]
```

---

### Phase 3: Gap Analysis

For each dimension, calculate:

```
VALUE GAP ANALYSIS:

PROMISE SCORE (what was claimed): 1-10
DELIVERY SCORE (what was delivered): 1-10
GAP = Promise - Delivery

Gap > +3: SIGNIFICANT VALUE DESTRUCTION — urgent fix required
Gap +1 to +3: MINOR UNDERDELIVERY — improve to meet expectations
Gap -1 to +1: VALUE EQUILIBRIUM — claims match delivery
Gap < -1: OVERDELIVERY — positive surprise, potential marketing asset
```

---

### Phase 4: Value Destruction Identification

Value destruction occurs when the product actively makes things worse.

**Types of Value Destruction:**

| Type | Example | Dimension |
|------|---------|-----------|
| Functional failure | App crashes during critical moment | Functional |
| Privacy violation | Unexpected data sharing | Emotional + Economic |
| Community toxicity | Platform enables harassment | Social |
| Pricing deception | Undisclosed price increase | Economic + Emotional |
| Feature regression | Removing loved features | Functional + Emotional |
| Complexity bloat | UI becomes harder with each update | Functional |
| Support failure | Issues ignored for weeks | Emotional |
| Lock-in exploitation | Making export deliberately hard | Economic |

**Severity Rating:**
```
Level 1 (Minor): Causes frustration, rarely causes churn
Level 2 (Moderate): Causes churn for some segments
Level 3 (Severe): Causes immediate churn and negative word-of-mouth
Level 4 (Critical): Causes public crisis, brand damage
```

---

### Phase 5: Strength Identification

What does this product do better than any alternative?

```
For each identified strength:
  - What TCV dimension does it serve?
  - How significant is this dimension to target consumers?
  - Is this strength defensible (or easily copied)?
  - Is this strength currently marketed clearly?
  - Could this strength be amplified further?
  - Are there adjacent segments who'd value this strength even more?
```

---

## IMPROVEMENT PRIORITY MATRIX

After the full audit, categorize findings:

```
CRITICAL (Fix immediately — causing significant harm):
  - [Finding]: [Impact] → [Recommended action]
  
HIGH (Fix in next release cycle — causing meaningful friction):
  - [Finding]: [Impact] → [Recommended action]
  
MEDIUM (Plan for roadmap — meaningful improvement opportunity):
  - [Finding]: [Impact] → [Recommended action]
  
LOW (Backlog — nice to improve, not urgent):
  - [Finding]: [Impact] → [Recommended action]
  
INVESTIGATE (Unclear — needs more data before deciding):
  - [Finding]: [What evidence would clarify priority?]
```

---

## COHORT-SPECIFIC AUDIT

Different consumer segments may experience dramatically different value.

**Audit by segment:**

```
POWER USERS (top 20% by usage):
  - What do they love most?
  - What do they complain about despite staying?
  - What would cause them to leave?
  - What do they wish existed?

NEW USERS (first 30 days):
  - What causes the activation drop-off?
  - What was the "aha moment" for those who stayed?
  - What confused them most?
  - What took longer than expected to understand?

CHURNED USERS (stopped using):
  - What was the final straw?
  - Was there a pattern to their departure point?
  - What did they switch to?
  - Is their need now unmet or met elsewhere?

NON-IDEAL USERS (using for wrong job):
  - What job are they actually trying to do?
  - Are they being served, or creating noise in the data?
  - Should they be part of the target segment?
```

---

## AUDIT REPORT STRUCTURE

```
01. AUDIT OVERVIEW
    - Product: [Name, version, platform]
    - Audit date: [Date]
    - Evidence sources: [List with dates]
    - Overall confidence: [%]
    - Overall verdict: [3-word summary]

02. VALUE PROMISE INVENTORY
    [Complete promise audit]

03. VALUE DELIVERY ASSESSMENT (by TCV dimension)
    [Detailed delivery findings with evidence]

04. VALUE GAP MATRIX
    [Promise vs. Delivery by dimension]

05. VALUE DESTRUCTION MAP
    [Critical failures with severity ratings]

06. STRENGTH INVENTORY
    [Defensible advantages]

07. IMPROVEMENT PRIORITY MATRIX
    [Critical / High / Medium / Low / Investigate]

08. COMPETITIVE IMPLICATION
    [How gaps compare to competitive landscape]

09. STRATEGIC RECOMMENDATIONS
    [Prioritized improvement initiatives]

10. VALIDATION EXPERIMENTS
    [How to confirm key findings]
```
