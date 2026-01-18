---
name: competitive-strategy-analysis
description: "Deep competitive analysis and growth opportunity identification. Maps competitive landscape, identifies untapped growth levers, and prioritizes actions by impact and feasibility. Use for strategic planning, market positioning, competitive intelligence, growth strategy, and opportunity assessment."
version: 1.0.0
created: 2026-01-18
license: MIT
---

# Competitive Strategy Analysis

**Purpose**: Conduct comprehensive competitive analysis to identify high-impact growth opportunities and strategic advantages for your business.

**Use case**: When you need to understand your competitive landscape, find untapped growth levers, and prioritize strategic actions based on impact and feasibility.

**Based on**: "$20K Growth Consultant" prompt framework

---

## What This Skill Does

This skill performs deep competitive research and strategic analysis to:

1. **Map your competitive landscape** - Identify direct competitors and adjacent-space disruptors
2. **Spot opportunity gaps** - Find growth/profitability levers your competitors use that you don't
3. **Prioritize actions** - Score opportunities on Impact × Feasibility to recommend top 3 moves

Unlike generic competitive analysis, this goes VERY deep - researching 100+ sources including competitor websites, analytics platforms, forums, articles, and industry data.

---

## How to Use This Skill

### For ChatGPT/Claude/AI Users

**Step 1: Prepare your context**

Before using this skill, gather:

```markdown
## Your Company Context

**Company Name**: [Your company name]
**Industry**: [Your specific industry/sector]

**What You Do Today**:
[One paragraph describing:
- Your core product/service
- Key revenue streams
- Pricing model
- Customer segments
- Current growth tactics]

**Known Challenges**:
[List your biggest obstacles:
- Slowing user growth?
- Rising customer acquisition costs?
- Competitive pressure?
- Market saturation?
- Regulatory issues?]
```

**Step 2: Run the analysis**

Paste this into ChatGPT/Claude:

```
You are a top-tier strategy consultant with deep expertise in competitive analysis, growth loops, pricing, and unit-economics-driven product strategy.

[Paste your company context from Step 1]

Please analyze:

1. MAP COMPETITIVE LANDSCAPE
   - Identify 3-5 direct competitors
   - Add 1-2 adjacent-space disruptors
   - For each: positioning, pricing, recent strategic moves

2. SPOT OPPORTUNITY GAPS
   - Compare my current tactics to competitors
   - Highlight at least 5 high-impact growth or profitability levers NOT currently exploited by my company
   - Focus on tactics competitors use successfully that I'm missing

3. PRIORITIZE ACTIONS
   - Score each lever on:
     * Impact (revenue/margin upside): 1-5 scale
     * Feasibility (time-to-impact, resource need): 1-5 scale
   - Recommend top 3 actions with strongest Impact × Feasibility
   - For each: rationale + first next step

IMPORTANT:
- Go VERY deep in research (100+ web pages if needed)
- Research competitor websites, analytics, forums, articles, case studies
- If information is unavailable, state that explicitly
- Provide sources for key findings
```

**Step 3: Review output**

You'll receive:
- Competitive landscape summary
- Untapped opportunity levers
- Prioritized action table with scores
- Sources/references

---

## Context Requirements

**Required for quality analysis:**

- [ ] **Company details** - What you do, how you make money, who you serve
- [ ] **Current state** - Your revenue streams, pricing, growth tactics
- [ ] **Known challenges** - What's not working, where you're stuck
- [ ] **Industry context** - Your specific market/sector

**Optional (enhances accuracy):**

- [ ] Your target market size
- [ ] Current revenue/growth metrics
- [ ] Resource constraints (budget, team size)
- [ ] Strategic priorities for next 6-12 months

---

## Output Format

**1. COMPETITIVE LANDSCAPE**

Table or bullets covering:
- Competitor name
- Their positioning (how they differentiate)
- Their pricing model
- Recent strategic moves (launches, pivots, funding)
- Key strengths/weaknesses

**2. OPPORTUNITY GAPS**

Numbered list of untapped levers:
1. **[Opportunity Name]**
   - What competitors are doing
   - Why you're not doing it yet
   - Potential impact if you adopted it

**3. PRIORITIZED ACTIONS**

Table format:

| Action | Impact (1-5) | Feasibility (1-5) | Score | Rationale | First Next Step |
|--------|-------------|-------------------|-------|-----------|-----------------|
| [Action 1] | X | Y | X×Y | Why this matters | Immediate action |
| [Action 2] | X | Y | X×Y | Why this matters | Immediate action |
| [Action 3] | X | Y | X×Y | Why this matters | Immediate action |

**4. SOURCES**

Numbered list of:
- URLs researched
- Publications/reports cited
- Data sources used

---

## Example Input/Output

### Input

```markdown
## Company Context

**Company Name**: StreamLearn
**Industry**: Online education / EdTech

**What We Do**:
We offer live cohort-based courses for professionals learning technical skills (data science, programming, AI). Revenue comes from $2K-5K course fees. We target mid-career professionals (30-45) looking to upskill. Current growth: email list + LinkedIn content marketing.

**Known Challenges**:
- Course completion rates dropping (60% → 45%)
- Customer acquisition cost rising ($200 → $400)
- Competition from self-paced platforms (Coursera, Udemy)
- Struggling to differentiate from bootcamps
```

### Output

**1. COMPETITIVE LANDSCAPE**

- **Coursera** - Self-paced, university partnerships, $49-99/month subscription
  - Recent: Added AI-powered learning paths
  - Strength: Brand, scale, affordability
  - Weakness: Low completion rates, no live interaction

