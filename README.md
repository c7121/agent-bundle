# Agent docs bundle

This bundle supports a "canonical repo + weekly sync PR" workflow and includes
security-focused agent standards plus a hardened GitHub Actions workflow.

Files included:
- AGENTS.md (repo-local stub and overrides)
- docs/agent/AGENTS.shared.md (shared standards; intended to be synced)
- docs/specs/_mini_template.md (hard-limited mini spec)
- docs/specs/_template.md
- docs/adr/_template.md
- docs/agent/references.md (external links/anchors)
- docs/agent/checklist.md
- scripts/sync_agent_standards.mjs
- .github/workflows/sync-agent-standards.yml (pinned SHAs)
- docs/agent/SETUP_SYNC.md


Update (v7): Added a "no performative citations" rule to shared standards and strengthened the checklist anchor check.
