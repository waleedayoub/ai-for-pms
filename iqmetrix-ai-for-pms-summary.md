# AI for Product Managers: Workshop Summary
**iQmetrix | 60-Minute Session**

---

## Workshop Goal

Help PMs build AI intuition through hands-on examples, then apply that intuition to iQmetrix product decisions.

---

## Session Flow (60 min)

| Section | Time | What We Cover |
|---------|------|---------------|
| Mental Models | 10 min | Two modes: "Thinking Partner" + "Task Automator" |
| Live Demos | 30 min | 5 PM workflows with AI (starred below) |
| Building AI Products | 10 min | Interface patterns, configuration, context vs concealment |
| Closing + Q&A | 10 min | Toolkit summary, next steps |

---

## The Two Modes (Core Mental Model)

| Mode | What It Does | Examples |
|------|--------------|----------|
| **Thinking Partner** | Brainstorms, researches, structures ideas, challenges assumptions | Interview synthesis, competitive analysis, feature ideation, launch planning |
| **Task Automator** | Executes across tools — reads, writes, updates, queries | Pull from SharePoint, query Databricks, update Aha!, create ADO work items |

---

## PM Workflows: Today vs. With AI

| # | User Story | Today | With AI | Tools | Time Saved |
|---|------------|-------|---------|-------|------------|
| ⭐1 | Research a topic deeply | Manual search, read articles, synthesize | AI searches dozens of sources, delivers report while you work | ChatGPT Deep Research | 1-2 days → 30 min |
| ⭐2 | Synthesize customer interviews | Read transcripts, highlight, organize themes manually | Upload transcripts, AI finds themes + contradictions + quotes | Claude.ai Projects | 3-4 hours → 30 min |
| 3 | Learn a new domain quickly | Google, read docs, take notes | AI creates structured learning plan with resources + quiz | Claude.ai | Days → 2 hours |
| 4 | Brainstorm feature ideas | Whiteboard session, solo thinking | AI generates options, critiques them, identifies risks | Claude.ai | Half-day → 45 min |
| ⭐5 | Explore data for product questions | Write SQL or wait for analyst | Ask questions in English, AI writes SQL, returns insights | Claude.ai + Databricks | Hours waiting → minutes |
| 6 | Turn PRD into work items | Write PRD, manually create tickets | AI extracts stories from PRD, creates in Azure DevOps | Claude Desktop + ADO MCP | 2-3 hours → 30 min |
| ⭐7 | Synthesize meeting notes into actions | Read notes, extract decisions, format | AI pulls from SharePoint, extracts decisions + action items | Claude.ai + M365 Connector | 1-2 hours → 10 min |
| 8 | Distribute meeting outputs | Copy to Slack, create tasks, update docs | AI routes to appropriate channels and tools | Claude Desktop + MCPs | 30-45 min → 5 min |
| 9 | Evaluate "should we add AI to X?" | Gut feel, ad-hoc analysis | Structured framework: capability fit, user value, failure modes | Claude.ai | Variable |
| 10 | Debug why AI feature gives wrong answers | Manual review of failure cases | AI categorizes failures, identifies patterns, suggests fixes | Claude.ai | Hours → 30 min |
| ⭐11 | Update roadmap + create follow-up work | Switch between Aha!, ADO, copy-paste | AI reads from Aha!, updates status, creates ADO work items | Claude Desktop + Aha!/ADO | 1-2 hours → 10 min |
| ⭐12 | **Build a plan to launch a new product** | Scattered docs, meetings, manual coordination | AI synthesizes context, drafts launch plan, identifies gaps | Claude.ai Projects | Days → hours |
| 13 | Create custom learning path | Search for resources, organize manually | AI curates resources, sequences them, creates checkpoints | Claude.ai | Weeks → days |
| 14 | **Create reusable Skills** | Re-explain standards every session | Encode expertise once, Claude applies it automatically | Claude Code/Desktop | 5-10 min/task saved |

**⭐ = Live demo in session**

---

## Tools We'll Show

| Tool | What It Does | Accessibility |
|------|--------------|---------------|
| ChatGPT Deep Research | Async research — runs while you do other things | ChatGPT Plus ($20/mo) |
| Claude.ai + Connectors | Thinking partner + reads from M365, Databricks | Claude Pro/Team |
| Claude Desktop + MCPs | Multi-system workflows (Aha!, Azure DevOps) | Free app + setup |
| Claude Code / Cowork | Full automation (glimpse only) | Pro/Max tiers |
| **Skills** | Reusable expertise that Claude auto-applies | Claude Code/Desktop |

---

## What Are Skills?

A **Skill** is a way to teach AI how to do something specific and reusable. Think of it as packaging your expertise into a format the AI can apply automatically.

