# Fork-specific notes

- This is a fork of openclaw/openclaw deployed on Railway at agent.hypertransient.com.
- Do NOT modify upstream source files (src/**, docs/**, etc.) — only deployment config.
- Railway auto-assigns the PORT env var. Do not override it manually.

## Syncing from upstream

1. On GitHub: "Sync fork" or merge upstream/main into your main
2. Resolve conflicts by accepting upstream — unless it's a file you intentionally changed for Railway
3. Push main, then rebase any feature branches on top
