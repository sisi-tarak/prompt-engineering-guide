# 🚀 The Ultimate Prompt Engineering Guide

> **From Zero to Prompt Engineer — A Complete, Progressive Guide with 100+ Production-Ready Prompt Templates**
>
> Created by **Sisindri Singamsetti**

[![Stars](https://img.shields.io/github/stars/sisi-tarak/prompt-engineering-guide?style=social)](https://github.com/sisi-tarak/prompt-engineering-guide)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Prompts](https://img.shields.io/badge/Prompts-100%2B-blue)](https://github.com/sisi-tarak/prompt-engineering-guide)
[![Categories](https://img.shields.io/badge/Categories-25-green)](https://github.com/sisi-tarak/prompt-engineering-guide)

---

## 📖 Table of Contents

- [What is Prompt Engineering?](#what-is-prompt-engineering)
- [How to Use These Templates](#how-to-use-these-templates)
- **Part 1 — Theory**: [Beginner](#level-1--beginner) | [Intermediate](#level-2--intermediate) | [Advanced](#level-3--advanced) | [Expert (Claude-Specific)](#level-4--expert)
- **Part 2 — 100+ Templates Across 25 Categories** (see full list below)
- [Prompt Testing Framework](#prompt-testing-framework)

---

## What is Prompt Engineering?

Prompt engineering is the practice of designing inputs for AI models to produce optimal outputs. Think of the AI as a world-class expert who just joined your team — the quality of their work depends entirely on the quality of your brief.

```
❌ Vague:  "Write me some code"
✅ Precise: "Write a React component for a user login form with email/password 
            validation, error states, and a loading spinner. Use TypeScript, 
            Tailwind CSS, and react-hook-form. Include accessibility attributes."
```

---

## How to Use These Templates

Every template uses `[PLACEHOLDERS]`. Replace them with your specifics:

| Placeholder | Example |
|------------|---------|
| `[NICHE]` | fitness coaching, SaaS, tech education |
| `[AUDIENCE]` | college students, small business owners, developers |
| `[TOPIC]` | AI automation, meal prep, web development |
| `[PRODUCT]` | your product/service name |
| `[BRAND]` | your brand name |
| `[PLATFORM]` | Instagram, YouTube, LinkedIn |
| `[SERVICE]` | what you offer |
| `[RESULT]` | transformation you deliver |
| `[COMPETITOR]` | competitor names |

**Pro tip:** The more specific your placeholders, the better the output.

---

# Part 1 — Theory

## Level 1 — Beginner

### 5 Principles of Good Prompting

**1. Be Specific** — "Create a 30-day content calendar for [NICHE]" beats "Help me with marketing"

**2. Give Context** — Who you are, who it's for, what stage you're at

**3. Define Format** — Tell the AI exactly how to structure the output

**4. Set Constraints** — Word limits, what to include, what to avoid

**5. Use Negative Instructions** — "Do NOT use jargon" is as important as "Use simple language"

### Prompt Anatomy
```
1. ROLE        — Who should the AI be?
2. CONTEXT     — What's the situation?
3. TASK        — What needs doing?
4. FORMAT      — What should output look like?
5. CONSTRAINTS — What are the limits?
6. EXAMPLES    — What does good look like?
7. TONE        — How should it sound?
```

## Level 2 — Intermediate

### Role-Based Prompting
```
You are a [ROLE] with [X] years of experience in [DOMAIN].
You specialize in [SPECIALIZATION].
RULES:
- Always consider [CONSTRAINT]
- Prioritize [PRIORITY] over [LOWER PRIORITY]
- Use [MARKET/CURRENCY] context
```

### XML Prompting (Claude-Optimized)
```xml
<role>You are a [ROLE] specializing in [DOMAIN].</role>
<context>Industry: [INDUSTRY] | Audience: [AUDIENCE] | Stage: [STAGE]</context>
<task>[SPECIFIC TASK]</task>
<constraints>
- Constraint 1
- Constraint 2
</constraints>
<output_format>
1. [FIELD 1]
2. [FIELD 2]
</output_format>
```

### JSON Prompting
```
Generate [X items] about [TOPIC]. Return ONLY valid JSON:
{
  "items": [
    { "title": "string", "description": "string", "priority": "high|medium|low" }
  ]
}
```

### Chain-of-Thought
```
Analyze [TOPIC]. Think step by step:
1. Identify the core problem
2. List 3 approaches with pros/cons
3. Evaluate against [CRITERIA]
4. Recommend with confidence level
```

### Few-Shot
```
Write [CONTENT] in this style:
GOOD: "[example matching desired output]"
BAD: "[example of what NOT to do]"
Now write [X items] about [TOPIC]. Match the GOOD style.
```

## Level 3 — Advanced

### RSSRO Framework
```
R — ROLE:      Who is the AI? (expertise, experience)
S — SKILLS:    What skills to apply? (list 5-7)
S — SUB-TASKS: What deliverables are needed?
R — RULES:     Non-negotiable constraints (max 10)
O — OUTPUT:    Exact response format
```

### Multi-Agent Prompting
```
Process [TASK] through 3 expert lenses:
AGENT 1 — The [ROLE]: [analyzes X]
AGENT 2 — The [ROLE]: [evaluates Y]
AGENT 3 — The Critic: [challenges assumptions]
Final: synthesized recommendation.
```

### Constraint Escalation
```
PREFER:  Suggestions (nice to have)
SHOULD:  Strong guidance (follow unless good reason)
MUST:    Requirements (always follow)
NEVER:   Absolute prohibitions (zero exceptions)
```

### Iterative Refinement
```
Step 1: Generate [X] options
Step 2: Rate each on [CRITERIA] (1-10)
Step 3: Take top 2, create 3 variations each
Step 4: Select best, explain why
```

## Level 4 — Expert

### Claude System Prompts
```xml
<role>You are a [ROLE] for [CONTEXT].</role>
<skills>Skill 1, Skill 2, Skill 3</skills>
<rules priority="non-negotiable">
1. Rule 1
2. Rule 2
</rules>
```

### CLAUDE.md (Claude Code)
```markdown
# CLAUDE.md
## Project: [NAME]
## Stack: [TECH]
## Standards: [RULES]
## Architecture: [DIRS]
```

### Claude API Structured Output
```javascript
const response = await anthropic.messages.create({
  model: "claude-sonnet-4-20250514",
  system: "Return ONLY valid JSON. No markdown.",
  messages: [{ role: "user", content: "[TASK]. Schema: {[SCHEMA]}" }]
});
```

---

# Part 2 — 100+ Prompt Templates (25 Categories)

---

## 1. Instagram Content Strategy

**T1.1 — 90-Day Content Calendar**
```
Act as a senior content strategist. Create a 90-day Instagram content strategy for a creator in [NICHE] targeting [AUDIENCE]. Include weekly themes, content format mix (Reels 40%, Carousels 30%, Stories 20%, Posts 10%), authority-building ideas, engagement drivers, and lead generation content for [PRODUCT/SERVICE]. Output as week-by-week table: Week | Theme | Format | Topic | CTA.
```

**T1.2 — 30 Content Ideas Generator**
```
Generate 30 high-performing content ideas for [NICHE] targeting [AUDIENCE]. Each idea: (1) content type, (2) hook (first line), (3) core value delivered, (4) why it attracts attention, (5) engagement type (saves/shares/comments). Mix: 40% educational, 25% entertaining, 20% inspirational, 15% promotional.
```

**T1.3 — Competitor Content Audit**
```
Analyze competitor accounts [COMPETITOR 1], [COMPETITOR 2], [COMPETITOR 3] in [NICHE]. For each: content themes, posting frequency, top formats, hook patterns, engagement tactics, gaps. Deliver: 5 opportunities they're ALL missing, 3 formats to replicate, 3 mistakes to avoid, unique positioning angle.
```

**T1.4 — Audience Persona Builder**
```
Create a detailed audience persona for [TARGET AUDIENCE] in [NICHE]. Include: demographics, psychographics, online behavior, top 5 pain points, purchase triggers, language patterns, content preferences, and buying objections for [PRODUCT/SERVICE].
```

## 2. Instagram Reels & Hooks

**T2.1 — 20 Scroll-Stopping Hooks**
```
Generate 20 scroll-stopping hooks for Reels about [TOPIC] targeting [AUDIENCE]. Each: under 10 words, creates information gap, conversational tone, works as text-on-screen AND spoken. Format: Hook | Trigger (curiosity/shock/FOMO/aspiration) | Why It Works.
```

**T2.2 — 60-Second Reel Script**
```
Write a 60-second Reel script about [TOPIC] for [AUDIENCE]. Structure: 0-3s pattern interrupt hook → 3-10s context → 10-40s three key points → 40-55s summary → 55-60s specific CTA. Include [TEXT ON SCREEN] and [VISUAL] suggestions. 140-170 words.
```

**T2.3 — Story Sequence (7-Slide)**
```
Design a 7-slide Instagram Story sequence about [TOPIC] driving viewers to [ACTION]. Slide 1: hook poll. Slide 2: surprising stat. Slide 3: common mistake. Slide 4: correct approach. Slide 5: quick hack. Slide 6: social proof. Slide 7: CTA. Each slide: text (max 20 words) + interactive element.
```

**T2.4 — 10 Viral Angles from One Topic**
```
Turn [TOPIC] into 10 Reel concepts using different viral mechanics: (1) curiosity gap, (2) listicle, (3) contrarian, (4) tutorial, (5) personal story, (6) comparison, (7) myth-buster, (8) challenge, (9) behind-the-scenes, (10) hot take. Each: title, hook, engagement type.
```

## 3. Instagram Sales & DMs

**T3.1 — Non-Salesy Sales Caption**
```
Write a caption selling [PRODUCT] without sounding salesy. Structure: one-line hook → personal story → 3 buyer benefits → social proof line → soft CTA to comment [KEYWORD]. Under 300 words. Genuine, warm tone. Include 20-25 hashtags.
```

**T3.2 — DM Automation Sequence**
```
Write a 3-message DM sequence for someone who commented [KEYWORD] on a post about [TOPIC]. I sell [PRODUCT] helping [AUDIENCE] achieve [RESULT]. Message 1 (immediate): deliver freebie warmly. Message 2 (24h): transformation story. Message 3 (48h): soft purchase invite with opt-out. Friendly, zero pressure.
```

**T3.3 — 9-Slide Sales Carousel**
```
Create a 9-slide carousel selling [PRODUCT] without feeling like an ad. Slide 1: viral hook. Slides 2-6: teach one thing [PRODUCT] solves. Slide 7: myth debunked. Slide 8: social proof. Slide 9: soft CTA. Each slide: text (max 30 words) + visual direction.
```

**T3.4 — Instagram Bio Optimizer**
```
Write 5 Instagram bio options selling [PRODUCT] without being pushy. Product helps [AUDIENCE] achieve [RESULT]. Include: who I help, what result they get, clear CTA. Under 150 characters each. Human, warm, authentic.
```

## 4. YouTube Strategy & Growth

**T4.1 — Niche Velocity Finder**
```
Act as a YouTube growth strategist. List high-velocity niches for [CHANNEL TYPE] channels. Focus on demand exceeding supply. For each: why it's growing, best content format, low-competition signals, monetization potential, repeatability score.
```

**T4.2 — 30 Viral Video Ideas**
```
Generate 30 viral video ideas for [NICHE] targeting [AUDIENCE]. Each: title (under 60 chars), hook (first sentence), emotional trigger, format, ideal length, thumbnail concept. Use: curiosity gaps, polarity, authority, trend-surfing. Include 5 Shorts concepts.
```

**T4.3 — Channel Audit**
```
Audit a YouTube channel in [NICHE] with [X] subscribers. Analyze: branding, content pillars, upload consistency, titles, thumbnails, hooks, retention, SEO. Deliver: 5 immediate fixes, 3 experiments, strategic moves, 30-day content calendar.
```

**T4.4 — Competitor Deep Dive**
```
Analyze top 5 YouTube competitors in [NICHE]. For each: strategy, formats, frequency, hooks, titles, thumbnails, engagement. Deliver: universal patterns, unique tactics, unfilled gaps, positioning strategy.
```

## 5. YouTube Scripting & Production

**T5.1 — 30-Second Viral Hook**
```
Write a 30-second YouTube hook about [TOPIC]. Start with shocking/counterintuitive statistic. Follow with a question making viewers feel they'll learn something game-changing. Under 80 words. Conversational, slightly alarming, no fluff.
```

**T5.2 — 10 High-CTR Titles**
```
Generate 10 title variations for [TOPIC]: 2 curiosity-gap, 2 number-list, 2 how-to, 2 contrarian, 2 emotional/story. Under 60 chars. No clickbait. Accurately reflect content.
```

**T5.3 — Beginner Tutorial Script**
```
Write a YouTube script teaching [TASK] to complete beginners. Structure: hook showing end result → 2-sentence overview → each step with real examples → common mistakes → motivating outro. 900-1100 words. Zero jargon.
```

**T5.4 — Script Retention Analysis**
```
Analyze scripts of 500K+ view videos in [NICHE]. Break down: hook, curiosity gaps, pacing, pattern interrupts, re-hooks, endings. Extract: repeatable template, 5 retention techniques, placeholder lines, do's and don'ts.
```

**T5.5 — Thumbnail Design Rules**
```
Analyze top thumbnails in [NICHE]. Break down: composition, text usage, color contrast, emotional signaling, simplicity. Deliver: 5 reusable templates, do/don't checklist, color palette, step-by-step design process.
```

## 6. LinkedIn & Professional

**T6.1 — Thought Leadership Post**
```
Write a LinkedIn post about [TOPIC] positioning me as a thought leader. Hook (first 2 lines) → personal insight/contrarian take → actionable takeaway → engagement question. Max 1300 chars. 3-5 hashtags at end.
```

**T6.2 — Cold Outreach DM (4-Touch)**
```
Write a 4-message LinkedIn DM sequence for [ROLE] at [COMPANY TYPE] needing [SERVICE]. Day 0: personalized connection (300 chars). Day 3: value-add. Day 7: case study. Day 14: soft ask or graceful exit.
```

**T6.3 — Company Content Calendar**
```
Create a 4-week LinkedIn company page plan for [COMPANY] in [INDUSTRY]. Week 1: thought leadership. Week 2: behind-the-scenes. Week 3: customer success. Week 4: educational. 3 posts/week with copy, visuals, timing.
```

**T6.4 — Profile Optimization**
```
Write 3 LinkedIn headline variations and About section for a [ROLE] who [WHAT YOU DO] for [AUDIENCE]. Headlines: under 120 chars, keyword-rich. About: 300 words — passion hook, results, approach, proof, CTA.
```

## 7. Content Repurposing

**T7.1 — One-to-Many Engine**
```
Repurpose this [CONTENT TYPE] about [TOPIC] into: 3 Instagram carousels, 5 tweets, 1 LinkedIn post, 3 Reel hooks, 1 newsletter section, 1 YouTube Shorts script. Each platform-native with unique hooks.
```

**T7.2 — Content Batching System**
```
Design a system for [NICHE] creator to produce 1 month of content in 1 day. Phases: pre-production (2h), production (4h), post-production (2h). Output: [X] Reels, [X] carousels, [X] stories. Steps, time blocks, tools.
```

## 8. Email Marketing

**T8.1 — Cold Email Sequence (5-Touch)**
```
Write 5-email outreach for [SERVICE] targeting [AUDIENCE]. Day 0: pain point intro (80 words). Day 3: value-add (60 words). Day 7: case study (100 words). Day 12: meeting ask (50 words). Day 18: break-up (60 words). Subject lines under 6 words.
```

**T8.2 — Newsletter Template**
```
Write a newsletter about [TOPIC] for [AUDIENCE]. Subject (3 options), preview text, personal hook, 3 sections (insight/tip/resource), takeaway, CTA, P.S. line. 500-700 words. Knowledgeable friend tone.
```

**T8.3 — Welcome Sequence (5-Email)**
```
Write welcome sequence for [BRAND]. Email 1: deliver + expectations. Email 2: your story. Email 3: best content. Email 4: social proof. Email 5: soft pitch. Each: subject, body (under 200 words), CTA.
```

## 9. Copywriting & Persuasion

**T9.1 — Landing Page Copy**
```
Write landing page for [PRODUCT]: hero (headline + sub), 3 pain points, solution, 3 features with benefits, social proof, how-it-works (3 steps), pricing with anchoring, 5 FAQs, final CTA with urgency.
```

**T9.2 — Objection Handling (10 Scripts)**
```
List 10 objections for [PRODUCT] with persuasive responses. Format: Objection → Response (empathize, reframe, prove) → Follow-up (transition to next step). Cover: price, timing, trust, competition, DIY.
```

**T9.3 — Value Proposition Canvas**
```
Create value proposition for [PRODUCT]: Customer side (jobs, pains, gains) → Product side (services, pain relievers, gain creators). Then: one-liner, elevator pitch (30 sec), long-form (100 words).
```

**T9.4 — Brand Voice Guide**
```
Define brand voice for [BRAND]: 5 personality traits, tone spectrum, words we use vs avoid, sentence style, humor level, platform adjustments, 3 on-brand vs 3 off-brand examples.
```

## 10. SEO & Keywords

**T10.1 — Keyword Cluster Map**
```
Generate keyword clusters for [TOPIC/BUSINESS]: 5 seed keywords → 10 long-tails each → group by intent (informational/commercial/transactional) → content type per cluster → priority ranking. Table format.
```

**T10.2 — Blog SEO Framework**
```
Write SEO outline for "[KEYWORD]": title tag (60 chars), meta description (155 chars), H1, 6-8 H2s targeting sub-keywords, key points per H2, internal links, FAQ (5 from "People Also Ask"), featured snippet format.
```

## 11. Startup & Business

**T11.1 — Business Validation**
```
Validate: [IDEA]. Analyze: market size (TAM/SAM/SOM), competition, unit economics, scalability, revenue model, GTM (first 100 customers), top 3 red flags. Verdict: GO/PIVOT/KILL with reasoning.
```

**T11.2 — Scaling Roadmap**
```
Plan to scale [BUSINESS] to [REVENUE TARGET]: what to automate, delegate, systematize. Hiring roadmap, bottlenecks per stage, key metrics per milestone. Output as phased execution plan.
```

**T11.3 — Pitch Deck Script (12 Slides)**
```
Write narration for: Problem → Solution → Demo → Market → Business Model → Traction → Competition → Team → GTM → Financials → Ask → Vision. Company: [NAME], Industry: [INDUSTRY], Stage: [STAGE].
```

**T11.4 — Pricing Strategy**
```
Design pricing for [PRODUCT]: competitor analysis, cost-plus analysis, value-based analysis. 3 tiers (Good/Better/Best) with names, prices, inclusions. Psychology tactics, discounting rules, anchoring approach.
```

## 12. Sales & Lead Gen

**T12.1 — Lead Scoring Model**
```
Design lead scoring for [BUSINESS]: demographic signals (+points), behavioral signals (+points), thresholds (cold/warm/hot/ready), qualification questions, disqualification criteria.
```

**T12.2 — Sales Call Script**
```
Consultative call script for [SERVICE] to [AUDIENCE]: opening (30s) → discovery (5 questions) → diagnosis → solution presentation → social proof → pricing with anchoring → objections → close. Not pushy.
```

**T12.3 — Lead Magnet Ideas**
```
Generate 10 lead magnet ideas for [NICHE]: each solves immediate problem, createable in under 4 hours, naturally leads to [SERVICE]. Format: name, type, creation time, conversion hook.
```

**T12.4 — Proposal Template**
```
Write a client proposal for [SERVICE]: executive summary, scope, timeline with milestones, deliverables, 3 pricing tiers, terms, team intro, next steps. Professional but approachable.
```

## 13. Market Research

**T13.1 — Market Sizing**
```
Estimate market for [PRODUCT] in [REGION]: TAM, SAM, SOM using top-down AND bottom-up. Data sources, assumptions, growth rate, drivers, risks. All in [CURRENCY].
```

**T13.2 — Trend Report**
```
Industry trend analysis for [INDUSTRY]: top 5 trends with drivers, technologies to watch, regulatory changes, buyer behavior shifts, opportunities, threats, 3 predictions for next 12 months. Executive briefing format.
```

## 14. Branding & Positioning

**T14.1 — Positioning Statement**
```
Write positioning for [BRAND]: "For [AUDIENCE] who [NEED], [BRAND] is the [CATEGORY] that [BENEFIT] because [REASON]." Then: 3 variations, one-liner, elevator pitch, social bio, tagline.
```

**T14.2 — Brand Identity System**
```
Design brand identity for [BRAND]: mission, vision, 5 values, personality traits, voice guidelines, visual direction, brand story, brand promise.
```

## 15. Digital Products & Courses

**T15.1 — Product Idea Generator**
```
Create digital product for [NICHE]. Skills: [SKILLS]. Audience: [AUDIENCE]. Problem: [PROBLEM]. Top 5 ideas ranked by ease × income: name, format, contents, price point, creation time, marketing angle.
```

**T15.2 — Course Outline Builder**
```
Course outline for [TOPIC] for [AUDIENCE]: compelling name, subtitle, 5-7 modules (name, objective, 3-5 lessons, exercise, deliverable each), quick win (first 10 min), capstone project, bonus materials. Worth [PRICE].
```

**T15.3 — Sales Funnel Design**
```
Sales funnel for [PRODUCT]: Awareness (content strategy) → Interest (lead magnet) → Consideration (5-email sequence) → Conversion (sales page) → Retention (post-purchase + upsell). Content, copy, metrics per stage.
```

## 16. Frontend Development

**T16.1 — React Component**
```
Build React component for [NAME]: TypeScript, Tailwind CSS, props with types, loading/error/empty/success states, accessibility (ARIA, keyboard), responsive, JSDoc, test template.
```

**T16.2 — Next.js Full Feature**
```
Build [FEATURE] for Next.js 14: database schema with types, server actions, React components (server + client), auth integration, Zod validation, error boundaries, TypeScript interfaces.
```

**T16.3 — Responsive Layout**
```
Create responsive [PAGE TYPE] with Tailwind: mobile-first, breakpoints (sm/md/lg/xl), navigation (hamburger→sidebar), lazy loading, accessibility, dark mode, semantic HTML.
```

**T16.4 — State Management**
```
Design state management for [APP] with [Zustand/Redux/Context]: store structure, actions, selectors, async handling, persistence, TypeScript types, testing approach.
```

## 17. Backend Development

**T17.1 — REST API**
```
Create API for [RESOURCE] with [Express/FastAPI] + [TypeScript/Python]: validation, ORM models, CRUD + pagination + filtering, JWT auth, rate limiting, error handling, logging, API docs.
```

**T17.2 — Authentication System**
```
Build auth system: registration + email verification, JWT (access + refresh), password hashing, reset flow, RBAC (admin/user/editor), rate limiting, security headers, audit logging.
```

**T17.3 — Background Job System**
```
Design background job processor for [USE CASE]: job queue ([Bull/Celery]), retry logic, dead letter queue, monitoring, scaling, priority levels, scheduled jobs, error handling.
```

## 18. Database Design

**T18.1 — Schema Design**
```
Design database for [APP]: entities with fields/types/constraints, relationships, indexes, unique constraints, defaults. Include: ER description, creation scripts, TypeScript interfaces, seed data, common queries.
```

**T18.2 — Migration Strategy**
```
Plan migration from [CURRENT] to [TARGET]: step-by-step, data transformation, rollback per step, downtime estimate, validation checks, testing, backup/recovery.
```

## 19. AI Agents & Automation

**T19.1 — Multi-Agent System**
```
Design multi-agent system for [PURPOSE]: orchestrator + [X] specialist agents. Each agent: system prompt, I/O format, tools needed, error handling, memory. Tech: [stack]. Include project structure and implementation order.
```

**T19.2 — Chatbot Builder**
```
Build [PLATFORM] chatbot for [PURPOSE]: capabilities (FAQ/booking/qualification/escalation), conversation flows (new/returning/error/handoff), tech stack, webhook setup, state management, analytics.
```

**T19.3 — Automation Workflow**
```
Design automation for [PROCESS]: trigger → steps with tools → conditional logic → output. Error handling per step, monitoring, cost estimate, scaling considerations.
```

**T19.4 — Voice AI System**
```
Build voice AI for [USE CASE]: telephony + STT + AI + TTS + integrations. Conversation design: greeting, intent detection, actions, error handling, summary. Architecture, latency, cost/call.
```

## 20. DevOps & CI/CD

**T20.1 — CI/CD Pipeline**
```
Write [GitHub Actions/GitLab CI] for [PROJECT]: lint → type-check → test → build → deploy to [PLATFORM]. Secrets, caching, branch protection, failure notifications, manual prod approval.
```

**T20.2 — Docker Configuration**
```
Docker for [APP]: multi-stage Dockerfile (dev+prod), docker-compose with all services, volumes, networks, health checks, .dockerignore. Comments explaining decisions.
```

**T20.3 — Infrastructure Design**
```
Infrastructure for [APP] on [CLOUD]: compute, database, storage, CDN, DNS, SSL, monitoring. Cost estimate, scaling strategy, backup plan, security config.
```

## 21. API Design

**T21.1 — API Specification**
```
Design API for [SERVICE]: all endpoints (method, path, description, auth), request/response schemas, error format, pagination, rate limits, versioning, auth flow, webhook design.
```

**T21.2 — Integration Builder**
```
Build integration with [API] for [PURPOSE]: auth setup, key endpoints with examples, error handling (retries, fallbacks), rate limits, data transformation, webhooks, monitoring, testing.
```

## 22. UI/UX Design

**T22.1 — Design System**
```
Design system for [PROJECT]: colors (hex + usage), typography (sizes, weights), spacing scale, borders, shadows, component patterns (buttons, inputs, cards, modals), breakpoints, animations, accessibility, dark mode.
```

**T22.2 — User Flow**
```
Design user flow for [FEATURE]: entry points, step-by-step with decisions, screen descriptions, error states, edge cases, success state, accessibility, mobile vs desktop differences.
```

**T22.3 — Wireframe Description**
```
Describe wireframe for [PAGE TYPE]: sections (hero, problem, solution, features, proof, pricing, FAQ, CTA), content per section, visual hierarchy, mobile layout, interaction notes.
```

## 23. Project Management

**T23.1 — Project Plan**
```
Project plan for [PROJECT]: scope (in/out), phases (Discovery→Design→Dev→Test→Launch), tasks with estimates, milestones, risk register (top 5), communication plan, resources.
```

**T23.2 — Sprint Planning**
```
Plan [X-week] sprint for [PROJECT]. Priorities: [LIST]. Capacity: [X people, X hours]. Produce: sprint goal, user stories with acceptance criteria, task breakdown, dependencies, definition of done.
```

**T23.3 — Technical Spec**
```
Tech spec for [FEATURE]: overview, user stories, architecture, API changes, DB changes, UI/UX, security, performance, testing, rollout plan, open questions. Include edge cases.
```

## 24. Productivity & Systems

**T24.1 — Weekly Workflow**
```
Design weekly system for [ROLE] managing [RESPONSIBILITIES]: time blocks (Mon-Fri), daily routines, priority framework, batching strategy, tools, review cadence, energy management.
```

**T24.2 — 90-Day Execution Roadmap**
```
Turn [GOAL] into 90-day roadmap: Phase 1 (Days 1-30) foundation, Phase 2 (31-60) momentum, Phase 3 (61-90) scale. 5 actions per phase with deliverables, milestones, time investment, obstacles.
```

**T24.3 — Decision Framework**
```
Decide: [DECISION]. Analyze via: first principles, reversibility, 10/10/10 rule, opportunity cost, pre-mortem, regret minimization. Recommendation with confidence level.
```

## 25. Graphic Design & Visuals

**T25.1 — Social Media Visual Brief**
```
Brief for [X] graphics for [PLATFORM]: theme, brand colors, style. Each: dimensions, layout, headline, body, image direction, typography, CTA element. Consistency rules across set.
```

**T25.2 — Infographic Structure**
```
Infographic about [TOPIC] for [AUDIENCE]: title, intro stat, 4-6 data sections (data point, viz type, text), flow direction, visual hierarchy, colors, sources, CTA.
```

**T25.3 — Presentation Design**
```
Design [X]-slide deck about [TOPIC]: each slide: type, headline (8 words), body (25 words), visual, speaker notes. Rules: one idea/slide, minimal text, visual-first, progressive disclosure.
```

**T25.4 — Thumbnail/Cover Concepts**
```
Design [X] thumbnails for [PLATFORM] about [TOPIC]: layout, text (max 4 words), colors (2-3), emotion/metaphor, readability at small size. Must work at 100x56px.
```

---

## Prompt Testing Framework

| Criteria | Score (1-5) | What to Check |
|----------|:-----------:|--------------|
| Relevance | ⭐⭐⭐⭐⭐ | Output matches request? |
| Specificity | ⭐⭐⭐⭐⭐ | Actionable or generic? |
| Accuracy | ⭐⭐⭐⭐⭐ | Facts correct? |
| Format | ⭐⭐⭐⭐⭐ | Structured as asked? |
| Completeness | ⭐⭐⭐⭐⭐ | All aspects covered? |
| Reusability | ⭐⭐⭐⭐⭐ | Works with different inputs? |

### Checklist
```
□ Clear role?          □ Enough context?      □ Output format defined?
□ Constraints set?     □ Examples included?    □ Negative instructions?
□ Critical rules at start AND end?             □ Tested with real case?
```

---

## Contributing

1. Fork → 2. Add template (use `[PLACEHOLDER]` format) → 3. Test with 2+ topics → 4. PR

---

## Sources & Inspiration

- [@shwetacreates](https://instagram.com/shwetacreates) — Content strategy & digital product prompts
- [@codingknowledge](https://instagram.com/codingknowledge) — DM automation & selling prompts
- [@razvanpbusiness](https://instagram.com/razvanpbusiness) — YouTube growth prompt chain
- [@paulhilse](https://instagram.com/paulhilse) — YouTube scripting prompts
- [@claudetricks.ai](https://instagram.com/claudetricks.ai) — Business automation prompts
- [Anthropic Prompt Engineering Docs](https://docs.anthropic.com/en/docs/build-with-claude/prompt-engineering)

---

**MIT License** — Use freely. Attribution appreciated.

**Created by [Sisindri Singamsetti](https://github.com/sisi-tarak)**

⭐ **Star this repo if it helped you!** ⭐
