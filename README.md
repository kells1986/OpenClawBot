# OpenClawBot backup

This repo is an automated nightly backup of:

- `workspace/` — OpenClaw workspace (SOUL.md, USER.md, MEMORY.md, memory/*.md, projects)
- `config/openclaw.json.gpg` — OpenClaw gateway config (encrypted; contains secrets)

Restoring:
- Install OpenClaw
- Put the workspace back at `~/.openclaw/workspace`
- Decrypt `config/openclaw.json.gpg` to `~/.openclaw/openclaw.json`
- Restart gateway
