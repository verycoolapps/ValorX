# PRODUCT DEVELOPMENT INTELLIGENCE — REFERENCE

> From validated consumer insight to strategic product decision.
> This reference guides the WHAT and HOW of product creation.

---

## PRODUCT STRATEGY FOUNDATION

A product strategy answers four questions:

```
1. WHO are we building for? (Target segment)
2. WHAT problem are we solving? (Core job)
3. HOW do we solve it differently? (Differentiation)
4. WHY will consumers choose us over alternatives? (Value proposition)
```

Every product decision must be traceable to answers to these four questions.
If a feature doesn't serve your target segment's core job differently, it doesn't belong in MVP.

---

## TARGET SEGMENT DEFINITION

### Beyond Demographics

Demographic targeting is table stakes. Behavioral and psychographic targeting is where strategy lives.

**Segment Definition Framework:**

```
SEGMENT NAME: [Memorable descriptor]

Demographic sketch: [Only what's genuinely relevant]

Behavioral profile:
  - Current solutions: [What they use today]
  - Usage pattern: [How often, when, where, with whom]
  - Switching history: [Have they switched before? Why?]

Psychographic profile:
  - Values: [What they care about most]
  - Identity: [How they see themselves]
  - Aspirations: [Who they want to become]

Job priority:
  - Primary job: [The one job that matters most]
  - Secondary jobs: [Important but not primary]
  - Jobs they don't care about: [Explicitly excluded from focus]

TCV priority order:
  - [Which of the 6 value dimensions matters most to this segment, ranked]

Willingness to pay range:
  - Floor: [Minimum viable price perception]
  - Ceiling: [Maximum before they look elsewhere]
  - Sweet spot: [Likely optimal price point]

Access to segment:
  - Where they gather: [Online, offline, communities]
  - What they trust: [Peer recommendation? Expert review? Brand?]
  - How to reach them: [Channels and messages that work]
```

---

## VALUE PROPOSITION DESIGN

### The Single-Sentence VP Test

```
For [TARGET SEGMENT],
who [THEIR PRIMARY JOB],
[PRODUCT NAME] is a [PRODUCT CATEGORY]
that [KEY BENEFIT / VALUE DELIVERED].

Unlike [PRIMARY ALTERNATIVE],
our product [KEY DIFFERENTIATOR].
```

