## mahdi afshari

cs @ mit, bs 2027 into meng 2028. i build systems, and i work on language models: post-training, forecasting, agents.

currently in [jacob andreas's group at csail](https://lingo.csail.mit.edu/), building an rl post-training loop (rest-em, then grpo) that trains a policy to inject task-relevant knowledge into a frozen model's context.

### selected work

- [oracle](https://github.com/ithons/oracle): forecasting pipeline for kalshi markets. the blind-forecast quarantine is enforced at the model layer and again at the tool layer, so the pipeline never sees a market's price before it commits to a forecast. log-odds aggregation across runs, fee-aware recommendation math, and a leakage-checked backtest replay.
- [mizan](https://github.com/ithons/mizan): local-first personal finance app. syncs bank and crypto accounts, encrypts credentials at rest with aes-256-gcm, sends no telemetry. data leaves the machine only on an explicit query.
- [public-games](https://github.com/ithons/public-games): llm agent memory in repeated social dilemmas. a hybrid trust-table plus strategy-note memory doubled group welfare over every other representation (240 vs. ~120) by unlocking full cooperation, while raw full-history memory gave no benefit over no memory at all despite 50% more tokens.
- [straggler](https://github.com/ithons/straggler): straggler-aware scheduler for distributed training. allocates gradient-sync rate to minimize collective completion time instead of per-flow fairness. cut iteration time 45% under persistent stragglers (1298ms to 717ms), at under 1% overhead in the bursty case. [paper](https://mahdiafshari.com/papers/straggler-6.5820-final-report.pdf)
- mausa: congestion-aware routing for an interplanetary delay-tolerant network (nasa solarnet simulation). worst-case control-message overhead of 0.008% of link bandwidth, while meeting delivery deadlines across earth, moon, and mars links. [paper](https://mahdiafshari.com/papers/mausa-6.1800-final-report.pdf)

most of my research code (self-adapting language models, the multi-agent negotiation environment, and the prediction-market forecasting study now under review) lives in private repos. happy to walk through any of it.

### elsewhere

[site](https://mahdiafshari.com) · [linkedin](https://linkedin.com/in/mahdiafshari) · afshari@mit.edu
