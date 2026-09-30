# Cloude Code ToolBox — MCP & Skills awareness

_Generated: 2026-09-30T20:07:10.489Z_

## How to use this report

- **Saved copy:** This file is **`.claude/cloude-code-toolbox-mcp-skills-awareness.md`** — refreshed whenever the toolbox runs an MCP & Skills scan (including on workspace open when auto-scan is enabled). It is meant for **Claude Code workspace context** together with `CLAUDE.md` (which gets a shorter replaceable summary when auto-merge is on).
- **MCP:** Lists **configured** servers from Claude Code config (`~/.claude.json` for user scope, `.mcp.json` for project scope). Use `/mcp` in the Claude Code panel to connect servers for your session.
- **Skills:** **On-disk** folders with `SKILL.md`. Claude Code does not auto-load them; attach `SKILL.md` or paths in chat when useful.
- **Task routing:** When the user’s request matches a server’s purpose (e.g. Confluence → Confluence/Atlassian MCP), prefer that **server id** from the tables below.

---

## MCP — workspace

Workspace `mcp.json` _(folder: handbook)_

- **c:\Users\Engineer Farhad Ali\handbook\.mcp.json** — _File exists — servers defined_

| Server id | Kind | Detail |
|-----------|------|--------|
| Neon | http | https://mcp.neon.tech/mcp |
| agentfactory-system-of-record | http | https://sor.panaversity.org/mcp |

## MCP — user profile

- **C:\Users\Engineer Farhad Ali\.claude.json** — _File exists — no servers defined_

_No active user-scoped servers in mcp.json._

## Skills (local `SKILL.md` folders)

### Project-scoped

- **add-sources** — `c:\Users\Engineer Farhad Ali\handbook\.claude\skills\add-sources`
  - Turn what the owner has into governed knowledge in knowledge/ — a document, a page, pasted text, notes, or something nobody ever wrote down that they tell you. Use when the owner shares material to add, says "add this to

- **format-checker** — `c:\Users\Engineer Farhad Ali\handbook\.claude\skills\format-checker`
  - The record's format rules as a runnable check — frontmatter, filenames, links, structure. Use before handing off any change to knowledge/, when a check fails and you need to fix it, or when unsure whether a document is w

- **intake-interview** — `c:\Users\Engineer Farhad Ali\handbook\.claude\skills\intake-interview`
  - The first conversation with the owner of this Knowledge System of Record — three questions that define what it is authoritative for, who may read it and who may approve it, then write instance.md together. Use when the o

- **add-sources** — `c:\Users\Engineer Farhad Ali\handbook\.agents\skills\add-sources`
  - Turn what the owner has into governed knowledge in knowledge/ — a document, a page, pasted text, notes, or something nobody ever wrote down that they tell you. Use when the owner shares material to add, says "add this to

- **format-checker** — `c:\Users\Engineer Farhad Ali\handbook\.agents\skills\format-checker`
  - The record's format rules as a runnable check — frontmatter, filenames, links, structure. Use before handing off any change to knowledge/, when a check fails and you need to fix it, or when unsure whether a document is w

- **intake-interview** — `c:\Users\Engineer Farhad Ali\handbook\.agents\skills\intake-interview`
  - The first conversation with the owner of this Knowledge System of Record — three questions that define what it is authoritative for, who may read it and who may approve it, then write instance.md together. Use when the o

### User-scoped

- **approval-handler** — `C:\Users\Engineer Farhad Ali\.claude\skills\approval-handler`
  - Monitor /Approved and /Rejected folders. When file moved to /Approved → execute the action via MCP (email send, post social, etc.). Log everything.

- **ceo-briefing** — `C:\Users\Engineer Farhad Ali\.claude\skills\ceo-briefing`
  - Generate Monday Morning CEO Briefing by Sunday night or on demand. Read Business_Goals.md, recent Done/, Accounting/, create summary of revenue, bottlenecks, suggestions.

