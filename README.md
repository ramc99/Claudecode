# Claude Code — Notes & Learning Log

Personal notes on installing and working with Claude Code (Anthropic's official AI CLI), built while developing real projects like the METAR weather app.

## Contents

| File | Description |
|------|-------------|
| `Claudecode Installation and working` | End-to-end guide: installation, authentication, key commands, how Claude Code works |
| `Long-sessions` | Notes on managing long Claude Code sessions — context, compaction, cost |
| `Metar App process` | Step-by-step log of building the METAR app using Claude Code |

## Quick-start (Claude Code)

```bash
# Install
npm install -g @anthropic-ai/claude-code

# Verify
claude --version

# Start a session in any project folder
cd /your/project
claude
```

**Requirements:** Node.js 18+, Anthropic API key from [console.anthropic.com](https://console.anthropic.com)

## Key commands

| Command | What it does |
|---------|-------------|
| `/help` | List all slash commands |
| `/clear` | Clear conversation context |
| `/compact` | Compress conversation to save context |
| `/cost` | Show token usage and cost |
| `/config` | Change model, theme, etc. |
| `Ctrl+C` | Cancel current tool call |

## Projects built with Claude Code

- [METAR App](https://github.com/ramc99/Metar-app) — aviation weather dashboard
- [METAR App (retested)](https://github.com/ramc99/Metar-app-retested-and-improved-) — improved version with fixes
- [Airport App](https://github.com/ramc99/airport-app) — flight info + AI chatbot
- [Weather Report](https://github.com/ramc99/Weather-Report) — city weather via wttr.in
- [Image Compressor](https://github.com/ramc99/Image-compressor) — Pillow-based image processing tool
- [CSV Split & Merge](https://github.com/ramc99/splitting-and-merging) — CSV file utilities
