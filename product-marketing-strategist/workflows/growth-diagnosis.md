<growth_diagnosis_workflow>

<objective>Diagnose why growth has stalled, declined, or underperformed expectations using Reforge and Growth Rockstar diagnostic frameworks. Move from symptoms to root causes to actionable recommendations.</objective>

<required_reading>
- references/reforge-growth.md (Four Fits, Growth Loops, Retention Framework)
- references/growth-rockstar-insights.md (Churn Diagnostics, Growth Quantitative Models, User Psychology)
- references/anti-patterns.md (all — growth problems often stem from known anti-patterns)
</required_reading>

<process>

**Phase 1: Symptom identification**

Ask the user to describe the growth problem in specific, measurable terms:

- "What metric has changed, by how much, and over what time period?"
- "Is this a sudden change or a gradual trend?"
- "What have you already tried to fix it?"
- "When was the last time growth was on track?"

Common symptom categories:
1. **Declining signups / trial starts**: Top-of-funnel problem
2. **Falling activation rates**: Onboarding or expectation-setting problem
3. **Increasing churn / declining retention**: Product value or competitive problem
4. **Revenue growth slowing despite user growth**: Monetization or expansion problem
5. **Rising CAC with flat conversion**: Channel saturation or positioning problem
6. **Growth plateauing at a level below target**: Market size or loop efficiency problem

**Phase 2: Growth equation decomposition**

Break the growth equation apart:

```
Net New Users = (Organic + Paid + Viral + Reactivated) - Churned
```

For revenue:
```
Net New Revenue = (New Revenue + Expansion Revenue) - (Contraction Revenue + Churn Revenue)
```

For each component, ask:
- What is the current value?
- What is the trend (improving, flat, declining)?
- What is the benchmark or target?

Identify which specific component(s) are driving the overall growth problem. Most growth problems are caused by 1-2 components, not all of them.

**Phase 3: Four Fits health check**

Run a systematic check of each fit:

**Market-Product Fit:**
- Is the problem you solve still urgent? Has the market changed?
- Has a new alternative emerged that redefines the category?
- Are you attracting the right users? (Check: are your best customers' profiles matching your target ICP?)
- Signal: If churn is high across all cohorts, the problem may be here.

**Product-Channel Fit:**
- Has your primary acquisition channel degraded? (Algorithm changes, rising costs, saturation)
- Is the product experience still aligned with the channel? (e.g., Is the free trial still compelling enough for PLG?)
- Signal: If CAC is rising but product has not changed, the problem may be here.

**Channel-Model Fit:**
- Have economics shifted? (ARPU down, costs up, payback period extending)
- Are you using channels that your model cannot support?
- Signal: If LTV:CAC ratio is declining, the problem may be here.

**Model-Market Fit:**
- Are you reaching the ceiling of your current segment?
- Is the addressable market smaller than projected?
- Signal: If growth is plateauing despite good execution, the problem may be here.

**Phase 4: Retention deep dive**

Using Growth Rockstar's churn taxonomy, analyze retention by type:

1. **Plot cohort retention curves**: Are they flattening? At what level? Is the flattening point getting worse over time?

2. **Segment by churn timing**:
   - Day 0-7 churn rate: ___% → If high, problem is activation/onboarding
   - Day 7-30 churn rate: ___% → If high, problem is engagement/habit formation
   - Day 30+ churn rate: ___% → If high, problem is ongoing value/competition

3. **Segment by user type**: Is churn concentrated in a specific segment? (Plan type, company size, use case, acquisition channel)

4. **Identify the "aha moment"**: What action separates users who retain from those who churn? At what point does retention stabilize?

**Phase 5: Growth loop audit**

If a growth loop exists, audit its health:

- Map every step in the loop with conversion rates
- Identify the weakest link (lowest conversion step)
- Calculate the overall loop efficiency
- Compare to previous periods — has efficiency declined?
- Check for "loop leakage" — users who exit the loop before completing a cycle

If no growth loop exists, this is likely a core part of the problem. Growth without a loop is dependent on continuous investment (paid acquisition, content production) with no compounding.

**Phase 6: Root cause synthesis**

Synthesize findings into a root cause analysis:

```
SYMPTOM: [What the user reported]
CONTRIBUTING FACTORS: [What the data shows]
ROOT CAUSE: [The underlying strategic issue]
FIT AFFECTED: [Which of the Four Fits is broken or degraded]
```

Common root cause patterns:
- "You have an activation problem disguised as an acquisition problem" (throwing more users into a broken funnel)
- "You have a positioning problem disguised as a churn problem" (attracting wrong users who were never going to retain)
- "You have a channel saturation problem disguised as a market problem" (the market is fine, your channel is exhausted)
- "You have a product-market fit regression" (the market evolved and the product did not)

**Phase 7: Prioritized recommendations**

Deliver 3-5 recommendations, ranked by:
1. **Impact**: How much will this move the needle?
2. **Confidence**: How sure are we this is the right fix?
3. **Effort**: How hard is it to implement?

For each recommendation:
- What to do (specific action)
- Why it addresses the root cause
- How to measure if it is working
- Timeline for expected impact
- What to do if it does not work (Plan B)

Format as:
```
RECOMMENDATION #[N]: [Title]
Impact: High/Medium/Low
Confidence: High/Medium/Low
Effort: High/Medium/Low
Action: [Specific steps]
Metric: [How to measure success]
Timeline: [When to expect results]
```

</process>

<success_criteria>
- Symptoms are defined in specific, measurable terms
- Growth equation is decomposed with real numbers (or identified gaps)
- All four fits are assessed
- Retention is analyzed by timing and segment
- Growth loop is audited (or absence is flagged)
- Root causes are clearly stated with supporting evidence
- Recommendations are prioritized by impact, confidence, and effort
- Anti-patterns are identified if present
</success_criteria>

</growth_diagnosis_workflow>
