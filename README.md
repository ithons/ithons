## mahdi afshari

cs @ mit, bs 2027 into meng 2028. i work on language models: rl post-training, forecasting, and multi-agent systems, in [jacob andreas's group at csail](https://lingo.csail.mit.edu/).

right now: an rl loop that trains a small policy to find and inject the knowledge a frozen language model needs for a task, scored by how much its accuracy improves on held-out questions.

### selected work

- forecasting: built the polymarket data pipeline and news-source setups for the agents in a csail study showing llm forecasters match market accuracy while earning higher returns (+4.0% vs −0.5% roi, p = 0.004); forecast@icml26 spotlight.
- simorgh: llm forecasting pipeline for kalshi markets. models never see the market price before they commit to a forecast; leakage-checked backtests and calibration-weighted aggregation across models and runs. (private for now)
- [public-games](https://github.com/ithons/public-games): how much memory an llm agent needs to keep cooperating in a repeated public-goods game. a hybrid trust-table plus strategy-note memory doubled group welfare (240 vs ~120); full chat history cost 50% more tokens and bought nothing.
- mizan: local-first personal finance app. bank and crypto sync, credentials encrypted at rest, no telemetry. (private for now)
- also: a straggler-aware scheduler for distributed training (45% faster iterations under persistent stragglers, [paper](https://mahdiafshari.com/papers/straggler-6.5820-final-report.pdf)) and a delay-tolerant routing protocol for an earth-moon-mars network simulation ([paper](https://mahdiafshari.com/papers/mausa-6.1800-final-report.pdf)).

research code (self-adapting language models, the multi-agent negotiation environment) is in private repos. happy to walk through any of it.
