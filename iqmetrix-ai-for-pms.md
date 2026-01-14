# AI for Product Managers: Training Workshop
**iQmetrix | Advisory Engagement with Waleed Ayoub**
**Prepared in partnership with Lauren**

---

## Workshop Overview

**Goal:** Help PMs develop deep AI understanding so they can evaluate how modern AI tools apply to Product Mangement and to building products.

**Path:** Build intuition through personal AI productivity and use case exploration **first**, then apply that understanding to product decisions.

**Format:** Single 60-minute session — demos for intuition building, then frameworks for product decisions.

**What They'll Leave With:**
- Hands-on experience with AI tools (Claude.ai with connectors, Claude Desktop, ChatGPT Deep Research, voice input)
- A mental model for "where can AI help in my workflow?"
- Framework for evaluating AI features in your own products
- Reference playbook with PM workflows they can try, build on and extend themselves

---

## Workshop Design Philosophy

This workshop follows an intentional and repeatable format:

### The 60-Minute Workshop Flow

```
┌─────────────────────────────────────────────────────────────┐
│ 1. MENTAL MODELS (10 min)                                   │
├─────────────────────────────────────────────────────────────┤
│ • Frame the session: intuition building → product decisions │
│ • Introduce two modes: thinking partner + task automator    │
│ • Show PM user stories and how AI transforms each           │
│                                                             │
└─────────────────────────────────────────────────────────────┘
                          │
                          ▼
┌─────────────────────────────────────────────────────────────┐
│ 2. LIVE DEMOS (30 min)                                      │
├─────────────────────────────────────────────────────────────┤
│ Show 4-5 PM workflows with AI:                              │
│ • Deep Research (async, "set and forget")                   │
│ • Interview Synthesis (thinking partner mode)               │
│ • Meeting Notes → Actions (M365 connector)                  │
│ • Data Exploration (Databricks connector)                   │
│ • Cross-system Updates (Aha! + Azure DevOps)                │
│                                                             │
│ Progression: Async → Interactive → Connected → Multi-system │
│ End with quick glimpse of Claude Code/Cowork (ceiling)      │
└─────────────────────────────────────────────────────────────┘
                          │
                          ▼
┌─────────────────────────────────────────────────────────────┐
│ 3. BUILDING AI PRODUCTS (10 min)                            │
├─────────────────────────────────────────────────────────────┤
│ Flip from user to builder perspective:                      │
│ • Interface patterns (chat, embedded, proactive, messaging) │
│ • Configuration space (what knobs to expose)                │
│ • Context vs concealment (user data vs system prompts)      │
│ • Quick framework for AI feature decisions                  │
│                                                             │
│ Key message: "Apply your intuition to product decisions"    │
└─────────────────────────────────────────────────────────────┘
                          │
                          ▼
┌─────────────────────────────────────────────────────────────┐
│ 4. CLOSING + Q&A (10 min)                                   │
├─────────────────────────────────────────────────────────────┤
│ • Summarize the progression (thinking partner → automation) │
│ • Share the playbook document for self-study                │
│ • Q&A focused on "what would you automate?"                 │
│                                                             │
│ Offer follow-up sessions:                                   │
│ • Claude Desktop setup with Aha!/Azure DevOps               │
│ • AI feature evaluation deep dive                           │
│ • Office hours for individual workflow design               │
└─────────────────────────────────────────────────────────────┘
```

### Why This Structure Works

1. **Mental models ground everyone** — Even if AI fluency varies, everyone starts with the same framework (thinking partner + task automator).

2. **Live demos build belief** — Seeing is believing. Demos with their actual tools (M365, Databricks) convert skeptics.

3. **Progression shows the path** — From simple (Deep Research) to sophisticated (multi-system) — everyone sees where to start and where it goes.

4. **Product section creates ownership** — Flipping to builder perspective connects personal experience to their day jobs.

5. **60 minutes creates awareness** — This session is the appetizer. Follow-up sessions and the playbook enable deeper skill-building.

---

# PART 1: MENTAL MODELS (10 minutes)

## Slide 1: Title + Framing

**SLIDE TITLE:** AI for Product Managers: From Personal Productivity to Product Strategy

**CONTENT:**

> "You can't design AI experiences you don't understand intuitively."

**Today's Session (60 min):**

| Part                    | Time   | What We'll Cover                       |
| ----------------------- | ------ | -------------------------------------- |
| 1. Mental Models        | 10 min | How to think about AI as a PM          |
| 2. Your Day-to-Day      | 35 min | Demos: AI applied to real PM workflows |
| 3. Building AI Products | 10 min | How to apply this to iQmetrix products |
| 4. Q&A                  | 5 min  | Your questions                         |

**The Goal:**
- **First:** Build intuition through examples from your daily work
- **Then:** Apply that intuition to building AI into iQmetrix products

**SPEAKER NOTES:**
We're going to move fast. The first half is about *you* — making your work easier. The second half is about *products* — how iQmetrix can use these same patterns. By the end, you'll have both personal tools and a framework for product decisions.

---

## Slide 2: The AI Landscape Today

**SLIDE TITLE:** The Tools Landscape (Early 2026)

**CONTENT:**

**What You Already Use:**
- M365 Copilot — AI embedded in Word, Excel, Outlook, Teams (you have this!)
- GitHub Copilot — Code completion and generation (some of you have this)

**What We'll Explore Today:**
- Claude.ai with Connectors — AI that reads/writes to your actual tools (Confluence, M365, Databricks)
- Claude Desktop — Local app with deeper integrations (Aha!, Azure DevOps)
- ChatGPT Deep Research — "Set it and forget it" async research assistant

**Voice & Multimodal:**
- Built-in voice input — Claude mobile, M365 Copilot voice
- Vision capabilities — Analyze screenshots, diagrams, documents

**The Key Shift:** Moving from "chat with AI" → "AI connected to your workflow"

| Old Way                                | New Way                                           |
| -------------------------------------- | ------------------------------------------------- |
| Ask AI → Copy answer → Paste into tool | Ask AI → AI updates the tool directly             |
| Upload a doc → Get analysis            | AI reads from SharePoint/Confluence automatically |
| Manual research → Summarize yourself   | Deep Research runs for 30 min → Delivers report   |
| Repeat instructions every session      | Skills encode your expertise once, applied always |

**What Are Skills?**

A **Skill** is a way to teach AI how to do something specific and reusable. Think of it as packaging your expertise into a format the AI can apply automatically.

**Generic Concept:** Any repeatable workflow, checklist, or standard you follow can become a skill — your code review standards, your PRD template, your interview synthesis method.

**Anthropic's Implementation:** In Claude Code/Desktop, Skills are markdown files (SKILL.md) that Claude automatically applies when relevant. You describe *when* to use the skill and *how* to execute it — Claude handles the rest.

**Examples:**
- "Review PRs using our team's security checklist"
- "Generate commit messages in our preferred format"
- "Synthesize customer interviews using our research framework"
- "Create Azure DevOps work items following our template"

**SPEAKER NOTES:**
You don't need to know all of these. The key insight: AI is moving from "assistant you talk to" toward "agent that takes actions in your tools." We'll show you what that means with your actual stack — Aha!, Azure DevOps, Confluence, Databricks.

---

## Slide 3: The Two Modes of AI

**SLIDE TITLE:** How to Think About AI: Two Modes

**CONTENT:**

| Mode                 | What It Does                                                               | When to Use It                                    |
| -------------------- | -------------------------------------------------------------------------- | ------------------------------------------------- |
| **Thinking Partner** | Brainstorms with you, researches, structures ideas, challenges assumptions | Discovery, planning, analysis, problem-solving    |
| **Task Automator**   | Executes actions across your tools — reads, writes, updates, queries       | Repetitive work, cross-system updates, data tasks |

**Thinking Partner Examples:**
- "Help me synthesize these 6 interview transcripts into themes"
- "What are the risks of adding AI to our inventory feature?"
- "Draft 3 different approaches to this problem and critique each"

**Task Automator Examples:**
- "Pull my meeting notes from SharePoint and extract action items"
- "Query our sales data and show me trends by region"
- "Update the Aha! roadmap status and create follow-up work items"

**The Key Insight:**
> Same AI, different modes. The thinking partner has access to context you provide. The task automator has access to your tools. The best workflows combine both.

**SPEAKER NOTES:**
This is the mental model I want you to take away. It's not "chatbot vs agent" — it's "when do I need a thinking partner, and when do I need a task automator?" Often, you'll use both in sequence: think through the problem first, then automate the execution.

---

## Slide 4: What Agents Are Good At (GDPVal Evidence)

**SLIDE TITLE:** Building Intuition: What Agents Can Actually Do

**CONTENT:**

**OpenAI's GDPVal Study:** Agents performing as well as human evaluators across retail trade tasks.

**Example: Retail Demand Forecasting**

| Metric           | Human     | Agent                   |
| ---------------- | --------- | ----------------------- |
| Time to complete | 2.5 hours | 8 minutes               |
| Accuracy (MAPE)  | 15%       | 14%                     |
| Factors analyzed | 4-6       | 12+ simultaneously      |
| Explainability   | Notes     | Full reasoning provided |

**Example: Root Cause Analysis**

Scenario: Sudden 40% spike in returns for electronics category

| Traditional Approach                          | Agent Approach                              |
| --------------------------------------------- | ------------------------------------------- |
| Data analyst pulls reports (2 days)           | Scanned 15 data sources simultaneously      |
| Cross-functional meeting (3 days to schedule) | Identified correlation in minutes           |
| Hypothesis testing (1 week)                   | Generated 3 ranked hypotheses with evidence |
| **Total: 10-14 days**                         | **Total: 12 minutes**                       |

