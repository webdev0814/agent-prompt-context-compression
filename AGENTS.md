# Agent Briefing: agent-prompt-context-compression

## 1. Repository Overview & Purpose
- **Repository**: `webdev0814/agent-prompt-context-compression`
- **Visibility**: `Public`
- **Default Branch**: `master`
- **Last Updated / Pushed**: 2026-09-09
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
- `[33edb02]` (2026-09-09) docs: update agent briefing with multi-computer handoff protocol
- `[82b4e47]` (2026-09-09) docs: update agent briefing with multi-computer handoff protocol
- `[9ee6a1d]` (2026-09-09) docs: update agent briefing with multi-computer handoff protocol
- `[fd2832a]` (2026-09-09) docs: update agent briefing with multi-computer handoff protocol
- `[0620876]` (2026-09-09) docs: update agent briefing with multi-computer handoff protocol
- `[10375a8]` (2026-09-09) docs: update agent briefing with multi-computer handoff protocol
- `[7808d70]` (2026-09-09) docs: update agent briefing with multi-computer handoff protocol
- `[fdb88bd]` (2026-09-09) docs: update agent briefing with multi-computer handoff protocol
- `[4bcaaad]` (2026-09-09) docs: update agent briefing with multi-computer handoff protocol
- `[3fb47c8]` (2026-09-09) docs: update agent briefing with multi-computer handoff protocol

---

## 5. Current State & Immediate Next Steps
- **Current State**: Project is active under branch `master`.
- **When picking up this repo**:
  1. Inspect the top-level files and recent commits to understand the active feature or bugfix context.
  2. Verify all required credentials and environment variables before running integration scripts.
  3. Ensure all tests and linting pass after making modifications.
  4. Follow the repository conventions and preserve existing architecture patterns.

---

## 6. Multi-Computer Handoff & Git Sync Protocol
- **On Session Start**: Always run `git pull` when opening this repository on any computer to synchronize the latest changes.
- **On Task Completion**: Before ending any agent session, the agent **MUST**:
  1. Update Section 5 (Current State & Next Steps) in this `AGENTS.md` file.
  2. Stage all modifications (`git add .`).
  3. Commit with a concise conventional message (`git commit -m "feat/fix: ..."`).
  4. Push directly to GitHub (`git push`).
- **Secret Hygiene**: NEVER commit plain-text API keys, tokens, or credentials into repository files.
