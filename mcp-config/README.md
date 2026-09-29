# MCP Server Configurations

This directory contains standardized Model Context Protocol (MCP) server definitions that can be reused across different projects and AI agents.

The full JSON configuration is located in [mcp_config.json](file:///c:/Users/Dell/Documents/GitHub/ai-toolkit/mcp-config/mcp_config.json).

---

## Configured MCP Servers

| Server | NPM Package | Purpose | Requirements / Configuration |
| :--- | :--- | :--- | :--- |
| **GitHub** | `@modelcontextprotocol/server-github` | Search repos, inspect issues/PRs, read files, and interact with the GitHub API | Requires `GITHUB_PERSONAL_ACCESS_TOKEN` |
| **Filesystem** | `@modelcontextprotocol/server-filesystem` | Secure, scoped read/write access to local project files and directories | Directory path arguments (e.g. `C:/Users/Dell/Documents/GitHub`) |
| **Terminal / Shell** | `@dillip285/mcp-terminal` | Secure command execution (`execute_command`) within allowed directory paths | `--allowed-paths <path>` argument |
| **SQLite** | `mcp-sqlite` | CRUD operations, schema inspection, and custom SQL queries on SQLite databases | Database path argument (e.g. `<path-to-database.db>`) |
| **21st.dev** | Remote HTTP/SSE | Search and insert React/Tailwind design components from 21st.dev | `x-api-key` header |
| **Context7** | `@upstash/context7-mcp` | Upstash Context7 vector memory and semantic context retrieval | Requires `CONTEXT7_API_KEY` |
| **Playwright** | `@playwright/mcp` | Browser automation, web testing, and web interaction tools | Node.js / npx |
| **Firecrawl** | `firecrawl-mcp` | Web scraping, crawling, and clean markdown extraction | Requires `FIRECRAWL_API_KEY` |
| **PyMuPDF4LLM** | `pymupdf4llm-mcp` (Python / `uvx`) | High-accuracy PDF parsing, extraction, and Markdown conversion for LLMs | Requires `uvx` (runs with `--with "mcp<2"`) |
| **Mem0** | `mem0-mcp` | Personalized, adaptive long-term memory layer for AI agents | Requires `MEM0_API_KEY` |
| **Agent Memory** | `@agentmemory/mcp` | Persistent agent session memory, recall, and governance/audit logging | `AGENTMEMORY_URL` (e.g. `http://localhost:3111`) |
| **Git** | `mcp-server-git` (Python / `uvx`) | Structured local git operations (diff, status, commit log, branch inspection) | Requires `uvx` |
| **Fetch** | `mcp-server-fetch` (Python / `uvx`) | Fast, lightweight HTTP requests and web page text/markdown extraction | Requires `uvx` |

---

## Global Setup (Use Across All Projects)

Copy or link the content of [mcp_config.json](file:///c:/Users/Dell/Documents/GitHub/ai-toolkit/mcp-config/mcp_config.json) to your tool's global configuration file:

- **Antigravity (Global)**: `~/.gemini/config/mcp_config.json` (or `.agents/mcp_config.json` for project scope)
- **Claude Desktop**: `%APPDATA%\Claude\claude_desktop_config.json`
- **Cursor**: `~/.cursor/mcp.json` (or Cursor Settings → Features → MCP)
- **VS Code (Cline / Roo Code)**: `%APPDATA%\Code\User\globalStorage\saoudrizwan.claude-dev\settings\cline_mcp_settings.json`

> **Note for Windows paths**: When configuring file paths, always use forward slashes (`/`) or escaped backslashes (`\\`) in JSON values.