**SPEAKER NOTES:**
These aren't lab experiments — these are production systems. The pattern: agents excel at pattern recognition, hypothesis generation, and multi-source synthesis. Humans excel at judgment on edge cases and strategic decisions.

---

## Slide 5: The Agent Capability Spectrum

**SLIDE TITLE:** Where Agents Excel vs. Where Humans Are Essential

**CONTENT:**

**Agents Excel At:**
- Processing large volumes of information quickly
- Finding patterns across multiple data sources
- Generating first drafts and variations
- Repetitive tasks with clear rules
- Maintaining consistency across documents
- 24/7 availability, no context-switching cost

**Humans Are Essential For:**
- Judgment on ambiguous situations
- Stakeholder relationships and politics
- Creative leaps and novel ideas
- Ethical considerations and values
- Final accountability for decisions
- Understanding unstated context

**The Sweet Spot:**
> Agent does the legwork → Human makes the call

**SPEAKER NOTES:**
The goal isn't replacement. It's leverage. A PM who used to spend 4 hours on competitive research can now spend 30 minutes reviewing and refining agent-generated analysis.

---

## Slide 6: The Prompting Mental Model

**SLIDE TITLE:** How to Talk to AI: The CRAFT Framework

**CONTENT:**

**C**ontext — Background information the AI needs
**R**ole — Who should the AI be? (analyst, writer, critic)
**A**sk — The specific request
**F**ormat — How you want the output structured
**T**one — Voice and style guidelines

**Example:**

> **Context:** I'm a PM at a retail POS company. We're evaluating whether to add AI-powered inventory recommendations.
>
> **Role:** Act as a senior product strategist who has shipped AI features at enterprise SaaS companies.
>
> **Ask:** Identify the top 3 risks of this feature and how to mitigate each.
>
> **Format:** Bullet points with risk, likelihood, impact, and mitigation for each.
>
> **Tone:** Direct and practical, no fluff.

**Pro Tips:**
- Be specific about what you DON'T want
- Include examples of good output when possible
- Iterate — first response is rarely final

**SPEAKER NOTES:**
You don't need to use this framework explicitly every time. But when you're not getting good results, walk through CRAFT to diagnose what's missing.

---

## Slide 7: Voice Input — Lowering the Barrier

**SLIDE TITLE:** Talk, Don't Type: Voice-First AI Interaction

**CONTENT:**

**Why Voice Matters:**
- Faster than typing (3x for most people)
- More natural for brainstorming and ideation
- Captures nuance and tone you'd edit out when typing
- Enables AI use while walking, commuting, thinking

**Free Tools:**
- **MacWhisper** (Mac) — Local transcription, privacy-friendly
- **Whisper.cpp browser tools** — Web-based, no install
- **Claude mobile app** — Built-in voice input
- **M365 Copilot voice** — In Teams and mobile apps

**Workflow Pattern:**
1. Voice-capture your raw thoughts (2 min ramble)
2. AI transcribes and structures
3. You refine the structured version
4. Result: 10 minutes vs. 45 minutes of writing

**SPEAKER NOTES:**
This is a game-changer for ideation. You can literally think out loud and get structured output. We'll demo this with interview synthesis.

---

## Slide 8: PM User Stories

**SLIDE TITLE:** Your Day-to-Day as a PM

**CONTENT:**

## PM Workflows: Today vs. With AI

| #   | User Story                               | Today                                                 | With AI                                                         | Tools                      | Time Saved              |
| --- | ---------------------------------------- | ----------------------------------------------------- | --------------------------------------------------------------- | -------------------------- | ----------------------- |
| ⭐1  | Research a topic deeply                  | Manual search, read articles, synthesize              | AI searches dozens of sources, delivers report while you work   | ChatGPT Deep Research      | 1-2 days → 30 min       |
| ⭐2  | Synthesize customer interviews           | Read transcripts, highlight, organize themes manually | Upload transcripts, AI finds themes + contradictions + quotes   | Claude.ai Projects         | 3-4 hours → 30 min      |
| 3   | Learn a new domain quickly               | Google, read docs, take notes                         | AI creates structured learning plan with resources + quiz       | Claude.ai                  | Days → 2 hours          |
| 4   | Brainstorm feature ideas                 | Whiteboard session, solo thinking                     | AI generates options, critiques them, identifies risks          | Claude.ai                  | Half-day → 45 min       |
| ⭐5  | Explore data for product questions       | Write SQL or wait for analyst                         | Ask questions in English, AI writes SQL, returns insights       | Claude.ai + Databricks     | Hours waiting → minutes |
| 6   | Turn PRD into work items                 | Write PRD, manually create tickets                    | AI extracts stories from PRD, creates in Azure DevOps           | Claude Desktop + ADO MCP   | 2-3 hours → 30 min      |
| ⭐7  | Synthesize meeting notes into actions    | Read notes, extract decisions, format                 | AI pulls from SharePoint, extracts decisions + action items     | Claude.ai + M365 Connector | 1-2 hours → 10 min      |
| 8   | Distribute meeting outputs               | Copy to Slack, create tasks, update docs              | AI routes to appropriate channels and tools                     | Claude Desktop + MCPs      | 30-45 min → 5 min       |
| 9   | Evaluate "should we add AI to X?"        | Gut feel, ad-hoc analysis                             | Structured framework: capability fit, user value, failure modes | Claude.ai                  | Variable                |
| 10  | Debug why AI feature gives wrong answers | Manual review of failure cases                        | AI categorizes failures, identifies patterns, suggests fixes    | Claude.ai                  | Hours → 30 min          |
| ⭐11 | Update roadmap + create follow-up work   | Switch between Aha!, ADO, copy-paste                  | AI reads from Aha!, updates status, creates ADO work items      | Claude Desktop + Aha!/ADO  | 1-2 hours → 10 min      |
| ⭐12 | **Build a plan to launch a new product** | Scattered docs, meetings, manual coordination         | AI synthesizes context, drafts launch plan, identifies gaps     | Claude.ai Projects         | Days → hours            |
| 13  | Create custom learning path              | Search for resources, organize manually               | AI curates resources, sequences them, creates checkpoints       | Claude.ai                  | Weeks → days            |
| 14  | **Create reusable Skills**               | Re-explain standards every session                    | Encode expertise once, Claude applies it automatically forever  | Claude Code/Desktop        | 5-10 min/task saved     |

**⭐ = Live demo in session**

**SPEAKER NOTES:**
These are universal PM tasks. Let me show you how AI changes each one — not just making them faster, but making them *better*.

---

## Slide 9: How AI Transforms Each Workflow

**SLIDE TITLE:** The AI Approach

**CONTENT:**

| Task                    | AI Approach                                                               | Tool                   | Time Savings            | Value Created                             |
| ----------------------- | ------------------------------------------------------------------------- | ---------------------- | ----------------------- | ----------------------------------------- |
| Deep research           | AI searches dozens of sources, synthesizes report while you do other work | ChatGPT Deep Research  | 1-2 days → 30 min       | Higher quality, more comprehensive        |
| Interview synthesis     | Upload transcripts, AI finds themes + contradictions + best quotes        | Claude.ai Projects     | 3-4 hours → 30 min      | Patterns you'd miss manually              |
| Meeting notes → actions | AI reads from SharePoint, extracts decisions + action items               | Claude.ai + M365       | 1-2 hours → 10 min      | Consistent format, nothing missed         |
| Data exploration        | Ask questions in English, AI writes SQL, returns insights                 | Claude.ai + Databricks | Hours waiting → minutes | Self-service, faster iteration            |
| Cross-system updates    | AI reads from one system, writes to another                               | Claude Desktop         | 1-2 hours → 10 min      | Single conversation, no context switching |

**The Progression:**
```
Async research  →  Thinking partner  →  Connected tools  →  Multi-system workflows  →  Full automation
(ChatGPT)          (Claude.ai)          (Connectors)        (Claude Desktop)           (Claude Code/Cowork)
```

*We'll demo the first four today. Claude Code/Cowork is where this goes when you want full automation — I'll show you a quick glimpse at the end.*

**SPEAKER NOTES:**
Notice the pattern: AI handles the grunt work, you keep the judgment. The time savings are real, but the bigger win is quality — AI catches things you'd miss when you're rushing.

---

# PART 2: THE 12 PM WORKFLOWS

---

## Workflow 1: Deep Research (Async) ⭐ RECOMMENDED DEMO

**User Story:** *"As a PM, I need comprehensive research on a topic but don't have hours to do it myself. I want to set it running and come back to a finished report."*

**Workflow Sketch:**

```
┌─────────────────────────────────────────────────────────────┐
│ KICK OFF (2 min)                                            │
├─────────────────────────────────────────────────────────────┤
│ In ChatGPT, select "Deep Research" mode                     │
│                                                             │
│ Prompt example:                                             │
│ "Research the current state of AI-powered inventory         │
│ optimization in retail POS systems. I need to understand:   │
│ - Key vendors and their approaches                          │
│ - Technical architectures being used                        │
│ - Success metrics retailers are reporting                   │
│ - Gaps and opportunities for a POS platform like ours       │
│                                                             │
│ Produce a report I can share with my leadership team."      │
└─────────────────────────────────────────────────────────────┘
            │
            ▼
┌─────────────────────────────────────────────────────────────┐
│ AI WORKS AUTONOMOUSLY (10-30 min)                           │
├─────────────────────────────────────────────────────────────┤
│ • Searches dozens of sources                                │
│ • Reads full articles, not just snippets                    │
│ • Cross-references and fact-checks                          │
│ • Synthesizes into coherent narrative                       │
│                                                             │
│ You can close the tab and come back later.                  │
└─────────────────────────────────────────────────────────────┘
            │
            ▼
┌─────────────────────────────────────────────────────────────┐
│ OUTPUT                                                      │
├─────────────────────────────────────────────────────────────┤
│ • 5-15 page structured report with citations                │
│ • Executive summary                                         │
│ • Detailed findings by topic                                │
│ • Source links for verification                             │
└─────────────────────────────────────────────────────────────┘
```

