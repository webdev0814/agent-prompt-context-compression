# Agent Briefing: agent-prompt-context-compression

## 1. Repository Overview & Purpose
- **Repository**: `webdev0814/agent-prompt-context-compression`
- **Visibility**: `Public`
- **Default Branch**: `master`
- **Last Updated / Pushed**: 2026-09-04
- **Description**: Reusable prompt instructions for reducing token usage across agent systems without sacrificing correctness.
- **Context from README**: Generic instructions for reducing token usage across an agent system without reducing correctness, safety, or task completion quality. Context growth is both a cost problem and a reliability problem. This reference architecture treats compression as a product control: preserve decisions, constraints...
- **Topics/Tags**: llm, prompt-engineering, token-compression

---

## 2. Tech Stack & Architecture
- **Primary Language / Ecosystem**: General / Multi-language
- **Key Directories**: Single root directory structure.
- **Notable Top-Level Files**: `.gitignore`, `AGENTS.md`, `AGENT_CONTEXT_COMPRESSION.md`, `CLAUDE.md`, `GEMINI.md`, `LICENSE`, `README.md`, `SECURITY.md`

---

## 3. Setup & Execution Commands
### Environment Setup & Installation
```bash
# Review repository files and install dependencies corresponding to the language/runtime.
```

### Running / Starting
```bash
# Check main entry point scripts or config files.
```

### Testing / Verification
```bash
# Run relevant unit/integration tests (e.g. pytest or npm test)
```

---

## 4. Recent Commit Activity (Where We Left Off)
The most recent commits show the latest development trajectory:
- `[9a8a005]` (2026-09-04) docs: add comprehensive agent briefing (AGENTS.md, GEMINI.md, CLAUDE.md)
- `[a13654f]` (2026-09-04) docs: add comprehensive agent briefing (AGENTS.md, GEMINI.md, CLAUDE.md)
- `[07d6258]` (2026-09-04) docs: add comprehensive agent briefing (AGENTS.md, GEMINI.md, CLAUDE.md)
- `[48fb6ed]` (2026-09-03) Add security reporting and repository hygiene policy
- `[a328fca]` (2026-09-03) Add AI product portfolio context
- `[b6d9203]` (2026-06-02) Initial commit

---

## 5. Current State & Immediate Next Steps
- **Current State**: Project is active under branch `master`.
- **When picking up this repo**:
  1. Inspect the top-level files and recent commits to understand the active feature or bugfix context.
  2. Verify all required credentials and environment variables before running integration scripts.
  3. Ensure all tests and linting pass after making modifications.
  4. Follow the repository conventions and preserve existing architecture patterns.

---

## 6. Agent Working Guidelines & Gotchas
- **Cross-Platform Compatibility**: Code may run across Windows, macOS, or Linux agent environments. Ensure path manipulations use OS-agnostic methods (e.g. `pathlib.Path` or `path.join`).
- **Secret Hygiene**: NEVER commit plain-text API keys, tokens, or credentials into repository files.
- **Git Commit Etiquette**: Use concise, conventional commit messages (e.g., `feat:`, `fix:`, `docs:`, `refactor:`).
- **Tooling Compatibility**: This briefing is kept aligned for Antigravity (`GEMINI.md`), Claude Code / Codex (`CLAUDE.md`), and general autonomous agents (`AGENTS.md`).
