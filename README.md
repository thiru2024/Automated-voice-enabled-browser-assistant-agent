# AI Voice Browser Assistant

Lightweight starter for an AI-driven voice-enabled browser assistant.

## Quick start

Install dependencies:

```bash
npm install
```

Run:

```bash
npm start
```

Run tests:

```bash
npm test
```

## Structure

- `src/` — application code
- `tests/` — tests
- `docs/` — design notes

# Architecture notes

This document will hold high-level design notes for the AI Voice Browser Assistant.

- Voice -> STT -> command parsing -> Browser actions
- Consider local TTS / STT or cloud providers
- Browser automation via puppeteer or extension APIs