**Tools:** ChatGPT Plus/Pro with Deep Research mode

**Time Savings:** 1-2 days of research → 30 minutes of AI work + 15 min review

**Why Demo This:**
- Shows "set it and forget it" AI — different from interactive chat
- Produces genuinely impressive, shareable output
- Easy for anyone to try immediately
- Good contrast to the interactive demos that follow

**Key Insight:** This is AI doing hours of work while you do other things. The quality rivals a junior analyst's output.

---

## Workflow 2: User Interview Synthesis ⭐ RECOMMENDED DEMO

**User Story:** *"As a PM, I need to synthesize 6 customer interview transcripts into actionable themes so I can identify patterns."*

**Workflow Sketch:**

```
┌─────────────────────────────────────────────────────────────┐
│ INPUT                                                       │
├─────────────────────────────────────────────────────────────┤
│ • 6 interview transcripts (or voice memos)                  │
│ • Research questions you were exploring                     │
│ • Any hypotheses you were testing                           │
└─────────────────────────────────────────────────────────────┘
            │
            ▼
┌─────────────────────────────────────────────────────────────┐
│ VOICE CAPTURE OPTION                                        │
├─────────────────────────────────────────────────────────────┤
│ Record yourself summarizing each interview (2-3 min each)   │
│ "Interview 3 was with Sarah, store manager. Key things:     │
│  she mentioned inventory counts take 2 hours, wishes she    │
│  could do it from her phone, frustrated that..."            │
│                                                             │
│ Whisper transcribes → feed to AI                            │
└─────────────────────────────────────────────────────────────┘
            │
            ▼
┌─────────────────────────────────────────────────────────────┐
│ AI SYNTHESIS                                                │
├─────────────────────────────────────────────────────────────┤
│ Prompt: "Analyze these 6 interviews. Identify:              │
│ 1. Top 5 themes by frequency                                │
│ 2. Surprising insights I might have missed                  │
│ 3. Contradictions between participants                      │
│ 4. Quotes that best illustrate each theme                   │
│ 5. Recommended next steps for product"                      │
└─────────────────────────────────────────────────────────────┘
            │
            ▼
┌─────────────────────────────────────────────────────────────┐
│ OUTPUT                                                      │
├─────────────────────────────────────────────────────────────┤
│ • Theme summary with evidence                               │
│ • Quote bank organized by theme                             │
│ • Recommendation for which themes to pursue                 │
└─────────────────────────────────────────────────────────────┘
```

**Tools:** MacWhisper or voice input + Claude.ai

**Time Savings:** 3-4 hours → 30 minutes

**Why Demo This:**
- Shows voice input (lowering the barrier)
- Relatable to every PM
- Clear before/after
- Quick to demonstrate

---

## Workflow 3: Rapid Domain Learning

**User Story:** *"As a PM, I need to quickly get up to speed on a new domain (e.g., inventory optimization algorithms) so I can have informed conversations with engineers."*

**Workflow Sketch:**

```
┌─────────────────────────────────────────────────────────────┐
│ PROMPT PATTERN                                              │
├─────────────────────────────────────────────────────────────┤
│ "I'm a PM who needs to understand [DOMAIN] well enough to:  │
│ - Have informed conversations with engineers                │
│ - Ask good questions in customer interviews                 │
│ - Evaluate vendor claims critically                         │
│                                                             │
│ Create a learning plan:                                     │
│ 1. Key concepts I must understand (with simple analogies)   │
│ 2. Common jargon and what it actually means                 │
│ 3. Questions that reveal if someone really knows this       │
│ 4. Red flags / BS indicators to watch for                   │
│ 5. Resources for going deeper (but only if needed)"         │
└─────────────────────────────────────────────────────────────┘
            │
            ▼
┌─────────────────────────────────────────────────────────────┐
│ FOLLOW-UP PROMPTS                                           │
├─────────────────────────────────────────────────────────────┤
│ "Explain [concept] like I'm smart but not technical"        │
│ "What would an expert ask about this that I wouldn't?"      │
│ "What's the difference between [A] and [B] in practice?"    │
│ "Quiz me on the key concepts"                               │
└─────────────────────────────────────────────────────────────┘
```

**Tools:** Claude.ai or ChatGPT

**Time Savings:** Days of research → 1-2 hours of conversation

**Key Insight:** The "quiz me" follow-up is powerful — it reveals gaps in your understanding before you're in a meeting.

---

## Workflow 4: Feature Ideation & Brainstorming

**User Story:** *"As a PM, I need to brainstorm feature ideas and explore different directions for a 'store manager copilot'."*

**Workflow Sketch:**

```
┌─────────────────────────────────────────────────────────────┐
│ DIVERGENT PHASE                                             │
├─────────────────────────────────────────────────────────────┤
│ Prompt: "I'm exploring a 'store manager copilot' feature.   │
│ Generate 15 different feature ideas across these lenses:    │
│ - Time-saving automation                                    │
│ - Decision support                                          │
│ - Communication enhancement                                 │
│ - Training and onboarding                                   │
│ - Exception handling                                        │
│                                                             │
│ For each: one sentence + who benefits + rough complexity"   │
└─────────────────────────────────────────────────────────────┘
            │
            ▼
┌─────────────────────────────────────────────────────────────┐
│ CONVERGENT PHASE                                            │
├─────────────────────────────────────────────────────────────┤
│ "Now critique these ideas harshly. For each:                │
│ - Why might this fail?                                      │
│ - What assumption is riskiest?                              │
│ - What would we need to prove first?"                       │
│                                                             │
│ Then: "Pick the 3 ideas with best effort/impact ratio"      │
└─────────────────────────────────────────────────────────────┘
            │
            ▼
┌─────────────────────────────────────────────────────────────┐
│ DEEP DIVE                                                   │
├─────────────────────────────────────────────────────────────┤
│ "For [selected idea], create:                               │
│ - 3 user stories                                            │
│ - Key assumptions to validate                               │
│ - Lightweight experiment to test demand"                    │
└─────────────────────────────────────────────────────────────┘
```

**Tools:** Claude.ai (strong reasoning helps with critique phase)

**Time Savings:** Half-day ideation session → 45 minutes

**Key Insight:** The AI is useful for both generating AND critiquing. Ask it to argue against its own ideas.

---

## Workflow 5: Querying Your Data with Natural Language ⭐ RECOMMENDED DEMO

**User Story:** *"As a PM, I need to explore our data to answer product questions without writing SQL or waiting for an analyst."*

**Workflow Sketch:**

```
┌─────────────────────────────────────────────────────────────┐
│ SETUP: CONNECT DATABRICKS                                   │
├─────────────────────────────────────────────────────────────┤
│ In Claude.ai: Settings → Connectors → Add Databricks        │
│ Authenticate with your Databricks workspace                 │
│ Claude now has access to your Unity Catalog tables          │
└─────────────────────────────────────────────────────────────┘
            │
            ▼
┌─────────────────────────────────────────────────────────────┐
│ ASK QUESTIONS IN PLAIN ENGLISH                              │
├─────────────────────────────────────────────────────────────┤
│ "What were our top 10 selling products last quarter?"       │
│ "Show me return rates by product category over time"        │
│ "Which stores have the highest inventory shrinkage?"        │
│ "Compare this month's sales to the same month last year"    │
│                                                             │
│ Claude translates to SQL, runs the query, returns results.  │
└─────────────────────────────────────────────────────────────┘
            │
            ▼
┌─────────────────────────────────────────────────────────────┐
│ EXPLORE AND REFINE                                          │
├─────────────────────────────────────────────────────────────┤
│ "Break that down by region"                                 │
│ "Why did returns spike in March?"                           │
│ "What's the correlation between promotions and returns?"    │
│ "Create a summary I can share with leadership"              │
└─────────────────────────────────────────────────────────────┘
            │
            ▼
┌─────────────────────────────────────────────────────────────┐
│ OUTPUT                                                      │
├─────────────────────────────────────────────────────────────┤
│ • Query results with visualizations                         │
│ • Insights and pattern identification                       │
│ • Exportable summaries for stakeholders                     │
│ • The actual SQL (for analysts to verify/reuse)             │
└─────────────────────────────────────────────────────────────┘
```

**Tools:** Claude.ai + Databricks Connector

**Time Savings:** Hours waiting for analyst → Minutes of self-service

**Why Demo This:**
- Directly relevant to the Luzmo dashboard project
- Shows AI accessing real enterprise data
- Empowers PMs to explore without dependencies
- "I could answer my own questions" is powerful

**Key Insight:** You're not replacing analysts — you're doing the exploratory work yourself so when you go to them, you have specific, informed questions.

**iQmetrix Context:** This connects directly to the data dashboard project. PMs can explore what metrics matter before the Luzmo dashboards are built.

---

## Workflow 6: PRD → Azure DevOps Work Items

