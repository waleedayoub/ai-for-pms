# iQmetrix AI for PMs — Project Context & Knowledge Export

**Purpose:** This document captures the full context from the initial brainstorming session to hydrate future agent conversations working on this project.

**Created:** December 2025
**Advisor:** Waleed Ayoub
**Client Partner:** Lauren (iQmetrix)

---

## Project Overview

### What This Is
A training workshop (potentially series) for Product Managers at iQmetrix to help them:
1. Build AI fluency through personal productivity use cases
2. Apply that intuition to evaluate AI opportunities for iQmetrix products

### The Key Insight
> "You can't design AI experiences you don't understand intuitively."

The path to **AI-informed product thinkers** (goal) runs through **AI-augmented personal productivity** (method). Start with hands-on experience, then layer on product evaluation frameworks.

---

## Audience Profile

**Who:** Product Managers at iQmetrix
**AI Maturity:** Mix of:
- **Beginners** — Dabbled with ChatGPT for personal use, don't systematically use AI for work
- **Practitioners** — Regularly use AI assistants for drafting/research, haven't built workflows
- **No one at advanced level** — Haven't built AI features or sophisticated personal workflows

**Tools Available:**
- M365 Copilot (company-provided)
- Claude.ai free tier (can sign up, no data sensitivity concerns for training exercises)
- No terminal/developer tools expected

**iQmetrix Context:**
- Retail/POS company — point of sale, inventory, retail operations software
- Existing AI work:
  - RAG-based Slack bot for diagnosing production incidents (internal)
  - Luzmo for customer-facing analytics/BI
  - Exploring Luzmo IQ (chat with your data agent)
- Long-running TMForum certification effort (Waleed built automation for this as advisor)

---

## Key Decisions Made

### Format
- **Initial session:** Single 60-90 minute workshop showcasing the full spectrum
- **Recommended follow-up:** Multi-session series going deeper on specific areas
- **Paid seats upsell:** Position hands-on agentic workflows as "next step with Claude Pro/Teams"

### Demo Approach
- **Mix of Waleed demos and participant hands-on**
- **Agentic capabilities = Waleed demos** (avoids terminal intimidation)
- **Prompting/voice = participant hands-on** (builds muscle memory)
- **Voice input included** — Using Whisper-based tools to lower barrier

### Scenario Types
- Mix of generic PM scenarios, Waleed's personal workflow examples (cleaned up for teaching), and iQmetrix-specific retail scenarios
- Personal examples need packaging — Waleed's current workflow is "too integrated" for education

### Structure Chosen
**Approach 3: Capability Layers** — Build from foundations → personal workflows → product thinking
- Session 1: AI Fluency (mental models, prompting, voice, tools landscape)
- Session 2: AI-Augmented PM (hands-on workflows across skill areas)
- Session 3: AI for Products (evaluation frameworks, architecture basics, iQmetrix applications)

For the single 60-90 min session: Show a taste of each layer through 11 user stories, demo 4 of them.

---

## PM Skill Areas Covered

1. **Research & Discovery** — Market research, competitor analysis, user interview synthesis
2. **Ideation & Prototyping** — Brainstorming features, writing specs, rapid prototyping concepts
3. **Product Ops & Governance** — Story/ticket creation, roadmap updates, status reporting, documentation
4. **Communication & Alignment** — Stakeholder updates, presentation creation, meeting prep/synthesis
5. **Data & Analysis** — Querying data, interpreting metrics, building dashboards/reports
6. **AI Product Evaluation** — Assessing where AI fits in your product, build vs. buy, understanding AI capabilities/limitations

---

## The 11 User Stories

### Discovery Phase
1. **Competitor Research** — "I need to understand what competitors are doing in AI-powered retail analytics so I can identify gaps and opportunities."

2. **Interview Synthesis** ⭐ DEMO — "I need to synthesize 6 customer interview transcripts into actionable themes so I can identify patterns."

3. **Rapid Domain Learning** — "I need to quickly get up to speed on a new domain (e.g., inventory optimization) so I can have informed conversations."

### Definition Phase
4. **Feature Ideation** — "I need to brainstorm feature ideas and explore different directions for a 'store manager copilot'."

5. **Vibe Coding Prototype** ⭐ DEMO — "I need to show my developers and designers what I have in mind with a real, interactive prototype that matches our brand."

