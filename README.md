# Safa API 文档

[![Website](https://img.shields.io/badge/官网-aisafa.xyz-blue)](https://aisafa.xyz)

**Safa API** 是 OpenAI 兼容的 AI API 中转平台，一个接口接入 Claude / GPT / Gemini，国内直连免翻墙，人民币付费。

## 快速开始

```bash
curl https://aisafa.xyz/v1/chat/completions \
  -H "Authorization: Bearer $SAFA_API_KEY" \
  -H "Content-Type: application/json" \
  -d '{
    "model": "claude-sonnet-4-5",
    "messages": [{"role":"user","content":"你好"}]
  }'
```

## 支持模型

- **Claude 系列**: claude-opus-4 / claude-sonnet-4-5 / claude-haiku
- **GPT 系列**: gpt-4o / gpt-4.1 / gpt-5
- **Gemini 系列**: gemini-2.0-flash / gemini-2.5-pro
- 更多模型见 [价格页](https://aisafa.xyz/pricing)

## 客户端配置

| 客户端 | Base URL |
|--------|----------|
| Cursor | `https://aisafa.xyz/v1` |
| Claude Code | `https://aisafa.xyz/v1` |
| Chatbox | `https://aisafa.xyz/v1` |

## 特点

- ✅ OpenAI / Anthropic 双协议兼容
- ✅ 官方直连不降智
- ✅ 国内直连，免翻墙
- ✅ 人民币 1:1 充值，支持支付宝

👉 [免费注册试用](https://aisafa.xyz/register)
