## mahdi afshari

cs @ mit (bs '27 → meng '28). i build systems and work on language models — post-training, forecasting, and multi-agent behavior.

currently in [jacob andreas's group at csail](https://lingo.csail.mit.edu/), building an rl post-training loop (rest-em → grpo) that trains a policy to inject task-relevant knowledge into a frozen model's context.

### selected work

- **[oracle](https://github.com/ithons/oracle)** — research-grade forecasting pipeline for kalshi markets. provider-neutral, with a blind-forecasting quarantine enforced at both the model and tool layers so the pipeline never sees a market's price before it commits a forecast. log-odds aggregation across runs, fee-aware recommendation math, and a leakage-checked backtest replay.
- **[mizan](https://github.com/ithons/mizan)** — local-first personal finance app. syncs bank and crypto accounts with aes-256-gcm credential encryption at rest and zero telemetry; data leaves the device only on an explicit query.
- **[public-games](https://github.com/ithons/public-games)** — llm agent memory in repeated social dilemmas. a hybrid trust-table + strategy-note memory doubled group welfare over every other representation (240 vs. ~120) by unlocking full cooperation, while raw full-history memory gave no benefit over no memory despite 50% more tokens.
- **straggler-aware scheduler for distributed training** — adaptive rate allocation for gradient sync that optimizes collective completion time instead of per-flow fairness. cut iteration time 45% under persistent stragglers (1298ms → 717ms) at under 1% overhead in the bursty case. [paper](https://mahdiafshari.com/papers/straggler-6.5820-final-report.pdf)
- **mausa** — congestion-aware routing for an interplanetary delay-tolerant network (nasa solarnet simulation). held control-message overhead under 8% while meeting delivery deadlines across earth–moon–mars links. [paper](https://mahdiafshari.com/papers/mausa-6.1800-final-report.pdf)

most of my research code — self-adapting language models, the multi-agent negotiation environment, and the prediction-market forecasting study now under review — lives in private repos. happy to walk through any of it.

### elsewhere

[site](https://mahdiafshari.com) · [linkedin](https://linkedin.com/in/mahdiafshari) · afshari@mit.edu