**User Story:** *"As a PM, I need to write a clear PRD and automatically create the Azure DevOps work items from it."*

**Workflow Sketch:**

```
┌─────────────────────────────────────────────────────────────┐
│ STEP 1: DRAFT PRD                                           │
├─────────────────────────────────────────────────────────────┤
│ Use standard prompting to draft PRD:                        │
│ "Help me write a PRD for [feature]. Include:                │
│ - Problem statement                                         │
│ - User stories                                              │
│ - Acceptance criteria                                       │
│ - Out of scope                                              │
│ - Success metrics"                                          │
│                                                             │
│ Iterate until satisfied.                                    │
└─────────────────────────────────────────────────────────────┘
            │
            ▼
┌─────────────────────────────────────────────────────────────┐
│ STEP 2: EXTRACT WORK ITEMS                                  │
├─────────────────────────────────────────────────────────────┤
│ "Based on this PRD, create Azure DevOps work items:         │
│ - One Feature for the overall capability                    │
│ - User Stories broken down by user-facing functionality     │
│ - Each story has acceptance criteria                        │
│ - Estimate effort (S/M/L)                                   │
│ - Identify dependencies between stories"                    │
└─────────────────────────────────────────────────────────────┘
            │
            ▼
┌─────────────────────────────────────────────────────────────┐
│ STEP 3: CREATE IN AZURE DEVOPS (with MCP)                   │
├─────────────────────────────────────────────────────────────┤
│ With Azure DevOps MCP connected (Claude Desktop):           │
│ "Create these work items in project [PROJECT_NAME]"         │
│                                                             │
│ AI creates Feature, creates User Stories, links them,       │
│ sets fields, returns links to created work items.           │
└─────────────────────────────────────────────────────────────┘
```

**Tools:**
- Claude.ai for PRD drafting
- Claude Desktop + Azure DevOps MCP for work item creation

**Time Savings:** 2-3 hours → 30 minutes

**Key Insight:** Even without MCP, the "extract work items from PRD" step saves massive time. MCP just eliminates copy-paste.

---

## Workflow 7: Meeting Notes → Structured Actions (M365 Connector) ⭐ RECOMMENDED DEMO

**User Story:** *"As a PM, I need to pull meeting notes from SharePoint, synthesize them, and create actionable outputs."*

**Workflow Sketch:**

```
┌─────────────────────────────────────────────────────────────┐
│ SETUP: CONNECT M365                                         │
├─────────────────────────────────────────────────────────────┤
│ In Claude.ai: Settings → Connectors → Microsoft 365         │
│ Authenticate with your iQmetrix account                     │
│ Claude now has read access to SharePoint, OneDrive, Outlook │
└─────────────────────────────────────────────────────────────┘
            │
            ▼
┌─────────────────────────────────────────────────────────────┐
│ CONTEXT GATHERING                                           │
├─────────────────────────────────────────────────────────────┤
│ "Find the meeting notes from last week's sprint planning    │
│ in our team SharePoint site"                                │
│                                                             │
│ Claude searches SharePoint, finds the relevant docs,        │
│ reads them without you uploading anything.                  │
└─────────────────────────────────────────────────────────────┘
            │
            ▼
┌─────────────────────────────────────────────────────────────┐
│ SYNTHESIS                                                   │
├─────────────────────────────────────────────────────────────┤
│ "Based on these meeting notes:                              │
│ 1. List all decisions made                                  │
│ 2. Extract action items with owners                         │
│ 3. Identify open questions that need follow-up              │
│ 4. Summarize key discussion points for stakeholders"        │
└─────────────────────────────────────────────────────────────┘
            │
            ▼
┌─────────────────────────────────────────────────────────────┐
│ OUTPUT OPTIONS                                              │
├─────────────────────────────────────────────────────────────┤
│ • Structured summary (copy to Confluence)                   │
│ • Action items formatted for Azure DevOps                   │
│ • Stakeholder email draft                                   │
│ • Follow-up meeting agenda                                  │
└─────────────────────────────────────────────────────────────┘
```

**Tools:** Claude.ai + Microsoft 365 Connector

**Time Savings:** 1-2 hours of manual synthesis → 10 minutes

**Why Demo This:**
- Uses tools they already have (SharePoint/OneDrive)
- Shows "AI reading from your systems" — not just uploads
- Practical, weekly task everyone recognizes
- Bridge from M365 Copilot: "Like Copilot, but pulls from anywhere"

**Key Insight:** The M365 connector respects your permissions — Claude only sees what you can see.

---

## Workflow 8: Meeting Synthesis

**User Story:** *"As a PM, I need to synthesize my meeting notes into action items and share them with the team."*

**Workflow Sketch:**

```
┌─────────────────────────────────────────────────────────────┐
│ CAPTURE                                                     │
├─────────────────────────────────────────────────────────────┤
│ Options:                                                    │
│ • Meeting transcript (Teams, Zoom, Otter)                   │
│ • Your handwritten notes (photo → OCR)                      │
│ • Voice memo recorded during/after                          │
└─────────────────────────────────────────────────────────────┘
            │
            ▼
┌─────────────────────────────────────────────────────────────┐
│ SYNTHESIS PROMPT                                            │
├─────────────────────────────────────────────────────────────┤
│ "Synthesize this meeting into:                              │
│                                                             │
│ **Summary** (3-5 sentences max)                             │
│                                                             │
│ **Decisions Made**                                          │
│ - [Decision]: [Rationale]                                   │
│                                                             │
│ **Action Items**                                            │
│ - [ ] [Task] — Owner: [Name] — Due: [Date]                  │
│                                                             │
│ **Open Questions**                                          │
│ - [Question] — Who needs to answer                          │
│                                                             │
│ **Parking Lot** (topics raised but deferred)"               │
└─────────────────────────────────────────────────────────────┘
            │
            ▼
┌─────────────────────────────────────────────────────────────┐
│ DISTRIBUTION                                                │
├─────────────────────────────────────────────────────────────┤
│ • Post to Slack channel                                     │
│ • Create follow-up tasks in Azure DevOps (via MCP)          │
│ • Update relevant Confluence pages                          │
└─────────────────────────────────────────────────────────────┘
```

**Tools:** Voice input + Claude.ai (or M365 Copilot in Teams)

**Time Savings:** 30-45 minutes → 5 minutes

**Key Insight:** This is Waleed's daily workflow at Daybreak. He uses Claude Code with MCP servers to automatically route meeting outputs to Obsidian, Slack, and Jira.

---

## Workflow 9: AI Feature Evaluation

**User Story:** *"As a PM, I need to evaluate whether we should add AI to our search feature so I can make a build/buy/skip recommendation."*

**Workflow Sketch:**

```
┌─────────────────────────────────────────────────────────────┐
│ FRAME THE OPPORTUNITY                                       │
├─────────────────────────────────────────────────────────────┤
│ "I'm evaluating adding AI to [feature]. Help me think       │
│ through:                                                    │
│                                                             │
│ 1. CAPABILITY FIT                                           │
│    - Is this a task AI is actually good at?                 │
│    - What type of AI would this use?                        │
│      (LLM, ML model, rule-based, etc.)                      │
│                                                             │
│ 2. USER VALUE                                               │
│    - What's the user pain point?                            │
│    - How much time/effort does this save them?              │
│    - Would they trust AI for this task?                     │
│                                                             │
│ 3. TECHNICAL FEASIBILITY                                    │
│    - What data do we need?                                  │
│    - What accuracy is required?                             │
│    - How do we handle errors?                               │
│                                                             │
│ 4. BUILD VS BUY                                             │
│    - What vendors offer this?                               │
│    - What's the integration effort?                         │
│    - What's the ongoing cost?"                              │
└─────────────────────────────────────────────────────────────┘
            │
            ▼
┌─────────────────────────────────────────────────────────────┐
│ RED TEAM                                                    │
├─────────────────────────────────────────────────────────────┤
│ "Now argue AGAINST adding AI to this feature.               │
│ What are the strongest reasons to skip this?"               │
└─────────────────────────────────────────────────────────────┘
            │
            ▼
┌─────────────────────────────────────────────────────────────┐
│ OUTPUT                                                      │
├─────────────────────────────────────────────────────────────┤
│ • Recommendation: Build / Buy / Skip                        │
│ • Key assumptions to validate                               │
│ • Risks and mitigations                                     │
│ • Next steps if proceeding                                  │
└─────────────────────────────────────────────────────────────┘
```

**Tools:** Claude.ai (reasoning quality matters here)

**Key Insight:** This framework comes from Teresa Torres's work — treat AI features like any product decision, with explicit hypothesis testing.

---

## Workflow 10: AI Debugging / Evals

**User Story:** *"As a PM, I need to understand why our RAG bot sometimes gives wrong answers so I can improve it."*

**Workflow Sketch:**

```
┌─────────────────────────────────────────────────────────────┐
│ COLLECT FAILURE CASES                                       │
├─────────────────────────────────────────────────────────────┤
│ Gather examples where the AI gave bad answers:              │
│ • User query                                                │
│ • AI response                                               │
│ • What should have happened                                 │
│ • Context available to the AI                               │
└─────────────────────────────────────────────────────────────┘
            │
            ▼
┌─────────────────────────────────────────────────────────────┐
│ PATTERN ANALYSIS                                            │
├─────────────────────────────────────────────────────────────┤
│ "Analyze these failure cases. Categorize by root cause:     │
│ • Missing information (not in knowledge base)               │
│ • Retrieval failure (info exists but wasn't found)          │
│ • Reasoning error (found info, drew wrong conclusion)       │
│ • Hallucination (made up information)                       │
│ • Scope confusion (answered different question)"            │
└─────────────────────────────────────────────────────────────┘
            │
            ▼
┌─────────────────────────────────────────────────────────────┐
│ PRIORITIZED FIXES                                           │
├─────────────────────────────────────────────────────────────┤
│ "For each category, suggest fixes ranked by effort/impact:  │
│ • Quick wins (prompt changes, guardrails)                   │
│ • Medium effort (knowledge base updates)                    │
│ • Larger effort (architecture changes)"                     │
└─────────────────────────────────────────────────────────────┘
```

