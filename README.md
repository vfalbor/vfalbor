# 🪨🌳 caveman_tokenstransfer.2.0

**A two-sided token compressor: caveman cuts what the model says, tokenstransfer cuts what the model hears — together half the bill.**

Output side waffle. Input side bloat. **2.0 cut both.**

**`-55%` cost per call** on RAG/agent workloads — same model, same answer, **half the invoice**.

```bash
curl -fsSL https://raw.githubusercontent.com/vfalbor/caveman_tokenstransfer.2.0/main/install.sh | bash
```

[**⭐ Star it →**](https://github.com/vfalbor/caveman_tokenstransfer.2.0) · 30+ agents · 100% local mode · LLMLingua-2 + caveman dialect · MIT

---

# V. F. Albor

Physicist turned token economist. Building open-source infra to cut what people pay LLM providers, and the social layer agents will need when there are more of them than us.

Python, FastAPI, React, Postgres, Docker. LLM token efficiency, agent infrastructure, open data.

[TokensTree](https://tokenstree.com) · [Newsletter](https://tokenstree.com/newsletter.html) · [transfer.tokenstree.com](https://transfer.tokenstree.com) · [translation.tokenstree.com](https://translation.tokenstree.com)

---

## Projects

### 🪨🌳 [caveman_tokenstransfer.2.0](https://github.com/vfalbor/caveman_tokenstransfer.2.0)
Fork of caveman adding LLMLingua-2 input compression (`/tokenstransfer`) and multilingual token-tax fix (`/tokenstranslation`) as peers. 100% local mode. -55% cost per call on long-context workloads.

### 🌳 [TokensTree](https://tokenstree.com)
Social network for AI agents. Reputation, SafePaths knowledge graph, plant-a-tree per 1B tokens saved.

### 🚇 [transfer.tokenstree.com](https://transfer.tokenstree.com)
Hosted LLMLingua-2 prompt compression — drop 50%+ of input tokens before they reach Claude. Free tier. Self-hostable Docker image.

### 🌍 [translation.tokenstree.com](https://translation.tokenstree.com)
The BPE language tax fix. Translates non-English prompts to English (the cheap-tokens language) on the way in, and back on the way out. -25% to -55% on multilingual UX.

### 📈 [llm-language-token-tax](https://github.com/vfalbor/llm-language-token-tax)
Reproducible benchmark showing non-English prompts pay 1.55× to 3.30× more tokens for the same content on OpenAI/Claude APIs. Companion: [vs-caveman](https://github.com/vfalbor/llm-language-token-tax/tree/main/vs-caveman) input-side head-to-head.

### 🧪 [tokenstree-trading](https://tokenstree.es)
Quant trading sandbox (GBM, Monte Carlo Jump, GARCH, Kalman, HMM, stacking ensemble) publishing daily calibrated predictions.

## Tech Stack

Python, FastAPI, React, TypeScript, Postgres, Redis, Celery, Docker, LLMLingua-2, PyTorch.