**Quality criteria:**
- Could only your product make this claim? (If competitors could also say it, it's not a differentiator)
- Is it specific enough to believe? (Vague claims destroy credibility)
- Does it connect to a real consumer job? (Product-centric claims fail)
- Does a real target consumer recognize themselves in it?

---

## FEATURE PRIORITIZATION METHODOLOGY

### The Three-Category Filter

Before any feature enters development, classify it:

**MUST-HAVE (Threshold Features)**
- Required for product to function at all
- Their absence causes product failure
- Consumer won't evaluate other features until these exist
- Example: A navigation app that works without internet (offline maps)

**PERFORMANCE FEATURES**
- More is better — directly correlates with satisfaction
- Consumers will pay more or switch for superiority here
- These are where you win or lose against competitors
- Example: Accuracy of search results, speed of transaction

**DELIGHT FEATURES (Latent Features)**
- Consumers didn't know they wanted this
- Their presence creates advocacy
- Their absence doesn't cause dissatisfaction
- Example: Spotify's "Discover Weekly" — nobody asked for it

**INDIFFERENT FEATURES**
- Consumers don't care either way
- Build only if trivially cheap; otherwise skip
- Example: Most configuration options no one touches

**REVERSE FEATURES**
- Causes active dissatisfaction
- Consumers want you to NOT do this
- Example: Autoplay with sound, mandatory account creation

**Decision rule:** MVP = All MUST-HAVEs + Top PERFORMANCE features.
No DELIGHT features until MUST-HAVEs and core PERFORMANCE are solid.

---

## MVP DESIGN PRINCIPLES

An MVP is not a minimal product. It's a maximum-learning vehicle.

### MVP Design Canvas

```
CORE HYPOTHESIS: [The single most important assumption to validate]

MINIMUM VIABLE FUNCTIONALITY:
  - Feature 1: [Addresses which consumer job?]
  - Feature 2: [Addresses which consumer job?]
  - Feature 3: [Addresses which consumer job?]
  
EXPLICITLY OUT OF MVP:
  - [What you're NOT building and why]
  - [What you're NOT building and why]
  
SUCCESS SIGNAL:
  - Primary metric: [What behavior indicates we're right?]
  - Secondary metrics: [Supporting signals]
  - Time horizon: [How long to collect meaningful signal?]
  
FAILURE SIGNAL:
  - [What would tell you the core hypothesis is wrong?]
  - Decision threshold: [At what point do you pivot or kill?]
```

---

## PRODUCT POSITIONING FRAMEWORK

### Positioning Map Construction

1. Identify the two dimensions that matter most to your target segment
2. Map all significant alternatives on those dimensions
3. Identify white space that is both underoccupied AND where real consumer demand exists

```
WHITE SPACE ≠ GOOD POSITIONING
White space where consumers don't want to be = no-man's-land

GOOD POSITIONING = White space where consumers WANT to be but can't get to
```

### Positioning Statement Validation

Your positioning is strong when:
- Target consumers immediately recognize it speaks to them
- Competitors cannot credibly claim the same position
- You can actually deliver the promised value
- The position is sustainable as you scale

---

## PRICING STRATEGY INTELLIGENCE

### Pricing and TCV Connection

| Primary TCV Driver | Pricing Implication |
|-------------------|---------------------|
| Functional Value | Value-based: price to ROI delivered |
| Social Value | Premium pricing reinforces status signal |
| Emotional Value | Price to trust: too cheap signals risk |
| Epistemic Value | Freemium / trial: let novelty drive adoption |
| Conditional Value | Usage-based: charge at the moment of value |
| Economic Value | Competitive pricing: match or beat alternatives |

### Pricing Model Selection

| Model | Best For | Risk |
|-------|---------|------|
| Subscription | Recurring value, behavior-dependent products | Churn at value perception drops |
| One-time purchase | Products with clear, bounded value | No revenue from retention |
| Freemium | Products with network effects or high novelty | Conversion rate optimization required |
| Usage-based | Variable-value products, B2B | Revenue predictability |
| Value-based | Measurable ROI products | Requires clear ROI story |
| Tiered | Multi-segment products | Cannibalization between tiers |

---

## PRODUCT-MARKET FIT INDICATORS

### Leading Indicators (Predict PMF)
- Unsolicited referrals and word-of-mouth
- Organic acquisition exceeding paid
- Users advocate before fully experiencing the product
- Competitors copy your features
- Support volume drops as product matures

### Lagging Indicators (Confirm PMF)
- Retention at Day 7, 30, 90 above category benchmarks
- NPS ≥ 50 (great) or ≥ 30 (good)
- "Very disappointed" if product went away: ≥ 40%
- CAC payback < 12 months
- LTV/CAC > 3

### PMF Failure Signals
- Activation < 30% (consumers try and don't get to value)
- Day 30 retention < category average (not retaining after first value)
- High DAU but low WTP (engaged but not paying)
- Extreme power user concentration (< 10% driving > 80% usage)

---

## PRODUCT ROADMAP PHILOSOPHY

### 30/60/90 Day Roadmap Structure

```
IMMEDIATE (0-30 DAYS):
  Focus: [The single most important thing]
  Action items: [3-5 specific, executable tasks]
  Success metric: [How we'll know this period succeeded]
  
SHORT TERM (30-60 DAYS):
  Focus: [Build on what immediate period validated]
  Action items: [Next prioritized initiatives]
  Success metric: [Leading indicator of next-stage readiness]
  
MEDIUM TERM (60-90 DAYS):
  Focus: [Scale or reposition based on 60-day learnings]
  Action items: [Dependent on earlier learnings]
  Decision trigger: [What would change this plan?]

BEYOND 90 DAYS:
  Ambition: [Where you want to be in 6-12 months]
  Key dependencies: [What must be true for this to happen]
  Major risks: [What could prevent it]
```

**Rule:** 30-day plan must be specific. 90-day plan must be flexible.
If your 90-day plan is too specific, you're not planning — you're pretending to know the future.