**Tools:** Claude.ai + spreadsheet for tracking

**Key Insight:** This connects to iQmetrix's existing Slack RAG bot. It's a practical way to improve a real system they've built.

**From the 9 AI Teams Research:**
> "Everyone begins with spreadsheets — even Arize, an eval tooling company."

Start simple. Track failures. Look for patterns. Improve iteratively.

---

## Workflow 11: Standards Conformance Automation (TMForum) ⭐ RECOMMENDED DEMO — CAPSTONE

**User Story:** *"As a PM/technical leader, I need to map our APIs to an industry standard (TMForum) and generate conformance adapters — a certification project we've struggled with for years."*

**Workflow Sketch:**

```
┌─────────────────────────────────────────────────────────────┐
│ KNOWLEDGE BUILDING (automated)                              │
├─────────────────────────────────────────────────────────────┤
│ Slash command: /build-tmforum-knowledge                     │
│                                                             │
│ AI reads and indexes:                                       │
│ • TMForum API specifications (Open APIs)                    │
│ • TMForum conformance requirements                          │
│ • Required data models and schemas                          │
│ • Certification criteria and test cases                     │
└─────────────────────────────────────────────────────────────┘
            │
            ▼
┌─────────────────────────────────────────────────────────────┐
│ API ANALYSIS (automated)                                    │
├─────────────────────────────────────────────────────────────┤
│ Slash command: /analyze-iqmetrix-apis                       │
│                                                             │
│ AI reads from developers.iqmetrix.com:                      │
│ • Current API endpoints                                     │
│ • Request/response schemas                                  │
│ • Authentication mechanisms                                 │
│ • Data models                                               │
└─────────────────────────────────────────────────────────────┘
            │
            ▼
┌─────────────────────────────────────────────────────────────┐
│ GAP MAPPING                                                 │
├─────────────────────────────────────────────────────────────┤
│ Slash command: /map-to-tmforum                              │
│                                                             │
│ AI produces:                                                │
│ • Mapping matrix: iQmetrix API ↔ TMForum API                │
│ • Gap analysis: What's missing, what needs transformation   │
│ • Conformance score by API category                         │
│ • Priority ranking for certification path                   │
└─────────────────────────────────────────────────────────────┘
            │
            ▼
┌─────────────────────────────────────────────────────────────┐
│ ADAPTER GENERATION                                          │
├─────────────────────────────────────────────────────────────┤
│ Slash command: /generate-adapter [API_NAME]                 │
│                                                             │
│ AI generates:                                               │
│ • Adapter code that transforms iQmetrix → TMForum format    │
│ • Test cases for the adapter                                │
│ • Documentation for the mapping                             │
└─────────────────────────────────────────────────────────────┘
```

**Tools:** Claude Code with custom slash commands, MCP servers for API access

**Time Savings:** Months of manual work → Days to weeks

**Why Demo This:**
- Real business problem iQmetrix has struggled with
- Shows the ceiling of what's possible
- Demonstrates compound workflows (multiple slash commands building on each other)
- "A PM with enough curiosity could have done this" — inspires them to think bigger
- Transitions naturally to "what could YOU automate?"

**Demo Script:** See detailed playbook below.

---

## Workflow 12: Custom Learning Path Generation

**User Story:** *"As a PM, I need a learning path for a specific topic and I want a custom learning plan that leverages information from all potential sources so I can get to a respectable level in just a few days."*

**Workflow Sketch:**

```
┌─────────────────────────────────────────────────────────────┐
│ DEFINE LEARNING GOAL                                        │
├─────────────────────────────────────────────────────────────┤
│ Prompt: "I need to learn [TOPIC] well enough to:            │
│ • [Specific goal 1: e.g., lead a stakeholder discussion]    │
│ • [Specific goal 2: e.g., evaluate vendor proposals]        │
│ • [Specific goal 3: e.g., write requirements]               │
│                                                             │
│ Time available: [X days/hours]                              │
│ My current level: [beginner/some familiarity/etc.]          │
│ Learning style preference: [reading/video/hands-on/mixed]"  │
└─────────────────────────────────────────────────────────────┘
            │
            ▼
┌─────────────────────────────────────────────────────────────┐
│ AI GENERATES LEARNING PLAN                                  │
├─────────────────────────────────────────────────────────────┤
│ "Create a structured learning plan that includes:           │
│ 1. Core concepts I must understand (priority order)         │
│ 2. Best resources for each concept:                         │
│    - Articles/blogs (with URLs)                             │
│    - YouTube videos or courses                              │
│    - Podcasts or audio content                              │
│    - Books or longer reads (if time permits)                │
│ 3. Hands-on exercises to cement understanding               │
│ 4. Knowledge checks — questions I should be able to answer  │
│ 5. Time estimates for each section                          │
│                                                             │
│ Total should fit within my [X days] timeframe."             │
└─────────────────────────────────────────────────────────────┘
            │
            ▼
┌─────────────────────────────────────────────────────────────┐
│ CURATE & VALIDATE                                           │
├─────────────────────────────────────────────────────────────┤
│ AI searches for and validates:                              │
│ • Current, high-quality sources (not outdated)              │
│ • Mix of formats matching your learning style               │
│ • Progressive difficulty (foundational → advanced)          │
│ • Reputable authors/creators in the space                   │
│                                                             │
│ You review and adjust based on what's accessible to you.    │
└─────────────────────────────────────────────────────────────┘
            │
            ▼
┌─────────────────────────────────────────────────────────────┐
│ TRACK & SYNTHESIZE                                          │
├─────────────────────────────────────────────────────────────┤
│ As you learn, use AI to:                                    │
│ • Summarize key takeaways from each resource                │
│ • Connect concepts across different sources                 │
│ • Quiz you on what you've learned                           │
│ • Identify gaps: "Based on my goals, what am I missing?"    │
│ • Generate a one-pager summary of your learning             │
└─────────────────────────────────────────────────────────────┘
```

**Example Prompt:**

> "I need to learn about **API design best practices** well enough to:
> - Review our team's API proposals intelligently
> - Have informed conversations with our platform architects
> - Understand trade-offs in REST vs GraphQL decisions
>
> Time available: 3 days (about 2-3 hours per day)
> Current level: I understand what APIs are, but not design principles
> Learning style: Mix of reading and short videos, no long courses
>
> Create a day-by-day learning plan with specific resources."

**Tools:** Claude.ai or ChatGPT with web search enabled

**Time Savings:** Weeks of scattered learning → Focused 2-3 day sprint with clear outcomes

**Key Insight:** The AI doesn't just list resources — it sequences them, estimates time, and creates checkpoints. You're not just learning; you're learning *efficiently* toward a specific goal.

**Pro Tips:**
- Be specific about your goals — "understand enough to ask good questions" is different from "be able to implement"
- Ask for a "Day 1 checkpoint" — questions you should be able to answer after the first day
- Use the synthesis step to create shareable artifacts (one-pagers, glossaries) that prove your learning

---

## Workflow 14: Creating Reusable Skills

**User Story:** *"As a PM, I want to encode my expertise into reusable Skills so Claude applies my standards automatically every time, without me having to re-explain."*

**What Are Skills?**

A **Skill** is a markdown file that teaches Claude how to do something specific. Once created, Claude automatically detects when the skill is relevant and applies it — no manual invocation needed.

**Generic Concept:** Any expertise you repeat can become a skill:
- Your interview synthesis method
- Your PRD review checklist
- Your stakeholder communication format
- Your competitive analysis framework

**Anthropic's Implementation:** Skills are SKILL.md files stored in `.claude/skills/` (project-level, shared with team) or `~/.claude/skills/` (personal, available everywhere).

**Workflow Sketch:**

```
┌─────────────────────────────────────────────────────────────┐
│ IDENTIFY REPEATABLE EXPERTISE                               │
├─────────────────────────────────────────────────────────────┤
│ Ask yourself:                                               │
│ • What do I explain to Claude repeatedly?                   │
│ • What standards do I apply manually every time?            │
│ • What would I want a junior PM to always remember?         │
│                                                             │
│ Examples:                                                   │
│ • "When synthesizing interviews, always look for..."        │
│ • "PRDs must include these sections..."                     │
│ • "Azure DevOps stories should be formatted like..."        │
└─────────────────────────────────────────────────────────────┘
            │
            ▼
┌─────────────────────────────────────────────────────────────┐
│ WRITE THE SKILL FILE                                        │
├─────────────────────────────────────────────────────────────┤
│ Create: .claude/skills/interview-synthesis/SKILL.md         │
│                                                             │
│ ---                                                         │
│ name: interview-synthesis                                   │
│ description: Synthesizes customer interviews using our      │
│   research framework, identifying themes, contradictions,   │
│   and actionable quotes for product decisions               │
│ ---                                                         │
│                                                             │
│ # Interview Synthesis Skill                                 │
│                                                             │
│ When synthesizing customer interviews, always:              │
│                                                             │
│ 1. **Identify themes** by frequency (3+ mentions = theme)   │
│ 2. **Flag contradictions** between participants             │
│ 3. **Extract quotes** that best illustrate each theme       │
│ 4. **Note participant context** (role, company size, etc.)  │
│ 5. **Recommend next steps** based on patterns               │
│                                                             │
│ ## Output Format                                            │
│ - Executive summary (3 sentences max)                       │
│ - Theme table with evidence count                           │
│ - Top 5 quotes with attribution                             │
│ - Contradictions section                                    │
│ - Recommended actions                                       │
└─────────────────────────────────────────────────────────────┘
            │
            ▼
┌─────────────────────────────────────────────────────────────┐
│ SKILL AUTO-APPLIES                                          │
├─────────────────────────────────────────────────────────────┤
│ Next time you ask Claude to synthesize interviews:          │
│                                                             │
│ "Synthesize these 6 customer interviews"                    │
│                                                             │
│ Claude detects the skill matches based on description,      │
│ loads it automatically, and applies your framework.         │
│                                                             │
│ No need to re-explain. Consistent output every time.        │
└─────────────────────────────────────────────────────────────┘
```

