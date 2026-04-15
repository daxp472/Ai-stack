# Model Comparison (April 2026 Snapshot)

A practical model-level cheat sheet for choosing quality vs cost.

> [!NOTE]
> Values here are quick-reference guidance. Verify current numbers on official pricing pages before production commitments.

## Top Model Families At A Glance

| Provider | Model Examples | Context | Typical Strength |
|---|---|---|---|
| OpenAI | gpt-5.4, gpt-5.4-mini, gpt-5.4-nano, gpt-5.3-codex | High | Coding, multimodal, tool-using agents |
| Anthropic | claude-opus-4-6, claude-sonnet-4-6, claude-haiku-4-5 | Up to 1M (Opus/Sonnet) | Reasoning quality, long-form synthesis |
| Google | gemini-2.5-pro, gemini-2.5-flash, gemini-2.5-flash-lite | Very high (selected models) | Cost-efficiency and throughput |
| xAI | grok-4.20, grok-4.1-fast | Up to 2M (as listed) | Fast reasoning + real-time angle |
| Mistral | Mistral Small/Large, Devstral, Codestral, Magistral | Varies | Open + hosted flexibility |

## Cost Orientation (API)

| Tier | Good Candidates | When to choose |
|---|---|---|
| Premium quality | OpenAI flagship large, Claude Opus, Grok flagship | Hard reasoning, mission-critical outputs |
| Balanced | OpenAI mini, Claude Sonnet, Gemini Pro/Flash | Most startup and product workloads |
| Budget/high volume | Gemini Flash-Lite, OpenAI nano, Grok fast | Batch transforms, classification, high-traffic pipelines |

## Selected Official Pricing Signals

### OpenAI (API docs)
- gpt-5.4: input $2.50 / 1M, output $15.00 / 1M
- gpt-5.4-mini: input $0.75 / 1M, output $4.50 / 1M
- gpt-5.4-nano: input $0.20 / 1M, output $1.25 / 1M
Source: https://developers.openai.com/api/docs/pricing

### Anthropic (model overview)
- Claude Opus 4.6: $5 input / MTok, $25 output / MTok
- Claude Sonnet 4.6: $3 input / MTok, $15 output / MTok
- Claude Haiku 4.5: $1 input / MTok, $5 output / MTok
Source: https://platform.claude.com/docs/en/docs/about-claude/models/overview

### Google (Gemini API pricing)
- Free + paid tiers available with different rate and data usage behavior
- Gemini 2.5 Flash and Flash-Lite families are positioned for strong cost-efficiency
Source: https://ai.google.dev/gemini-api/docs/pricing

### xAI (API overview)
- Grok 4.20 and Grok 4.1 Fast pricing signals listed with token-based pricing
- API highlights 2M context windows on listed model cards
Source: https://x.ai/api

## Which Model Should You Pick?

| If you need... | Start with... | Fallback |
|---|---|---|
| Best coding + agents | gpt-5.4-mini or gpt-5.3-codex | claude-sonnet-4-6 |
| Best long-form strategic writing | claude-opus-4-6 | gpt-5.4 |
| Cheapest large-scale processing | gemini-2.5-flash-lite | gpt-5.4-nano |
| Real-time trend-aware assistant | grok fast model line | perplexity orchestration |

> [!IMPORTANT]
> Build model routing from day one: high-value queries go to premium model, bulk queries go to low-cost model.
