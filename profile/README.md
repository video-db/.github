<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/video-db/.github/main/assets/videodb-logo-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/video-db/.github/main/assets/videodb-logo-light.svg">
  <img alt="VideoDB" src="https://raw.githubusercontent.com/video-db/.github/main/assets/videodb-logo-light.svg" height="50">
</picture>

### The modern backend for AI agents working with video and audio

[![Website](https://img.shields.io/badge/videodb.io-website-blue)](https://videodb.io)
[![Documentation](https://img.shields.io/badge/docs-videodb.io-green)](https://docs.videodb.io)
[![Discord](https://img.shields.io/discord/1098764508042039398?label=Discord&logo=discord)](https://discord.gg/py9P639jGz)
[![Twitter](https://img.shields.io/twitter/follow/video_db?style=social)](https://twitter.com/video_db)

---

**VideoDB** gives AI agents eyes, ears, memory, and actions over video and audio.

We turn continuous media into real-time context, searchable memory, and event-driven actions — enabling agents to **see**, **understand**, and **act**.

```
See (Ingest) → Understand (Index) → Act (Transform)
```

<br>

## Quick Start

Get perception capabilities for your AI agent in seconds:

```bash
npx videodb-skills
```

Or try our interactive notebooks:

[![Open Quickstart in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/video-db/videodb-cookbook/blob/main/quickstart/VideoDB_Quickstart_See_Understand_Act.ipynb) **See → Understand → Act Quickstart**

[![Open Multicam in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/video-db/videodb-cookbook/blob/main/quickstart/Multicam_Quickstart.ipynb) **Multi-Camera Surveillance Demo**

<br>

## SDKs & Agent Skills

Build AI applications that understand and process video as structured data.

| | |
|---|---|
| [**skills**](https://github.com/video-db/skills) | Server-side video workflows for agents — capture, process, understand, generate, stream |
| [**videodb-python**](https://github.com/video-db/videodb-python) | Official Python SDK — upload, index, search, edit, and stream video programmatically |
| [**videodb-node**](https://github.com/video-db/videodb-node) | Official Node.js/TypeScript SDK |
| [**agent-toolkit**](https://github.com/video-db/agent-toolkit) | MCP server + LLM context files for seamless AI IDE integration |

<br>

## Agent Frameworks

Build intelligent video agents and orchestrate complex workflows.

| | |
|---|---|
| [**Director**](https://github.com/video-db/Director) ⭐ 1.4k | AI video agents framework — 20+ pre-built agents for summarization, search, clipping, script-to-movie, dubbing, and more |

<br>

## Desktop Applications

Screen-aware, voice-aware AI applications built on VideoDB.

| | |
|---|---|
| [**call.md**](https://github.com/video-db/call.md) | Transform meetings into agentic loops — record, transcribe, analyze with real-time AI |
| [**bloom**](https://github.com/video-db/bloom) | Open-source agentic Loom alternative — local-first recording with AI-powered workflows |
| [**pair-programmer**](https://github.com/video-db/pair-programmer) | AI coding assistant that sees your screen and hears your voice — works with Claude Code, Cursor, Codex |

<br>

## Reference Systems

Open-source applications showcasing what's possible with VideoDB.

| | |
|---|---|
| [**agentic-streams**](https://github.com/video-db/agentic-streams) | Autonomous agents that research the web and generate personalized video briefings |
| [**PromptClip**](https://github.com/video-db/PromptClip) | Create video clips instantly from natural language prompts |
| [**videodb-capture-quickstart**](https://github.com/video-db/videodb-capture-quickstart) | Real-time desktop capture SDK for AI agent perception |

<br>

## Examples & Tutorials

Explore our comprehensive collection of examples and use cases:

| Category | Examples |
|---|---|
| **Agentic Workflows** | Pair Programmer, OpenClaw Monitoring, Call.md, Bloom, Focusd |
| **Video Search** | Keyword Search, Multimodal Search, Character Clips, Conference Slides |
| **Live Intelligence** | Intrusion Detection, Baby Monitoring, Road Monitoring, Sports Analytics |
| **Content Creation** | Faceless Videos, AI Dubbing, Voiceovers, Text-to-Video |
| **Programmatic Editing** | Intro/Outro, Brand Elements, Dynamic Ads, Audio Overlay |

[**Browse all examples →**](https://docs.videodb.io/examples-and-tutorials)
&nbsp;&nbsp;|&nbsp;&nbsp;
[**VideoDB Cookbook →**](https://github.com/video-db/videodb-cookbook)

<br>

## Integrations

Connect VideoDB to your existing workflows.

| | |
|---|---|
| [**n8n-nodes-videodb**](https://github.com/video-db/n8n-nodes-videodb) | n8n workflow nodes |
| [**videodb-zapier-integration**](https://github.com/video-db/videodb-zapier-integration) | Zapier integration |

<br>

---

### Why VideoDB?

- **Real-time & streaming-first** — process live streams, RTSP, desktop capture, not just files
- **Playable outputs** — retrieval returns video evidence, not just metadata
- **Programmable understanding** — indexes-as-code, evolving over time
- **Built for agents** — the perception, memory, and action layer between storage and reasoning

<br>

### Get Started

```bash
pip install videodb
```

```python
from videodb import connect

conn = connect()
coll = conn.get_collection()

# Upload and index
video = coll.upload(url="https://www.youtube.com/watch?v=...")
video.index_spoken_words()

# Search with playable results
results = video.search("key moments")
results.play()
```

[**Read the docs →**](https://docs.videodb.io)

---

<p align="center">
  <a href="https://videodb.io">Website</a> •
  <a href="https://docs.videodb.io">Docs</a> •
  <a href="https://discord.gg/py9P639jGz">Discord</a> •
  <a href="https://twitter.com/video_db">Twitter</a>
</p>