**Example Skills for PMs:**

| Skill Name | Description | What It Encodes |
|------------|-------------|-----------------|
| interview-synthesis | Synthesize customer interviews | Your research framework, quote selection criteria |
| prd-reviewer | Review PRDs for completeness | Your checklist, common gaps to flag |
| ado-story-creator | Create Azure DevOps stories | Your template, field mappings, acceptance criteria format |
| competitive-analysis | Analyze competitor products | Your framework, comparison dimensions |
| meeting-summarizer | Summarize meeting notes | Your format, action item extraction rules |
| launch-planner | Plan product launches | Your phased approach, checklist, risk categories |

**Tools:** Claude Code, Claude Desktop, or Claude.ai (Pro/Team/Enterprise plans)

**Time Savings:** 5-10 minutes per task (no re-explaining) + consistent quality

**Key Insight:** Skills are how you scale your expertise. Instead of being the bottleneck who "knows how we do things," you encode that knowledge once and Claude applies it for anyone on the team.

**The Skill Creation Pattern:**

```
1. Notice you're repeating yourself  →  "I keep explaining our PRD format"
2. Write it as instructions         →  Create SKILL.md with your standards
3. Let Claude auto-apply            →  Consistent output without reminders
4. Iterate based on gaps            →  Add to the skill when you spot issues
```

**Pro Tips:**
- **Start with descriptions** — Claude uses the description to decide when to apply your skill. Be specific: "Synthesizes customer interviews for product decisions" beats "Helps with interviews"
- **Include examples** — Show Claude what good output looks like
- **Commit to version control** — `.claude/skills/` in your repo means the whole team benefits
- **Compose multiple skills** — You can have an interview-synthesis skill AND a stakeholder-summary skill; Claude applies both when relevant

---

# PART 3: RECOMMENDED DEMOS & PLAYBOOKS

## Demo Selection Rationale

| #   | Demo                    | Tool                       | Why Demo This                                |
| --- | ----------------------- | -------------------------- | -------------------------------------------- |
| 1   | Deep Research           | ChatGPT                    | "Set and forget" async — easy entry point    |
| 2   | Interview Synthesis     | Claude.ai                  | Voice input, relatable to all PMs            |
| 3   | Meeting Notes → Actions | Claude.ai + M365 Connector | Uses their existing tools (SharePoint)       |
| 4   | Querying Data           | Claude.ai + Databricks     | Directly relevant to Luzmo dashboard project |
| 5   | Roadmap Updates         | Claude Desktop + Aha!/ADO  | Shows the ceiling with multi-tool workflows  |

**Progression:** Async research → Interactive prompting → Connected workflows → Multi-tool orchestration

---

## Demo Playbook 0: Deep Research — Kick Off Before Session (2 minutes live)

### Setup Before Session
- Have ChatGPT Plus/Pro account ready
- Prepare a research question relevant to iQmetrix (see example below)
- **IMPORTANT:** Kick off the research 20-30 min before the session so results are ready

### Script

**[KICK OFF — shown live, 2 min]**

> "Let me start with something different. This isn't interactive chat — it's 'set it and forget it' AI.
>
> I'm going to ask ChatGPT to do deep research on a topic. It will spend 15-30 minutes searching dozens of sources, reading full articles, and synthesizing a report. I kicked one off before this session — let me show you what I asked."

*Show the prompt you used:*

> "Research the current state of AI-powered inventory optimization in retail POS systems. Cover:
> - Key vendors and their technical approaches
> - What accuracy and ROI metrics retailers are reporting
> - Integration patterns with existing POS systems
> - Risks and failure modes to watch for
>
> Produce a report suitable for a product leadership audience."

**[SHOW RESULTS — 3 min, later in session or at end]**

> "Here's what came back..."

*Show the report structure — table of contents, executive summary, detailed sections, citations*

> "This would have taken me a day or two of research. The AI did it in 20 minutes while I was doing other things.
>
> The quality isn't perfect — you still need to verify claims and add your judgment. But as a starting point? This is hours of work saved."

**Key Talking Points:**
- Different from interactive chat — you can close the tab and come back
- Quality rivals a junior analyst's first pass
- Great for competitive research, market analysis, technical deep dives
- Available to anyone with ChatGPT Plus ($20/mo)

---

## Glimpse: Claude Code / Cowork (2 minutes, after Demo 4)

### Purpose
Show the "ceiling" — full automation with reusable Skills — without spending time on it.

### Script

> "Before we move to talking about products, let me show you where this all goes if you want full automation."

*Flash Claude Code in terminal or Claude Cowork GUI (screenshot or live)*

> "This is Claude Code — or the new Claude Cowork for non-coders. Same AI, but it can:
> - Read and write files on your computer
> - Run commands
> - Execute multi-step workflows automatically
> - **Apply Skills you've created** — reusable expertise that runs automatically
>
> Remember the TMForum certification project? This is how you'd build something like that — custom automation that runs across your entire workflow.
>
> We're not covering this today, but I wanted you to see the ceiling. If you're curious, we can do a follow-up session."

*Show one quick example — Claude Code creating a file or Cowork managing a folder*

> "Anthropic just launched Cowork last week — it's basically Claude Code with a visual interface. Same power, no terminal required. Available on Mac for Claude Max subscribers."

**The Power of Skills:**

> "One more thing — Skills. Remember I mentioned these earlier? Here's where they really shine.
>
> A Skill is a markdown file that teaches Claude how to do something specific. Once you create a Skill, Claude automatically applies it whenever relevant.
>
> For example, if I create a 'PM Interview Synthesis' skill with my preferred format, themes to look for, and quote selection criteria — Claude applies that every time I ask it to synthesize interviews. No re-explaining. No forgetting details. Consistent output every time.
>
> This is how you scale your expertise. Write it once, use it forever."

**Key Points:**
- This is the "full automation" end of the progression
- Not for everyone, but shows what's possible
- Cowork makes it accessible to non-technical users
- **Skills** let you encode and reuse your expertise
- Offer follow-up for interested folks

---

## Demo Playbook 1: Interview Synthesis (10 minutes)

### Setup Before Session
- Prepare 2-3 fake interview transcripts (or use sanitized real ones)
- Have MacWhisper or Claude mobile app ready
- Have Claude.ai open in browser

### Script

**[SETUP — 1 min]**

> "Let's start with something every PM does: synthesizing customer interviews.
>
> I've got three interview transcripts here — about 45 minutes of conversations with store managers about their inventory challenges.
>
> Normally, I'd spend 2-3 hours reading through these, highlighting themes, organizing quotes. Let me show you a faster way."

**[VOICE CAPTURE DEMO — 3 min]**

> "First, I'm going to show you voice input. Instead of typing a long prompt, I'll just talk."

*Open MacWhisper or Claude mobile*

> "Watch this..."

*Speak naturally:*
> "I just did three interviews with store managers about inventory. The first was with Sarah at the downtown location — she mentioned the inventory count takes her 2 hours every morning and she wishes she could do it from her phone. The second was with Marcus who said his biggest frustration is when the system shows stock that's actually missing. The third was with Jennifer who actually loved the current system but wished it could predict when she'd run low on popular items."

*Show the transcription*

> "Thirty seconds of talking, and I've captured the key points. Now let's feed this to Claude."

**[AI SYNTHESIS — 4 min]**

*Paste transcription into Claude with this prompt:*

> "I conducted 3 customer interviews about inventory management. Here are my notes: [paste]
>
> Synthesize these into:
> 1. Top themes by frequency
> 2. Contradictions or tensions between participants
> 3. The most compelling quote for each theme
> 4. Recommended next steps for product"

*Show the output*

> "In 30 seconds, I have a structured synthesis. Notice it caught that Jennifer contradicts the others — she likes the system. That's the kind of thing you might miss when you're deep in the transcripts."

**[KEY TAKEAWAY — 2 min]**

> "Two things I want you to notice:
>
> First, voice input. I didn't carefully compose a prompt — I just talked. This is how you brainstorm with AI. Think out loud.
>
> Second, the AI found patterns I might have missed. It's not replacing my judgment — it's giving me a better starting point.
>
> Now imagine doing this with 20 interviews. Same process, same 30 seconds of synthesis. That's the leverage."

---

## Demo Playbook 2: Meeting Notes → Actions with M365 Connector (10 minutes)