6. **PRD → Jira Tickets (MCP)** — "I need to write a clear PRD and automatically create the Jira tickets from it."

### Delivery Phase
7. **Confluence/Aha Updates (MCP)** ⭐ DEMO — "I need to update our Confluence roadmap and Aha status documents based on what shipped this sprint."

8. **Meeting Synthesis** — "I need to synthesize my meeting notes into action items and share them with the team."

### AI Product Thinking
9. **AI Feature Evaluation** — "I need to evaluate whether we should add AI to our search feature so I can make a build/buy/skip recommendation."

10. **AI Debugging/Evals** — "I need to understand why our RAG bot sometimes gives wrong answers so I can improve it."

### Capstone
11. **TMForum Standards Automation** ⭐ DEMO — "I need to map our APIs to an industry standard (TMForum) and generate conformance adapters — a certification project we've struggled with for years."

---

## Demo Selection Rationale

| # | Workflow | Why Selected |
|---|----------|--------------|
| 2 | Interview Synthesis | Foundational, shows voice input, relatable to all PMs, clear before/after |
| 5 | Vibe Coding Prototype | Visual "wow" factor, shows AI creating real UI, brand consistency angle is sophisticated |
| 7 | MCP Artifact Updates | Shows AI *in* the workflow not alongside it, practical weekly task, MCP is the differentiator |
| 11 | TMForum Capstone | Shows the ceiling of what's possible, real iQmetrix business problem, inspires bigger thinking |

**Progression:** Basic prompting → Voice input → Tool integration → Compound workflows

---

## Resources Consulted & Key Insights

### Teresa Torres (Product Talk)
**Source:** producttalk.org articles on Claude Code

**Key Insights:**
- "How can Claude help with this?" at each step rather than automating everything at once
- Workflow design: Map the task → Identify augmentation points → Prototype → Refine
- Claude Code eliminates repetition, enables compound systems, parallelizes work
- "Using Claude Code isn't about being technical" — willingness to try 3-4 simple commands
- Treat AI workflow design like product discovery — systematic and exploratory

### 9 AI Product Teams Research (Product Talk)
**Source:** producttalk.org/learning-from-8-ai-product-teams/

**Key Insights:**
- **Small cross-functional teams win** — 2-3 person teams where members span disciplines
- **Domain expertise > AI expertise** — None started as AI specialists; POS knowledge matters more than knowing transformers
- **Start narrow, expand gradually** — Resist temptation to solve everything; build confidence through sequencing
- **Evals evolve from simple to sophisticated** — Everyone starts with spreadsheets, even eval tooling companies
- **Getting LLMs to say "I don't know" is hard** — Requires explicit guardrails, not prompt engineering alone
- **The integration maze never ends** — AI products depend on data from multiple systems

