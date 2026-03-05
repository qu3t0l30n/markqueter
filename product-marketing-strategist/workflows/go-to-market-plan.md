<go_to_market_workflow>

<objective>Build a go-to-market strategy grounded in the Four Fits framework, growth loops, and continuous discovery. This is not a launch plan — it is the strategic system for connecting product value to market demand.</objective>

<required_reading>
- references/reforge-growth.md (Four Fits, Growth Loops, Monetization, Product Strategy Stack)
- references/growth-rockstar-insights.md (GTM as a System, Virality, Growth Quantitative Models, User Psychology)
- references/cagan-principles.md (Product Operating Model, Discovery, Empowered Teams)
- references/anti-patterns.md (Strategy-Free Tactics, Acquisition Addiction, TAM Fantasy)
</required_reading>

<process>

**Phase 1: Four Fits assessment**

Before building any GTM plan, audit the four fits. Ask the user to describe their current state for each:

1. **Market-Product Fit**: "Who is your target customer? How urgent is their problem? How are they solving it today? What evidence do you have that they want what you are building?"

2. **Product-Channel Fit**: "How do customers currently discover products like yours? Is your product designed to work with that channel? (e.g., Is there a self-serve trial for PLG? Is it demo-able for sales-led?)"

3. **Channel-Model Fit**: "What is your pricing model and average deal size? Does it support the acquisition channels you plan to use? (A $10/mo product cannot support an enterprise sales team)"

4. **Model-Market Fit**: "Is the market large enough to support your revenue goals with your pricing model? Show the math: ARPU × Addressable customers × Realistic capture rate = ?"

**Score each fit**: Strong / Emerging / Weak / Missing

If any fit is "Missing" — that is the #1 priority. No GTM plan survives a missing fit. Help the user address the gap before proceeding.

**Phase 2: GTM motion selection**

Based on the Four Fits assessment, recommend the primary GTM motion:

| ARPU Range | Primary Motion | Supporting Motions |
|-----------|---------------|-------------------|
| < $100/yr | Product-led growth (PLG) | Content, community, viral |
| $100 - $1K/yr | PLG + Inside sales | Content, paid, partner |
| $1K - $10K/yr | Inside sales + PLG | Content, ABM, events |
| $10K - $100K/yr | Field sales + ABM | Content, events, partner |
| > $100K/yr | Enterprise sales | ABM, strategic partner, executive engagement |

For each motion, specify:
- **Primary acquisition channel**: Where you invest most
- **Supporting channels**: 1-2 channels that amplify the primary
- **Channel you should NOT use**: Based on Four Fits analysis
- **Rationale**: Why this motion fits your four fits

**Phase 3: Growth loop design**

Identify and design the primary growth loop for the product:

1. **Map the current loop** (if one exists):
   - Input: What brings a new user into the system?
   - Action: What do they do that generates value?
   - Output: What does that action produce that could attract the next user?
   - Loop back: How does the output connect to the next input?

2. **Evaluate loop health**:
   - Cycle time: How long does one loop iteration take?
   - Conversion rates: At each step, what % of users progress?
   - K-factor (for viral loops): Is it > 1, between 0.5-1, or < 0.5?
   - Compounding: Does each loop iteration make the next one stronger?

3. **Design improvements**:
   - Where is the biggest drop-off in the loop?
   - What is the highest-leverage improvement? (usually reducing friction at the weakest step)
   - Can you add a secondary loop that reinforces the primary?

**Phase 4: Customer journey and messaging map**

Map the GTM messaging to the customer's buying journey:

| Stage | Customer mindset | Key question | Messaging focus | Channel | Content type |
|-------|-----------------|-------------|----------------|---------|-------------|
| Unaware | Does not know they have a problem | "Is this even a problem?" | Problem education, market trend | Content, social, events | Thought leadership, research |
| Problem-aware | Knows the problem, exploring solutions | "What options exist?" | Solution category, approach | SEO, content, community | Comparison guides, frameworks |
| Solution-aware | Evaluating specific solutions | "Why you vs. alternatives?" | Differentiation, proof | Sales, demo, review sites | Case studies, ROI calculator |
| Decision | Ready to buy, needs confidence | "Will this work for me?" | Risk reduction, social proof | Sales, customer success | References, pilot program |
| Onboarding | New user, needs to activate | "How do I get value fast?" | Time-to-value, quick wins | In-app, email, docs | Tutorials, templates |
| Expansion | Active user, could do more | "What else can I do?" | Advanced use cases, ROI | CS, in-app, community | Advanced guides, webinars |
| Advocacy | Power user, could refer | "Can I share this?" | Community, recognition | Community, referral program | Referral tools, badges, events |

**Phase 5: Metrics and measurement**

Define the GTM scorecard:

**Leading indicators** (weekly):
- Traffic / reach by channel
- Signup / trial / demo requests
- Activation rate (% reaching core value)

**Core metrics** (monthly):
- Customer acquisition cost (CAC) by channel
- Conversion rate by stage
- Time to close / time to activate
- Retention rate (Day 7, Day 30, Day 90)

**Lagging indicators** (quarterly):
- Revenue growth rate
- Net revenue retention (NRR)
- LTV:CAC ratio
- Payback period

**Growth model metrics**:
- Primary loop efficiency (conversion at each step)
- Viral coefficient (if applicable)
- Organic vs. paid acquisition mix

**Phase 6: 90-day execution plan**

Break the GTM into a 90-day action plan:

**Month 1 — Foundation**:
- Finalize positioning (use positioning-strategy workflow if not done)
- Set up measurement infrastructure (analytics, attribution, CRM)
- Launch primary channel with minimum viable messaging
- Begin customer discovery cadence (5 interviews/week)

**Month 2 — Iteration**:
- Analyze first month data: What is working? What is not?
- Run messaging A/B tests based on customer feedback
- Expand to one supporting channel
- Refine the growth loop based on data

**Month 3 — Scale**:
- Double down on winning channels and messages
- Kill or deprioritize underperforming tactics
- Launch secondary growth loop or reinforcement
- Build case studies and social proof from early adopters

Output the plan using the `templates/gtm-brief.md` template.

</process>

<success_criteria>
- All four fits are assessed with evidence
- GTM motion is justified by the Four Fits analysis
- At least one growth loop is designed with quantified metrics
- Customer journey messaging map covers all stages
- Metrics scorecard includes leading, core, and lagging indicators
- 90-day plan has specific, actionable steps for each month
- Anti-patterns are checked: no Strategy-Free Tactics, no Acquisition Addiction
</success_criteria>

</go_to_market_workflow>
