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

**Part 1 — Theory (Progressive Levels)**
- [Level 1 — Beginner: Foundations](#level-1--beginner-foundations)
- [Level 2 — Intermediate: Structured Prompting](#level-2--intermediate-structured-prompting)
- [Level 3 — Advanced: System Design](#level-3--advanced-system-design)
- [Level 4 — Expert: Claude-Specific Mastery](#level-4--expert-claude-specific-mastery)

**Part 2 — 100+ Templates Across 25 Categories**

| # | Category | Templates |
|---|----------|-----------|
| 1 | [Instagram Content Strategy](#1-instagram-content-strategy) | T1.1 – T1.4 |
| 2 | [Instagram Reels & Hooks](#2-instagram-reels--hooks) | T2.1 – T2.4 |
| 3 | [Instagram Sales & DMs](#3-instagram-sales--dms) | T3.1 – T3.4 |
| 4 | [YouTube Strategy & Growth](#4-youtube-strategy--growth) | T4.1 – T4.4 |
| 5 | [YouTube Scripting & Production](#5-youtube-scripting--production) | T5.1 – T5.5 |
| 6 | [LinkedIn & Professional](#6-linkedin--professional-branding) | T6.1 – T6.4 |
| 7 | [Content Repurposing](#7-content-repurposing) | T7.1 – T7.2 |
| 8 | [Email Marketing & Outreach](#8-email-marketing--outreach) | T8.1 – T8.3 |
| 9 | [Copywriting & Persuasion](#9-copywriting--persuasion) | T9.1 – T9.4 |
| 10 | [SEO & Keyword Strategy](#10-seo--keyword-strategy) | T10.1 – T10.2 |
| 11 | [Startup & Business Strategy](#11-startup--business-strategy) | T11.1 – T11.4 |
| 12 | [Sales & Lead Generation](#12-sales--lead-generation) | T12.1 – T12.4 |
| 13 | [Market Research & Analysis](#13-market-research--analysis) | T13.1 – T13.2 |
| 14 | [Branding & Positioning](#14-branding--positioning) | T14.1 – T14.2 |
| 15 | [Digital Products & Courses](#15-digital-products--courses) | T15.1 – T15.3 |
| 16 | [Frontend Development](#16-frontend-development-react--nextjs) | T16.1 – T16.4 |
| 17 | [Backend Development](#17-backend-development-nodejs--python) | T17.1 – T17.3 |
| 18 | [Database Design](#18-database-design--management) | T18.1 – T18.2 |
| 19 | [AI Agents & Automation](#19-ai-agents--automation) | T19.1 – T19.4 |
| 20 | [DevOps & CI/CD](#20-devops--cicd) | T20.1 – T20.3 |
| 21 | [API Design & Integration](#21-api-design--integration) | T21.1 – T21.2 |
| 22 | [UI/UX & Design Systems](#22-uiux--design-systems) | T22.1 – T22.3 |
| 23 | [Project Management](#23-project-management--planning) | T23.1 – T23.3 |
| 24 | [Personal Productivity](#24-personal-productivity--systems) | T24.1 – T24.3 |
| 25 | [Graphic Design & Visuals](#25-graphic-design--visual-content) | T25.1 – T25.4 |

- [Prompt Testing Framework](#prompt-testing-framework)
- [Contributing](#contributing)

---

## What is Prompt Engineering?

Prompt engineering is the practice of designing inputs for AI language models to produce optimal, specific, and actionable outputs. Think of the AI as a world-class expert who just joined your team — the quality of their work depends entirely on the quality of your brief.

**Bad prompt:**
> "Write me some code"

**Good prompt:**
> "Write a React component for a user login form
> with email and password validation, error states,
> and a loading spinner. Use TypeScript, Tailwind CSS,
> and react-hook-form. Include accessibility attributes."

---

## How to Use These Templates

Every template uses `[PLACEHOLDERS]` in brackets. Replace them with your specifics.

| Placeholder | What to Replace With | Example |
|------------|---------------------|---------|
| `[NICHE]` | Your industry or topic | fitness coaching, SaaS, tech education |
| `[AUDIENCE]` | Your target audience | college students, small business owners |
| `[TOPIC]` | Specific subject | AI automation, meal prep, web development |
| `[PRODUCT]` | Your product or service name | "10x Prompting Course", "FitMeal App" |
| `[BRAND]` | Your brand name | Any brand you're working on |
| `[PLATFORM]` | Social media platform | Instagram, YouTube, LinkedIn |
| `[SERVICE]` | What you offer | web development, consulting |
| `[RESULT]` | Transformation you deliver | "land their first tech job" |
| `[COMPETITOR]` | Competitor names or handles | @competitor1, @competitor2 |
| `[KEYWORD]` | CTA keyword | "LEARN", "FREE", "GUIDE" |

**Pro tip:** The more specific your placeholders, the better the output. "College students in India interested in AI" beats "young people" every time.

---

# Part 1 — Theory

## Level 1 — Beginner: Foundations

### The 5 Principles of Good Prompting

**Principle 1: Specificity Beats Vagueness**

❌ Bad:
> "Help me with marketing"

✅ Good:
> "Create a 30-day Instagram content calendar for a [NICHE]
> brand targeting [AUDIENCE]. Include 4 posts per week:
> 2 Reels, 1 carousel, 1 story sequence. Each entry should
> include the hook, topic summary, and CTA."

---

**Principle 2: Context is Everything**

❌ Bad:
> "Write a caption"

✅ Good:
> "Write an Instagram caption for a Reel about [TOPIC].
> Target audience: [AUDIENCE].
> Tone: casual and relatable.
> Include a CTA to comment '[KEYWORD]' for a free resource.
> Maximum 150 words."

---

**Principle 3: Format Controls Output**

❌ Bad:
> "Give me some ideas"

✅ Good:
> "Give me 10 video ideas about [TOPIC]. For each idea provide:
>
> - **Title**: under 60 characters
> - **Hook**: first sentence of the video, under 15 words
> - **Format**: tutorial, listicle, story, or review
> - **Emotional trigger**: curiosity, FOMO, aspiration, or shock"

---

**Principle 4: Constraints Improve Quality**

❌ Bad:
> "Write a blog post about React"

✅ Good:
> "Write a blog post about [TOPIC].
> - Length: 1200–1500 words
> - Reading level: intermediate developer
> - Include 3 code examples, each under 20 lines
> - No jargon without immediate explanation
> - End with a 'Key Takeaways' section (max 5 bullets)"

---

**Principle 5: Say What NOT to Do**

> "RESTRICTIONS:
> - Do NOT use buzzwords like 'leverage', 'synergy', 'disrupt'
> - Do NOT assume prior experience with [TOPIC]
> - Do NOT include unverified statistics
> - Do NOT use passive voice
> - NEVER exceed the specified word count"

---

### The Anatomy of a Prompt

Every effective prompt can include these 7 building blocks:

| # | Component | Purpose | Example |
|---|-----------|---------|---------|
| 1 | **Role** | Who should the AI be? | "You are a senior content strategist" |
| 2 | **Context** | What's the situation? | "For a startup at seed stage" |
| 3 | **Task** | What needs doing? | "Create a 90-day content plan" |
| 4 | **Format** | How should output look? | "Output as a weekly table" |
| 5 | **Constraints** | What are the limits? | "Max 10 items, under 60 chars each" |
| 6 | **Examples** | What does good look like? | "Like this: [example]" |
| 7 | **Tone** | How should it sound? | "Casual, like explaining to a friend" |

---

## Level 2 — Intermediate: Structured Prompting

### Role-Based Prompting

Assign a specific identity to activate domain expertise:

> You are a [ROLE] with [X] years of experience in [DOMAIN].
> You specialize in [SPECIALIZATION] and have worked with [CLIENT TYPE].
>
> BEHAVIORAL RULES:
> - Always consider [CONSTRAINT]
> - Prioritize [PRIORITY] over [LOWER PRIORITY]
> - Challenge assumptions when you spot weak reasoning
> - Use [MARKET/CURRENCY] context for all examples

---

### XML Prompting (Claude-Optimized)

Claude respects XML tag boundaries precisely. Use them to create clear semantic sections:

```xml
<role>
  You are a [ROLE] specializing in [DOMAIN].
</role>

<context>
  Industry: [INDUSTRY]
  Target audience: [AUDIENCE]
  Current stage: [STAGE]
</context>

<task>
  [SPECIFIC TASK DESCRIPTION]
</task>

<constraints>
  - Constraint 1
  - Constraint 2
  - Maximum: [X words/items]
</constraints>

<output_format>
  For each item provide:
  1. [FIELD 1]
  2. [FIELD 2]
  3. [FIELD 3]
</output_format>
```

**Why XML works:** Tags prevent instructions from bleeding into each other. You can reference specific sections. Nested tags enable hierarchy.

---

### JSON Prompting

Force structured, machine-readable outputs — essential for automation pipelines:

```json
{
  "instruction": "Generate [X items] about [TOPIC]",
  "rules": "Return ONLY valid JSON. No markdown. No explanation.",
  "schema": {
    "items": [
      {
        "title": "string",
        "description": "string",
        "category": "string",
        "priority": "high | medium | low",
        "tags": ["string"]
      }
    ]
  }
}
```

**When to use JSON prompting:**
- API integrations and automation
- Database seeding
- Feeding output into code
- Building structured datasets

---

### Chain-of-Thought Prompting

Force step-by-step reasoning before conclusions:

> Analyze [TOPIC/DECISION]. Think step by step:
>
> 1. First, identify the core problem
> 2. Then, list 3 possible approaches with pros and cons
> 3. Next, evaluate each against [CRITERIA]
> 4. Then, identify the top risks
> 5. Finally, give a recommendation with confidence level (high/medium/low)

---

### Few-Shot Prompting

Teach the AI through examples of desired output:

> Write [CONTENT TYPE] in this style:
>
> **GOOD EXAMPLES:**
> - "90% of students make this mistake when applying for tech jobs 👇"
> - "Stop grinding LeetCode. Here's what actually gets you hired."
>
> **BAD EXAMPLES (avoid this):**
> - "In this post, I will discuss job preparation strategies"
> - "Furthermore, it is advisable to practice coding regularly"
>
> Now write [X items] about [TOPIC]. Match the GOOD style. Avoid the BAD style.

---

## Level 3 — Advanced: System Design

### The RSSRO Framework

The gold standard for production-grade prompts:

| Letter | Component | Description |
|--------|-----------|-------------|
| **R** | Role | Who is the AI? (expertise, experience, personality) |
| **S** | Skills | What specific skills to apply? (list 5–7) |
| **S** | Sub-Tasks | What specific deliverables are needed? |
| **R** | Rules | Non-negotiable constraints (max 10, numbered) |
| **O** | Output | Exact format the response should follow |

---

### Multi-Agent Prompting

Process tasks through multiple expert perspectives:

> Analyze [TOPIC] through these expert lenses:
>
> **AGENT 1 — The Researcher:**
> Analyze the market opportunity and data.
>
> **AGENT 2 — The Builder:**
> Assess technical feasibility and requirements.
>
> **AGENT 3 — The Critic:**
> Challenge every positive assumption. Find the 3 biggest failure risks.
>
> Each agent builds on the previous one's output.
> Agent 3 must challenge at least 2 points from each earlier agent.
> Final output: synthesized recommendation.

---

### Constraint Engineering

Layer constraints from soft to hard:

| Level | Keyword | Meaning | Example |
|-------|---------|---------|---------|
| Soft | **PREFER** | Nice to have | "Prefer short sentences" |
| Medium | **SHOULD** | Follow unless good reason not to | "Should include examples" |
| Hard | **MUST** | Always follow | "Must be under 500 words" |
| Absolute | **NEVER** | Zero exceptions | "Never use jargon" |

---

### Iterative Refinement Pattern

> Step 1: Generate [X] options for [TASK]
>
> Step 2: Rate each on [CRITERIA 1] (1–10) and [CRITERIA 2] (1–10)
>
> Step 3: Take the top 2 and create 3 variations of each
>
> Step 4: Select the single best and explain why it wins
>
> Step 5: If score is below 8/10, repeat from Step 2

---

### Context Window Management

Place critical instructions where the AI pays most attention:

| Position | Priority | What to Put Here |
|----------|----------|-----------------|
| 🔴 **Start** | Highest (primacy effect) | Role, critical rules, key constraints |
| 🟡 **Middle** | Lower | Detailed context, examples, background |
| 🔴 **End** | High (recency effect) | Output format, final reminders |

---

## Level 4 — Expert: Claude-Specific Mastery

### Claude System Prompts

```xml
<role>
  You are a [ROLE] for [CONTEXT].
</role>

<skills>
  - Skill 1
  - Skill 2
  - Skill 3
</skills>

<rules priority="non-negotiable">
  1. Rule 1
  2. Rule 2
  3. Rule 3
</rules>

<communication>
  - Response style preferences
  - Format requirements
  - Language and tone rules
</communication>
```

---

### CLAUDE.md for Claude Code Projects

```markdown
# CLAUDE.md

## Project Overview
[What this project does, in 2 sentences]

## Tech Stack
- Frontend: [framework, language, styling]
- Backend: [framework, database]
- Deployment: [platform]

## Code Standards
- [Language] strict mode — no any types
- [Naming conventions]
- [Error handling approach]
- [Testing requirements]

## Architecture
- /app — Routes and layouts
- /components — Reusable UI components
- /lib — Utility functions
- /types — Type definitions
```

---

### Claude API — Structured Outputs

```javascript
const response = await anthropic.messages.create({
  model: "claude-sonnet-4-20250514",
  max_tokens: 1024,
  system: `Return ONLY valid JSON.
           No markdown. No preamble. No explanation.`,
  messages: [{
    role: "user",
    content: `[YOUR TASK HERE]
    
    Return as this exact JSON schema:
    {
      "items": [
        {
          "title": "string",
          "description": "string"
        }
      ]
    }`
  }]
});

const data = JSON.parse(response.content[0].text);
```

---

# Part 2 — 100+ Prompt Templates

## 25 Categories × 2–5 Templates Each

> **How to read:** Each template has an ID (e.g., T1.1), a name, and the full prompt.
> Replace all `[PLACEHOLDERS]` with your specifics before using.

---

## 1. Instagram Content Strategy

### T1.1 — 90-Day Content Calendar

> Act as a senior content strategist.
> Create a 90-day Instagram content strategy
> for a creator in [NICHE] targeting [AUDIENCE].
>
> Include:
> - Weekly themes with rationale
> - Content format mix: Reels (40%), Carousels (30%), Stories (20%), Posts (10%)
> - Authority-building ideas to position as expert
> - Engagement-driving content for comments, saves, and shares
> - Lead generation content for [PRODUCT/SERVICE]
> - Hashtag strategy per content type
> - Best posting times for [TIMEZONE/REGION]
>
> Output as a week-by-week table:
> Week # | Theme | Content Type | Topic | CTA

---

### T1.2 — 30 Content Ideas Generator

> Generate 30 high-performing content ideas
> for a creator in [NICHE] targeting [AUDIENCE].
>
> For each idea include:
> 1. Content type (Reel / Carousel / Post / Story)
> 2. Hook — the first line that stops the scroll
> 3. Core value — what the viewer learns or feels
> 4. Why this idea would attract attention
> 5. Expected engagement type (saves / shares / comments)
>
> Mix: 40% educational, 25% entertaining,
> 20% inspirational, 15% promotional.

---

### T1.3 — Competitor Content Audit

> Act as a social media analyst.
> Analyze these competitor accounts in [NICHE]:
> [COMPETITOR 1], [COMPETITOR 2], [COMPETITOR 3].
>
> For each competitor assess:
> - Content themes and pillars
> - Posting frequency and timing
> - Highest-performing content formats
> - Hook patterns they use repeatedly
> - Engagement tactics (polls, questions, CTAs)
> - Gaps in their content strategy
>
> Then deliver:
> 1. Five content opportunities they are ALL missing
> 2. Three formats I should replicate immediately
> 3. Three mistakes I should avoid
> 4. My unique positioning angle against all of them

---

### T1.4 — Audience Persona Builder

> Create a detailed audience persona
> for [TARGET AUDIENCE] in [NICHE].
>
> Include:
> - Demographics: age, location, income, education
> - Psychographics: values, aspirations, fears, frustrations
> - Online behavior: platforms, content consumed, active hours
> - Pain points: top 5 problems they want solved
> - Purchase behavior: what they buy, price sensitivity, triggers
> - Language patterns: how they talk about their problems
> - Content preferences: what makes them save, share, or comment
> - Objections: why they hesitate to buy [PRODUCT/SERVICE]

---

## 2. Instagram Reels & Hooks

### T2.1 — 20 Scroll-Stopping Hooks

> Generate 20 scroll-stopping hooks
> for Instagram Reels about [TOPIC]
> targeting [AUDIENCE].
>
> Each hook must:
> - Be under 10 words
> - Create an information gap (viewer NEEDS to keep watching)
> - Sound conversational, not like an advertisement
> - Work as both text-on-screen AND spoken intro
> - Trigger one of: curiosity, shock, FOMO, aspiration, or controversy
>
> Format each as:
> Hook | Emotional Trigger | Why It Works

---

### T2.2 — 60-Second Reel Script

> Write a 60-second Instagram Reel script
> about [TOPIC] for [AUDIENCE].
>
> Structure:
> - **0–3 seconds:** Pattern interrupt hook
>   (shocking stat or bold claim)
> - **3–10 seconds:** Context — why this matters to the viewer
> - **10–40 seconds:** Three key points delivered with energy
>   (not lecture-style)
> - **40–55 seconds:** "The one thing to remember" summary
> - **55–60 seconds:** Specific CTA
>   (not generic "follow for more")
>
> Also include:
> - [TEXT ON SCREEN] suggestions for each section
> - [VISUAL/B-ROLL] direction
> - [MUSIC MOOD] recommendation
>
> Total word count: 140–170 words (natural speaking pace).

---

### T2.3 — 7-Slide Story Sequence

> Design a 7-slide Instagram Story sequence
> about [TOPIC] that drives engagement
> and leads viewers to [ACTION].
>
> - **Slide 1:** Hook question with poll sticker
> - **Slide 2:** Surprising fact or stat about [TOPIC]
> - **Slide 3:** "Here's what most people get wrong..."
> - **Slide 4:** The correct approach (value delivery)
> - **Slide 5:** Quick actionable tip or hack
> - **Slide 6:** Social proof or result
> - **Slide 7:** CTA with link, swipe-up, or DM prompt
>
> For each slide provide:
> - Exact text (max 20 words)
> - Sticker or interactive element to include

---

### T2.4 — 10 Viral Angles from One Topic

> Turn the topic [TOPIC] into 10 different
> Instagram Reel concepts, each using
> a different viral mechanic:
>
> 1. **Curiosity gap:** "The thing nobody tells you about [TOPIC]..."
> 2. **Listicle:** "5 [TOPIC] mistakes you're making"
> 3. **Contrarian:** "Stop doing [COMMON ADVICE] — here's why"
> 4. **Tutorial:** "How to [TASK] in 60 seconds"
> 5. **Story:** "I tried [TOPIC] for 30 days — here's what happened"
> 6. **Comparison:** "[OPTION A] vs [OPTION B] — which actually works?"
> 7. **Myth-buster:** "This [TOPIC] 'rule' is completely wrong"
> 8. **Challenge:** "Try this [TOPIC] hack and tell me your results"
> 9. **Behind-the-scenes:** "How I actually do [TOPIC]"
> 10. **Hot take:** "Unpopular opinion about [TOPIC]"
>
> For each: title, hook (first 3 seconds), expected engagement type.

---

## 3. Instagram Sales & DMs

### T3.1 — Non-Salesy Sales Caption

> Write an Instagram caption that sells [PRODUCT]
> without sounding salesy.
>
> Structure:
> - **Line 1:** One-line hook that stops the scroll
> - **Lines 2–4:** Short personal story about
>   why this product exists
> - **Lines 5–7:** Three specific things
>   the buyer will be able to do after purchasing
> - **Line 8:** One line of social proof
>   (testimonial, number of users, or a specific result)
> - **Line 9:** Soft CTA to comment [KEYWORD]
>   or tap the link in bio
>
> Tone: genuine, warm, encouraging.
> No buzzwords. No hype.
> Under 300 words.
> Include 20–25 hashtags at the end.

---

### T3.2 — 3-Message DM Sequence

> Write a 3-message Instagram DM sequence
> for someone who commented [KEYWORD]
> on my post about [TOPIC].
>
> I sell [PRODUCT] that helps [AUDIENCE] achieve [RESULT].
>
> **Message 1 (immediate):**
> Deliver the freebie or training link warmly.
> Make them feel seen.
> Ask one engaging question about their situation.
>
> **Message 2 (24 hours later):**
> Share a short transformation story
> of someone who used [PRODUCT] and got [SPECIFIC RESULT].
>
> **Message 3 (48 hours later):**
> Invite them to purchase with a soft urgency line.
> Include an easy opt-out option.
>
> Tone: warm, genuine, like a friend who wants to help.
> No pressure. No pushy sales language.

---

### T3.3 — 9-Slide Sales Carousel

> Create a 9-slide Instagram carousel
> that sells [PRODUCT] without feeling like an ad.
>
> - **Slide 1:** Viral hook using a trending topic
>   or bold statement
> - **Slides 2–6:** Pure value — teach one thing
>   that [PRODUCT] solves
> - **Slide 7:** A common myth about [TOPIC]
>   that [PRODUCT] disproves
> - **Slide 8:** Social proof or transformation story
> - **Slide 9:** Soft CTA to comment [KEYWORD]
>   for a free resource
>
> For each slide provide:
> - Exact text (max 30 words)
> - Visual direction and layout notes
>
> Tone: warm, real, conversational.
> No corporate language.

---

### T3.4 — Instagram Bio Optimizer

> Write 5 Instagram bio options
> that sell [PRODUCT] without being pushy.
>
> Context:
> - Product: [PRODUCT NAME]
> - It helps: [AUDIENCE]
> - To achieve: [TRANSFORMATION/RESULT]
> - Creator name: [YOUR NAME]
>
> Each bio must include:
> - Who I help (the audience)
> - What result they get (the transformation)
> - A clear CTA to click the link in bio
>
> Rules:
> - Under 150 characters per bio
> - Human, warm, and authentic tone
> - Not corporate. Not salesy.

---

## 4. YouTube Strategy & Growth

### T4.1 — Niche Velocity Finder

> Act as a YouTube growth strategist.
> Generate a list of high-velocity YouTube niches
> suitable for [CHANNEL TYPE] channels
> that are currently under-served.
>
> Focus on niches where view demand
> is accelerating faster than creator supply.
> Avoid saturated topics.
>
> For each niche provide:
> - Why it's taking off right now
> - What content format works best
>   (tutorials, clips, narration, reviews, AI visuals)
> - What signal indicates low competition but rising interest
> - Estimated monetization potential
>   (AdSense, sponsors, digital products)
> - How repeatable the content format is
>   (can you batch-produce it?)
>
> Prioritize niches with strong binge potential
> and evergreen value.

---

### T4.2 — 30 Viral Video Ideas

> Generate 30 viral-designed video ideas
> for a YouTube channel in [NICHE]
> targeting [AUDIENCE].
>
> Each idea should use proven viral mechanics:
> curiosity gaps, polarity, authority,
> trend-surfing, or pattern interruption.
>
> For every idea include:
> 1. Compelling title (under 60 characters)
> 2. Core hook in one sentence
>    (the first thing said in the video)
> 3. Primary emotional trigger driving clicks
> 4. Video format
>    (tutorial / listicle / story / reaction / comparison / review)
> 5. Estimated ideal length
> 6. Thumbnail concept in one line
>
> Rules:
> - No generic ideas — each must feel native to [NICHE]
> - At least 5 should be YouTube Shorts concepts
> - Include 3 "controversial take" ideas that drive comments
> - Mix: 70% evergreen content, 30% trend-riding

---

### T4.3 — Channel Audit

> Act as a YouTube growth expert.
> Perform a deep audit of a YouTube channel
> in [NICHE] with [X] subscribers.
>
> Analyze:
> 1. **Branding:** channel name, banner, profile photo,
>    about section clarity
> 2. **Content:** niche clarity, content pillars,
>    format mix, upload consistency
> 3. **Videos:** titles, thumbnails, hooks (first 30 seconds),
>    retention structure, CTAs
> 4. **SEO:** descriptions, tags, playlists, keyword targeting
> 5. **Growth:** what's driving subscribers,
>    what's causing audience drop-off
>
> Deliver:
> - **5 IMMEDIATE FIXES** (do this week)
> - **3 EXPERIMENTS** (test this month)
> - **STRATEGIC MOVES** (plan for next quarter)
> - **30-DAY CONTENT CALENDAR** (optimized based on findings)

---

### T4.4 — Competitor Deep Dive

> Act as a YouTube competitive intelligence analyst.
> Analyze the top 5 competitors in [NICHE].
>
> For each competitor identify:
> - Content strategy and positioning
> - Upload frequency and consistency
> - Top-performing video formats
> - Title and thumbnail patterns
> - Hook styles and retention techniques
> - Audience engagement patterns
> - Monetization approach
>
> Then deliver:
> 1. Patterns working across ALL channels (replicate these)
> 2. Tactics unique to individual creators (learn from these)
> 3. Gaps NO competitor is filling (your opportunity)
> 4. Positioning strategy to differentiate your channel

---

## 5. YouTube Scripting & Production

### T5.1 — Viral 30-Second Hook

> Write a 30-second YouTube hook
> for a video about [TOPIC].
>
> Start with a shocking or counterintuitive statistic
> that most people don't know.
>
> Then ask a question that makes the viewer feel
> they're about to learn something
> that will change how they see [TOPIC].
>
> Rules:
> - Under 80 words total
> - Tone: conversational, slightly alarming, no fluff
> - Must work for both face-on-camera and voiceover

---

### T5.2 — 10 High-CTR Title Variations

> Generate 10 YouTube title variations
> for a video about [TOPIC]:
>
> - 2 **curiosity-gap** titles
>   ("The [TOPIC] secret nobody talks about")
> - 2 **number-list** titles
>   ("7 [TOPIC] mistakes killing your [RESULT]")
> - 2 **how-to** titles
>   ("How to [GOAL] in [TIMEFRAME]")
> - 2 **contrarian** titles
>   ("Stop doing [COMMON ADVICE] — here's why")
> - 2 **emotional/story** titles
>   ("I tried [TOPIC] for 30 days...")
>
> Rules:
> - Each title under 60 characters
> - No clickbait — must accurately reflect content
> - Front-load the most important words

---

### T5.3 — Beginner Tutorial Script

> Write a step-by-step YouTube script
> explaining how to [TASK/GOAL]
> for complete beginners who have never done this
> and are slightly skeptical it will work for them.
>
> Structure:
> 1. **Hook (15 sec):** Show the end result
>    and why it matters
> 2. **Overview (10 sec):** 2-sentence preview
>    of all the steps coming
> 3. **Steps:** Walk through each step
>    in plain language with a real example or analogy.
>    At each step, acknowledge the most common mistake
>    people make and how to avoid it.
> 4. **Outro (15 sec):** Short motivating close
>    that makes the viewer feel capable
>
> Total: 900–1100 words.
> Zero jargon — if a technical term is unavoidable,
> explain it immediately in plain language.

---

### T5.4 — Script Retention Analysis

> Act as a YouTube retention and storytelling strategist.
> Analyze the scripts or transcripts
> of successful videos in [NICHE]
> with over 500,000 views.
>
> Break down:
> - Opening hook technique
> - Curiosity gap placement
> - Pacing and information density
> - Pattern interrupts (where and what type)
> - Re-hook points (where viewers might leave)
> - Escalation structure
> - Ending strategy (CTA vs cliffhanger vs emotional close)
>
> Extract and deliver:
> 1. A repeatable script template with section-by-section timing
> 2. Five retention techniques that appear across multiple viral videos
> 3. Placeholder lines for each section
> 4. Do's and don'ts for scripting in this niche

---

### T5.5 — Thumbnail Design Rules

> Act as a YouTube thumbnail optimization expert.
> Analyze the top-performing thumbnails in [NICHE].
>
> Break down what drives high click-through rates:
> - Composition and focal hierarchy
> - Face vs no-face elements
> - Text usage: how many words, font style, placement
> - Color contrast and emotional signaling
> - Visual simplicity at small sizes
>
> Deliver:
> 1. Five reusable thumbnail layout templates
> 2. A do/don't checklist for this niche
> 3. Color palette recommendations for maximum CTR
> 4. Step-by-step thumbnail design process

---

## 6. LinkedIn & Professional Branding

### T6.1 — Thought Leadership Post

> Write a LinkedIn post about [TOPIC]
> that positions me as a thought leader.
>
> Structure:
> - **Hook** (first 2 lines, visible before "see more"):
>   Create a curiosity gap or bold statement
> - **Body:** Personal insight, contrarian take,
>   or lesson learned (3–4 short paragraphs)
> - **Takeaway:** One thing the reader can implement today
> - **Question:** Engagement-driving question at the end
>
> Rules:
> - Maximum 1300 characters
> - No hashtags in the body text
> - 3–5 hashtags at the very end
> - Tone: professional but authentic,
>   confident but not arrogant

---

### T6.2 — Cold Outreach DM Sequence (4-Touch)

> Write a 4-message LinkedIn DM sequence
> targeting [ROLE] at [COMPANY TYPE]
> who might need [SERVICE].
>
> **Message 1 (Day 0):**
> Personalized connection request.
> Reference something specific from their profile.
> No selling. Max 300 characters.
>
> **Message 2 (Day 3):**
> After connection accepted.
> Share a relevant insight or free resource.
> Zero pitch.
>
> **Message 3 (Day 7):**
> Share a case study or social proof
> relevant to their industry.
> Subtle positioning only.
>
> **Message 4 (Day 14):**
> Soft ask: "Would a 15-min call be worth it?"
> OR graceful exit: "No worries if not relevant right now."
>
> Tone: professional, helpful, human. Never pushy.

---

### T6.3 — Company Content Calendar (4 Weeks)

> Create a 4-week LinkedIn company page content plan
> for [COMPANY] in [INDUSTRY].
>
> - **Week 1:** Thought leadership and industry insights
> - **Week 2:** Behind-the-scenes and team culture
> - **Week 3:** Customer success story and social proof
> - **Week 4:** Educational content and tool recommendations
>
> For each week: 3 posts with exact copy,
> image/visual suggestions, posting time,
> and engagement strategy.

---

### T6.4 — Profile Optimization

> Write 3 LinkedIn headline variations
> and 1 About section for a [ROLE]
> who [WHAT YOU DO] for [AUDIENCE].
>
> **Headlines:** Under 120 characters each.
> Include keywords: [KEYWORD 1], [KEYWORD 2].
> Variations: value-driven, authority-driven, curiosity-driven.
>
> **About section** (300 words max):
> - Opening hook about what you're passionate about
> - Who you help and what results you deliver
> - Your unique approach or methodology
> - 1–2 key achievements as social proof
> - CTA: how to get in touch or work together

---

## 7. Content Repurposing

### T7.1 — One-to-Many Repurposing Engine

> Take this [CONTENT TYPE] about [TOPIC]
> and repurpose it into:
>
> 1. Three Instagram carousel topics
>    (with slide-by-slide breakdown)
> 2. Five tweet-sized insights
>    (each under 280 characters)
> 3. One LinkedIn thought leadership post
> 4. Three Instagram Reel hooks
> 5. One email newsletter section
> 6. One YouTube Shorts script
>
> Rules:
> - Each piece must feel NATIVE to the platform
>   (not copy-pasted)
> - Each must have a UNIQUE hook
>   (never repeat the same angle)
> - Adapt tone: casual for Instagram,
>   professional for LinkedIn,
>   punchy for Twitter,
>   educational for YouTube

---

### T7.2 — Content Batching System

> Design a content batching system
> for a creator in [NICHE]
> that produces one month of content in a single day.
>
> Include:
> 1. **Pre-production (2 hours):**
>    Topic selection, scripting, asset preparation
> 2. **Production (4 hours):**
>    Filming and recording schedule with time blocks
> 3. **Post-production (2 hours):**
>    Editing, caption writing, scheduling
>
> Output targets:
> - [X] Reels
> - [X] Carousels
> - [X] Stories
> - [X] Posts
>
> For each phase: exact steps, time allocations,
> tools needed, and templates to use.
> Assume one person with a smartphone.

---

## 8. Email Marketing & Outreach

### T8.1 — Cold Email Sequence (5-Touch)

> Write a 5-email cold outreach sequence
> for [SERVICE] targeting [AUDIENCE].
>
> **Email 1 (Day 0):**
> Personalized intro — reference a specific pain point.
> One-line value proposition. Under 80 words.
>
> **Email 2 (Day 3):**
> Value-add — share a relevant insight, tip, or resource.
> No pitch at all. Under 60 words.
>
> **Email 3 (Day 7):**
> Case study — "Here's how we helped [similar company]
> achieve [specific result]." Under 100 words.
>
> **Email 4 (Day 12):**
> Direct ask — "Worth a 15-minute call this week?"
> Under 50 words.
>
> **Email 5 (Day 18):**
> Break-up — "Seems like the timing isn't right.
> Here's a free [resource] anyway."
> Under 60 words.
>
> Include subject lines for each
> (under 6 words, no spam trigger words).

---

### T8.2 — Newsletter Template

> Write a weekly newsletter edition
> about [TOPIC] for [AUDIENCE].
>
> - **Subject line:** 3 options, each under 50 characters
> - **Preview text:** Under 90 characters
> - **Opening:** Personal and relatable hook (2–3 sentences)
> - **Section 1:** Key insight of the week (100 words)
> - **Section 2:** Practical tip or tool recommendation (100 words)
> - **Section 3:** Curated resource or link (50 words)
> - **Takeaway:** One actionable thing to do this week
> - **CTA:** [SPECIFIC ACTION]
> - **P.S. line:** Bonus tip or teaser for next week
>
> Total: 500–700 words.
> Tone: knowledgeable friend, not corporate newsletter.

---

### T8.3 — Welcome Email Sequence (5 Emails)

> Write a 5-email welcome sequence
> for new subscribers to [BRAND]'s list about [NICHE].
>
> - **Email 1 (Day 0):** Welcome, deliver the lead magnet,
>   set expectations for what's coming
> - **Email 2 (Day 1):** Your story —
>   why you do this, relatable origin
> - **Email 3 (Day 3):** Best content —
>   your most popular or valuable piece
> - **Email 4 (Day 5):** Social proof —
>   testimonials, results, or a case study
> - **Email 5 (Day 7):** Soft pitch —
>   introduce [PRODUCT/SERVICE] with a value-first frame
>
> Each email: subject line, preview text,
> body (under 200 words), and CTA.

---

## 9. Copywriting & Persuasion

### T9.1 — Landing Page Copy

> Write complete landing page copy for [PRODUCT/SERVICE]:
>
> 1. **HERO:** Headline (10 words max),
>    sub-headline (20 words), primary CTA button text
> 2. **PROBLEM:** 3 pain points your audience faces
>    (emotional and specific)
> 3. **SOLUTION:** How [PRODUCT] solves each pain point
> 4. **FEATURES:** 3 key features
>    with benefit-focused descriptions
> 5. **SOCIAL PROOF:** Testimonial format,
>    stats format, partner logos section
> 6. **HOW IT WORKS:** 3-step process
>    (simple, visual-friendly)
> 7. **PRICING:** Present [PRICE POINT]
>    with value anchoring
> 8. **FAQ:** 5 most common objections reframed as questions
> 9. **FINAL CTA:** Urgency-driven
>    with risk reversal (guarantee)
>
> Tone: confident, clear, conversational. No jargon.

---

### T9.2 — Objection Handling Scripts (10)

> List 10 objections people have
> before buying [PRODUCT/SERVICE]
> and write a persuasive response for each.
>
> Format for each:
> - **Objection:** "[What the prospect says]"
> - **Response:** "[How to address it —
>   empathize, reframe, provide proof]"
> - **Follow-up:** "[How to transition to the next step]"
>
> Include objections about:
> price, timing, trust, competition,
> "I can do it myself," and "I need to think about it."

---

### T9.3 — Value Proposition Canvas

> Create a value proposition canvas for [PRODUCT/SERVICE]:
>
> **CUSTOMER SIDE:**
> - Jobs to be done (what they're trying to accomplish)
> - Pains (frustrations, risks, obstacles)
> - Gains (desired outcomes, benefits, aspirations)
>
> **PRODUCT SIDE:**
> - Products and services (what you offer)
> - Pain relievers (how you address each pain)
> - Gain creators (how you deliver each gain)
>
> Then write:
> 1. One-line value proposition
> 2. Elevator pitch (30 seconds / 75 words)
> 3. Long-form value proposition (100 words)

---

### T9.4 — Brand Voice Guide

> Define a complete brand voice guide for [BRAND]:
>
> 1. **Personality:** 5 adjectives describing the brand
> 2. **Tone spectrum:** Where it sits between formal and casual
> 3. **Vocabulary:** Words we USE vs words we AVOID
> 4. **Sentence style:** Short or long, simple or complex
> 5. **Humor level:** None, subtle, or frequent
> 6. **Examples:** 3 on-brand sentences vs 3 off-brand sentences
> 7. **Platform adjustments:**
>    How voice changes on Instagram vs LinkedIn vs Email

---

## 10. SEO & Keyword Strategy

### T10.1 — Keyword Cluster Map

> Generate a keyword cluster map for [TOPIC/BUSINESS]:
>
> 1. **Seed keywords:** 5 primary keywords
>    (high volume, high intent)
> 2. **Long-tail variations:** 10 per seed keyword
> 3. **Group by intent:**
>    informational, commercial, transactional
> 4. **Content type per cluster:**
>    blog post, landing page, FAQ, tool page
> 5. **Priority ranking:**
>    which to target first based on difficulty + opportunity
>
> Format as a table:
> Keyword | Search Intent | Content Type | Priority | Difficulty

---

### T10.2 — Blog Post SEO Framework

> Write an SEO-optimized blog post outline
> for the target keyword "[KEYWORD]":
>
> 1. **Title tag** (under 60 characters, keyword front-loaded)
> 2. **Meta description** (under 155 characters, keyword + CTA)
> 3. **H1** (matches primary search intent)
> 4. **H2 structure** (6–8 sections,
>    each targeting a related sub-keyword)
> 5. **Key points per H2** (3–5 bullets each)
> 6. **Internal linking suggestions**
> 7. **FAQ section** (5 questions from "People Also Ask")
> 8. **Featured snippet target**
>    (paragraph, list, or table format)
> 9. **Recommended word count**
>    (based on top-ranking competitor analysis)

---

## 11. Startup & Business Strategy

### T11.1 — Business Idea Validation

> Validate this business idea: [DESCRIBE IDEA]
>
> Analyze through these lenses:
> 1. **Market Size:** TAM, SAM, SOM (in [CURRENCY])
> 2. **Competition:** Who else does this?
>    What's the defensible edge?
> 3. **Unit Economics:** Customer acquisition cost,
>    lifetime value, margins
> 4. **Scalability:** Can this grow 10x
>    without 10x cost increase?
> 5. **Revenue Model:** How does money flow?
>    Recurring vs one-time?
> 6. **Go-to-Market:** First 100 customers —
>    where do you find them and how?
> 7. **Red Flags:** Top 3 reasons this could fail
> 8. **Verdict:** GO / PIVOT / KILL
>    with reasoning and confidence level

---

### T11.2 — Scaling Roadmap

> Give me a plan to scale [DESCRIBE BUSINESS]
> to [REVENUE TARGET]:
>
> - What to automate first (biggest time-wasters)
> - What to delegate (tasks below founder-level value)
> - What systems to build (SOPs, workflows, dashboards)
> - Hiring roadmap (roles, timing, estimated cost)
> - Bottlenecks that will appear at each growth stage
> - Key metrics to track at each revenue milestone
>
> Output as a phased execution roadmap with timelines.

---

### T11.3 — Pitch Deck Narration (12 Slides)

> Write the narration script
> for a 12-slide investor pitch deck:
>
> 1. **Problem** — the pain, who feels it, how big it is
> 2. **Solution** — what you built, one-sentence magic
> 3. **Demo** — key features, UX highlights
> 4. **Market** — TAM / SAM / SOM with sources
> 5. **Business Model** — how money flows
> 6. **Traction** — what you've achieved, growth metrics
> 7. **Competition** — 2x2 matrix, why you win
> 8. **Team** — why THIS team is right for this problem
> 9. **Go-to-Market** — growth strategy, channels, timeline
> 10. **Financials** — projections, unit economics
> 11. **The Ask** — amount needed, use of funds, timeline
> 12. **Vision** — where this goes in 5 years
>
> Company: [NAME] | Industry: [INDUSTRY] | Stage: [STAGE]

---

### T11.4 — Pricing Strategy Design

> Design a pricing strategy for [PRODUCT/SERVICE]:
>
> 1. **Competitor pricing:** What does the market charge?
> 2. **Cost-plus analysis:** What does it cost you to deliver?
> 3. **Value-based analysis:** What is the outcome worth
>    to the customer?
> 4. **Recommended pricing:** 3 tiers (Good / Better / Best)
> 5. **For each tier:** Name, price, what's included,
>    ideal customer profile
> 6. **Psychology tactics:** Anchoring, decoy, charm pricing
> 7. **Discounting rules:** When and how much to discount
> 8. **Price anchoring approach:** How to frame the investment

---

## 12. Sales & Lead Generation

### T12.1 — Lead Scoring Model

> Design a lead scoring system
> for [BUSINESS] selling [SERVICE]:
>
> **Demographic scoring (who they are):**
> - Industry match: +[X] points
> - Company size match: +[X] points
> - Role/title match: +[X] points
> - Location match: +[X] points
>
> **Behavioral scoring (what they do):**
> - Visited pricing page: +[X] points
> - Downloaded resource: +[X] points
> - Replied to outreach: +[X] points
> - Attended webinar: +[X] points
>
> **Thresholds:**
> - Cold (0–30): Nurture with content
> - Warm (31–60): Personalized outreach
> - Hot (61–90): Direct sales conversation
> - Ready (90+): Send proposal
>
> Include: qualification questions
> and disqualification criteria.

---

### T12.2 — Consultative Sales Call Script

> Write a consultative sales call script
> for selling [SERVICE] to [AUDIENCE]:
>
> 1. **Opening (30 sec):** Build rapport, set agenda
> 2. **Discovery (5 min):** Ask 5 questions
>    to understand their specific pain
> 3. **Diagnosis (3 min):** Summarize their situation
>    back to them accurately
> 4. **Solution (5 min):** Present how [SERVICE]
>    solves their specific pain (not generic features)
> 5. **Proof (2 min):** Relevant case study or testimonial
> 6. **Pricing (2 min):** Present with value anchoring
> 7. **Objections:** Top 3 objections with responses
> 8. **Close (1 min):** Clear, specific next step
>
> Tone: consultative, not pushy.
> Focus on their problem, not your features.

---

### T12.3 — 10 Lead Magnet Ideas

> Generate 10 lead magnet ideas for [NICHE] that:
> - Solve a specific, immediate problem
> - Can be created in under 4 hours
> - Naturally lead to selling [SERVICE]
> - Work as both downloadable PDF and email mini-course
>
> For each provide:
> - Name (compelling, benefit-driven)
> - Format (checklist / template / guide / toolkit / quiz)
> - Estimated creation time
> - Conversion hook (how it leads to the paid offering)

---

### T12.4 — Client Proposal Template

> Write a client proposal for [SERVICE]:
>
> 1. **Executive Summary** —
>    Problem understood, solution proposed (3 sentences)
> 2. **Scope of Work** —
>    What's included and what's NOT included
> 3. **Timeline** —
>    Milestones with dates
> 4. **Deliverables** —
>    Specific outputs the client receives
> 5. **Pricing** —
>    3 tiers with clear differentiation
> 6. **Terms** —
>    Payment schedule, revision policy, ownership
> 7. **Team Introduction** —
>    Who will work on this and their relevant experience
> 8. **Next Steps** —
>    Clear action to move forward
>
> Tone: professional but approachable, not intimidating.

---

## 13. Market Research & Analysis

### T13.1 — Market Sizing

> Estimate the market size
> for [PRODUCT/SERVICE] in [MARKET/REGION]:
>
> Using both top-down and bottom-up approaches:
> - **TAM** (Total Addressable Market)
> - **SAM** (Serviceable Available Market)
> - **SOM** (Serviceable Obtainable Market)
>
> Include:
> - Data sources and assumptions used
> - Growth rate and trajectory
> - Key market drivers and tailwinds
> - Potential risks and headwinds
> - Comparison with adjacent markets
>
> All figures in [CURRENCY].

---

### T13.2 — Industry Trend Report

> Create an industry trend analysis
> for [INDUSTRY] in [YEAR]:
>
> 1. Top 5 trends shaping the industry
> 2. For each trend: what's driving it,
>    who benefits, expected timeline
> 3. Technologies to watch closely
> 4. Regulatory changes on the horizon
> 5. Consumer or buyer behavior shifts
> 6. Opportunities for new entrants
> 7. Threats to existing players
> 8. Three predictions for the next 12 months
>
> Format as an executive briefing (under 1500 words).

---

## 14. Branding & Positioning

### T14.1 — Brand Positioning Statement

> Write a brand positioning statement for [BRAND]
> using this framework:
>
> "For [TARGET AUDIENCE] who [NEED/WANT],
> [BRAND] is the [CATEGORY]
> that [KEY BENEFIT]
> because [REASON TO BELIEVE]."
>
> Then create:
> 1. Three variations (functional, emotional, aspirational)
> 2. A one-liner (under 10 words)
> 3. An elevator pitch (30 seconds / 75 words)
> 4. A social media bio version (under 150 characters)
> 5. A tagline (under 6 words)

---

### T14.2 — Brand Identity System

> Design a complete brand identity brief
> for [BRAND] in [INDUSTRY]:
>
> 1. **Mission statement** (one sentence)
> 2. **Vision statement** (one sentence)
> 3. **Core values** (5 values with 1-sentence explanations)
> 4. **Brand personality**
>    (5 adjectives with behavioral descriptions)
> 5. **Brand voice:**
>    Tone, vocabulary, and style guidelines
> 6. **Visual identity direction:**
>    Color emotions, typography feel, imagery style
> 7. **Brand story:**
>    Origin, purpose, the change you're making
> 8. **Brand promise:**
>    What you guarantee to every customer

---

## 15. Digital Products & Courses

### T15.1 — Digital Product Idea Generator

> I want to create a digital product in [NICHE].
> My skills and experience are [SKILLS].
> My target audience is [AUDIENCE]
> and their biggest problem is [PROBLEM].
>
> Give me the top 5 most profitable
> digital product ideas, ranked by
> ease of creation and income potential.
>
> For each product provide:
> 1. Product name (compelling, benefit-driven)
> 2. Format (ebook / template / course / checklist / toolkit)
> 3. What to include (table of contents or feature list)
> 4. Recommended price point and reasoning
> 5. Estimated time to create
> 6. Marketing angle (how to position and sell it)

---

### T15.2 — Course Outline Builder

> Create a complete course outline
> for teaching [TOPIC] to [AUDIENCE]:
>
> 1. **Course name** (compelling, transformation-focused)
> 2. **Subtitle** (clearly explains the outcome)
> 3. **5–7 Modules,** each with:
>    - Module name
>    - Learning objective (what they'll DO after completing it)
>    - 3–5 lessons per module
>    - Hands-on exercise per module
>    - Deliverable or output per module
> 4. **Quick win:** What they accomplish
>    in the first 10 minutes of the course
> 5. **Final project:** Capstone that proves mastery
> 6. **Bonus materials:**
>    Templates, checklists, resource lists
>
> Make it feel premium and worth [PRICE POINT].

---

### T15.3 — Sales Funnel for Digital Products

> Design a complete sales funnel for [DIGITAL PRODUCT]:
>
> **Stage 1 — Awareness:**
> Content strategy to attract [AUDIENCE] organically
>
> **Stage 2 — Interest:**
> Lead magnet that solves a small piece of the problem
>
> **Stage 3 — Consideration:**
> 5-email nurture sequence that builds trust
>
> **Stage 4 — Conversion:**
> Sales page elements, pricing strategy, urgency triggers
>
> **Stage 5 — Retention:**
> Post-purchase experience, community, upsell path
>
> For each stage: specific content to create,
> copy templates, and metrics to track.

---

## 16. Frontend Development (React / Next.js)

### T16.1 — React Component

> Build a React component for [COMPONENT NAME]
> with these requirements:
>
> - TypeScript with proper interfaces and types
> - Tailwind CSS for styling (mobile-first responsive)
> - Props: [LIST EXPECTED PROPS WITH TYPES]
> - States to handle: loading, error, empty, success
> - Accessibility: ARIA labels, keyboard navigation,
>   focus management
> - Performance: memo, useMemo, useCallback where needed
> - Include JSDoc comments for all props
> - Include a test template using Vitest
>   and React Testing Library

---

### T16.2 — Next.js Full Feature

> Build a complete [FEATURE NAME]
> for a Next.js 14 application:
>
> 1. **Database:** Schema using [Supabase/Prisma/Drizzle]
>    with TypeScript types
> 2. **Server:** Server Actions or Route Handlers
>    with Zod input validation
> 3. **UI:** React Server Components
>    + Client Components where interactivity is needed
> 4. **Auth:** Protected routes
>    using [AUTH PROVIDER]
> 5. **Error handling:** Error boundaries
>    + loading states + empty states
> 6. **Types:** Shared TypeScript interfaces
>    for the entire feature
>
> Include: file structure, all imports,
> and complete implementation.

---

### T16.3 — Responsive Layout

> Create a responsive [PAGE TYPE] layout:
>
> - Mobile-first approach using Tailwind CSS
> - Breakpoints: sm (640px), md (768px),
>   lg (1024px), xl (1280px)
> - Components needed: [LIST SECTIONS]
> - Navigation: hamburger on mobile,
>   sidebar on desktop
> - Performance: lazy loading for images,
>   code splitting
> - Accessibility: semantic HTML, skip links,
>   proper contrast ratios
> - Dark mode support using CSS variables

---

### T16.4 — State Management Design

> Design state management for [APPLICATION]
> using [Zustand / Redux Toolkit / React Context]:
>
> - Store structure with all slices
> - Actions and action creators
> - Selectors for derived data
> - Async handling (API calls, loading states)
> - Persistence strategy (localStorage / server sync)
> - TypeScript types for all state shapes
> - Testing approach for stores and selectors

---

## 17. Backend Development (Node.js / Python)

### T17.1 — REST API

> Create a RESTful API for [RESOURCE]
> using [Express / Fastify / FastAPI]:
>
> - Input validation using [Zod / Pydantic]
> - ORM models using [Mongoose / Prisma / SQLAlchemy]
> - CRUD operations: GET (list + single),
>   POST, PUT, PATCH, DELETE
> - Pagination, filtering, sorting, and search
> - JWT authentication middleware
> - Rate limiting middleware
> - Error handling with proper HTTP status codes
> - Request logging
> - API documentation comments (Swagger/OpenAPI)
>
> Include TypeScript types or Python type hints throughout.

---

### T17.2 — Authentication System

> Build a complete authentication system
> for [FRAMEWORK]:
>
> - Registration with email verification
> - Login with JWT (access + refresh tokens)
> - Password hashing with bcrypt or argon2
> - Password reset flow (token-based)
> - Session management
> - Role-based access control (admin, user, editor)
> - Rate limiting on all auth endpoints
> - Security headers (CORS, CSP, HSTS)
> - Input sanitization
> - Audit logging for authentication events

---

### T17.3 — Background Job System

> Design a background job processing system
> for [USE CASE]:
>
> - Job queue using [Bull / Celery / BullMQ]
> - Retry logic with exponential backoff
> - Dead letter queue for failed jobs
> - Monitoring dashboard or logging
> - Scaling strategy (workers, concurrency)
> - Priority levels for different job types
> - Scheduled/recurring jobs (cron-like)
> - Error handling and alerting

---

## 18. Database Design & Management

### T18.1 — Schema Design

> Design a database schema for [APPLICATION TYPE]:
>
> Tables or collections needed: [LIST ENTITIES]
>
> For each entity provide:
> - Fields with data types and constraints
> - Relationships (one-to-one, one-to-many, many-to-many)
> - Indexes for common query patterns
> - Unique constraints
> - Default values
>
> Include:
> - ER diagram description (entities and relationships)
> - SQL or NoSQL creation scripts
> - TypeScript interfaces matching the schema
> - Seed data (5 sample records per table)
> - 5 common queries with examples

---

### T18.2 — Migration Strategy

> Plan a database migration
> from [CURRENT STATE] to [TARGET STATE]:
>
> - Step-by-step migration plan
> - Data transformation logic for each step
> - Rollback strategy for each step
> - Estimated downtime
> - Data validation checks (before and after)
> - Testing approach
> - Backup and recovery plan

---

## 19. AI Agents & Automation

### T19.1 — Multi-Agent System

> Design a multi-agent AI system for [PURPOSE]:
>
> **Architecture:**
> - Orchestrator agent that routes requests
> - Agent 1 — [NAME]: [RESPONSIBILITY]
> - Agent 2 — [NAME]: [RESPONSIBILITY]
> - Agent 3 — [NAME]: [RESPONSIBILITY]
>
> **For each agent provide:**
> - System prompt (complete)
> - Input and output format
> - Tools or APIs it needs access to
> - Error handling approach
> - Memory and context requirements
>
> **Tech stack:** [LANGUAGE], [AI API], [DATABASE], [FRAMEWORK]
>
> Include: project structure,
> implementation order, and testing strategy.

---

### T19.2 — Chatbot / Virtual Assistant

> Build a [PLATFORM] chatbot for [PURPOSE]:
>
> **Capabilities:**
> 1. [CAPABILITY 1 — e.g., answer FAQs from knowledge base]
> 2. [CAPABILITY 2 — e.g., book appointments]
> 3. [CAPABILITY 3 — e.g., qualify leads]
> 4. [CAPABILITY 4 — e.g., escalate to human agent]
>
> **Conversation flows:**
> - New user flow
> - Returning user flow
> - Error and fallback flow
> - Handoff to human flow
>
> **Tech:** [FRAMEWORK], [AI API],
> [DATABASE], [MESSAGING API]
>
> Include: webhook setup, conversation state management,
> rate limiting, and analytics tracking.

---

### T19.3 — Automation Workflow

> Design an automation workflow for [PROCESS]:
>
> - **Trigger:** What starts the automation
> - **Step 1:** [Action] using [Tool]
> - **Step 2:** [Action] using [Tool]
> - **Step 3:** Conditional logic
>   (if X then Y, else Z)
> - **Step 4:** Output, notification, or storage
>
> Also define:
> - Error handling for each step (what if it fails?)
> - Monitoring (how do you know it's working?)
> - Cost estimate (per run and monthly)
> - Scaling considerations (what breaks at 10x volume?)

---

### T19.4 — Voice AI System

> Build a voice AI system for [USE CASE]:
>
> **Components:**
> - Telephony: [Twilio / Vonage] for call handling
> - STT: [Deepgram / Whisper] for speech-to-text
> - AI: [Claude / GPT] for conversation intelligence
> - TTS: [ElevenLabs / PlayHT] for text-to-speech
> - Integration: [Calendar / CRM / Database] for actions
>
> **Conversation design:**
> - Greeting and intent detection
> - Information gathering flow
> - Action execution (booking, FAQ, transfer)
> - Graceful error handling (poor audio, unclear intent)
> - Post-call summary generation
>
> Include: architecture diagram description,
> estimated latency per turn,
> cost per call, and deployment plan.

---

## 20. DevOps & CI/CD

### T20.1 — CI/CD Pipeline

> Write a [GitHub Actions / GitLab CI] pipeline
> for a [PROJECT TYPE] project:
>
> **Triggers:** Push to main branch, pull requests
>
> **Stages:**
> 1. **Lint:** [ESLint / Pylint / Ruff]
> 2. **Type check:** [TypeScript / mypy]
> 3. **Test:** [Vitest / Pytest] with coverage report
> 4. **Build:** [Framework-specific build command]
> 5. **Deploy:** [Vercel / Railway / AWS / Docker registry]
>
> Include:
> - Environment secrets management
> - Dependency caching for faster builds
> - Branch protection rules
> - Notification on failure (Slack / Discord / email)
> - Manual approval gate for production deploys

---

### T20.2 — Docker Configuration

> Create Docker configuration for [APPLICATION]:
>
> **1. Dockerfile:**
> - Multi-stage build (development + production)
> - Minimal base image for production
> - Non-root user for security
> - Health check endpoint
> - Optimized layer caching
>
> **2. docker-compose.yml:**
> - Application service
> - Database service
> - Cache service (Redis, if needed)
> - Volumes for data persistence
> - Network configuration
> - Environment variable management
>
> **3. .dockerignore** (optimized for image size)
>
> Include comments explaining each decision.

---

### T20.3 — Infrastructure Design

> Design infrastructure for [APPLICATION]
> on [CLOUD PROVIDER]:
>
> **Resources needed:**
> - Compute: [type + sizing rationale]
> - Database: [type + configuration]
> - Storage: [type + lifecycle policies]
> - CDN: [configuration]
> - DNS and SSL/TLS: [setup]
> - Monitoring: [metrics + alert thresholds]
>
> Include:
> - Monthly cost estimate (in [CURRENCY])
> - Scaling strategy (horizontal vs vertical)
> - Backup and disaster recovery plan
> - Security configuration (IAM, firewalls, encryption)

---

## 21. API Design & Integration

### T21.1 — API Specification

> Design a RESTful API for [SERVICE]:
>
> - List all endpoints:
>   method, path, description, auth required
> - Request and response schemas for each endpoint
> - Consistent error response format
> - Pagination strategy (cursor vs offset)
> - Rate limiting tiers (free / standard / premium)
> - Versioning strategy (URL path vs header)
> - Authentication flow (OAuth2 / JWT / API key)
> - Webhook design for async events
> - OpenAPI specification outline

---

### T21.2 — Third-Party Integration

> Build an integration with [THIRD-PARTY API]
> for [PURPOSE]:
>
> 1. Authentication setup (API key / OAuth / webhook)
> 2. Key endpoints to use
>    with request and response examples
> 3. Error handling (retries, fallbacks, circuit breaker)
> 4. Rate limit management
> 5. Data transformation layer
>    (their format → your format)
> 6. Webhook handler (if applicable)
> 7. Monitoring and alerting for integration health
> 8. Testing approach (mocks, sandbox environment)
>
> Include: environment variable setup
> and TypeScript types for API responses.

---

## 22. UI/UX & Design Systems

### T22.1 — Design System Specification

> Create a design system specification
> for [BRAND/PROJECT]:
>
> 1. **Colors:** Primary, secondary, accent,
>    success, warning, error, neutrals
>    (hex codes + usage guidelines)
> 2. **Typography:** Font families, sizes (h1–h6, body, caption),
>    weights, line heights
> 3. **Spacing:** Base unit system (4px or 8px),
>    full spacing scale
> 4. **Borders:** Radius tokens, border styles
> 5. **Shadows:** Elevation levels (low, medium, high)
> 6. **Components:** Button variants, input states,
>    card patterns, modal structure
> 7. **Responsive breakpoints** with behavior changes
> 8. **Animation:** Timing functions, duration tokens
> 9. **Accessibility:** Contrast ratios, focus styles,
>    reduced motion preferences
> 10. **Dark mode:** Color mapping strategy

---

### T22.2 — User Flow Design

> Design the user flow for [FEATURE]
> in [APPLICATION]:
>
> 1. **Entry points:** How users discover this feature
> 2. **Step-by-step flow** with decision points
> 3. **For each step:** Screen description,
>    user action, system response
> 4. **Error states:** What happens when things go wrong
> 5. **Edge cases:** Empty state, first-time user, power user
> 6. **Success state:** Confirmation and next steps
> 7. **Accessibility:** Considerations at each step
> 8. **Mobile vs desktop:** Key differences in the flow
>
> Include: estimated completion time
> and drop-off risk points with mitigation strategies.

---

### T22.3 — Wireframe Description

> Describe a detailed wireframe
> for a [PAGE TYPE] page for [PRODUCT]:
>
> **Sections:**
> 1. Hero: headline, sub-headline, CTA, key visual
> 2. Problem: pain points with supporting icons
> 3. Solution: how the product works (3-step process)
> 4. Features: key features with benefit descriptions
> 5. Social proof: testimonials, partner logos, stats
> 6. Pricing: comparison table for tiers
> 7. FAQ: 5–7 common questions with answers
> 8. Final CTA: urgency element + action button
>
> Include mobile layout considerations
> and interaction notes for each section.

---

## 23. Project Management & Planning

### T23.1 — Project Plan Generator

> Create a project plan for building [PROJECT]:
>
> 1. **Scope:** What's included and explicitly NOT included
> 2. **Phases:** Discovery → Design → Development
>    → Testing → Launch
> 3. **For each phase:**
>    - Tasks with descriptions
>    - Dependencies between tasks
>    - Time estimates (optimistic, realistic, pessimistic)
>    - Deliverables
>    - Responsible roles
> 4. **Milestones** and review checkpoints
> 5. **Risk register:** Top 5 risks with mitigation plans
> 6. **Communication plan:**
>    Who gets updates, how often, in what format
> 7. **Resource requirements:** People, tools, budget

---

### T23.2 — Sprint Planning

> Plan a [2-week / 1-week] sprint
> for [PROJECT/TEAM]:
>
> Priorities: [LIST CURRENT PRIORITIES]
> Team capacity: [X] developers, [X] designers,
> [X] available hours each
>
> Produce:
> 1. **Sprint goal** (one clear sentence)
> 2. **User stories** with acceptance criteria (5–8 stories)
> 3. **Task breakdown** for each story
>    (with hour estimates)
> 4. **Dependencies** and potential blockers
> 5. **Definition of Done** checklist
> 6. **Sprint risks** and contingency plans
> 7. **Demo/review plan** for end of sprint

---

### T23.3 — Technical Specification

> Write a technical specification for [FEATURE]:
>
> 1. **Overview:** What it does and why it matters
> 2. **User stories:** As a [user], I want [action],
>    so that [benefit]
> 3. **Technical approach:** Architecture, data flow,
>    components involved
> 4. **API changes:** New or modified endpoints with schemas
> 5. **Database changes:** New tables, migrations needed
> 6. **UI/UX:** Key screens with interaction notes
> 7. **Security considerations**
> 8. **Performance requirements**
> 9. **Testing strategy:** Unit, integration, and E2E
> 10. **Rollout plan:** Feature flags, gradual release, rollback
> 11. **Open questions** and decisions still needed
>
> Include edge cases and non-goals.

---

## 24. Personal Productivity & Systems

### T24.1 — Weekly Workflow System

> Design a weekly workflow system
> for a [ROLE] managing [RESPONSIBILITIES]:
>
> 1. **Time blocks:** Map the ideal week (Monday–Friday)
> 2. **Daily routines:** Morning startup, deep work,
>    admin tasks, wind-down
> 3. **Priority framework:** How to decide
>    what gets done first each day
> 4. **Batching strategy:** Group similar tasks
>    for maximum efficiency
> 5. **Tools and systems:** What to use for each workflow
> 6. **Review cadence:** Daily check-in,
>    weekly review, monthly reflection
> 7. **Energy management:** Map high-energy tasks
>    to high-energy hours
> 8. **Buffer time:** Where to leave space
>    for unexpected work
>
> Include an example Monday–Friday schedule
> with specific time blocks.

---

### T24.2 — 90-Day Goal Execution Roadmap

> Turn this goal into a 90-day execution roadmap:
> [DESCRIBE YOUR GOAL]
>
> **Phase 1 — Foundation (Days 1–30):**
> - 5 key actions with specific deliverables
> - Weekly milestones to track progress
>
> **Phase 2 — Momentum (Days 31–60):**
> - 5 key actions building on Phase 1
> - Weekly milestones
>
> **Phase 3 — Scale (Days 61–90):**
> - 5 key actions for compounding results
> - Weekly milestones
>
> For each action: what exactly to do,
> how to measure success, time investment needed,
> dependencies, and potential obstacles.

---

### T24.3 — Decision Framework

> Help me make this decision:
> [DESCRIBE THE DECISION]
>
> Analyze using these frameworks:
> 1. **First Principles:** What are the fundamental truths?
> 2. **Reversibility:** Is this a one-way or two-way door?
> 3. **10/10/10 Rule:** How will I feel about this
>    in 10 minutes, 10 months, and 10 years?
> 4. **Opportunity Cost:** What am I saying NO to
>    by saying YES to this?
> 5. **Pre-mortem:** Imagine this failed — why did it fail?
> 6. **Regret Minimization:** Which choice would I regret
>    NOT taking when I'm 80?
>
> Final recommendation with confidence level
> (high / medium / low).

---

## 25. Graphic Design & Visual Content

### T25.1 — Social Media Visual Brief

> Create a design brief
> for [NUMBER] social media graphics
> for [PLATFORM]:
>
> **Theme:** [CAMPAIGN/TOPIC]
> **Brand colors:** [HEX CODES or "suggest based on industry"]
> **Style:** [minimal / bold / playful / professional]
>
> For each graphic provide:
> - Dimensions and file format
> - Layout description
>   (text placement, visual elements, whitespace)
> - Headline text and body text
> - Image or illustration direction
> - Typography: font suggestions and hierarchy
> - CTA element (button, arrow, swipe indicator)
>
> Include consistency rules across the entire set
> and a file naming convention.

---

### T25.2 — Infographic Structure

> Design an infographic about [TOPIC]
> for [AUDIENCE]:
>
> 1. **Title:** Compelling headline
> 2. **Introduction:** One context-setting stat or statement
> 3. **Data sections (4–6 sections):** Each with:
>    - Key data point
>    - Visualization type (bar, pie, icon, comparison)
>    - Supporting text (1–2 sentences)
> 4. **Flow:** Reading order
>    (top-to-bottom or left-to-right)
> 5. **Visual hierarchy:**
>    What draws the eye first, second, third
> 6. **Color strategy:**
>    Data colors, background, accent colors
> 7. **Sources:** Where the data comes from
> 8. **CTA:** What the viewer should do after reading
>
> Include all content for each section
> and visualization recommendations.

---

### T25.3 — Presentation Slide Design

> Design a [X]-slide presentation
> about [TOPIC] for [AUDIENCE]:
>
> For each slide provide:
> 1. **Slide type:**
>    title / content / data / image / quote / CTA
> 2. **Headline:** Maximum 8 words
> 3. **Body content:**
>    Maximum 25 words or 3 bullet points
> 4. **Visual element:** Description of image,
>    chart, icon, or diagram
> 5. **Speaker notes:**
>    What to say (2–3 sentences)
>
> Design rules:
> - One idea per slide
> - Minimal text (audience should listen, not read)
> - Every slide has a visual element
> - Consistent template across all slides
> - Progressive disclosure (build information gradually)

---

### T25.4 — Thumbnail & Cover Concepts

> Design [NUMBER] thumbnail or cover image concepts
> for [PLATFORM] about [TOPIC]:
>
> For each concept provide:
> 1. **Layout:** Composition and focal point description
> 2. **Text overlay:** Maximum 4 words
> 3. **Color palette:** 2–3 high-contrast colors
> 4. **Emotional element:**
>    Expression, visual metaphor, or symbol
> 5. **Before/after element:** If applicable
> 6. **Small-size readability:**
>    How it looks at mobile thumbnail size
>
> Rules:
> - Must be recognizable at 100×56 pixels
>   (YouTube mobile thumbnail test)
> - Maintain brand consistency across all concepts
> - Avoid visual clutter — simplicity wins

---

# Prompt Testing Framework

### Rating System

| Criteria | Score (1–5) | What to Check |
|----------|:-----------:|--------------|
| **Relevance** | ⭐⭐⭐⭐⭐ | Does the output match your request? |
| **Specificity** | ⭐⭐⭐⭐⭐ | Is it actionable or too generic? |
| **Accuracy** | ⭐⭐⭐⭐⭐ | Are all facts, code, and claims correct? |
| **Format** | ⭐⭐⭐⭐⭐ | Is it structured exactly as requested? |
| **Completeness** | ⭐⭐⭐⭐⭐ | Are all aspects of the task covered? |
| **Reusability** | ⭐⭐⭐⭐⭐ | Can this template work with different inputs? |

### Pre-Flight Checklist

Before submitting any prompt, verify:

- ✅ Did I specify a clear **role**?
- ✅ Did I provide enough **context**?
- ✅ Did I define the **output format**?
- ✅ Did I set meaningful **constraints**?
- ✅ Did I include **examples** (few-shot)?
- ✅ Did I specify what **NOT** to do?
- ✅ Did I put critical rules at **start AND end**?
- ✅ Did I test with a **real use case**?
- ✅ Is the prompt **reusable** with placeholder swaps?
- ✅ Could someone else use this and get **similar quality**?

### Effectiveness Tracker

| Template | Category | Use Case | Score | Notes | Date |
|----------|----------|----------|:-----:|-------|------|
| T2.1 | Reels | Product launch hooks | 9/10 | Great variety | 2026-04-01 |
| T5.3 | YouTube | Tutorial script | 8/10 | Needed shorter | 2026-04-02 |
| T11.1 | Startup | New idea evaluation | 10/10 | Perfect framework | 2026-04-03 |

---

## Contributing

1. **Fork** this repository
2. **Add** your template to the relevant category
3. **Follow** the format: ID, name, full prompt with `[PLACEHOLDERS]`
4. **Test** with at least 2 different topics before submitting
5. **Submit** a pull request

### Guidelines
- All templates must use `[PLACEHOLDER]` format
- Include which AI model you tested with
- Add attribution if inspired by another creator's work
- Follow the existing numbering: `T[Category].[Number]`

---

## Sources & Inspiration

Prompt patterns inspired by and extracted from:
- [@shwetacreates](https://instagram.com/shwetacreates) — Content strategy, growth, monetization
- [@codingknowledge](https://instagram.com/codingknowledge) — Digital product selling, DM automation
- [@razvanpbusiness](https://instagram.com/razvanpbusiness) — YouTube growth prompt chain
- [@paulhilse](https://instagram.com/paulhilse) — YouTube hook, title, tutorial scripting
- [@claudetricks.ai](https://instagram.com/claudetricks.ai) — Business scaling prompts
- [Anthropic Prompt Engineering Guide](https://docs.anthropic.com/en/docs/build-with-claude/prompt-engineering)

---

## License

**MIT License** — Use freely. Attribution appreciated but not required.

---

**Created by [Sisindri Singamsetti](https://github.com/sisi-tarak)**

⭐ **If this helped you, star the repo!** ⭐