### Setup Before Session
- Have Claude.ai open with M365 connector already authenticated
- Ensure there are meeting notes in a SharePoint location you can access
- Have the Confluence page or Azure DevOps board open for showing where outputs would go

### Script

**[SETUP — 1 min]**

> "Now let me show you what 'AI connected to your tools' really means.
>
> You're all using M365. Meeting notes live in SharePoint or OneDrive. Right now, synthesizing those notes means opening each doc, reading through, and manually extracting action items.
>
> Claude can now read directly from your SharePoint. Watch this."

**[SHOW THE CONNECTION — 2 min]**

*Show the Claude.ai settings with M365 connector*

> "I've connected Claude to my Microsoft 365 account. This is a one-time setup — takes about 2 minutes. Claude now has read access to SharePoint, OneDrive, and Outlook.
>
> Important: it respects your permissions. If you can't see a document, neither can Claude."

**[LIVE QUERY — 4 min]**

*In Claude.ai:*

> "Find the meeting notes from last week's sprint planning meeting in our team SharePoint"

*Show Claude searching and finding the document*

> "It found the document without me uploading anything. Now let me ask for synthesis."

*Type:*
> "Based on these meeting notes:
> 1. List all decisions that were made
> 2. Extract action items with owners
> 3. Identify any open questions that need follow-up
> 4. Create a 3-sentence summary for stakeholders who weren't there"

*Show the structured output*

> "In 30 seconds, I have a structured summary. Decisions, action items with names attached, open questions flagged."

**[BRIDGE TO M365 COPILOT — 2 min]**

> "Some of you are thinking: 'Copilot does this too.' And you're right — Copilot is great for summarizing a single meeting.
>
> The difference: Claude can pull from multiple sources at once. Watch..."

*Type:*
> "Now also find any emails from this week that reference the sprint planning decisions, and flag any conflicts or changes"

> "Claude just cross-referenced SharePoint docs with Outlook emails. That's harder to do in Copilot today."

**[KEY TAKEAWAY — 1 min]**

> "The pattern here: AI that reads from your systems, not just documents you upload. This is where things are heading — AI embedded in your workflow, not alongside it."

---

## Demo Playbook 3: Querying Data with Databricks Connector (10 minutes)

### Setup Before Session
- Have Claude.ai open with Databricks connector already authenticated
- Know which tables/datasets are available and have interesting data
- Prepare 2-3 business questions that would resonate with the audience
- Have Luzmo open in another tab to show the connection to their dashboard project

### Script

**[SETUP — 1 min]**

> "Now let's talk about something directly relevant to a project many of you are involved in — the Luzmo dashboards.
>
> Before you can build great dashboards, you need to explore the data. What metrics matter? What patterns exist? Normally that means writing SQL or waiting for an analyst.
>
> Claude can now query your Databricks directly. Watch."

**[SHOW THE CONNECTION — 1 min]**

*Show Claude.ai settings with Databricks connector*

> "I've connected Claude to our Databricks workspace. It can see the tables in Unity Catalog — but only the ones I have permission to access. Same security model you're used to."

**[FIRST QUERY — 3 min]**

*In Claude.ai:*

> "What tables do we have related to sales transactions?"

*Show Claude listing available tables*

> "It can see the schema. Now let me ask a business question."

*Type:*
> "What were our top 10 selling product categories last quarter, and how do they compare to the same quarter last year?"

*Show Claude generating SQL, running it, returning results*

> "Claude wrote the SQL, ran it against Databricks, and gave me the results. I didn't write a single line of code."

**[EXPLORATORY FOLLOW-UP — 3 min]**

> "But here's where it gets interesting. I can explore naturally..."

*Type:*
> "That's interesting — Category X dropped significantly. Can you break that down by region to see if it's widespread or concentrated?"

*Show the follow-up query and results*

> "And now..."

*Type:*
> "What promotions were running in the regions where Category X held steady? I want to understand what might have helped."

> "This is the kind of exploratory analysis that used to take hours of back-and-forth with an analyst. I just did it in 2 minutes."

**[KEY TAKEAWAY — 2 min]**

> "Two things I want you to notice:
>
> First, I'm not replacing analysts. I'm doing the exploratory work myself so when I go to them, I have specific, informed questions. 'Can you help me understand the correlation between promotions and category performance in Q3?' is a much better ask than 'Can you pull some data on sales?'
>
> Second, this connects directly to your Luzmo dashboard project. Before you build dashboards, you can explore what metrics actually matter. What questions do people ask? What patterns are interesting? Claude helps you discover that."

---

## Demo Playbook 4: Roadmap Updates with Aha! + Azure DevOps (10 minutes)

### Setup Before Session
- Have Claude Desktop installed with Aha! and Azure DevOps MCP servers configured
- Have an Aha! roadmap open showing features to update
- Have Azure DevOps board open showing work items
- Prepare a scenario: "Sprint ended, need to update roadmap and create follow-up work items"

### Script

**[CONTEXT — 2 min]**

> "Let me end with something that shows the ceiling of what's possible — and what you could build toward.
>
> This demo uses Claude Desktop instead of Claude.ai. The desktop app can connect to tools that don't have native web connectors yet — like Aha! and Azure DevOps.
>
> I'm going to update our product roadmap in Aha! and create work items in Azure DevOps, all from a single conversation."

**[SHOW THE SETUP — 1 min]**

*Show Claude Desktop with MCP servers listed*

> "I've connected two MCP servers: one for Aha!, one for Azure DevOps. This is a one-time setup — about 10 minutes if you're comfortable with configuration files.
>
> Now Claude can read from and write to both systems."

**[ROADMAP UPDATE — 3 min]**

*In Claude Desktop:*

> "Check the Aha! roadmap for our Inventory Management initiative. What features are marked as 'In Development'?"

*Show Claude pulling feature list from Aha!*

> "Now let me update based on what actually shipped..."

*Type:*
> "Update the 'Automated Reorder Suggestions' feature to 'Shipped' status, set the release date to last Friday, and add a note: 'Launched to 50 pilot stores, full rollout in 2 weeks.'"

*Show the update happening*

> "The Aha! roadmap is updated. No copy-paste, no context switching."

**[CROSS-SYSTEM WORKFLOW — 3 min]**

> "But here's where it gets powerful. I can work across systems..."

*Type:*
> "Based on the pilot feedback notes in that Aha! feature, create Azure DevOps user stories for the top 3 improvement areas. Put them in the Inventory sprint backlog."

*Show Claude reading from Aha!, creating items in Azure DevOps*

> "Claude just read the feedback from Aha!, extracted themes, and created work items in Azure DevOps. Two systems, one conversation."

**[KEY TAKEAWAY — 1 min]**

> "This is where things are heading. Not AI that works in one tool — AI that orchestrates across your entire workflow.
>
> Today this requires some setup. But the pattern is clear: describe what you want done across your systems, and AI executes.
>
> For PMs, this is huge. We're the connective tissue between tools. If AI can handle that integration work, we can focus on the judgment calls that actually matter."

**[REALISTIC NEXT STEPS]**

> "I want to be honest: this setup takes some technical comfort. But once it's configured, anyone can use it.
>
> If this is interesting, we can do a follow-up session on setting up Claude Desktop with your specific tools. The investment is about an hour of setup for hours of ongoing savings."

---

# PART 4: BUILDING AI INTO iQMETRIX PRODUCTS (10 minutes)

## Slide: From Personal Use to Product Decisions

**SLIDE TITLE:** Now Let's Talk About Your Products

**CONTENT:**

You've just experienced AI as a user. Now let's flip perspectives.

> "Every interaction you had today — the prompting, the connectors, the context — those are product decisions when *you're* the one building."

**The Questions to Ask:**
1. Where does AI show up? (Interface)
2. What can users control? (Configuration)
3. What context does AI need? (Data)
4. What stays hidden? (System prompts, guardrails)

---

## Slide: AI Interface Patterns

**SLIDE TITLE:** Where Does AI Show Up?

**CONTENT:**

| Pattern                   | Example                                | When to Use                             |
| ------------------------- | -------------------------------------- | --------------------------------------- |
| **Chat interface**        | Claude.ai, ChatGPT, your RAG Slack bot | Open-ended exploration, complex queries |
| **Embedded assistant**    | M365 Copilot in Word                   | Task-specific help in context           |
| **Proactive suggestions** | "Did you mean...?", auto-complete      | Low-friction, predictable tasks         |
| **Background agent**      | ChatGPT Deep Research                  | Long-running tasks, async results       |
| **Messaging channels**    | Slack bot, email assistant             | Where users already work                |

**Key Insight:**
> Chat isn't always the answer. The best AI features meet users where they are.

**iQmetrix Examples:**
- Store manager asking Slack bot about inventory levels (chat)
- POS suggesting upsell items during checkout (proactive)
- Email digest of daily anomalies (background agent + messaging)

**SPEAKER NOTES:**
The RAG Slack bot you've built is a great example — it's in Slack because that's where your users already are. The interface choice is a product decision.

---

## Slide: The Configuration Space

**SLIDE TITLE:** What Can Users Control?

**CONTENT:**

Every AI feature has knobs. Deciding which knobs to expose is a product decision.

| Configuration             | User Benefit          | Risk if Exposed          |
| ------------------------- | --------------------- | ------------------------ |
| **Tone/style**            | Personalization       | Inconsistent brand voice |
| **Output format**         | Flexibility           | Analysis paralysis       |
| **Data sources**          | Relevance             | Security/privacy         |
| **Confidence thresholds** | Control over accuracy | Complexity               |
| **Action permissions**    | Safety                | Friction                 |