**Generic Concept:** Any repeatable workflow, checklist, or standard you follow can become a skill — your interview synthesis method, your PRD template, your stakeholder communication format.

**Anthropic's Implementation:** In Claude Code and Claude Desktop, Skills are markdown files (SKILL.md) that Claude automatically applies when relevant. You describe *when* to use the skill and *how* to execute it — Claude handles the rest.

**Why Skills Matter for PMs:**

| Without Skills | With Skills |
|----------------|-------------|
| Re-explain your format each session | Format encoded once, applied always |
| Quality varies by who's prompting | Consistent output for everyone |
| New team members start from scratch | Expertise transfers instantly |

**Example Skills:**
- **Interview Synthesis:** Your research framework, quote selection criteria, output format
- **PRD Reviewer:** Your checklist, common gaps to flag, acceptance criteria standards
- **ADO Story Creator:** Your template, field mappings, how to write acceptance criteria
- **Meeting Summarizer:** Your format, action item extraction rules, stakeholder summary style

**The Skill Creation Pattern:**
```
1. Notice you're repeating yourself  →  "I keep explaining our PRD format"
2. Write it as instructions         →  Create SKILL.md with your standards
3. Let Claude auto-apply            →  Consistent output without reminders
4. Iterate based on gaps            →  Add to the skill when you spot issues
```

**Key Insight:** Skills are how you scale your expertise. Instead of being the bottleneck who "knows how we do things," you encode that knowledge once and Claude applies it for anyone on the team.

---

## Detailed Example: Planning the Visualize & Explore Launch

This demo uses a real iQmetrix project — the new Luzmo/Databricks analytics product launching Q4 2025.

### The Scenario

Ben is the PM for Visualize & Explore. He needs to build a launch plan that covers:
- Customer onboarding and migration from RQ Reports
- Internal training for support and sales
- Communications to different audiences
- Success metrics and rollout phases

### Today's Approach
- Review the SummitX presentation deck
- Dig through Confluence for past launch playbooks
- Schedule meetings with stakeholders to gather input
- Manually draft the plan in a doc
- **Time: 2-3 days of scattered work**

### With AI (Thinking Partner Mode)

**Step 1: Load Context into a Claude Project**
```
Upload to Claude.ai Project:
- SummitX presentation PDF
- Any existing launch playbooks
- Customer feedback from pilots
- Competitive intelligence on analytics tools
```

**Step 2: Have a Launch Planning Conversation**
```
"I'm launching Visualize & Explore, our new Databricks + Luzmo analytics
product. Based on the SummitX presentation and what you know about
data product launches:

1. What are the key workstreams I need to plan for?
2. What's missing from our current materials?
3. Draft a phased rollout plan
4. What are the riskiest assumptions we're making?"
```

**Step 3: AI Output**
- Structured launch plan with phases (pilot → early access → GA)
- Onboarding checklist based on the "Report → Visualize → Explore" journey
- Gap analysis: "You have technical architecture but no customer success metrics defined"
- Risk register: "Migration from RQ Reports needs clearer path"
- Draft communications for different audiences

**Step 4: Iterate**
```
"Good start. Now draft the customer email announcing early access,
emphasizing the AI-native 'text to visualization' capability."
```

### Time Saved
- **Before:** 2-3 days of context gathering + drafting
- **After:** 2-3 hours of focused conversation + refinement

### Why This Demo Works
- It's a **real project** the audience knows about
- Shows AI as **thinking partner** (not just task automation)
- Demonstrates **context loading** via Projects
- Output is **immediately useful** — not a toy example

---

## Building AI Products (10 min section)

We'll cover how to apply this intuition to iQmetrix products:

1. **Interface Patterns** — Chat isn't always the answer. Options: chat, embedded, proactive suggestions, background agents, messaging channels (Slack, email)

2. **Configuration Space** — What knobs to expose to users vs. keep hidden. Start opinionated, add flexibility based on feedback.

3. **Context vs. Concealment** — Users provide their data/queries. You provide system prompts, guardrails, tool definitions (hidden from users).

4. **Quick Framework** — 6 questions to ask when someone says "let's add AI to X"

---

## What Attendees Leave With

- Mental model: thinking partner + task automator
- Understanding of **Skills** — how to encode and reuse your expertise
- Hands-on experience seeing AI applied to their workflows
- Framework for evaluating AI features in iQmetrix products
- This playbook for self-study and experimentation

---

## Follow-Up Options

- Claude Desktop setup session (Aha! + Azure DevOps)
- AI feature evaluation deep dive
- Office hours for individual workflow design

---

*Prepared by Waleed Ayoub | January 2026*