- **email-triage** — `C:\Users\Engineer Farhad Ali\.claude\skills\email-triage`
  - |

- **email-triage copy** — `C:\Users\Engineer Farhad Ali\.claude\skills\email-triage copy`
  - |

- **invoice-generator** — `C:\Users\Engineer Farhad Ali\.claude\skills\invoice-generator`
  - Create invoice from client request (WhatsApp/email). Read Rates.md or Business_Goals.md, generate markdown + suggest PDF via MCP if available.

- **whatsapp-handler** — `C:\Users\Engineer Farhad Ali\.claude\skills\whatsapp-handler`
  - |

- **whatsapp-handler copy** — `C:\Users\Engineer Farhad Ali\.claude\skills\whatsapp-handler copy`
  - Process incoming WhatsApp messages from /Needs_Action/WHATSAPP_*.md. Classify intent, suggest replies, flag sales/invoice/support, create follow-up tasks.

- **code-review** — `C:\Users\Engineer Farhad Ali\.agents\skills\code-review`
  - AI-powered code review using CodeRabbit. Default code-review skill. Trigger for any explicit review request AND autonomously when the agent thinks a review is needed (code/PR/quality/security).

- **crypto-com-exchange** — `C:\Users\Engineer Farhad Ali\.agents\skills\crypto-com-exchange`
  - Trade on Crypto.com Exchange — market data, spot/derivatives orders, portfolio management, wallet operations. Uses cdcx CLI for execution with built-in auth, safety tiers, and dry-run.

- **deploy-to-vercel** — `C:\Users\Engineer Farhad Ali\.agents\skills\deploy-to-vercel`
  - Deploy applications and websites to Vercel. Use when the user requests deployment actions like "deploy my app", "deploy and give me the link", "push this live", or "create a preview deployment".

- **fastapi** — `C:\Users\Engineer Farhad Ali\.agents\skills\fastapi`
  - FastAPI best practices and conventions. Use when working with FastAPI APIs, Pydantic models, dependencies, streaming responses including Server-Sent Events (SSE), and serving frontend apps. Keeps FastAPI code clean and u

- **find-skills** — `C:\Users\Engineer Farhad Ali\.agents\skills\find-skills`
  - Helps users discover and install agent skills when they ask questions like "how do I do X", "find a skill for X", "is there a skill that can...", or express interest in extending capabilities. This skill should be used w

- **python-mcp-server-generator** — `C:\Users\Engineer Farhad Ali\.agents\skills\python-mcp-server-generator`
  - Generate a complete MCP server project in Python with tools, resources, and proper configuration

- **skill-creator** — `C:\Users\Engineer Farhad Ali\.agents\skills\skill-creator`
  - Create new skills, modify and improve existing skills, and measure skill performance. Use when users want to create a skill from scratch, edit, or optimize an existing skill, run evals to test a skill, benchmark skill pe

- **trading-analysis** — `C:\Users\Engineer Farhad Ali\.agents\skills\trading-analysis`
  - Generate professional investment reports for stocks and ETFs. Use when user requests market analysis, investment reports, stock analysis, or trading recommendations for financial instruments (SPY, AAPL, TSLA, etc.). Crea

- **trading-signal** — `C:\Users\Engineer Farhad Ali\.agents\skills\trading-signal`
  - |

- **voice-ai-integration** — `C:\Users\Engineer Farhad Ali\.agents\skills\voice-ai-integration`
  - |

---

## Suggested next steps

- **MCP:** Use this extension’s hub **MCP** tab, or `claude mcp list` in the terminal. In Claude Code, use `/mcp` to connect servers for the session.
- **Edit config:** Open `~/.claude.json` (user MCP) or `<workspace>/.mcp.json` (project MCP) via the extension commands.
- **Refresh this report:** run **Intelligence — scan MCP & Skills awareness** again after changing MCP config or adding skills.

_Report from Cloude Code ToolBox extension._
