---
"@ai-hero/sandcastle": patch
---

Add GitHub Copilot as a supported agent provider. New `githubCopilot()` factory function, Dockerfile template, CLI integration, and init scaffolding support. The copilot command uses `COPILOT_GITHUB_TOKEN` (fine-grained PAT) instead of `GH_TOKEN` (Classic PAT) to avoid auth issues.
