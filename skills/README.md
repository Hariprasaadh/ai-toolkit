# AI Agent Skills Catalog

A production-grade collection of **45 modular, progressive-disclosure AI skills** following the Anthropic and Antigravity specifications.

Every skill is packaged in its own self-contained directory with a standardized `SKILL.md` file, accompanied by `references/`, `templates/`, and `scripts/` where appropriate.

---

## Skills Directory Overview

```text
skills/
├── <skill-name>/
│   ├── SKILL.md             # Primary instructions with YAML frontmatter
│   ├── references/          # Optional: deep-dive guides & domain documentation
│   ├── templates/           # Optional: code and configuration starter templates
│   └── scripts/             # Optional: automation and helper utilities
```

---

## Categorized Skill Matrix

### 1. AI, LLM & Multi-Agent Frameworks
| Skill | Description | Path |
| :--- | :--- | :--- |
| **A2A Protocol** | Connect and orchestrate agents via the Agent2Agent communication protocol | [`a2a-protocol`](a2a-protocol/SKILL.md) |
| **Agent Builder** | Meta-framework for scaffolding custom autonomous agent systems | [`agent-builder`](agent-builder/SKILL.md) |
| **Agent Creator** | Step-by-step procedures for defining persona, role, and capabilities | [`agent-creator`](agent-creator/SKILL.md) |
| **Agent Evals** | Automated evaluation benchmarks and rubric testing for LLM agents | [`agent-evals`](agent-evals/SKILL.md) |
| **AI Agent Development** | Core architecture patterns for resilient, stateful AI agents | [`ai-agent-development`](ai-agent-development/SKILL.md) |
| **CrewAI** | Multi-agent collaboration, delegation, and sequential task flows | [`crewai`](crewai/SKILL.md) |
| **LangChain Architecture** | Modern LangChain chains, runnables, and tool integration | [`langchain-architecture`](langchain-architecture/SKILL.md) |
| **Mastering LangGraph** | Cyclic stateful workflows, human-in-the-loop, and persistence | [`mastering-langgraph`](mastering-langgraph/SKILL.md) |
| **Multi-Agent Orchestration** | Supervisor, hierarchical, and peer-to-peer agent patterns | [`multi-agent-orchestration`](multi-agent-orchestration/SKILL.md) |
| **Pydantic AI** | Type-safe, validated agent development in Python with Pydantic | [`pydantic-ai`](pydantic-ai/SKILL.md) |
| **Skill Creator** | Standardized generator for authoring new agent skills | [`skill-creator`](skill-creator/SKILL.md) |
| **Using Superpowers** | Composing high-order tools and cognitive abilities for agents | [`using-superpowers`](using-superpowers/SKILL.md) |

### 2. Memory & Context Engineering
| Skill | Description | Path |
| :--- | :--- | :--- |
| **Agent Memory Discipline** | Strict conventions for reading, updating, and expiring agent memory | [`agent-memory-discipline`](agent-memory-discipline/SKILL.md) |
| **Agent Memory Systems** | Architecture for short-term, working, episodic, and semantic memory | [`agent-memory-systems`](agent-memory-systems/SKILL.md) |
| **Compress Skill** | Context minimization, token compression, and prompt pruning | [`compress-skill`](compress-skill/SKILL.md) |
| **Context Engineering** | Strategic attention management and token-window optimization | [`context-engineering`](context-engineering/SKILL.md) |
| **Create Agent Prompt** | System prompt engineering with guardrails and defense baselines | [`create-agent-prompt`](create-agent-prompt/SKILL.md) |
| **Harness Engineering** | Evaluation harnesses and benchmark harness construction | [`harness-engineering`](harness-engineering/SKILL.md) |

### 3. Backend, APIs & Model Context Protocol (MCP)
| Skill | Description | Path |
| :--- | :--- | :--- |
| **API & Interface Design** | REST, RPC, and GraphQL interface contracts and schema design | [`api-and-interface-design`](api-and-interface-design/SKILL.md) |
| **FastAPI** | High-performance Python async REST APIs, dependency injection, and Pydantic v2 | [`fastapi`](fastapi/SKILL.md) |
| **FastMCP** | Building custom MCP tools and resources with FastMCP | [`fastmcp`](fastmcp/SKILL.md) |
| **FastMCP Client CLI** | Interacting with and testing MCP servers via command-line tools | [`fastmcp-client-cli`](fastmcp-client-cli/SKILL.md) |

