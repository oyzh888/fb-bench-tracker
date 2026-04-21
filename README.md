# fb-bench-tracker

Finance-Bench evaluation tracker — automated dashboard for [QuantitativeFinance-Bench](https://github.com/when2buy/QuantitativeFinance-Bench) trials.

## [📊 Dashboard](DASHBOARD.md)

## What's tracked

- **145 tasks** across quantitative finance domains (options, fixed income, risk, portfolio, etc.)
- **Multiple models**: Haiku 4.5, Sonnet 4.5, Opus 4.6, Gemini, GPT-5
- **Oracle validation**: ground truth pass/fail/broken status
- **Agent**: Claude Code via [Harbor](https://github.com/harbor-framework/harbor) framework

## Infrastructure

Runs on Adobe Pluto cluster with Docker-in-Docker (DinD) training jobs. See dashboard for details.