### Clare Vo "How I AI" Podcast
**Source:** youtube.com/@howiaipodcast (couldn't fetch directly)

**Context:** Interview-focused podcast on how leaders actually use AI in their workflows. Relevant for understanding real practitioner patterns.

### Waleed's India Workshop (GDPVal Content)
**Source:** workshops/india-workshop-november2025/kickoff-presentation-v2-slide-builder.md

**Reusable Content:**
- GDPVal study examples showing agents performing as well as human evaluators
- Retail demand forecasting comparison (Human: 2.5 hours, 15% MAPE vs Agent: 8 minutes, 14% MAPE)
- Root cause analysis example (10-14 days traditional vs 12 minutes agent)
- "Agent does the legwork → Human makes the call" framing
- Pattern: Agents excel at pattern recognition, hypothesis generation, multi-source synthesis; Humans excel at judgment, relationships, strategic decisions

---

## Tools Mentioned

### For Daily Work (Participant Hands-On)
- **Claude.ai** — Research, drafting, analysis (free tier generous)
- **ChatGPT** — Alternative to Claude
- **M365 Copilot** — In-context help in Word, Excel, Teams (they have this)
- **Voice input tools** — MacWhisper (Mac), Whisper.cpp browser tools, Claude mobile app

### For Prototyping (Demo + Optional Hands-On)
- **v0.dev** (Vercel) — Best for React/Next.js components, good free tier
- **Lovable** — Full app generation, good for multi-page flows
- **Bolt.new** — Quick prototypes, runs in browser
- **Figma Make** — Design-to-code from Figma files

### For Power Users (Waleed Demo Only)
- **Claude Code** — Terminal-based agentic coding, file management, automation
- **MCP servers** — Direct connection to Jira, Confluence, Slack, Aha!, etc.
- **GitHub Copilot** — Mentioned but more code-completion focused, not ideal for PM workflows

---

## Waleed's Relevant Experience

### Agent-Assist Repository
Waleed uses Claude Code daily for engineering leadership work at Daybreak:
- Meeting synthesis (Google Drive transcripts → Obsidian)
- Developer productivity analysis (Azure DevOps data → reports)
- Product updates (aggregating from Azure DevOps, Jira, Confluence)
- Planning documents
- Git workflow automation

**Challenge for teaching:** His workflow is "too integrated" — optimized for doing, not teaching. Needs "demo-ready" versions with clear before/during/after.

### TMForum Automation
Built a Claude Code workflow with slash commands for iQmetrix's TMForum certification:
- `/build-tmforum-knowledge` — Indexes TMForum API specs
- `/analyze-iqmetrix-apis` — Reads from developers.iqmetrix.com
- `/map-to-tmforum` — Creates mapping matrix, gap analysis
- `/generate-adapter [API]` — Generates conformance adapter code

**Key message:** "A PM with enough curiosity could have done this themselves."

### Vibe Coding Presentations
Has given presentations on vibe coding for non-developers to iQmetrix previously.

---

## Document Outputs

### Created
- `workshops/iqmetrix-ai-for-pms.md` — Full workshop document with:
  - 8 preamble slides
  - 11 workflow sketches
  - 4 detailed demo playbooks with speaker scripts
  - Closing slides and evaluation framework
  - Session timing guides (60-min and 90-min versions)
  - Pre-session and post-session checklists

### Still Needed
- Actual slide deck (PowerPoint/Google Slides/Keynote)
- Demo environment setup and testing
- Sanitized interview transcripts for Demo 1
- Brand assets for vibe coding demo (iQmetrix colors, style guide)
- TMForum demo outputs (can be screenshots if not live)
- Pre-read communication for attendees

---

## Open Questions / Future Decisions

1. **Which prototyping tool to use for vibe coding demo?** — v0.dev recommended, but Lovable or Bolt are alternatives
2. **Should there be a Slack channel for post-session questions?** — Suggested but not confirmed
3. **How to handle brand assets?** — Need iQmetrix colors, typography, screenshots for vibe coding demo
4. **Live TMForum demo vs. screenshots?** — Depends on prep time and environment setup
5. **Follow-up session topics?** — Vibe coding deep-dive and AI product evaluation suggested as options

---

## Prompting Tips for Future Agents

When continuing this work:

1. **Reference the main document** — `iqmetrix-ai-for-pms.md` has the full workshop content
2. **Audience is non-technical PMs** — Avoid jargon, emphasize practical outcomes
3. **iQmetrix context matters** — Retail/POS, RAG Slack bot, Luzmo, TMForum are all relevant anchors
4. **Voice input is a key differentiator** — Emphasize as barrier-lowering technique
5. **MCP is the "agentic" proof point** — Shows AI in workflow, not alongside it
6. **TMForum is the capstone** — Real business problem, shows the ceiling
7. **Waleed's examples need cleanup** — Can't just show his actual workflow, needs demo-ready packaging

---

## Quick Reference: Session Structure

### 90-Minute Version
| Time | Section |
|------|---------|
| 0-20 | Preamble slides (framing, landscape, agents, prompting) |
| 20-30 | Demo 1: Interview Synthesis |
| 30-42 | Demo 2: Vibe Coding Prototype |
| 42-50 | Demo 3: MCP Artifact Updates |
| 50-60 | Demo 4: TMForum Capstone |
| 60-75 | Closing slides |
| 75-90 | Q&A |

### 60-Minute Version
| Time | Section |
|------|---------|
| 0-15 | Compressed preamble |
| 15-25 | Demo 1: Interview Synthesis |
| 25-40 | Demo 2: Vibe Coding Prototype |
| 40-50 | Demo 3: TMForum Capstone (abbreviated) |
| 50-60 | Closing + Q&A |

---

*End of context export*