### 4. Frontend & Animation
| Skill | Description | Path |
| :--- | :--- | :--- |
| **Anime.js Animation** | High-performance web animations, timelines, and SVG transitions | [`animejs-animation`](animejs-animation/SKILL.md) |
| **Antigravity Design Expert**| Premium visual design system, glassmorphism, and modern UI tokens | [`antigravity-design-expert`](antigravity-design-expert/SKILL.md) |
| **Frontend Design** | Layouts, accessibility, typography, responsive design, and CSS architecture | [`frontend-design`](frontend-design/SKILL.md) |
| **GSAP Animation** | Complex scroll-triggered animations and timeline choreography | [`gsap-animation`](gsap-animation/SKILL.md) |
| **UI/UX Pro Max** | High-conversion UI design, micro-interactions, and visual hierarchy | [`ui-ux-pro-max`](ui-ux-pro-max/SKILL.md) |
| **Vercel React Best Practices**| Next.js App Router, Server Components, and streaming rendering | [`vercel-react-best-practices`](vercel-react-best-practices/SKILL.md) |

### 5. Testing, QA & Debugging
| Skill | Description | Path |
| :--- | :--- | :--- |
| **Code Review & Quality** | Strict automated pre-commit and PR code review rubrics | [`code-review-and-quality`](code-review-and-quality/SKILL.md) |
| **Systematic Debugging** | 4-phase root-cause isolation and minimal reproduction techniques | [`code-showcase-systematic-debugging`](code-showcase-systematic-debugging/SKILL.md) |
| **Test-Driven Development** | Strict Red-Green-Refactor test-first engineering | [`test-driven-development`](test-driven-development/SKILL.md) |
| **Verification Before Completion** | Final definition-of-done checklists and regression gates | [`verification-before-completion`](verification-before-completion/SKILL.md) |

### 6. Workflow, Planning & Best Practices
| Skill | Description | Path |
| :--- | :--- | :--- |
| **Agents.md Maintainer** | Authoring and updating repository guideline files (`AGENTS.md`) | [`agents-md`](agents-md/SKILL.md) |
| **Agent Browser** | Web-based research, scraping, and verification workflows | [`agent-browser`](agent-browser/SKILL.md) |
| **Antigravity Skill Orchestrator** | Dynamic loading and chaining of specialized skills | [`antigravity-skill-orchestrator`](antigravity-skill-orchestrator/SKILL.md) |
| **Brainstorming** | Collaborative exploration and creative technical brainstorming | [`brainstorming`](brainstorming/SKILL.md) |
| **Codebase Understanding** | Rapid repository mapping, symbol tracing, and architectural discovery | [`codebase-understanding`](codebase-understanding/SKILL.md) |
| **Data Scientist** | Exploratory data analysis, feature engineering, and statistical modeling | [`data-scientist`](data-scientist/SKILL.md) |
| **Executing Plans** | Disciplined execution of multi-step implementation plans | [`executing-plans`](executing-plans/SKILL.md) |
| **Find Skills** | Semantic routing and skill lookup for agent workflows | [`find-skills`](find-skills/SKILL.md) |
| **Implementation Plan** | Creating structured, risk-aware feature roadmaps | [`implementation-plan`](implementation-plan/SKILL.md) |
| **Incremental Implementation** | Small, verifiable diffs with zero regression drift | [`incremental-implementation`](incremental-implementation/SKILL.md) |
| **Planning with Files** | Persistent markdown files (`task_plan.md`, `findings.md`, `progress.md`) | [`planning-with-files`](planning-with-files/SKILL.md) |
| **TypeScript Best Practices** | Modern TS 5.x strict mode, `satisfies`, and type safety | [`typescript-best-practices`](typescript-best-practices/SKILL.md) |
| **Writing Plans** | Technical specification and implementation plan authoring | [`writing-plans`](writing-plans/SKILL.md) |
