# Safa API Documentation

[Safa API](https://aisafa.xyz) is an enterprise-grade AI API relay service providing **OpenAI-compatible** access to Claude, GPT and Gemini models — designed for developers in China and beyond who need stable, direct-connection access without VPN.

## Features

- 🚀 **OpenAI-compatible** — works with any OpenAI SDK / client
- 🔥 **Latest models** — Claude Opus 4.8, GPT-5.5, Gemini 3 Pro
- 🇨🇳 **China-friendly** — no VPN required, pay in RMB
- 💬 **Native Anthropic format** — for Claude Code compatibility
- ⚡ **Stable & fast** — official upstream connections, no downgrade

## Quick Start

```python
from openai import OpenAI

client = OpenAI(
    base_url="https://aisafa.xyz/v1",
    api_key="your-key",
)

resp = client.chat.completions.create(
    model="claude-opus-4-8",
    messages=[{"role": "user", "content": "Hello!"}],
)
print(resp.choices[0].message.content)
```

## Base URL

| Client | Base URL |
|--------|----------|
| OpenAI SDK / Cursor / Chatbox | `https://aisafa.xyz/v1` |
| Claude Code (Anthropic format) | `https://aisafa.xyz` |
| OpenAI Node SDK | `https://aisafa.xyz/v1` |

## Docs

- [Quickstart](docs/quickstart.md)
- [Models](docs/models.md)

## Links

- Website: [https://aisafa.xyz](https://aisafa.xyz)
- Register: [https://aisafa.xyz/register](https://aisafa.xyz/register)
