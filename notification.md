## 🔔 Live Notifications

These updates are fetched live by the website from this repository.

<!-- NOTIFICATIONS:START -->
```json
[
  {
    "id": "2026-01-17-001",
    "date": "2026-01-17",
    "level": "feature",
    "category": "models",
    "title": "New Jira & Confluence Tools",
    "message": "Extend your AI capabilities with our new Atlassian integrations. Available now in Workspace.",
    "tags": ["Integration", "New Feature"],
    "cta": { "label": "Configure Tools", "url": "/workspace?tab=tools" }
  },
{
    "id": "2026-01-13-002",
    "date": "2026-01-13",
    "level": "feature",
    "category": "models",
    "title": "New air-gapped model pack available",
    "message": "Added a curated offline bundle for code + ops workloads (includes model weights, tokenizer assets, and a verified checksums file). Optimized presets for vLLM + multi-GPU are included.",
    "tags": ["vllm", "offline", "models"],
    "cta": { "label": "View model pack notes", "url": "/docs/models/offline-pack" }
  },
  {
    "id": "2026-01-13-003",
    "date": "2026-01-13",
    "level": "info",
    "category": "models",
    "title": "Vision support expanded (air-gapped)",
    "message": "New vision-capable model profile added with recommended image-size defaults, concurrency limits, and fallback routing (vision → text) for constrained GPUs.",
    "tags": ["vision", "routing", "gpu"],
    "cta": { "label": "See vision profiles", "url": "/docs/models/vision" }
  },
  {
    "id": "2026-01-13-004",
    "date": "2026-01-13",
    "level": "feature",
    "category": "mcp",
    "title": "MCP support: more tools, same air-gap guarantees",
    "message": "Added new MCP server compatibility notes + hardened templates (TLS/certs, allowlists, audit logging). Includes ready-to-run examples for common internal services.",
    "tags": ["mcp", "security", "templates"],
    "cta": { "label": "Open MCP guide", "url": "/docs/mcp" }
  },
  {
    "id": "2026-01-13-005",
    "date": "2026-01-13",
    "level": "feature",
    "category": "tooling",
    "title": "OpenCode POC (air-gapped installer) is ready",
    "message": "Proof-of-concept installer now supports offline wheels/artifacts, custom corporate CAs, and a Nexus/registry-only mode. Includes a “connected → transfer → install” workflow.",
    "tags": ["opencode", "airgapped", "nexus"],
    "cta": { "label": "Read the POC steps", "url": "/docs/tools/opencode-poc" }
  },
  {
    "id": "2026-01-13-006",
    "date": "2026-01-13",
    "level": "maintenance",
    "category": "platform",
    "title": "Open WebUI upgrade deployed in production",
    "message": "Production updated to a newer Open WebUI release with improved multi-node worker behavior and admin controls. Rollback plan + validation checklist attached.",
    "tags": ["openwebui", "production", "upgrade"],
    "cta": { "label": "View rollout checklist", "url": "/docs/platform/openwebui-rollout" }
  }
]