**The Spectrum:**
```
Fully automated          ←→          Fully user-controlled
(Simple, opinionated)                (Flexible, complex)
```

**Rule of Thumb:**
> Start opinionated. Add configuration when users ask for it — not before.

**SPEAKER NOTES:**
This is where PM judgment matters. Too many options overwhelm users. Too few frustrate power users. Watch what people actually try to do, then expose controls for that.

---

## Slide: Skills — Encoding Expertise for Your Users

**SLIDE TITLE:** Skills: Reusable Expertise at Scale

**CONTENT:**

**The Challenge:**
- Users have to re-explain their context every session
- Institutional knowledge lives in people's heads
- Inconsistent outputs when different people prompt differently

**The Solution: Skills**

A Skill encodes expertise so AI applies it automatically:

| Without Skills | With Skills |
|----------------|-------------|
| User explains their format each time | Format encoded once, applied always |
| Quality varies by who's prompting | Consistent output for everyone |
| New team members start from scratch | Expertise transfers instantly |
| You're the bottleneck for "how we do it" | AI applies your standards for you |

**iQmetrix Examples:**
- **Support Skill:** "When answering RQ questions, always check the knowledge base first, cite specific articles, and escalate if confidence is low"
- **API Review Skill:** "When reviewing API designs, check for TMForum alignment, security requirements, and versioning standards"
- **Customer Comms Skill:** "When drafting customer communications, use our brand voice, avoid jargon, and include relevant support links"

**For Product Teams:**
Skills aren't just for personal use — they're a product pattern. Consider: what expertise could your *product* encode as Skills for your *users*?

---

## Slide: Context vs. Concealment

**SLIDE TITLE:** What Does AI See? What Stays Hidden?

**CONTENT:**

**What Users Provide (Context):**
- Their documents, data, queries
- Preferences and settings
- Conversation history

**What You Provide (Concealed):**
- System prompts (instructions, persona, guardrails)
- Task-specific prompts (how to format output)
- Safety rails and filters
- Tool definitions and capabilities
- **Skills** (reusable expertise packages)

**Example Architecture:**
```
┌─────────────────────────────────────────────────┐
│ SYSTEM PROMPT (hidden from user)                │
│ "You are a retail inventory assistant.          │
│  Never recommend products we don't carry.       │
│  Always cite data sources. Be concise."         │
├─────────────────────────────────────────────────┤
│ USER CONTEXT (provided by user)                 │
│ Store ID, role, recent queries, uploaded docs   │
├─────────────────────────────────────────────────┤
│ USER QUERY                                      │
│ "What should I reorder this week?"              │
└─────────────────────────────────────────────────┘
```

**Why This Matters:**
- System prompts control behavior without user effort
- Guardrails prevent harmful/wrong outputs
- Users shouldn't see the "machinery" — just the results

**SPEAKER NOTES:**
This is how your RAG bot works. Users ask questions; the system prompt tells Claude how to behave, what sources to use, how to format answers. Users never see that layer — and they shouldn't have to.

---

## Slide: Quick Framework for AI Feature Decisions

**SLIDE TITLE:** When Someone Says "Let's Add AI to X"

**CONTENT:**

**Ask These Questions:**

1. **Is this a good fit for AI?**
   - Pattern recognition, synthesis, generation → Yes
   - Novel judgment, high stakes, no room for error → Careful

2. **Where does it show up?**
   - Chat, embedded, proactive, background, messaging?

3. **What context does it need?**
   - User data? System data? External data?

4. **What can users control?**
   - Start minimal, add based on feedback

5. **What do we hide?**
   - System prompts, guardrails, sensitive logic

6. **What does failure look like?**
   - Annoying but recoverable? → Ship it
   - Trust-breaking or costly? → More guardrails

**SPEAKER NOTES:**
This is the lens to use when evaluating AI features. You now have intuition from using these tools yourself — apply that same intuition to product decisions.

---

# PART 5: CLOSING & NEXT STEPS

## Slide: The PM AI Toolkit (Summary)

**SLIDE TITLE:** Your AI Toolkit

**CONTENT:**

**Start Here (This Week):**
- ChatGPT Deep Research — Async research that runs while you work
- Claude.ai — Thinking partner for synthesis, brainstorming, analysis
- M365 Copilot — In-context help in Word, Excel, Teams (you have this!)

**Add Connectors (When Ready):**
- Claude.ai + M365 Connector — Read from SharePoint, OneDrive, Outlook
- Claude.ai + Databricks — Query your data with natural language

**Power User Path:**
- Claude Desktop + Aha!/Azure DevOps — Multi-system workflows
- Claude Code — Full automation, custom workflows (terminal-based)
- Claude Cowork — Same power as Claude Code, GUI for non-coders (new!)
- **Skills** — Encode your expertise into reusable markdown files that Claude auto-applies

**The Progression:**
```
Thinking partner  →  Connected tools  →  Multi-system  →  Full automation
(Claude.ai)          (Connectors)        (Desktop)        (Code/Cowork)
```

**What We Showed Today:**
1. ✅ Thinking partner (interview synthesis)
2. ✅ Connected tools (M365, Databricks)
3. ✅ Multi-system (Aha! + Azure DevOps)
4. 👀 Glimpse of full automation (Claude Code/Cowork)

---

## Slide: Evaluating AI for Your Products

**SLIDE TITLE:** When You're Evaluating AI for iQmetrix Products

**CONTENT:**

**Questions to Ask:**

1. **Is this a task AI is actually good at?**
   - Pattern recognition? ✓
   - Data synthesis? ✓
   - Novel judgment? ✗

2. **What does failure look like?**
   - Annoying but recoverable? → Ship it
   - Costly or trust-breaking? → More guardrails needed

3. **Do users trust AI for this?**
   - High-stakes decisions need human confirmation
   - Routine tasks can be more autonomous

4. **What's the evaluation plan?**
   - Start with spreadsheets
   - Graduate to automated evals
   - Always have a feedback loop

**Remember:** Domain expertise > AI expertise. Your POS knowledge matters more than knowing how transformers work.

---

## Slide: Next Steps

**SLIDE TITLE:** Where to Go From Here

**CONTENT:**

**This Week:**
- [ ] Try ChatGPT Deep Research on a topic you're exploring
- [ ] Set up Claude.ai account (free tier works for basics)
- [ ] Connect the M365 connector if you have Claude Pro/Team

**This Month:**
- [ ] Explore the Databricks connector for your dashboard project questions
- [ ] Build one reusable workflow for a recurring task
- [ ] Share what's working in your team channel

**If You Want to Go Deeper:**
- Claude Pro ($20/mo) or Team plan enables connectors
- Follow-up session: Setting up Claude Desktop with Aha!/Azure DevOps
- Follow-up session: Evaluating AI features for iQmetrix products
- Office hours for individual workflow design

**Resources:**
- This playbook (reference any time)
- Claude.ai connectors docs: claude.com/connectors
- Azure DevOps MCP: github.com/microsoft/azure-devops-mcp
- Databricks MCP docs: docs.databricks.com

---

## Slide: Q&A

**SLIDE TITLE:** Questions?

**DISCUSSION PROMPTS:**

- Which workflow would save you the most time?
- What's a task you do repeatedly that feels like it could be automated?
- Where do you see AI fitting into iQmetrix products?
- What concerns do you have about adopting AI in your workflow?

---

# APPENDIX: Session Logistics

## Session Structure (60 minutes)

| Time  | Section              | Content                                           |
| ----- | -------------------- | ------------------------------------------------- |
| 0-10  | Mental Models        | Slides 1-4: Framing, two modes, user stories      |
| 10-12 | Demo 0               | Deep Research kick-off (show prompt)              |
| 12-20 | Demo 1               | Interview Synthesis (thinking partner mode)       |
| 20-28 | Demo 2               | Meeting Notes → Actions (M365 connector)          |
| 28-36 | Demo 3               | Querying Data (Databricks connector)              |
| 36-40 | Demo 4               | Roadmap Updates (Aha! + ADO — can be screenshots) |
| 40-42 | Demo 0 Results       | Show Deep Research results + Claude Code glimpse  |
| 42-52 | Building AI Products | Interface, config, context, framework             |
| 52-57 | Closing              | Toolkit summary, next steps                       |
| 57-60 | Q&A                  | Quick questions                                   |

**Pacing Notes:**
- Demos are tight — have backup screenshots ready
- Skip Demo 4 live if running behind; show screenshots instead
- Building AI Products section is the payoff — don't cut it

## Pre-Session Checklist

- [ ] Kick off ChatGPT Deep Research 30 min before session starts
- [ ] Confirm Claude.ai account with M365 + Databricks connectors working
- [ ] Test Claude Desktop with Aha! + Azure DevOps MCP servers (or prep screenshots)
- [ ] Prepare sanitized interview transcripts for synthesis demo
- [ ] Ensure SharePoint has accessible meeting notes for M365 demo
- [ ] Know which Databricks tables have interesting demo data
- [ ] Have Aha! roadmap with features ready to update
- [ ] Prep Claude Code or Cowork screenshot/quick video for "glimpse" moment
- [ ] Test screen sharing and audio setup
- [ ] Send pre-read: "Come with one task you do repeatedly that feels tedious"

## Post-Session Materials

- [ ] Share this playbook document
- [ ] Provide links to recommended tools
- [ ] Set up Slack channel for questions / sharing wins
- [ ] Schedule optional follow-up sessions

---

*Document created: December 2025*
*Advisor: Waleed Ayoub*
*Partner: Lauren*
