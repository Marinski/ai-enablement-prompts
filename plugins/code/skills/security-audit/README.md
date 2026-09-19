# security-audit

Vendored from [cloudflare/security-audit-skill](https://github.com/cloudflare/security-audit-skill) (`skills/security-audit/`).

This skill is MIT licensed by Cloudflare, Inc. Copyright (c) 2025-2026 Cloudflare, Inc. See `LICENSE` in this directory.

To update from upstream:

```bash
git clone --depth 1 https://github.com/cloudflare/security-audit-skill /tmp/security-audit-skill
rsync -a --delete /tmp/security-audit-skill/skills/security-audit/ plugins/code/skills/security-audit/
```