- **Lambda School (Bloom Institute)** - Income share agreements, bootcamp model
  - Recent: Shift to upfront payment due to regulatory pressure
  - Strength: Outcomes guarantee, job placement
  - Weakness: High cost, long commitment (9 months)

- **Maven** - Live cohort platform, creator-led, premium pricing
  - Recent: Raised $25M, expanding beyond tech education
  - Strength: Creator network, community focus
  - Weakness: Limited course selection, high prices

*(+ 2 more competitors)*

**2. OPPORTUNITY GAPS**

1. **Income Share Agreements / Outcomes Guarantee**
   - Lambda School does this successfully
   - We haven't explored due to complexity
   - Could differentiate vs self-paced platforms

2. **AI-Powered Personalized Learning Paths**
   - Coursera investing heavily here
   - We still use fixed curriculum
   - Could improve completion rates

3. **Job Placement / Career Services**
   - Bootcamps include this as core value prop
   - We only offer course content
   - Could justify premium pricing

*(+ 2 more gaps)*

**3. PRIORITIZED ACTIONS**

| Action | Impact | Feasibility | Score | Rationale | First Next Step |
|--------|--------|-------------|-------|-----------|-----------------|
| Add basic job placement support | 5 | 4 | 20 | Differentiates vs self-paced, justifies price, addresses key pain point | Survey recent graduates on job search needs |
| Implement cohort accountability system | 4 | 5 | 20 | Low-cost way to boost completion (45%→60%), proven by Maven | Add weekly peer check-ins and progress tracking |
| Launch outcomes-based pricing pilot | 5 | 2 | 10 | High impact but complex to implement, regulatory risk | Research ISA providers and compliance requirements |

**4. SOURCES**

1. Coursera 2023 earnings call transcript
2. Lambda School lawsuit documents (outcomes data)
3. Maven course catalog analysis
4. EdTech funding database (Crunchbase)

*(+ 10 more sources)*

---

## Why This Works Better Than a Prompt

**Traditional prompt approach:**
❌ Generic, one-time analysis
❌ Shallow research (5-10 sources)
❌ No structured prioritization framework
❌ Results vary by how well you explain context

**Skill with structured process:**
✅ Deep research protocol (100+ sources)
✅ Consistent Impact × Feasibility scoring
✅ Actionable first steps, not just ideas
✅ Reusable framework for ongoing competitive intelligence

---

## Tool Integrations

This skill can be adapted to work with your tools:

**For Google Docs users:**
- Export analysis as Google Doc with table formatting
- Create linked strategy document

**For Notion users:**
- Format as Notion database for tracking competitors
- Link to opportunity backlog

**For Obsidian users:**
- Create competitor notes with frontmatter
- Build competitive intelligence vault

**For project management tools (Asana, Linear):**
- Convert prioritized actions to tasks with Impact/Feasibility labels
- Link to strategic initiatives

**How to adapt:**
1. Take the output format above
2. Map to your tool's structure (tables, databases, tasks)
3. Add tool-specific metadata (tags, dates, owners)

---

## Tips for Best Results

**To get deeper insights:**
- Be specific about your challenges (not "growth is slow" but "CAC increased from $200 to $400 in 6 months")
- Name specific competitors if you know them
- Mention what you've already tried (so AI doesn't suggest it)

**To improve feasibility scores:**
- Include your resource constraints (budget, team size)
- Note your technical capabilities
- Mention regulatory or market constraints

**To ensure actionable output:**
- Ask for "first next step" for each recommendation
- Request specific tools/vendors when relevant
- Ask for timeline estimates (weeks vs months)

---

## Limitations

**What this skill does well:**
✅ Identify obvious competitive gaps
✅ Surface publicly available strategies
✅ Provide structured prioritization framework

**What this skill doesn't do:**
❌ Access proprietary competitor data
❌ Validate opportunities with real customer research
❌ Account for your internal politics/culture
❌ Replace deep domain expertise

**Best used as:**
- Starting point for strategic planning
- Rapid competitive intelligence gathering
- Framework for prioritizing opportunities

**Should be combined with:**
- Customer interviews and validation
- Financial modeling of opportunities
- Internal stakeholder alignment

---

## Customization

You can modify this skill for specific needs:

**For B2B SaaS:**
- Add section on pricing/packaging analysis
- Include GTM motion comparison (sales-led vs product-led)
- Analyze integration ecosystems

**For E-commerce:**
- Add merchandising strategy analysis
- Include conversion funnel comparison
- Analyze shipping/fulfillment approaches

**For Content/Media:**
- Add content strategy analysis
- Include distribution channel comparison
- Analyze monetization models

**For Services:**
- Add delivery model comparison
- Include pricing structure analysis
- Analyze client acquisition tactics

---

## Related Skills

- `/market-research` - Deep dive into target market and customer needs
- `/pricing-strategy` - Analyze pricing models and optimize your pricing
- `/growth-strategy` - Broader growth planning beyond competitive moves

---

## Notes

**Origin**: Based on viral LinkedIn prompt by Khizer Abbas, described as "$20K growth consultant" prompt.

**Key improvement over original**: Added structured output format, clearer instructions for depth of research, and explicit prioritization framework.

**Best for**: Established businesses with 1+ years in market. Less useful for pre-launch startups (not enough competitive data).

**Frequency**: Run quarterly or when planning major strategic shifts. Competitive landscape changes fast.

---

**Prompts are good. Skills with memory are better.**

Stop copy-pasting prompts. Use this skill framework repeatedly for consistent competitive intelligence.
