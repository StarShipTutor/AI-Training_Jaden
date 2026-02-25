## Simple Agents
[Parent Page](Home)

Simple agents are structured AI workflows designed to complete a specific task with limited autonomy.

They are not fully autonomous systems.  
They do not operate independently for long periods.  
They are bounded tools with clear scope and human oversight.

In this program, simple agents are used to increase productivity while maintaining control.

---

# What Is a Simple Agent?

A simple agent typically includes:

- A defined objective  
- A structured prompt or instruction set  
- Limited decision scope  
- Human review before final output  

It may:

- Execute a repeatable workflow  
- Transform inputs into structured outputs  
- Perform research and summarization  
- Generate drafts for refinement  

It does not:

- Set its own goals  
- Modify system-level rules  
- Operate without oversight  
- Access external systems without permission  

Simple agents are controlled automation — not autonomous AI.

---

# Why Start with Simple Agents?

Organizations often attempt advanced automation too early.

Simple agents provide:

- Predictable behavior  
- Reduced risk  
- Easier debugging  
- Clear boundaries  
- Faster adoption  

They are ideal for teams learning AI-assisted workflows.

---

# Common Simple Agent Patterns

---

## Research Agent

- **Input:** Topic or question  
- **Output:** Structured summary with sources  
- **Human Role:** Validate sources and conclusions  

Used for:

- Market overviews  
- Regulatory summaries  
- Industry updates  

---

## Drafting Agent

- **Input:** Outline or bullet points  
- **Output:** Structured draft document  
- **Human Role:** Edit, refine, approve  

Used for:

- Investment memos  
- Market reports  
- Client communications  

---

## Data Structuring Agent

- **Input:** Raw notes, text, or spreadsheet data  
- **Output:** Organized table or structured format  
- **Human Role:** Validate calculations and assumptions  

Used for:

- Cleaning financial inputs  
- Organizing deal summaries  
- Converting notes into actionable formats  

---

## Assumption Audit Agent

- **Input:** Model, memo, or analysis  
- **Output:** List of explicit and implicit assumptions  
- **Human Role:** Confirm or correct assumptions  

Used for:

- Financial models  
- Investment theses  
- Strategic planning  

---

# Design Principles for Simple Agents

---

## Clear Scope

Each agent should have a narrowly defined task.

Avoid:

- Multi-goal prompts  
- Open-ended objectives  
- Undefined decision authority  

Clarity reduces error.

---

## Structured Inputs

Agents perform best when given:

- Clean data  
- Explicit instructions  
- Defined format requirements  

Garbage in produces amplified garbage out.

---

## Human in the Loop

Every simple agent workflow should include:

- Review  
- Validation  
- Approval  

Autonomy increases only after reliability is demonstrated.

---

## Logging and Documentation

Maintain records of:

- Inputs  
- Outputs  
- Key assumptions  
- Corrections made  

This creates institutional learning and reduces repeated mistakes.

---

# What Simple Agents Are Not

- They are not autonomous decision-makers.  
- They are not self-improving systems.  
- They are not replacements for professional judgment.  
- They are not enterprise-wide automation solutions.  

They are controlled tools that extend human capability.

---

# Position in the AI Maturity Curve

AI adoption typically progresses through stages:

1. Prompting  
2. Structured prompting  
3. Simple agents  
4. Multi-agent systems  
5. Autonomous workflows  

Simple agents represent the first stable automation layer.

Mastery here prevents downstream failures.

---

# GPT-Based Simple Agent Example

A simple agent can be implemented directly inside ChatGPT (or a Custom GPT) with a fixed instruction set.

### Example: Weekly Market Summary Agent

**System Instructions:**

- You are a commercial real estate research assistant.
- Always produce:
  - Executive Summary (5 bullet points)
  - Market Drivers
  - Risks
  - Assumptions
  - Sources (if applicable)

**Workflow:**

1. User provides topic or region.
2. GPT produces structured summary.
3. GPT lists assumptions explicitly.
4. Human reviews and edits before distribution.

This agent:

- Has clear scope  
- Produces structured output  
- Requires human validation  
- Does not operate autonomously  

It is a repeatable, bounded workflow.

---

# Notion-Based Simple Agent Example

Notion can host simple agents using templates, AI blocks, and structured databases.

### Example: Deal Memo Drafting Agent

**Structure:**

- Database fields:
  - Property Name  
  - Location  
  - Purchase Price  
  - NOI  
  - Cap Rate  
  - Key Risks  
  - Assumptions  

**Workflow:**

1. User enters structured deal data into Notion database.
2. AI block generates:
   - Executive Summary  
   - Investment Thesis  
   - Risk Section  
   - Assumption Audit  
3. Human reviews calculations and narrative.
4. Final memo exported to presentation.

Advantages of Notion-based agents:

- Persistent structured data  
- Institutional memory  
- Version history  
- Repeatable templates  

This creates continuity rather than isolated chat sessions.

---

# Starting Recommendation

Begin by building one simple agent for a repeatable task.

Examples:

- Weekly market summary agent  
- Deal memo drafting agent  
- Assumption-checking agent  

Test it.  
Refine it.  
Document it.  

Expand only after reliability is demonstrated.

Controlled leverage beats uncontrolled automation.