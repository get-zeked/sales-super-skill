---
name: sales-super-skill
description: Comprehensive end-to-end sales skill merging Perplexity Computer's 6 built-in sales skills with Claude Code's customer interview analysis, brand voice analysis, content research, RICE prioritization, and UX research. Covers the full sales cycle from prospecting to close. Use when doing account research, call prep, competitive intelligence, outreach drafting, asset creation, daily briefings, customer interview analysis, deal prioritization, or prospect research.
license: MIT
metadata:
  author: get-zeked
  version: '1.0'
---

# Sales Super-Skill

The complete sales operating system — merging Perplexity Computer's 6 built-in sales skills with Claude Code's product management, UX research, brand voice, and content frameworks. Covers the full cycle from prospecting to close, from account research to deal prioritization, from competitive intelligence to personalized asset creation.

---

## Table of Contents

1. [Gap Analysis Table](#section-1-gap-analysis-table)
2. [Account Research & Prospect Intelligence](#section-2-account-research--prospect-intelligence)
3. [Call Prep & Meeting Readiness](#section-3-call-prep--meeting-readiness)
4. [Competitive Intelligence & Positioning](#section-4-competitive-intelligence--positioning)
5. [Outreach & Content Creation](#section-5-outreach--content-creation)
6. [Sales Assets & Deliverables](#section-6-sales-assets--deliverables)
7. [Deal Prioritization & Pipeline Management](#section-7-deal-prioritization--pipeline-management)
8. [Unique Perplexity Computer Capabilities](#section-8-unique-perplexity-computer-capabilities)

---

## How to Trigger This Skill

Use this skill when you hear any of these:

| Phrase | Section to Execute |
|--------|--------------------|
| "Research [company]" / "Intel on [company]" | Section 2 — Account Research |
| "Prep me for my call with [company]" | Section 3 — Call Prep |
| "Build battlecard for [competitor]" | Section 4 — Competitive Intel |
| "Draft outreach to [person/company]" | Section 5 — Outreach |
| "Create an asset / landing page / one-pager" | Section 6 — Sales Assets |
| "Morning briefing" / "Start my day" | Section 7 — Daily Briefing |
| "Prioritize my pipeline / deals" | Section 7 — Pipeline Prioritization |
| "Analyze interview transcript" | Section 2 — Customer Interview Analysis |
| "Build customer persona" | Section 2 — Persona Development |
| "Analyze brand voice" | Section 4 & 5 — Voice Analysis |
| "Map user journey" | Section 2 — Journey Mapping |

---

## Section 1: Gap Analysis Table

### What Each System Contributes

| Capability | Perplexity Computer | Claude Code | Merged Super-Skill |
|------------|---------------------|-------------|-------------------|
| **Company research** | Web search, live data, enrichment/CRM integrations | Static frameworks only | Live + structured — real-time web data with PM interview frameworks |
| **Person/contact research** | LinkedIn search, enrichment APIs | Persona generator from JSON data | Live LinkedIn + data-driven persona synthesis |
| **Customer interview analysis** | Basic Q&A extraction | NLP-based pain point/JTBD/sentiment extraction with severity scoring | Full interview ingestion pipeline feeding directly into sales qualification |
| **Prospect persona development** | Role-based talking points | 4-archetype persona generator (Power User, Business User, Casual, Mobile-First) | UX persona archetypes mapped to buyer roles for hyper-targeted messaging |
| **Call preparation** | Meeting prep brief with agenda + objections | Discovery frameworks, PRD review templates | Meeting-type-specific prep (discovery/demo/negotiation/QBR) + deeper discovery question banks |
| **Competitive intelligence** | HTML battlecard with talk tracks, landmine questions, win/loss analysis | None native | Battlecard + brand voice positioning analysis for each competitor |
| **Outreach drafting** | AIDA email, LinkedIn, follow-up sequences | Content framework templates, SEO-optimized copy | Research-first AIDA outreach + brand voice consistency check |
| **Brand voice analysis** | Not available | Formality/tone/readability scoring | Applies to prospect's brand (for tailoring assets) and competitor's brand (for positioning) |
| **Sales asset creation** | Landing pages, decks, one-pagers, workflow demos | Blog/content frameworks, email campaign templates | 7-phase asset creation + content repurposing matrix |
| **Deal prioritization** | Priority ranking heuristics | RICE scoring framework with portfolio analysis | RICE adapted for deals — Reach/Impact/Confidence/Effort scoring per opportunity |
| **Daily briefing** | Pipeline alerts, meeting prep, email priorities | Not available | Briefing + RICE-scored top-3 deal focus |
| **Journey mapping** | Not available | Full B2B SaaS journey mapping (Awareness → Advocacy) | Journey-mapped buyer experience powering discovery questions |
| **Usability/UX research** | Not available | 4 research method frameworks, sample size tables | Translates to sales: understanding how buyers evaluate products |
| **Content calendar** | Not available | 40/25/25/10 pillar ratio, batch creation workflow | Follow-up content sequences with pillar-based cadence |
| **Campaign analytics** | Not available | Attribution, funnel analysis, ROI calculator | Post-deal analysis using attribution model logic |
| **Live web research** | Yes — real-time | No | Perplexity Computer only |
| **Social media monitoring** | Yes — X/Twitter search | No | Perplexity Computer only |
| **Image/video generation** | Yes | No | Perplexity Computer only |
| **Website deployment** | Yes — Netlify/Vercel | No | Perplexity Computer only |
| **App integrations (CRM/email/calendar)** | Yes — 400+ apps | No | Perplexity Computer only |
| **Scheduled monitoring** | Yes — competitor alerts | No | Perplexity Computer only |

### What the Merge Adds That Neither Had Alone

1. **Interview-to-Account-Research Pipeline** — Customer interview analysis results directly feed account research and qualification signals
2. **UX Persona → Buyer Persona Bridge** — UX archetypes (Power User, Business User) map to economic buyer roles, enriching messaging
3. **RICE-Scored Deal Pipeline** — PM prioritization framework applied to deals: Reach = accounts, Impact = deal size, Confidence = win probability, Effort = sales effort required
4. **Brand Voice–Aware Outreach** — Every email draft can be validated against a prospect's brand voice profile before sending
5. **Journey-Mapped Discovery** — B2B buyer journey stages (Awareness → Advocacy) drive discovery question banks for each meeting type
6. **Competitive Positioning via Brand Voice** — Competitor brand voice analysis (formality, tone) reveals positioning gaps you can exploit

---

## Section 2: Account Research & Prospect Intelligence

### Overview

```
┌─────────────────────────────────────────────────────────────────┐
│              ACCOUNT RESEARCH & PROSPECT INTELLIGENCE            │
├─────────────────────────────────────────────────────────────────┤
│  ALWAYS (works standalone via web search)                        │
│  ✓ Company overview: what they do, size, industry               │
│  ✓ Recent news: funding, leadership changes, announcements      │
│  ✓ Hiring signals: open roles, growth indicators                │
│  ✓ Key people: leadership team, LinkedIn profiles               │
│  ✓ Customer interview analysis: pain points, JTBD, sentiment    │
│  ✓ UX persona development from research data                    │
│  ✓ Buyer journey mapping by stage                               │
├─────────────────────────────────────────────────────────────────┤
│  SUPERCHARGED (when you connect your tools)                      │
│  + Enrichment: verified emails, phone, tech stack, org chart    │
│  + CRM: prior relationship, past opportunities, contacts        │
└─────────────────────────────────────────────────────────────────┘
```

### Trigger Phrases

- "Research [Company]" / "Look up [Company]"
- "Intel on [Company or domain]"
- "Who is [Name] at [Company]?"
- "Analyze this interview transcript"
- "Build a persona for [segment]"
- "Map the buyer journey for [persona]"

---

### 2.1 Company Research Workflow

**Step 1: Parse Request**

```
Identify what to research:
- "Research Stripe"                    → Company research
- "Look up Jane Smith at Acme"         → Person + company
- "Who is the CTO at Notion"           → Role-based search
- "Intel on acme.com"                  → Domain-based lookup
- "Analyze this transcript [file]"     → Customer interview analysis
```

**Step 2: Web Search (Always)**

Run these searches in parallel:
1. `"[Company name]"` → Homepage, about page, product
2. `"[Company name] news"` → Recent announcements (last 90 days)
3. `"[Company name] funding"` → Investment history, stage
4. `"[Company name] careers"` → Hiring signals, growth areas
5. `"[Person name] [Company] LinkedIn"` → Profile info
6. `"[Company name] customers"` → Who they serve
7. `"[Company name] technology stack"` → Tooling intel

**Step 3: Enrichment (If Connected)**

```
If enrichment tools available:
1. Enrich company → Firmographics, funding, tech stack
2. Search people  → Org chart, contact list
3. Enrich person  → Email, phone, background
4. Get signals    → Intent data, hiring velocity
```

**Step 4: CRM Check (If Connected)**

```
If CRM available:
1. Search for account by domain
2. Get related contacts and history
3. Get opportunity history (won/lost)
4. Get activity timeline and notes
```

**Step 5: Synthesize**

```
1. Combine all sources
2. Prioritize enrichment data over web (more accurate)
3. Add CRM context if available
4. Identify qualification signals (positive, concerns, unknowns)
5. Generate talking points per contact
6. Recommend approach and entry point
```

---

### 2.2 Account Research Output Format

```markdown
# Research: [Company or Person Name]

**Generated:** [Date]
**Sources:** Web Search [+ Enrichment] [+ CRM]

---

## Quick Take

[2-3 sentences: Who they are, why they might need you, best angle for outreach]

---

## Company Profile

| Field | Value |
|-------|-------|
| **Company** | [Name] |
| **Website** | [URL] |
| **Industry** | [Industry] |
| **Size** | [Employee count] |
| **Headquarters** | [Location] |
| **Founded** | [Year] |
| **Funding** | [Stage + amount if known] |
| **Revenue** | [Estimate if available] |

### What They Do
[1-2 sentence description of their business, product, and customers]

### Recent News
- **[Headline]** — [Date] — [Why it matters for your outreach]
- **[Headline]** — [Date] — [Why it matters]

### Hiring Signals
- [X] open roles in [Department]
- Notable: [Relevant roles like Engineering, Sales, AI/ML]
- Growth indicator: [Hiring velocity interpretation]

---

## Key People

### [Name] — [Title]
| Field | Detail |
|-------|--------|
| **LinkedIn** | [URL] |
| **Background** | [Prior companies, education] |
| **Tenure** | [Time at company] |
| **Email** | [If enrichment connected] |

**Talking Points:**
- [Personal hook based on background]
- [Professional hook based on role]

---

## Tech Stack [If Enrichment Connected]

| Category | Tools |
|----------|-------|
| **Cloud** | [AWS, GCP, Azure, etc.] |
| **Data** | [Snowflake, Databricks, etc.] |
| **CRM** | [Salesforce, HubSpot, etc.] |
| **Other** | [Relevant tools] |

**Integration Opportunity:** [How your product fits their stack]

---

## Prior Relationship [If CRM Connected]

| Field | Detail |
|-------|--------|
| **Status** | [New / Prior prospect / Customer / Churned] |
| **Last Contact** | [Date and type] |
| **Previous Opps** | [Won/Lost and why] |
| **Known Contacts** | [Names already in CRM] |

---

## Qualification Signals

### Positive Signals
- ✅ [Signal and evidence]

### Potential Concerns
- ⚠️ [Concern and what to watch for]

### Unknown (Ask in Discovery)
- ❓ [Gap in understanding]

---

## Recommended Approach

**Best Entry Point:** [Person and why]
**Opening Hook:** [What to lead with based on research]

**Discovery Questions:**
1. [Question about their current situation]
2. [Question about pain points or priorities]
3. [Question about decision process and timeline]

---

## Sources
- [Source 1](URL)
- [Source 2](URL)
```

---

### 2.3 Customer Interview Analysis Framework

Use when you have interview transcripts, call recordings, or notes from customer conversations. Directly feeds account research and qualification signals.

**Trigger:**
- "Analyze this interview transcript"
- "Extract pain points from this call recording"
- "What did this customer say about their workflow?"

**Analysis Process:**

```
Step 1: Code the data
Tag each data point with:
- [GOAL]     — What they want to achieve
- [PAIN]     — What frustrates them (extract severity: HIGH/MEDIUM/LOW)
- [BEHAVIOR] — What they actually do (not what they say they'd do)
- [CONTEXT]  — When/where they use the product or encounter problems
- [QUOTE]    — Direct user words (gold for personalized outreach)
- [JTBD]     — Jobs-to-be-done pattern (When I... I want... So I can...)
- [COMP]     — Competitor mentions
- [BUDGET]   — Budget signals or willingness-to-pay indicators

Step 2: Extract pattern frequency
- 3+ mentions across interviews = confirmed pattern
- 1-2 mentions = hypothesis to validate

Step 3: Map to opportunity areas
- Group pain points → theme clusters
- Score by: Frequency × Severity × Solvability

Step 4: Generate sales intelligence
- Pain points → discovery question bank
- Competitor mentions → battlecard update triggers
- Budget signals → qualification confidence
- JTBD patterns → value proposition refinement
```

**Interview Analysis Output:**

```
============================================================
CUSTOMER INTERVIEW ANALYSIS
============================================================

📋 INTERVIEW METADATA
Customer: [Name, Title, Company]
Date: [Date]
Segments found: [N]

😟 PAIN POINTS ([N] found)

1. [HIGH] [Pain point]
   "[Direct quote from customer]"
   Sales implication: [How to use this in outreach/discovery]

2. [MEDIUM] [Pain point]
   "[Direct quote]"
   Sales implication: [How to use this]

💡 FEATURE REQUESTS / PRIORITIES ([N] found)
1. [Request] — Priority: High
2. [Request] — Priority: Medium

🎯 JOBS TO BE DONE

When [context/trigger]
I want [capability or outcome]
So I can [goal or result]

📊 SENTIMENT ANALYSIS
Overall: [Positive/Neutral/Negative]
Key emotions: [Frustration, Time pressure, Excitement, etc.]
Engagement level: [High / Medium / Low]

💬 KEY QUOTES (for personalized outreach)
• "[Quote 1]"
• "[Quote 2]"

🏷️ THEMES
- [Theme 1]
- [Theme 2]

🏢 COMPETITOR MENTIONS
- [Competitor] — Context: [What they said]

💰 BUDGET/BUYING SIGNALS
- [Signal] — Implication: [How to use in sales process]
```

---

### 2.4 Persona Development from Research Data

Use when building buyer personas from customer data (analytics, surveys, interviews). Bridges UX research to sales targeting.

**Input Format (JSON):**
```json
[
  {
    "user_id": "user_1",
    "role": "VP Engineering",
    "company_size": "Series B",
    "usage_frequency": "daily",
    "features_used": ["dashboard", "reports", "export"],
    "primary_device": "desktop",
    "usage_context": "work",
    "tech_proficiency": 7,
    "pain_points": ["slow reporting", "no API access"],
    "deal_size": 45000,
    "sales_cycle_days": 62
  }
]
```

**Archetype Classification for Sales:**

| Archetype | Signals | Sales Focus | Discovery Angle |
|-----------|---------|-------------|-----------------|
| **Power User / Champion** | Daily use, 10+ features, advanced needs | Efficiency, customization, API access | "What would you automate first?" |
| **Economic Buyer** | Work context, team use, budget awareness | ROI, business impact, risk reduction | "How do you measure success?" |
| **Technical Evaluator** | High tech proficiency, security questions | Architecture, integrations, compliance | "Walk me through your current stack" |
| **Casual / End User** | Weekly use, basic needs, ease-of-use focus | Simplicity, onboarding, support | "What's the hardest part today?" |

**Persona Output Template:**

```
============================================================
BUYER PERSONA: [Name] the [Archetype]
============================================================

📝 One-line summary: [Daily/weekly] user who [primary use case]

Archetype: [Power User / Economic Buyer / Technical Evaluator / End User]
Confidence: [High / Medium / Low] — based on [N] users

👤 Demographics:
  • Role Range: [e.g., VP Engineering, CTO, Director of Data]
  • Company Stage: [Seed / Series A / Series B / Enterprise]
  • Tech Proficiency: [Advanced / Intermediate / Beginner]

🎯 Goals & Needs:
  • [Primary goal]
  • [Secondary goal]
  • [Functional need]

😤 Frustrations (with frequency):
  • [Pain 1] ([N]/[total] users)
  • [Pain 2] ([N]/[total] users)

💼 Sales Implications:
  → Lead with: [angle most relevant to this persona]
  → Proof point: [type of evidence that resonates]
  → Objection to expect: [common pushback]
  → Discovery question: [best question to qualify]

📈 Deal Profile:
  • Average deal size: $[X]
  • Typical sales cycle: [N] days
  • Key stakeholders in decision: [roles]
```

---

### 2.5 Buyer Journey Mapping

Map the stages your buyers go through from awareness to advocacy. Use to build discovery questions for each stage and identify where deals stall.

**B2B SaaS Buyer Journey:**

```
Awareness → Evaluation → Onboarding → Adoption → Advocacy
```

**Stage-by-Stage Intelligence:**

| Stage | Buyer Actions | Touchpoints | Emotions | Your Sales Role | Discovery Questions |
|-------|---------------|-------------|----------|-----------------|---------------------|
| **Awareness** | Researching pain, seeing content, peer referrals | Blog, LinkedIn, G2, conferences | Frustrated, curious | Create urgency, be the catalyst | "What made you start looking at this now?" |
| **Evaluation** | Demo requests, trials, RFPs, vendor comparison | Product demos, trials, sales calls | Analytical, cautious | Remove barriers, build confidence | "What does your evaluation process look like?" |
| **Onboarding** | Implementation, training, configuration | Customer success, support | Anxious, hopeful | Ensure quick wins | "What would success look like in 30 days?" |
| **Adoption** | Regular use, team rollout, integrations | Usage analytics, QBRs | Confident, invested | Expand usage, prove ROI | "Who else in your org could benefit from this?" |
| **Advocacy** | Case studies, referrals, reviews | Reference calls, G2 reviews | Proud, loyal | Activate references, expand | "Who else do you know that has this problem?" |

**Opportunity Score:** Frequency × Severity × Solvability (1–5 each)

**Where Deals Stall (Common Bottlenecks):**

| Stage | Common Stall Reason | Intervention |
|-------|--------------------|-----------------------------|
| Awareness → Evaluation | No urgency established | Attach to a trigger event (news, hire, initiative) |
| Evaluation → Decision | Multi-stakeholder misalignment | Build champion kit + executive one-pager |
| Decision → Close | Legal/procurement delay | Start paperwork earlier; use order form template |
| Onboarding → Adoption | Poor implementation | Assign CSM at contract signature |

---

### 2.6 Research Variations

| Research Type | Focus | Key Output |
|--------------|-------|------------|
| **Company Research** | Business overview, news, hiring, leadership | Company profile + recommended approach |
| **Person Research** | Background, role, LinkedIn activity, talking points | Contact brief + hooks |
| **Competitor Research** | Product comparison, positioning, win/loss | Feeds Section 4 battlecard |
| **Pre-Meeting Research** | Attendee backgrounds, recent news, relationship history | Feeds Section 3 call prep |
| **Customer Interview Analysis** | Pain points, JTBD, sentiment, competitor mentions | Qualification signals + discovery question bank |

---

## Section 3: Call Prep & Meeting Readiness

### Overview

```
┌─────────────────────────────────────────────────────────────────┐
│                        CALL PREP                                 │
├─────────────────────────────────────────────────────────────────┤
│  ALWAYS (works standalone)                                       │
│  ✓ You tell me: company, meeting type, attendees                │
│  ✓ Web search: recent news, funding, leadership changes         │
│  ✓ Output: prep brief with agenda, questions, objections        │
│  ✓ Journey-stage-aware discovery questions                      │
│  ✓ Persona-mapped talking points per attendee                   │
├─────────────────────────────────────────────────────────────────┤
│  SUPERCHARGED (when you connect your tools)                      │
│  + CRM: account history, contacts, opportunities, activities    │
│  + Email: recent threads, open questions, commitments           │
│  + Chat: internal discussions, colleague insights               │
│  + Transcripts: prior call recordings, key moments              │
│  + Calendar: auto-find meeting, pull attendees                  │
└─────────────────────────────────────────────────────────────────┘
```

### Trigger Phrases

- "Prep me for my call with [Company]"
- "I'm meeting with [Company], prep me"
- "Call prep [Company]"
- "Get me ready for [Meeting type] with [Company]"

---

### 3.1 Context Gathering

**Required inputs:**
- Company or contact name
- Meeting type (discovery / demo / negotiation / check-in / QBR)

**Helpful if available:**
- Attendee names and titles
- Prior notes, emails, or context to paste
- What you want to accomplish ("I want to get them to agree to a pilot")
- Known concerns ("They mentioned budget is tight")

**If connectors are active, pull automatically:**

```
1. Calendar → Find upcoming meeting matching company name
   Pull: title, time, attendees, description, attachments

2. CRM → Query account
   Pull: account details, all contacts, open opportunities
   Pull: last 10 activities, account notes, competitor field

3. Email → Search recent threads
   Query: emails with company domain (last 30 days)
   Extract: key topics, open questions, commitments

4. Chat → Search internal discussions
   Query: company name mentions (last 30 days)
   Extract: colleague insights, competitive intel, red flags

5. Transcripts → Find prior calls
   Pull: call recordings with this account
   Extract: key moments, objections raised, topics covered
```

---

### 3.2 Meeting Type Playbooks

#### Discovery Call
- **Goal:** Understand their world, qualify the opportunity
- **Agenda emphasis:** Questions > Talking (70/30 ratio)
- **Key output:** Qualification signals, next step proposal
- **Duration:** 30–45 minutes

**Discovery Question Bank (Journey-Stage Mapped):**

```
Situation Questions (understand current state):
1. "Walk me through your current process for [relevant workflow]."
2. "How long has this been the way you've handled [area]?"
3. "Who else is involved in [process]?"

Problem Questions (surface pain):
4. "What's the hardest part about [current process]?"
5. "What happens when [pain scenario] occurs?"
6. "How much time does your team spend on [area] each week?"

Implication Questions (amplify impact):
7. "What does that cost you in terms of [time/money/opportunity]?"
8. "How does that affect [downstream team or goal]?"
9. "If nothing changes, where does that leave you in [6–12 months]?"

Need-Payoff Questions (future state):
10. "If you could [solve the problem], what would that mean for your team?"
11. "What would a successful outcome look like?"
12. "How would you measure whether this was working?"

Qualification Questions (process/authority/timeline/budget):
13. "How are decisions like this typically made here?"
14. "Who else needs to be involved in evaluating a solution?"
15. "Is there a timeline driving this initiative?"
16. "Do you have budget allocated, or is this exploratory?"
```

#### Demo / Presentation
- **Goal:** Show relevant capabilities, get technical/business validation
- **Agenda emphasis:** Tailored use cases, their language, feedback checkpoints
- **Key output:** Technical requirements confirmed, timeline established

**Pre-Demo Checklist:**
- [ ] Know the top 2–3 pain points to anchor the demo around
- [ ] Prepare industry-specific examples, not generic
- [ ] Identify which features to demo based on their stated priorities
- [ ] Prepare a "what if" scenario for likely objections
- [ ] Set the agenda explicitly at the start: "I've prepared X, Y, Z — is that still the right focus?"

**Demo Structure:**
```
1. Confirm agenda + their priorities (5 min)
2. Set up the scenario — "Here's the situation we'll walk through" (2 min)
3. Demo section 1 → pause, check in: "How does that compare to today?" (10 min)
4. Demo section 2 → pause, check in: "Is this relevant to what [Name] mentioned?" (10 min)
5. Demo section 3 → tie to ROI: "What would this mean for your team?" (10 min)
6. Next steps (3 min)
```

#### Negotiation / Proposal Review
- **Goal:** Address concerns, justify value, close gaps
- **Agenda emphasis:** Handle objections, clarify terms, find path to agreement
- **Key output:** Agreed path forward, clear next steps with dates

**Negotiation Prep:**
```
For each open issue, prepare:
- Our position
- Their likely concern
- Our response / trade
- Acceptable compromise
- Walk-away line

Common negotiation scenarios:
- Price pushback → ROI justification, multi-year discount, scope reduction
- Timeline concern → Phased implementation, pilot first
- Legal/terms → Pre-approved redlines, escalation to legal contact
- Competitor comparison → Differentiation talk track (see Section 4)
```

#### Check-in / QBR
- **Goal:** Demonstrate value delivered, surface expansion opportunities
- **Agenda emphasis:** Review wins, align on usage, identify new needs
- **Key output:** Renewal confidence, upsell pipeline, reference potential

**QBR Structure:**
```
1. Review metrics since last QBR
   - Usage data vs. baseline
   - Business outcomes achieved
   - ROI calculation (use their metrics)

2. Highlight wins
   - Specific examples from their team
   - Quote from internal champions

3. Address challenges openly
   - Issues encountered
   - Actions taken / planned

4. Strategic alignment
   - Their priorities for next period
   - How your roadmap supports them

5. Expansion discussion
   - Additional use cases
   - Other teams / departments
   - Upcoming features relevant to them

6. Confirm renewal / next steps
```

---

### 3.3 Attendee Research Framework

For each meeting attendee, research:

```
1. Web search: "[Name] [Title] [Company] LinkedIn"
2. Extract: Prior companies, education, tenure, published content
3. Identify: Their functional priority (revenue / cost / risk / efficiency)
4. Map to persona archetype (Section 2.4)
5. Generate: 1 personal hook + 1 professional hook
```

**Attendee Role Mapping:**

| Title Pattern | Likely Role in Deal | What They Care About | Best Message |
|--------------|---------------------|----------------------|--------------|
| C-suite (CEO, CFO, COO) | Economic Buyer | ROI, risk, strategic fit | Business outcomes, not features |
| CTO, VP Engineering | Technical Evaluator | Architecture, security, scalability | Integration depth, reliability |
| VP Sales, RevOps | Champion/Champion-builder | Revenue impact, adoption | Time to value, ease of rollout |
| Director, Manager | Day-to-day Champion | Ease of use, team productivity | Workflow improvement, support quality |
| IT/Procurement | Gatekeeper | Compliance, cost, contracts | Security, vendor stability, terms |

---

### 3.4 Call Prep Output Format

```markdown
# Call Prep: [Company Name]

**Meeting:** [Type] — [Date/Time if known]
**Attendees:** [Names with titles]
**Your Goal:** [What you want to accomplish]

---

## Account Snapshot

| Field | Value |
|-------|-------|
| **Company** | [Name] |
| **Industry** | [Industry] |
| **Size** | [Employees / Revenue if known] |
| **Status** | [New prospect / Active opportunity / Customer] |
| **Last Touch** | [Date and summary] |

---

## Who You're Meeting

### [Name] — [Title]
- **Background:** [Career history, education if found]
- **LinkedIn:** [URL]
- **Persona Archetype:** [Economic Buyer / Technical Evaluator / Champion / End User]
- **Role in Deal:** [Decision maker / Champion / Evaluator]
- **Last Interaction:** [Summary if known]
- **Talking Point:** [Personal or professional hook]

---

## Context & History

**What's happened so far:**
- [Key point from prior interactions]
- [Open commitments or action items]
- [Any concerns or objections raised]

**Recent news about [Company]:**
- [News item 1 — why it matters]
- [News item 2 — why it matters]

**Buyer Journey Stage:** [Awareness / Evaluation / Negotiation / Onboarding / Adoption]

---

## Suggested Agenda

1. **Open** — [Reference last conversation or trigger event]
2. **[Topic 1]** — [Discovery question or value discussion]
3. **[Topic 2]** — [Address known concern or explore priority]
4. **[Topic 3]** — [Demo section / Proposal review / etc.]
5. **Next Steps** — [Propose clear follow-up with timeline]

---

## Discovery Questions

Prioritized for this meeting type and buyer stage:

1. [Situation question]
2. [Problem question]
3. [Implication question]
4. [Need-payoff question]
5. [Qualification question]

---

## Potential Objections

| Objection | Suggested Response |
|-----------|-------------------|
| [Likely objection] | [How to address it] |
| [Common objection for this stage] | [How to address it] |

---

## Internal Notes

[Any internal chat context, colleague insights, or competitive intel]

---

## After the Call

Run call-follow-up to:
- Extract action items and commitments
- Update CRM with outcome and next step
- Draft follow-up email
- Identify any new qualification signals
```

---

### 3.5 Post-Call Follow-Up Framework

```
Immediately after the call (within 2 hours):
1. Log notes to CRM:
   - Meeting outcome (positive / neutral / negative)
   - Pain points surfaced
   - Objections raised and how handled
   - Commitments made by both sides
   - Next step agreed with date

2. Send follow-up email:
   - Subject: "Following up — [Company] + [Your Company]"
   - Thank them for time
   - Recap top 3 takeaways
   - List all action items with owners and dates
   - Confirm next step

3. Update deal stage if appropriate
4. Update contact records with new intel
5. Flag any new competitive mentions for battlecard update
```

---

## Section 4: Competitive Intelligence & Positioning

### Overview

```
┌─────────────────────────────────────────────────────────────────┐
│                  COMPETITIVE INTELLIGENCE                        │
├─────────────────────────────────────────────────────────────────┤
│  ALWAYS (works standalone via web search)                        │
│  ✓ Competitor product deep-dive: features, pricing, positioning │
│  ✓ Recent releases: what they've shipped in last 90 days        │
│  ✓ Your company releases: what you've shipped to counter        │
│  ✓ Differentiation matrix: where you win vs. where they win     │
│  ✓ Sales talk tracks: how to position against each competitor   │
│  ✓ Landmine questions: expose their weaknesses naturally        │
│  ✓ Brand voice analysis: their tone vs. your tone              │
├─────────────────────────────────────────────────────────────────┤
│  OUTPUT: Interactive HTML Battlecard                             │
│  ✓ Comparison matrix overview                                    │
│  ✓ Clickable tabs for each competitor                           │
│  ✓ Dark theme, professional styling                             │
│  ✓ Brand voice positioning overlay                              │
├─────────────────────────────────────────────────────────────────┤
│  SUPERCHARGED (when you connect your tools)                      │
│  + CRM: Win/loss data, competitor mentions in closed deals      │
│  + Docs: Existing battlecards, competitive playbooks            │
│  + Chat: Internal intel, field reports from colleagues          │
│  + Transcripts: Competitor mentions in customer calls           │
└─────────────────────────────────────────────────────────────────┘
```

### Trigger Phrases

- "Build battlecard for [Competitor]"
- "Research competitors"
- "How do we compare to [Competitor]"
- "Competitive intel"
- "What's new with [Competitor]"
- "Analyze [Competitor]'s brand voice"

---

### 4.1 Competitor Research Methodology

**Phase 1: Gather seller context**

```
If first time:
1. Ask: "What company do you work for?"
2. Ask: "What do you sell? (one line)"
3. Ask: "Who are your main competitors? (up to 5)"
4. Store context for future sessions

If returning user:
1. Confirm: "Still at [Company] selling [Product]?"
2. Ask: "Same competitors, or any new ones to add?"
```

**Phase 2: Research your company**

```
Web searches:
1. "[Your company] product"           → Current offerings
2. "[Your company] pricing"           → Pricing model
3. "[Your company] news"              → Recent announcements (90 days)
4. "[Your company] changelog releases" → What you've shipped
5. "[Your company] vs [competitor]"    → Existing comparisons
```

**Phase 3: Research each competitor**

```
For each competitor, run:
1. "[Competitor] product features"          → What they offer
2. "[Competitor] pricing"                   → How they charge
3. "[Competitor] news"                      → Recent announcements
4. "[Competitor] changelog releases"        → What they've shipped (90 days)
5. "[Competitor] reviews G2 Capterra TrustRadius" → Customer sentiment
6. "[Competitor] vs alternatives"           → How they position
7. "[Competitor] customers"                 → Who uses them
8. "[Competitor] careers"                   → Hiring signals (their strategy)
9. "[Competitor] brand voice about page"    → Tone and messaging style
```

**Phase 4: Brand voice analysis for each competitor**

```
For each competitor, analyze their website copy and marketing for:
- Formality level (formal ↔ casual, score 1–100)
- Tone characteristics: professional, conversational, technical, bold, friendly
- Perspective: 1st person ("we"), 2nd person ("you"), 3rd person
- Key messaging pillars (what they repeat)
- Emotional appeal: fear, ambition, efficiency, community
- Readability: complex/technical vs. accessible

Compare to your own brand voice:
- Where do they sound similar to you? (differentiation risk)
- Where are they opposite to you? (exploit the contrast)
- What emotional territory do they own? (avoid or challenge)
```

**Phase 5: Pull connected sources (if available)**

```
If CRM connected:
1. Query closed-won deals with competitor field = [Competitor]
2. Query closed-lost deals with competitor field = [Competitor]
3. Extract win/loss patterns and win rate

If docs connected:
1. Search for "battlecard [competitor]"
2. Pull existing positioning docs

If chat connected:
1. Search "[Competitor]" mentions (last 90 days)
2. Extract field intel and colleague insights

If transcripts connected:
1. Search calls for "[Competitor]" mentions
2. Extract objections and customer quotes about competitor
```

---

### 4.2 Competitor Data Structure

```yaml
competitor:
  name: "[Name]"
  website: "[URL]"
  profile:
    founded: "[Year]"
    funding: "[Stage + amount]"
    employees: "[Count]"
    target_market: "[Who they sell to]"
    pricing_model: "[Per seat / usage / etc.]"
    market_position: "[Leader / Challenger / Niche]"

  what_they_sell: "[Product summary]"
  their_positioning: "[How they describe themselves]"

  brand_voice:
    formality_score: "[0-100]"
    tone: "[Professional / Conversational / Technical / Bold]"
    perspective: "[We / You / Third person]"
    key_pillars: ["[Pillar 1]", "[Pillar 2]", "[Pillar 3]"]
    emotional_appeal: "[Fear / Ambition / Efficiency / Community]"
    vs_your_voice: "[How to exploit the contrast]"

  recent_releases:
    - date: "[Date]"
      release: "[Feature/Product]"
      impact: "[Why it matters]"

  where_they_win:
    - area: "[Area]"
      advantage: "[Their strength]"
      how_to_handle: "[Your counter]"

  where_you_win:
    - area: "[Area]"
      advantage: "[Your strength]"
      proof_point: "[Evidence]"

  pricing:
    model: "[How they charge]"
    entry_price: "[Starting price]"
    enterprise: "[Enterprise pricing]"
    hidden_costs: "[Implementation, overage, etc.]"
    talk_track: "[How to discuss pricing comparison]"

  talk_tracks:
    early_mention: "[Strategy if they come up early in deal]"
    displacement: "[Strategy if customer currently uses them]"
    late_addition: "[Strategy if added late to eval]"
    voice_contrast: "[Emphasize your voice/positioning contrast]"

  objections:
    - objection: "[What customer says]"
      response: "[How to handle]"

  landmines:
    - "[Question that exposes their weakness naturally]"
    - "[Question about hidden cost or implementation complexity]"

  win_loss:  # If CRM connected
    win_rate: "[X]%"
    common_win_factors: "[What predicts wins against them]"
    common_loss_factors: "[What predicts losses against them]"
    key_battleground_deals: "[Deal types where this matters most]"
```

---

### 4.3 Win/Loss Pattern Analysis

Run after 10+ competitive deals to identify patterns:

```
Win Patterns (deals won against Competitor X):
- Common buyer persona: [which archetype wins]
- Common deal size: [$X–$Y range]
- Common use case that tipped: [specific capability]
- Common champion profile: [title/role]
- Common objection resolved: [what we overcame]

Loss Patterns (deals lost to Competitor X):
- Common loss scenario: [what triggered the loss]
- Feature gap that mattered: [what they had we didn't]
- Pricing gap that mattered: [discount required]
- Champion who didn't advocate: [why they didn't]
- Competitive move that worked against us: [their tactic]

Countermeasures:
- For win scenarios: Double down on [strength], lead with [angle]
- For loss scenarios: Disqualify earlier, improve [area], add [proof point]
```

---

### 4.4 HTML Battlecard Structure

The battlecard is a self-contained HTML file with:

**Landing View — Comparison Matrix:**
- Feature comparison grid (you vs. each competitor)
- Pricing comparison table
- Market positioning diagram
- Win rate indicators (if CRM connected)
- Quick win/loss guide per competitor

**Competitor Tabs (click to expand each):**
- Company profile (size, funding, target market)
- Brand voice summary + contrast with yours
- Recent releases (last 90 days)
- Where they win vs. where you win
- Pricing intelligence + hidden cost exposure
- Talk tracks (early mention / displacement / late addition)
- Objection handling card
- Landmine questions

**Visual Design:**
```css
:root {
    --bg-primary: #0a0d14;
    --bg-elevated: #0f131c;
    --bg-surface: #161b28;
    --text-primary: #ffffff;
    --text-secondary: rgba(255, 255, 255, 0.7);
    --accent: #3b82f6;
    --you-win: #10b981;
    --they-win: #ef4444;
    --tie: #f59e0b;
}
```

**Refresh Cadence:**

| Trigger | Action |
|---------|--------|
| Monthly | Quick refresh — releases, news, pricing |
| Before major deal | Deep refresh for specific competitor |
| After win/loss | Update patterns |
| Competitor announcement | Immediate update |

---

### 4.5 Talk Track Templates

#### When Competitor Comes Up Early (Prospect Mentions Them Proactively)

```
"[Competitor] is a solid option and I'd expect them to be on your list.
Here's what I'd suggest — let's first make sure we're aligned on what
you actually need to solve. Then you'll have a clear lens to evaluate
both of us on what matters. Does that make sense?

[If they push on comparison]

The biggest differences I hear from customers who've evaluated both:
[Difference 1 in their language, not yours]
[Difference 2 tied to their specific pain point]

The best way to make this concrete is [landmine question]."
```

#### Displacement (Customer Currently Uses Competitor)

```
"I appreciate you sharing that. A lot of our customers came from
[Competitor]. Can I ask — what's prompting you to look at alternatives
right now? [Let them answer]

[After they answer]
That makes sense. That's actually one of the areas where [your product]
was designed differently — [specific differentiator in their context].
Mind if I show you how that works?"
```

#### Competitive Landmine Questions (Examples)

```
On pricing complexity:
"How does [Competitor]'s pricing scale as your usage grows?"

On implementation:
"What does the typical implementation timeline look like with [Competitor]?"

On support:
"When something breaks at 2am, how does support work with [Competitor]?"

On data ownership:
"If you were to switch away from [Competitor], how easy is it to export your data?"

On roadmap:
"Have you had a chance to talk to [Competitor] about their roadmap for [area you win in]?"
```

---

## Section 5: Outreach & Content Creation

### Overview

```
┌─────────────────────────────────────────────────────────────────┐
│                   OUTREACH & CONTENT CREATION                    │
├─────────────────────────────────────────────────────────────────┤
│  ALWAYS (works standalone via web search)                        │
│  ✓ Research first — never send generic outreach                 │
│  ✓ AIDA email structure with personalized hook                  │
│  ✓ LinkedIn connection request + follow-up message              │
│  ✓ Follow-up sequence (Day 3, Day 7, Day 14 break-up)          │
│  ✓ Brand voice validation before sending                        │
│  ✓ Content pillar-based cadence planning                        │
├─────────────────────────────────────────────────────────────────┤
│  SUPERCHARGED (when you connect your tools)                      │
│  + Enrichment: verified email, phone, background details        │
│  + CRM: prior relationship context, existing contacts           │
│  + Email: create draft directly in your inbox                   │
└─────────────────────────────────────────────────────────────────┘
```

### Trigger Phrases

- "Draft outreach to [Person/Company]"
- "Write cold email to [Prospect]"
- "Reach out to [Name]"
- "Create follow-up sequence for [Company]"
- "Check brand voice of this email"

---

### 5.1 Research-First Outreach Methodology

**Never draft before researching.** Always execute in this order:

```
Step 1: Research (always happens first)
  ├── Web search: company + person
  ├── + Enrichment: verified contact info, background (if connected)
  └── + CRM: prior relationship (if connected)

Step 2: Identify Hook (priority order)
  1. Trigger event (funding, new hire, product launch, news) → Most timely
  2. Mutual connection → Social proof
  3. Their content (post, article, talk, podcast) → Shows you did research
  4. Company initiative (new product, expansion, earnings) → Relevant to role
  5. Role-based pain point (universal for their function) → Least personal, still valid

Step 3: Draft (based on research + hook)
  ├── Personalized opening (from research)
  ├── Relevant hook (their stated priorities)
  ├── Proof point (similar company result)
  └── Low-friction CTA

Step 4: Brand Voice Validation
  ├── Does tone match your brand guidelines?
  ├── Formality appropriate for their seniority?
  ├── Plain text only (no markdown in emails)?
  └── Under 150 words for cold outreach?

Step 5: Deliver
  ├── Email draft (if email connector available)
  ├── LinkedIn message template
  └── Copy to clipboard
```

---

### 5.2 AIDA Email Structure

**Subject line rules:**
- Under 50 characters
- Personalized (their company, role, or initiative)
- No spam trigger words (FREE, LIMITED TIME, URGENT)
- Curiosity-driven, not pitch-driven

**Body structure:**

```
ATTENTION: [Personal hook — 1 sentence showing you researched them]
           Reference: news, funding, content, mutual connection, hire

INTEREST:  [Their likely challenge in 1-2 sentences]
           Frame around their role and industry, not your product

DESIRE:    [Brief proof point — similar company, specific result]
           "We helped [Similar company] achieve [Specific outcome]"
           Keep it concrete: time saved, revenue added, cost reduced

ACTION:    [One clear, low-friction ask]
           Options: "Worth a 15-min call?", "Open to a quick look?",
                    "Can I send over more detail?", "Happy to share a demo?"

SIGNATURE: [Name, title, company, one-liner value prop optional]
```

**Example — Cold Outreach:**

```
Subject: Notion's AI scaling + a thought

Hi David,

Saw Notion's AI rollout is gaining serious traction — congrats.
With 5 ML roles open, seems like you're scaling fast.

Curious how you're thinking about inference infrastructure as usage
grows. We helped [Similar Company] cut their AI serving costs 40%
while improving latency.

Worth a 15-min call to see if relevant to your roadmap?

Best,
[Name]
```

**What NOT to do:**
- "I hope this email finds you well" → Delete it
- "I'm reaching out because..." → Delete it
- "I wanted to introduce myself..." → Delete it
- Using **bold** or *italic* in email body (markdown won't render)
- More than one CTA
- Listing 5 features in the body
- "Congrats on your role" without any specific context

---

### 5.3 LinkedIn Messaging

**Connection Request (< 300 characters):**

```
Hi [Name], [Mutual connection / shared interest / specific observation].
Would love to connect. No pitch — just find your work on [topic] interesting.
```

**Follow-up Message (after connected, 24–48 hours later):**

```
Thanks for connecting! Saw you're working on [initiative] at [Company].

[Value-first: relevant insight, article, framework related to their work]

Happy to share more context if useful. No pressure either way.

[Name]
```

**Rules:**
- Never pitch on the connection request
- Lead follow-up with value, not ask
- Keep under 300 characters for connection request
- Reference something specific — no "I came across your profile"

---

### 5.4 Follow-Up Sequence

After the initial email, follow this cadence if no response:

**Day 3 — Follow-Up 1 (New Angle):**

```
Subject: Re: [Original subject line]

Hi [Name],

Wanted to add one thing I forgot to mention — [new insight or value add].

If it's not relevant right now, no worries at all. Just thought it might
be useful given [specific context from research].

[Name]
```

**Day 7 — Follow-Up 2 (Different Value Prop):**

```
Subject: [Company] + [your product]: quick question

Hi [Name],

I'll keep this short. [Different angle than email 1 — different use case
or different pain point relevant to their role].

We saw [result] with [similar company] by [specific approach].

Worth 15 minutes?

[Name]
```

**Day 14 — Break-Up Email:**

```
Subject: Closing the loop

Hi [Name],

I've reached out a few times — I'm guessing the timing isn't right,
which is completely fine.

I'll stop following up, but if [trigger event — initiative, goal, problem]
becomes a priority, I'd love to reconnect.

[Name]
```

---

### 5.5 Outreach Scenario Templates

#### Warm Outreach (Have Met / Mutual Connection)

```
Subject: Following up from [Context — event, intro, conversation]

Hi [Name],

[Reference to how you know them or who connected you — specific detail].

[Why reaching out now — their news, trigger, or your relevance to a
current initiative they're running].

[Specific value you can offer in this context].

[CTA]

[Name]
```

#### Re-Engagement (Went Dark After Active Conversation)

```
Subject: [Short, curiosity-driven — not guilt-inducing]

Hi [Name],

It's been a while. I noticed [something new and relevant at their company
— news, hire, launch, announcement].

Thought it might be a good time to reconnect — [brief reason tied to that
trigger].

Are you still thinking about [original pain point / initiative]?

[Name]
```

#### Post-Event Follow-Up

```
Subject: Great [meeting/conversation] at [Event]

Hi [Name],

Really enjoyed [specific topic or moment from your conversation] — the
point about [their insight] was something I'm still thinking about.

[Value-add: article, intro, resource connected to what you discussed]

Would love to continue the conversation — [soft CTA for 30-min call].

[Name]
```

---

### 5.6 Brand Voice Analysis for Outreach

Before sending any outreach, validate against your brand voice profile:

```
Brand Voice Dimensions:
1. Formality Score: [0-100]
   - 0-30: Casual/friendly ("Hey!", contractions, slang)
   - 31-60: Semi-formal (professional but approachable)
   - 61-100: Formal (titles, no contractions, structured)

2. Tone Attributes (choose 2-3):
   - Professional | Conversational | Technical | Bold | Empathetic | Direct

3. Perspective: First person (we) / Second person (you-focused) / Mixed

4. Readability Target: [Audience-appropriate]
   - C-suite: Clear and punchy (Flesch score 60+)
   - Technical: Can be more detailed (Flesch score 40-60)
   - Operations: Procedural clarity (Flesch score 50-70)

Validation Checklist:
- [ ] Formality appropriate for recipient seniority
- [ ] Tone consistent with brand guidelines
- [ ] You-focused (about their problem, not your product)
- [ ] Plain text only (no markdown formatting)
- [ ] Under 150 words for cold outreach
- [ ] One CTA only
- [ ] Personal hook shows actual research
```

---

### 5.7 Content Pillar-Based Cadence Planning

For accounts in active pipeline, plan a content-driven multi-touch cadence:

**Content Pillar Ratio (40/25/25/10):**

| Pillar | % of Touches | Example |
|--------|--------------|---------|
| **Education** | 40% | Industry insight, research, framework they can use |
| **Social Proof** | 25% | Case study from similar company, customer quote |
| **Product Insight** | 25% | Use case demo, feature relevant to their pain |
| **Direct Ask** | 10% | Explicit CTA — meeting request, demo offer |

**4-Week Content Cadence Example:**

```
Week 1, Touch 1: Education — "Here's a trend in [their industry]..."
Week 1, Touch 3: Social Proof — "A company like yours did [result]..."
Week 2, Touch 5: Product Insight — "This is how [feature] solves [their pain]..."
Week 2, Touch 7: Direct Ask — "Worth 15 minutes this week?"
Week 3, Touch 9: Education — "Thought you'd find this relevant..."
Week 3, Touch 11: Social Proof — "[Relevant customer quote]..."
Week 4, Touch 13: Direct Ask — "Break-up email..."
```

**Platform-Specific Optimization:**

| Platform | Tone | Length | Frequency |
|----------|------|--------|-----------|
| **Email** | Semi-formal, direct | <150 words cold / <250 warm | 2–3x per week max |
| **LinkedIn** | Professional, thoughtful | 300 chars connection / 500 follow-up | 1–2x per week |
| **LinkedIn DM** | Conversational | Under 300 chars | Sparingly after connect |

---

### 5.8 Outreach Output Format

```markdown
# Outreach Draft: [Person] @ [Company]
**Generated:** [Date] | **Research Sources:** [Web, Enrichment, CRM]

---

## Research Summary

**Target:** [Name], [Title] at [Company]
**Hook:** [Why reaching out now — personalized angle]
**Goal:** [What you want from this outreach]

---

## Email Draft

**To:** [email if known]
**Subject:** [Personalized subject line]

---

[Email body — AIDA structure, plain text]

---

**Subject Line Alternatives:**
1. [Option 2]
2. [Option 3]

---

## LinkedIn Message (backup / parallel)

**Connection Request (< 300 chars):**
[Short, no-pitch connection request]

**Follow-up Message (after connected):**
[Value-first message under 300 chars]

---

## Why This Approach

| Element | Based On |
|---------|----------|
| Opening | [Research finding] |
| Hook | [Their priority/pain point] |
| Proof | [Relevant customer story] |
| CTA | [Low-friction ask] |

---

## Brand Voice Validation

| Check | Pass? |
|-------|-------|
| Formality appropriate | [Y/N] |
| You-focused tone | [Y/N] |
| Plain text only | [Y/N] |
| Under 150 words | [Y/N] |
| Single CTA | [Y/N] |

---

## Follow-up Sequence

**Day 3:**
[New angle follow-up]

**Day 7:**
[Different value prop]

**Day 14:**
[Break-up email]
```

---

## Section 6: Sales Assets & Deliverables

### Overview

Generate custom sales assets tailored to your prospect, audience, and goals. Supports interactive landing pages, presentation decks, executive one-pagers, and workflow/architecture demos.

### Trigger Phrases

- "Create an asset / landing page / one-pager for [Company]"
- "Build a demo for [Prospect]"
- "Make a workflow demo for [Company]"
- "Create a deck for my meeting with [Company]"

---

### 6.1 Asset Types

| Format | Description | Best For | Build Time |
|--------|-------------|----------|------------|
| **Interactive Landing Page** | Multi-tab HTML page with demos, metrics, calculators | Exec alignment, intros, value prop | Medium |
| **Deck-Style** | Linear slides, presentation-ready | Formal meetings, large audiences | Medium |
| **One-Pager** | Single-scroll executive summary | Leave-behinds, quick summaries | Fast |
| **Workflow / Architecture Demo** | Interactive animated diagram | Technical deep-dives, POC demos, integrations | Slow |

---

### 6.2 7-Phase Asset Creation Process

#### Phase 0: Context Detection & Input Collection

**Detect seller context:**
```
1. Extract domain from user's email
2. Search: "[domain]" company products services
3. If single-product company → auto-populate
4. If multi-product → ask: "Which product is this asset for?"
5. If unknown → ask: "What are you selling?"
```

**Collect prospect context:**

| Field | Prompt | Required |
|-------|--------|----------|
| Company | "Which company is this asset for?" | Yes |
| Key contacts | "Who are the key contacts? (names, roles)" | No |
| Deal stage | "What stage is this deal?" | Yes |
| Pain points | "What pain points have they shared?" | No |
| Materials | "Upload transcripts, emails, or notes" | No |

**Deal stages:**
- Intro / First meeting → Awareness/discovery
- Discovery → Problem qualification
- Evaluation / Technical review → Feature comparison
- POC / Pilot → Proof of concept
- Negotiation → Value justification
- Close → Final commitment

**Collect audience context:**

| Audience Type | Primary Concern | Lead Section |
|--------------|-----------------|--------------|
| Executive (C-suite, VPs) | ROI / Business impact | Strategic Fit → Business Impact |
| Technical (Architects, Engineers) | Architecture / Security | Integration → Security → Performance |
| Operations (IT, Procurement) | Workflow / Change management | Implementation → Support |
| Mixed / Cross-functional | Strategic + tactical balance | Balance with tabbed depth levels |

**Select format:**

```
"What format works best for this?"
→ Interactive landing page / Deck-style / One-pager / Workflow demo
```

#### Phase 1: Research (Adaptive)

**Assess context richness:**

| Level | Indicators | Research Depth |
|-------|------------|----------------|
| Rich | Transcripts uploaded, detailed pain points | Light — fill gaps only |
| Moderate | Some context, no transcripts | Medium — company + industry |
| Sparse | Just company name | Deep — full research pass |

**Always research:**
1. `"[Company]" annual report CEO strategy priorities 2025 2026`
2. `"[Company]" CEO CTO CIO 2025` — extract names, titles, quotes
3. `"[Company]" brand guidelines` — primary/secondary colors
4. Industry trends: `"[Industry]" challenges trends 2025 2026`

**If moderate/sparse, also research:**
5. Technology landscape: `"[Company]" technology stack tools`
6. Competitive context: `"[Company]" vs [your competitors]`

**If transcripts/materials uploaded:**
7. Extract stated pain points, decision criteria, objections, timeline
8. Pull exact customer quotes (use their language in the asset)
9. Note specific terminology, acronyms, internal project names

#### Phase 2: Structure Decision

**Interactive Landing Page by Purpose:**

| Purpose | Recommended Section Order |
|---------|--------------------------|
| Intro / First impression | Company Fit → Solution Overview → Use Cases → Why Us → Next Steps |
| Discovery follow-up | Their Priorities → How We Help → Relevant Examples → ROI Framework → Next Steps |
| Technical deep-dive | Architecture → Security → Integration → Performance → Support |
| Exec alignment | Strategic Fit → Business Impact → ROI Calculator → Risk Mitigation → Partnership |
| POC proposal | Scope → Success Criteria → Timeline → Team → Investment → Next Steps |
| Deal close | Value Summary → Pricing → Implementation Plan → Terms → Sign-off |

**One-Pager Structure:**

```
┌─────────────────────────────────────────────────────────┐
│ HERO: "[Prospect Goal] with [Product]"                  │
│ Subhead: [Tied to their stated priority]                │
├─────────────────────────────────────────────────────────┤
│ KEY POINT 1    │ KEY POINT 2    │ KEY POINT 3           │
│ [Icon + 2-3    │ [Icon + 2-3    │ [Icon + 2-3           │
│ sentences]     │ sentences]     │ sentences]            │
├─────────────────────────────────────────────────────────┤
│ PROOF POINT: [Metric, quote, or case study]             │
├─────────────────────────────────────────────────────────┤
│ CTA: [Clear next action]  │  [Contact info]             │
└─────────────────────────────────────────────────────────┘
```

**Workflow Demo Structure (by complexity):**

| Complexity | Components | Structure |
|------------|------------|-----------| 
| Simple | 3–5 | Single-view diagram with step annotations |
| Medium | 5–10 | Zoomable canvas with step-by-step walkthrough |
| Complex | 10+ | Multi-layer (overview → detailed) with guided tour |

#### Phase 3: Content Generation

**Core principles for all assets:**
- Reference **specific pain points** from input or transcripts
- Use **their language** — their terminology, their priorities, their acronyms
- Map your product to their needs explicitly
- Include **proof points** (case studies, metrics, customer quotes)
- Feel tailored, not templated

**Section templates:**

```
Hero / Intro:
Headline: "[Prospect's Goal] with [Seller's Product]"
Subhead: Tie to their stated priority or top industry challenge
Metrics: 3-4 key facts about the prospect (shows homework done)

Their Priorities (discovery follow-up only):
- Use exact words from their transcript/notes where possible
- Show you listened; connect each to how you help

Solution Mapping:
For each pain point:
├── The challenge (in their words)
├── How [Product] addresses it
├── Proof point or example
└── Outcome / benefit (quantified)

ROI / Business Case:
Interactive calculator:
├── Inputs: relevant to their business from research
│   ├── Number of users/teams
│   ├── Current costs or time spent
│   └── Expected improvement %
├── Outputs:
│   ├── Annual value / savings
│   ├── Cost of solution
│   ├── Net ROI and payback period
└── Assumptions clearly stated (editable)

Next Steps / CTA:
├── Clear action aligned to purpose
├── Specific next step (not vague "let's chat")
├── Contact information
├── Suggested timeline
└── What happens after they act
```

#### Phase 4: Visual Design (Non-Web Outputs Only)

For decks, one-pagers, and workflow demos:

```css
:root {
    /* Prospect brand colors (extracted from research) */
    --brand-primary: #[extracted];
    --brand-secondary: #[extracted];

    /* Dark theme */
    --bg-primary: #0a0d14;
    --bg-surface: #161b28;
    --text-primary: #ffffff;
    --text-secondary: rgba(255, 255, 255, 0.7);
    --accent: var(--brand-primary);
    --success: #10b981;
    --warning: #f59e0b;
}
```

**Typography:**
```css
font-family: 'Inter', -apple-system, BlinkMacSystemFont, sans-serif;
h1: 2.5rem, font-weight: 700
h2: 1.75rem, font-weight: 600
body: 1rem, line-height: 1.6
```

**Brand color fallbacks by industry:**

| Industry | Primary | Secondary |
|----------|---------|-----------|
| Technology | #2563eb | #7c3aed |
| Finance | #0f172a | #3b82f6 |
| Healthcare | #0891b2 | #06b6d4 |
| Manufacturing | #ea580c | #f97316 |
| Retail | #db2777 | #ec4899 |
| Default | #3b82f6 | #8b5cf6 |

> **For interactive landing pages:** Load the `website-building` skill for all visual design, typography, color systems, and CSS.

#### Phase 5: Clarifying Questions (Always Ask Before Building)

Before building, show what you understood and confirm:

```
"Here's what I'm planning to build:

Asset: [Format] for [Prospect Company]
Audience: [Type] — specifically [roles if known]
Goal: [Purpose] → driving toward [desired action]
Key themes: [2-3 main points to emphasize]

[For workflow demos:]
Components: [List of systems]
Flow: [Step 1] → [Step 2] → [Step 3] → ...
```

**Standard questions (all formats):**
1. "Does this match your vision?"
2. "What's the ONE thing this must nail to succeed?"
3. "Tone preference? (Bold & confident / Consultative / Technical & precise)"
4. "Focused and concise, or comprehensive?"

**Max 2 rounds of questions.** If still ambiguous, decide and note: "I went with X — easy to adjust if you prefer Y."

#### Phase 6: Build & Deliver

**Output format:**
- Self-contained HTML file (all CSS and JS inline)
- No external dependencies except Google Fonts
- Single file for easy sharing
- File naming: `[ProspectName]-[format]-[YYYY-MM-DD].html`

**Delivery message:**

```markdown
## ✓ Asset Created: [Prospect Name]

[View your asset]

---

Summary:
- Format: [Interactive Page / Deck / One-Pager / Workflow Demo]
- Audience: [Type and roles]
- Purpose: [Goal] → [Desired action]
- Sections/Steps: [Count]

---

Deployment Options:
- Static hosting: Upload to Netlify, Vercel, GitHub Pages, AWS S3
- Password protection: Available on most hosting platforms
- Direct share: Send the HTML file — fully self-contained
```

#### Phase 7: Iteration Support

| User Request | Action |
|--------------|--------|
| "Change the colors" | Regenerate with new palette, keep content |
| "Add a section on X" | Insert new section, maintain flow |
| "Make it shorter" | Condense, prioritize key points |
| "The flow is wrong" | Rebuild architecture from correction |
| "Use our brand instead" | Switch from prospect to seller brand |
| "Add more detail on step 3" | Expand that section specifically |
| "Can I get this as a PDF?" | Provide print-optimized version |

---

### 6.3 Quality Checklist

**Content:**
- [ ] Prospect company name spelled correctly throughout
- [ ] Leadership names are current (not outdated)
- [ ] Pain points accurately reflect input/transcripts
- [ ] No placeholder text remaining
- [ ] Proof points are accurate and sourced

**Visual:**
- [ ] Brand colors applied correctly
- [ ] All text readable (sufficient contrast)
- [ ] Animations smooth, not distracting
- [ ] Mobile responsive (if interactive page)

**Functional:**
- [ ] All tabs/sections load correctly
- [ ] Interactive elements work (calculators, demos)
- [ ] Navigation is intuitive
- [ ] CTA is clear and clickable

**Professional:**
- [ ] Tone matches audience
- [ ] No typos or grammatical errors
- [ ] Feels tailored, not templated

---

## Section 7: Deal Prioritization & Pipeline Management

### Overview

```
┌─────────────────────────────────────────────────────────────────┐
│              DEAL PRIORITIZATION & PIPELINE MANAGEMENT           │
├─────────────────────────────────────────────────────────────────┤
│  ALWAYS (works standalone)                                       │
│  ✓ Daily briefing from user-provided meetings and deals         │
│  ✓ RICE-scored deal prioritization for pipeline focus           │
│  ✓ Suggested top-3 actions for the day                          │
│  ✓ End-of-day summary mode                                      │
│  ✓ Quick brief mode (< 2 minutes)                               │
├─────────────────────────────────────────────────────────────────┤
│  SUPERCHARGED (when you connect your tools)                      │
│  + Calendar: auto-pull today's meetings with attendees          │
│  + CRM: open pipeline, closing soon, stale deals, tasks         │
│  + Email: unread from key accounts, waiting on replies          │
│  + Enrichment: overnight signals on your accounts               │
└─────────────────────────────────────────────────────────────────┘
```

### Trigger Phrases

- "Morning briefing" / "Start my day" / "Daily brief"
- "What's on my plate today?"
- "Prioritize my deals / pipeline"
- "Quick brief" / "tldr my day"
- "Wrap up my day" / "End of day summary"

---

### 7.1 Daily Briefing Workflow

**Step 1: Gather context**

```
If connectors active:
1. Calendar → Get today's external meetings
   Pull: time, attendees, title, description
2. CRM → Query your pipeline
   Pull: open opps, deals closing within 7 days, stale (7+ days no activity)
   Pull: overdue tasks, upcoming tasks due today
3. Email → Priority messages
   Pull: unread from opportunity contact domains
   Pull: sent messages with no reply (3+ days)
4. Enrichment → Overnight signals
   Pull: funding, hiring, news on open accounts

If no connectors:
Ask user:
1. "What meetings do you have today?"
2. "What deals are you focused on? Any closing soon or needing attention?"
3. "Anything urgent I should know about?"
```

**Step 2: Priority ranking**

```
Priority tiers:
1. URGENT:  Deal closing today/tomorrow not yet won
2. HIGH:    Meeting today with >$50K or strategic deal
3. HIGH:    Unread email from decision-maker (>3 days old)
4. MEDIUM:  Deal closing this week
5. MEDIUM:  Stale deal (7+ days no activity)
6. LOW:     Tasks due this week

#1 Priority logic:
- If meeting with high-value deal today → prep that meeting
- If deal closing today → focus on close activity
- If urgent email from buyer → respond first
- Else → highest-value stale deal
```

**Step 3: Generate briefing**

Assemble based on available data:
1. #1 Priority — Always include
2. Today's Numbers — If CRM connected
3. Today's Meetings — From calendar or user input
4. Pipeline Alerts — If CRM connected
5. Email Priorities — If email connected
6. Suggested Actions — Always include top 3

---

### 7.2 Daily Briefing Output Format

```markdown
# Daily Briefing | [Day, Month Date]

---

## #1 Priority

**[Most important thing to do today]**
[Why it matters and what to do about it]

---

## Today's Numbers

| Open Pipeline | Closing This Month | Meetings Today | Action Items |
|---------------|-------------------|----------------|--------------|
| $[X]          | $[X]              | [N]            | [N]          |

---

## Today's Meetings

### [Time] — [Company] ([Meeting Type])
**Attendees:** [Names]
**Context:** [One-line: deal status, last touch, what's at stake]
**Prep:** [Quick action before this meeting]
**RICE Priority Score:** [Deal score from 7.3]

Run `call-prep [company]` for detailed meeting prep

---

## Pipeline Alerts

### Needs Attention
| Deal | Stage | Amount | Alert | Action |
|------|-------|--------|-------|--------|
| [Deal] | [Stage] | $[X] | [Why flagged] | [What to do] |

### Closing This Week
| Deal | Close Date | Amount | Confidence | Blocker |
|------|------------|--------|------------|---------|
| [Deal] | [Date] | $[X] | [H/M/L] | [If any] |

---

## Email Priorities

### Needs Response
| From | Subject | Received |
|------|---------|----------|
| [Name @ Company] | [Subject] | [Time] |

### Waiting On Reply
| To | Subject | Sent | Days Waiting |
|----|---------|------|--------------|
| [Name @ Company] | [Subject] | [Date] | [N] |

---

## Suggested Actions

1. **[Action]** — [Why now]
2. **[Action]** — [Why now]
3. **[Action]** — [Why now]

---

Run `call-prep [company]` before your meetings
Run `call-follow-up` after each call
```

---

### 7.3 RICE Framework for Deal Prioritization

Adapted from the PM RICE prioritization framework (Reach × Impact × Confidence ÷ Effort) for sales pipeline management.

**RICE Deal Scoring:**

| Dimension | Sales Definition | Scoring |
|-----------|-----------------|---------|
| **Reach** | Number of stakeholders / accounts this deal unlocks (referral potential, platform expansion) | 1–10 scale or estimated user count |
| **Impact** | Deal size × strategic value × customer logo quality | Scoring below |
| **Confidence** | Win probability based on qualification signals | % expressed as decimal (0.1–1.0) |
| **Effort** | Estimated selling effort remaining to close (meetings, POC work, legal, etc.) | Person-days or weeks |

**RICE Score Formula:**
```
RICE Score = (Reach × Impact × Confidence) / Effort
```

**Impact Scoring Table (for sales):**

| Impact Score | Deal Size Equivalent | Strategic Value |
|-------------|----------------------|-----------------|
| 4 (Massive) | >$250K ARR | Platform deal, referenceable logo |
| 3 (High) | $50K–$250K ARR | Growth account, strong reference potential |
| 2 (Medium) | $10K–$50K ARR | Solid deal, limited expansion |
| 1 (Low) | <$10K ARR | Transactional, low strategic value |
| 0.5 (Minimal) | <$5K ARR | Long-tail, high overhead |

**Effort Scoring Table:**

| Effort Level | Label | Description |
|-------------|-------|-------------|
| 0.5 | XS | Ready to close — paperwork only |
| 1 | S | 1–2 weeks — minor final steps |
| 2 | M | 2–4 weeks — demo, legal, approval |
| 4 | L | 1–2 months — POC, multi-stakeholder |
| 8 | XL | 2+ months — complex enterprise |

**Example RICE Deal Scoring:**

```
Deal: Acme Corp
  Reach: 4 (platform deal, could expand to 3 divisions)
  Impact: 3 (high — $120K ARR, strong logo)
  Confidence: 0.7 (good champion, budget confirmed, 70% win prob)
  Effort: 2 (medium — 3-week final push needed)

  RICE Score = (4 × 3 × 0.7) / 2 = 4.2

Deal: Beta Inc
  Reach: 1 (single department, limited expansion)
  Impact: 1 (low — $8K ARR)
  Confidence: 0.9 (clear buy signal, champion bought in)
  Effort: 0.5 (XS — just paperwork)

  RICE Score = (1 × 1 × 0.9) / 0.5 = 1.8

Deal: Gamma Co (Strategic)
  Reach: 8 (industry logo, case study ready)
  Impact: 4 (massive — $400K ARR + partner ecosystem)
  Confidence: 0.4 (early stage, champion still building)
  Effort: 8 (XL — complex enterprise, 3 months out)

  RICE Score = (8 × 4 × 0.4) / 8 = 1.6
```

**Portfolio Analysis for Pipeline:**

```
Quick Wins (high Confidence + low Effort):
- Beta Inc (RICE 1.8) → Close this week

Big Bets (high Reach + Impact, lower Confidence):
- Gamma Co (RICE 1.6) → Invest in champion building

Core Focus (balanced scores):
- Acme Corp (RICE 4.2) → Top priority this week
```

---

### 7.4 Pipeline Scoring Output

```
============================================================
PIPELINE PRIORITIZATION — RICE SCORING
============================================================

Top Prioritized Deals

1. Acme Corp
   RICE Score: 4.2
   Reach: 4 | Impact: High ($120K) | Confidence: 70% | Effort: Medium
   Status: Final proposal sent, legal review pending
   Action: Follow up with VP Procurement on contract timeline

2. Delta Systems
   RICE Score: 3.1
   Reach: 3 | Impact: High ($85K) | Confidence: 65% | Effort: Small
   Status: Demo complete, champion building business case
   Action: Send champion kit + exec one-pager for internal approval

3. Zeta Corp
   RICE Score: 2.8
   Reach: 2 | Impact: Medium ($35K) | Confidence: 80% | Effort: XS
   Status: Verbal yes, paperwork not started
   Action: Send order form today

Portfolio Analysis:
  Total Pipeline: $[X]
  Quick Wins: [N] deals (close in <2 weeks)
  Big Bets: [N] deals (>$200K, need champion investment)
  Stale: [N] deals (7+ days no activity, needs re-engagement)

Today's Focus (RICE top 3):
  Q1 Actions: Close Zeta Corp, advance Acme legal, build Delta champion
```

---

### 7.5 Quick Brief Mode

Trigger: "quick brief" or "tldr my day"

```markdown
# Quick Brief | [Date]

**#1:** [Priority action — one sentence]

**Meetings:** [N] — [Company 1], [Company 2]

**Top Deal Alert:** [Deal] — [What needs to happen]

**Do Now:** [Single most important action with ETA]
```

---

### 7.6 End-of-Day Mode

Trigger: "wrap up my day" or "end of day summary"

```markdown
# End of Day | [Date]

**Completed:**
- [Meeting 1] — [Outcome: positive / neutral / negative, next step]
- [Meeting 2] — [Outcome]

**Pipeline Changes:**
- [Deal] moved to [Stage]
- [Deal] — new blocker surfaced: [description]

**RICE Score Updates:**
- [Deal] Confidence updated: [old%] → [new%] — reason: [why]
- [Deal] Effort updated: [old] → [new] — reason: [discovery meeting, POC started, etc.]

**Tomorrow's Focus (RICE-ranked):**
1. [Priority 1 — deal + action]
2. [Priority 2 — deal + action]
3. [Priority 3 — deal + action]

**Open Loops:**
- [ ] [Unfinished item with owner + due date]
- [ ] [Follow-up promised to prospect]
```

---

### 7.7 Deal Health Indicators

**Green (On Track):**
- Active champion advocating internally
- Budget confirmed or allocated
- Timeline defined
- Agreed next step within 7 days
- Multi-stakeholder engagement

**Yellow (Monitor):**
- Champion going quiet (>5 days no response)
- Timeline slipped without explanation
- New stakeholder added late in process
- Competitor mentioned that wasn't before
- Procurement delays

**Red (At Risk):**
- No contact for 10+ days
- Decision maker has changed
- Budget moved or reduced
- Competitor selected for POC
- Legal review stalled >2 weeks

**Intervention Playbook by Color:**

| Status | Intervention |
|--------|-------------|
| Yellow — champion quiet | Champion re-engagement email + exec outreach |
| Yellow — timeline slipped | "What changed?" conversation; re-qualify urgency |
| Yellow — new stakeholder | Research them fast (Section 2); get intro from champion |
| Red — no contact 10+ days | Break-up email; re-engage from different contact |
| Red — competitor POC | Accelerate your POC; request joint technical session |
| Red — budget moved | ROI conversation with finance stakeholder |

---

## Section 8: Unique Perplexity Computer Capabilities

Capabilities that exist only in Perplexity Computer and cannot be replicated in offline/static environments like Claude Code.

---

### 8.1 Live Web Research with Real-Time Data

**What it does:** Searches the live web in real time, returning current information published within hours or days.

**Why it matters for sales:**
- Catch funding announcements the day they happen → trigger outreach immediately
- Find leadership changes before they're in LinkedIn (often announced in press first)
- Monitor competitor product launches as they go live
- Detect hiring spikes that signal a new initiative (they're building X → sell them Y)
- Pull current pricing from competitor websites (prices change; static knowledge doesn't)

**Sales use cases:**
```
Trigger event detection:
- "[Company] funding announcement this week"
- "[Company] news today"
- "[Executive name] leaving [Company]"

Real-time hiring signals:
- "[Company] site:lever.co OR site:greenhouse.io"
- "[Company] VP of [function] new hire"

Live competitor intel:
- "[Competitor] pricing 2026"
- "[Competitor] new features released"
```

---

### 8.2 Social Media Search (X/Twitter)

**What it does:** Searches live X (formerly Twitter) posts, threads, and replies.

**Why it matters for sales:**
- Find complaints about competitors from real users in real time
- Identify prospects publicly discussing pain points you solve
- Track executive thought leadership to personalize outreach
- Monitor competitor announcements before they hit mainstream press

**Sales use cases:**
```
Competitor sentiment:
from:[competitor_handle] product -is:retweet

Prospect pain points:
"[pain point keyword]" "[competitor product]" is:reply

Executive monitoring:
from:[prospect_ceo_handle] -is:retweet

Industry conversation:
#[industry_hashtag] from:[prospect_company]
```

---

### 8.3 Website Deployment for Sales Assets

**What it does:** Deploys HTML sales assets to live URLs (Netlify, Vercel, etc.) directly from the conversation.

**Why it matters for sales:**
- Share a custom prospect URL instead of an email attachment
- Password-protect assets for confidential proposals
- Track opens and engagement (if analytics added)
- Update assets in real time before and after meetings

**Deployment options:**
- Netlify instant deploy → `https://[your-company]-[prospect].netlify.app`
- Password protection for sensitive pricing or roadmap content
- Custom domain if available

---

### 8.4 AI Image and Video Generation for Assets

**What it does:** Generates original images and short video clips using AI models.

**Why it matters for sales:**
- Create custom hero images for landing pages featuring prospect's industry
- Generate workflow diagrams without needing a designer
- Produce short product demo video clips for email attachments
- Create infographics for ROI summaries or one-pagers

**Sales use cases:**
```
Images:
- Hero image for [Prospect]'s industry with your product featured
- Workflow diagram showing [Prospect]'s process before/after
- Infographic summarizing ROI calculation visually

Videos:
- 8-second product teaser clip for email footer
- Animated workflow demo (alternative to interactive HTML)
- Personalized "Hi [Prospect]" intro video
```

---

### 8.5 400+ App Integrations (CRM, Email, Calendar, Chat)

**What it does:** Connects natively to CRM systems (Salesforce, HubSpot), email (Gmail, Outlook), calendar (Google, Outlook), chat (Slack, Teams), and 400+ other apps.

**Why it matters for sales:**

| Integration | What It Unlocks |
|-------------|-----------------|
| **CRM (Salesforce, HubSpot)** | Auto-read account history, contact records, opportunity pipeline, activity log |
| **Email (Gmail, Outlook)** | Draft outreach directly in inbox, read thread context, send follow-ups |
| **Calendar (Google, Outlook)** | Auto-detect today's meetings, pull attendees, schedule prep briefs |
| **Slack / Teams** | Read internal account discussions, surface competitor mentions, tag colleagues |
| **LinkedIn** | Enrich prospect profiles, find mutual connections, surface shared content |
| **Enrichment (Apollo, Clay, ZoomInfo)** | Verified emails, phone numbers, org charts, intent signals |
| **Document storage (Notion, Confluence)** | Read existing battlecards, playbooks, case studies |
| **Call transcripts (Gong, Chorus, Otter)** | Pull prior call recordings, extract objections and competitor mentions |

**No manual copy-paste required.** Every workflow in this skill becomes fully automated when connectors are active.

---

### 8.6 Scheduled Monitoring (Competitor Alerts, Deal Alerts)

**What it does:** Runs recurring automated searches on a schedule (daily, weekly) and surfaces changes since the last run.

**Why it matters for sales:**

| Alert Type | Schedule | What to Watch |
|-----------|----------|---------------|
| Competitor news | Weekly | New features, pricing changes, funding, leadership |
| Prospect signals | Daily (hot accounts) | Funding, hires, news, job postings |
| Deal health | Daily | Champion LinkedIn activity, company news |
| Win/loss triggers | Weekly | Closed competitor deals, reference checks |

**Setting up a monitoring workflow:**
```
"Monitor [Competitor] for product releases and pricing changes.
Alert me every Monday morning with anything new."

"Watch [Prospect Company] for funding announcements and executive
changes. Alert me immediately when something happens."
```

---

### 8.7 Wide Parallel Research Across Multiple Entities

**What it does:** Runs dozens of web searches simultaneously across multiple companies, people, or topics and synthesizes the results.

**Why it matters for sales:**
- Research 20 accounts before a prospecting blitz in minutes (not hours)
- Build a complete territory landscape — all competitors, all key players
- Run account research on every attendee before a large conference
- Score and rank an entire inbound lead list by firmographic fit

**Example parallel research prompts:**
```
"Research all 15 companies from my lead list and score them
by [ICP criteria]. Output a ranked table."

"Build a competitive landscape of all 8 vendors in [category].
Compare them on pricing, features, and recent releases."

"Research all attendees at [Conference] from [Target Industry]
and find the top 10 most relevant prospects for my product."
```

---

### 8.8 Capability Comparison Summary

| Capability | Perplexity Computer | Claude Code (offline) | Notes |
|------------|--------------------|-----------------------|-------|
| Live web search | ✅ Real-time | ❌ Knowledge cutoff | Critical for trigger events |
| Social media search | ✅ X/Twitter live | ❌ | Competitor intel, prospect pain |
| CRM integration | ✅ 400+ apps | ❌ | Native data pull |
| Email integration | ✅ Draft + send | ❌ | Outreach automation |
| Calendar integration | ✅ Auto-pull | ❌ | Meeting prep automation |
| Image generation | ✅ AI models | ❌ | Asset creation |
| Video generation | ✅ AI models | ❌ | Demo clips |
| Website deployment | ✅ Netlify/Vercel | ❌ | Asset hosting |
| Scheduled monitoring | ✅ Recurring | ❌ | Competitor alerts |
| Parallel research | ✅ Many entities at once | Limited | Territory research |
| RICE prioritization logic | ✅ | ✅ | Both can execute |
| Interview analysis | ✅ | ✅ | Both can execute |
| Brand voice analysis | ✅ | ✅ | Both can execute |
| Journey mapping | ✅ | ✅ | Both can execute |
| Battlecard generation | ✅ | Limited | Perplexity adds live data |
| Asset creation | ✅ | Limited | Perplexity adds live research + deploy |

---

## Quick Reference: Command Index

| What you want | What to say | Section |
|--------------|-------------|---------|
| Research a company before outreach | "Research [Company]" | 2.1 |
| Research a specific person | "Look up [Name] at [Company]" | 2.1 |
| Analyze a customer interview | "Analyze this transcript [paste/attach]" | 2.3 |
| Build a buyer persona | "Build a persona for [segment]" | 2.4 |
| Map the buyer journey | "Map buyer journey for [persona/product]" | 2.5 |
| Full meeting prep | "Prep me for my call with [Company]" | 3.1 |
| Prep a discovery call specifically | "Prep me for discovery call with [Company]" | 3.2 |
| Prep a demo | "Prep me for my demo with [Company]" | 3.2 |
| Build a competitive battlecard | "Build battlecard for [Competitor]" | 4.1 |
| Analyze competitor brand voice | "Analyze [Competitor]'s brand voice" | 4.1 |
| Get landmine questions | "Give me landmine questions for [Competitor]" | 4.5 |
| Draft cold outreach email | "Draft outreach to [Person] at [Company]" | 5.1 |
| Write LinkedIn message | "LinkedIn message to [Name] at [Company]" | 5.3 |
| Create a follow-up sequence | "Create follow-up sequence for [Company]" | 5.4 |
| Validate email brand voice | "Check brand voice of this email" | 5.6 |
| Build a landing page | "Create landing page for [Company]" | 6.1 |
| Build a one-pager | "One-pager for [Company]" | 6.2 |
| Build a workflow demo | "Workflow demo for [Company]" | 6.2 |
| Get daily briefing | "Morning briefing" / "Start my day" | 7.1 |
| Quick brief | "Quick brief" / "tldr my day" | 7.5 |
| End of day summary | "Wrap up my day" | 7.6 |
| Prioritize my pipeline with RICE | "Prioritize my deals" | 7.3 |
| Score a specific deal | "Score this deal with RICE: [details]" | 7.3 |
| Check deal health | "What's the health of my [Company] deal?" | 7.7 |

---

## Integration Reference

### CRM Systems
| CRM | Key Data Available | Use In |
|-----|-------------------|--------|
| Salesforce | Accounts, contacts, opportunities, activities, custom fields | All sections |
| HubSpot | Contacts, deals, timeline, emails, meetings | All sections |
| Pipedrive | Deals, persons, organizations, activities | Sections 3, 7 |
| Outreach/Salesloft | Sequences, cadences, call recordings | Sections 5, 7 |

### Enrichment Tools
| Tool | Data Provided | Use In |
|------|--------------|--------|
| Apollo | Verified emails, phones, org charts, tech stack | Sections 2, 5 |
| Clay | Multi-source enrichment, intent signals, AI enrichment | Sections 2, 7 |
| ZoomInfo | Firmographics, buying signals, org chart | Sections 2, 7 |

### Research & Intelligence
| Tool | Data Provided | Use In |
|------|--------------|--------|
| LinkedIn Sales Navigator | Profiles, signals, job changes | Sections 2, 3, 5 |
| G2/Capterra | Competitor reviews, user sentiment | Section 4 |
| Gong/Chorus | Call transcripts, deal intelligence | Sections 3, 4 |

### Content & Communication
| Tool | Purpose | Use In |
|------|---------|--------|
| Gmail/Outlook | Draft and send outreach | Section 5 |
| Slack/Teams | Internal intel, account discussions | Sections 3, 4 |
| Notion/Confluence | Battlecards, playbooks, case studies | Sections 4, 6 |

---

## Common Pitfalls to Avoid

| Pitfall | Description | Prevention |
|---------|-------------|------------|
| **Generic outreach** | Not researching before sending | Always run Step 1 research before drafting |
| **Feature dumping** | Leading with product features, not prospect pain | Lead with their problem, not your solution |
| **Stale battlecards** | Using outdated competitive intel in deals | Refresh battlecards monthly or before major deals |
| **One-size personas** | Treating all buyers the same | Map to archetype (Section 2.4) for every key contact |
| **RICE paralysis** | Over-scoring instead of selling | Score takes 5 minutes; use it to pick top 3 and move |
| **Asset without context** | Building a generic landing page | Always complete Phase 0 context gathering (Section 6.2) |
| **Post-call amnesia** | Not logging insights after calls | Run post-call framework within 2 hours (Section 3.5) |
| **Ignoring brand voice** | Sending emails that don't match your voice | Validate against brand voice checklist (Section 5.6) |
| **Missing the champion** | Focusing only on the economic buyer | Map all stakeholders to personas; build internal coalition |
| **Skipping discovery** | Going straight to demo without qualification | Always complete discovery question bank first (Section 3.2) |

---

## Best Practices Summary

**Account Research:**
- Include the domain ("research acme.com") for better precision
- Specify the person ("look up Jane Smith, VP Sales at Acme")
- State your goal ("research Stripe before my demo call")
- Run interview analysis on all call recordings (Section 2.3)

**Call Prep:**
- More context = better prep — paste emails, notes, anything you have
- Name all attendees with titles; even just titles help
- State your meeting goal explicitly ("I want to get them to agree to a pilot")
- Flag known concerns upfront ("They mentioned budget is tight")

**Competitive Intelligence:**
- Be honest about weaknesses — credibility requires acknowledging where competitors are strong
- Focus on outcomes, not features — "customers achieve Y result" beats "they have X feature"
- Plant landmines, don't badmouth — ask questions that expose weaknesses naturally
- Update from the field — best intel comes from customer conversations, not websites

**Outreach:**
- Never send until research is done
- One CTA only
- Plain text only in emails (no markdown)
- Under 150 words for cold outreach
- Follow AIDA structure: hook first, problem second, proof third, ask last

**Asset Creation:**
- Use their language, their metrics, their priorities
- Feel tailored, not templated — no generic placeholders
- Always ask clarifying questions before building
- Phase 7 iteration is expected — first draft is not final

**Deal Prioritization:**
- Score every deal with RICE once a week
- Focus on top 3 by score — ignore the rest that day
- Update Confidence immediately after any meeting or signal
- Use portfolio view to balance quick wins vs. big bets

---

*Sales Super-Skill v1.0 — Merges Perplexity Computer's 6 built-in sales skills with Claude Code's Product Manager Toolkit (RICE + Customer Interview Analyzer), UX Researcher Designer, and Content Creator (Brand Voice Analyzer + Content Research Writer).*
