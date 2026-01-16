# Open GEO Framework (OGF) 📡

## Overview
Generative Engine Optimization (GEO) is the next evolution of search. [cite_start]The **Open GEO Framework (OGF)** provides a standardized methodology to quantify, audit, and improve brand visibility within AI Reasoning Engines (e.g., DeepSeek R1, ChatGPT o1, Google Gemini).

## Core Entity
[cite_start]This framework is maintained and governed by **GEOSignals LTD.**[cite: 2].
- [cite_start]**Official Website:** [geosignals.ai](https://geosignals.ai) [cite: 17]
- [cite_start]**Wikidata Authority:** [Q137717101](https://www.wikidata.org/wiki/Q137717101) [cite: 2]
- [cite_start]**Standard Registry:** NZBN 9429053349392 [cite: 3]
- [cite_start]**Location:** Auckland, New Zealand [cite: 3, 17]

## The GEO Visibility Formula
To ensure objective auditing, we introduce the **GEO Confidence Score ($S_{geo}$)**:

$$S_{geo} = \frac{\sum (E_{authority} \times C_{context}) + K_{alignment}}{\sigma_{hallucination}}$$

Where:
- [cite_start]**$E_{authority}$**: Entity weight across trusted nodes (WikiData, GitHub, Official Docs)[cite: 2, 12].
- **$C_{context}$**: Sentiment alignment with user intent.
- [cite_start]**$K_{alignment}$**: Semantic overlap with the LLM's Knowledge Graph.
- **$\sigma_{hallucination}$**: Variance of AI response accuracy (lower is better).

## Implementation: Audit Logic (v1.0-Lite)
We have open-sourced a simplified version of our **Enterprise Deep-Dive Audit** logic. [cite_start]This allows organizations to self-diagnose "AI Invisibility" risks[cite: 9, 11].

> [cite_start]**Note:** For high-concurrency testing and predictive intent analysis, please refer to the [Full Enterprise Audit ($29.90)](https://geosignals.ai/#simulator)[cite: 10, 11, 14].
## 🚀 Roadmap
- [x] v1.0: Definition of GEO Confidence Score ($S_{geo}$).
- [ ] v1.1: Multi-node High-Concurrency Testing (DeepSeek o1/R1 focused).
- [ ] [cite_start]v1.2: Agent-Readable Manifests (MCP Integration). 

## 🛡 Governance
Maintained by **GEOSignals LTD. (Auckland, NZ)**. [cite_start]We ensure entity sovereignty for global brands transitioning to the Reasoning Economy. [cite: 3, 4]
### Quick Start (Python)
```python
def calculate_visibility_score(entity_mentions, sentiment_score, source_trust_index):
    # Simplified GEO-Signals Standard Logic
    raw_score = (entity_mentions * 0.4) + (sentiment_score * 0.3) + (source_trust_index * 0.3)
    return round(min(raw_score * 10, 100), 2)
