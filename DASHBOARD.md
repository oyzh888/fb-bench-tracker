# Finance-Bench Evaluation Dashboard

> Last updated: 2026-04-21 17:16 UTC
> Tasks: 145 total, 19 broken (excluded from scoring)

## Summary

| Model | Completed | Pass (reward>0.5) | Fail | Error | Pass Rate |
|-------|-----------|-------------------|------|-------|-----------|
| **Haiku 4.5** | 120 | 39 | 80 | 7 | 32.8% |
| **Sonnet 4.5** | 120 | 55 | 64 | 7 | 46.2% |

## Other Model Runs (non-PR tasks)

| Model | Trials | Pass | Fail | Pass Rate |
|-------|--------|------|------|-----------|
| GPT-5 | 96 | 0 | 96 | 0.0% |
| Gemini | 96 | 0 | 96 | 0.0% |
| Haiku 4.5 (original 16) | 33 | 0 | 33 | 0.0% |
| Haiku 4.5 Bedrock | 96 | 13 | 83 | 13.5% |
| Opus 4 | 32 | 0 | 32 | 0.0% |
| Opus 4.6 | 96 | 31 | 65 | 32.3% |
| Sonnet 4 | 130 | 10 | 120 | 7.7% |
| Sonnet 4.5 (original 16) | 97 | 14 | 83 | 14.4% |

## Detailed Results (PR Tasks)

| Task | Oracle | Haiku 4.5 | Sonnet 4.5 |
|------|--------|-----------|------------|
| 13f-amendment-aware-crowding | 🔧 broken | — | — |
| alpha-hedge-strategy | ❌ fail | ✅ 0.6 | ✅ 1.0 |
| american-binomial-tree | ? | ✅ 1.0 | ✅ 1.0 |
| american-option-fd-new | ✅ pass | ❌ 0.0 | ❌ 0.0 |
| amortization-schedule | ✅ pass | ✅ 1.0 | ✅ 1.0 |
| asian-option-levy-curran | ? | ❌ 0.0 | ❌ 0.0 |
| asian-option-pricing | ✅ pass | ✅ 1.0 | ✅ 1.0 |
| barone-adesi-whaley | ? | ❌ 0.0 | ✅ 1.0 |
| barra-cne6-risk | ❌ fail | ❌ 0.2 | ❌ 0.3 |
| barrier-garch-var | solve_fail | ❌ 0.1 | ✅ 0.7 |
| barrier-gbm-analytics | ? | ❌ 0.0 | ❌ 0.0 |
| barrier-option-mc | ✅ pass | ❌ 0.0 | ✅ 1.0 |
| beta-hedging | ✅ pass | ✅ 1.0 | ✅ 1.0 |
| binance-btc-participation-tca | build_fail | — | — |
| binary-option-pricing | ✅ pass | ✅ 1.0 | ✅ 1.0 |
| bl-regime-hmm | ❌ fail | ❌ 0.5 | ✅ 0.6 |
| black-litterman-allocation | 🔧 broken | — | — |
| black-scholes-pricing | ✅ pass | ✅ 1.0 | ✅ 1.0 |
| bollinger-backtest-aapl | ✅ pass | ❌ 0.0 | ✅ 1.0 |
| bond-callable-pricing | solve_fail | — | — |
| bond-convexity | ✅ pass | ✅ 1.0 | ✅ 1.0 |
| bond-portfolio-analytics | ✅ pass | ✅ 1.0 | ✅ 1.0 |
| bond-yield-curve | ✅ pass | ✅ 1.0 | ❌ 0.0 |
| brinson-sector-attribution | ✅ pass | ❌ 0.0 | ❌ 0.0 |
| bs-greeks-pde | ? | ❌ 0.0 | ✅ 1.0 |
| cap-floor-black-pricing | ✅ pass | ❌ 0.0 | ❌ 0.0 |
| carry-trade-fx | solve_fail | — | — |
| cds-curve-stripping | ✅ pass | ❌ 0.0 | ❌ 0.0 |
| cds-pricing | ✅ pass | ✅ 1.0 | ✅ 1.0 |
| cev-option-pricing | ? | ❌ 0.0 | ❌ 0.0 |
| cheapest-ETF-creation-basket | 🔧 broken | ❌ 0.0 | ✅ 1.0 |
| chooser-option-pricing | ? | ❌ 0.0 | ❌ 0.0 |
| cir-bond-pricing | ? | ✅ 1.0 | ✅ 1.0 |
| cir-calibration | 🔧 broken | — | — |
| cliquet-ratchet-pricing | ? | ❌ 0.0 | ❌ 0.0 |
| cme-hdd-option-pricing | solve_fail | ❌ 0.0 | ✅ 1.0 |
| compound-option-geske | ? | ✅ 1.0 | ❌ 0.0 |
| corporate-action-adjustment | ✅ pass | ✅ 1.0 | ✅ 1.0 |
| credit-migration-matrix | ✅ pass | ❌ 0.0 | ❌ 0.0 |
| credit-portfolio-var-cvar | solve_fail | ❌ 0.0 | ❌ 0.0 |
| credit-spread-decomposition | ✅ pass | ❌ 0.0 | ✅ 1.0 |
| cross-sectional-momentum | ✅ pass | ✅ 1.0 | ✅ 1.0 |
| crypto-funding-rate-basis-carry | solve_fail | ❌ 0.0 | ❌ 0.0 |
| cta-basel-capital | solve_fail | ❌ 0.2 | ❌ 0.2 |
| cta-ewma-cvar | ✅ pass | ❌ 0.0 | ❌ 0.0 |
| data-cleaning | ✅ pass | ✅ 1.0 | ✅ 1.0 |
| dcc-garch-portfolio-var | ✅ pass | ❌ 0.0 | ❌ 0.0 |
| delta-hedging-pnl-simulation | ✅ pass | ❌ 0.0 | ✅ 1.0 |
| digital-barrier-options | ? | ❌ 0.0 | ✅ 1.0 |
| dirty-gap-momentum-aapl | ✅ pass | ✅ 1.0 | ✅ 1.0 |
| double-barrier-options | ? | ❌ 0.0 | ❌ 0.0 |
| double-sort | ❌ fail | — | — |
| dupire-local-vol | ? | ❌ 0.0 | ❌ 0.0 |
| earnings-news-event-alpha | solve_fail | ❌ 0.0 | ❌ 0.0 |
| earnings-surprise-calculator | ✅ pass | ✅ 1.0 | ✅ 1.0 |
| equity-vendor-restatement-break-audit | solve_fail | ❌ 0.0 | ❌ 0.0 |
| etf-cross-asset-lead-lag | solve_fail | ❌ 0.0 | ❌ 0.0 |
| etf-overlap-redemption-pressure | 🔧 broken | — | — |
| event-study-earnings | ✅ pass | ❌ 0.0 | ❌ 0.0 |
| evt-pot-var | ❌ fail | ✅ 0.7 | ✅ 0.9 |
| ewma-portfolio-risk-decomposition | ✅ pass | ❌ 0.0 | ✅ 1.0 |
| execution-is-vwap | ✅ pass | ❌ 0.0 | ❌ 0.0 |
| execution-ledger-pnl-reconciliation | ✅ pass | ✅ 1.0 | ✅ 1.0 |
| factor-momentum-spanning | ✅ pass | ❌ 0.0 | ❌ 0.0 |
| fama-french-factor-model-new | ✅ pass | ✅ 1.0 | ✅ 1.0 |
| fama-macbeth-risk-premia | ✅ pass | ❌ 0.0 | ❌ 0.0 |
| first-passage-time | ? | ❌ 0.0 | ✅ 1.0 |
| fixed-income-market-stress | ✅ pass | ✅ 1.0 | ✅ 1.0 |
| fomc-tone-event-study | ✅ pass | ❌ 0.0 | ❌ 0.0 |
| form4-cross-sectional-sale-pressure | 🔧 broken | — | — |
| futures-carry-repair | 🔧 broken | — | — |
| fx-carry-forward-hedge | ✅ pass | ❌ 0.0 | ❌ 0.0 |
| fx-carry-trade-backtest | ✅ pass | ❌ 0.0 | ❌ 0.0 |
| fx-forward-cross-rate | ✅ pass | ❌ 0.0 | ✅ 1.0 |
| fx-quanto-options | ? | ❌ 0.0 | ❌ 0.0 |
| garch-vecm-cointegration | ✅ pass | ✅ 1.0 | ✅ 1.0 |
| geometric-mean-reverting-jd | ? | ❌ 0.0 | ❌ 0.0 |
| heston-cf-pricing | ? | ❌ 0.0 | ❌ 0.0 |
| heston-mc-pricing | 🔧 broken | — | — |
| historical-var-data-prep | ✅ pass | ✅ 1.0 | ✅ 1.0 |
| hull-white-swaption | ✅ pass | ❌ 0.0 | ❌ 0.0 |
| implied-vol-approximations | ? | ❌ 0.0 | ❌ 0.0 |
| insider-buy-clusters | 🔧 broken | — | — |
| interest-rate-cap-floor | ✅ pass | ❌ 0.0 | ✅ 1.0 |
| intraday-volume-fitting-and-execution-scheduling | ❌ fail | ❌ 0.0 | ✅ 1.0 |
| ipca-latent-factors | ❌ fail | ❌ 0.3 | ❌ 0.3 |
| kelly-var-sizing | solve_fail | ✅ 0.9 | ✅ 0.8 |
| kou-double-exponential | ? | ❌ 0.0 | ❌ 0.0 |
| ledoit-wolf-shrinkage | ✅ pass | ✅ 1.0 | ❌ 0.0 |
| liquidity-var-backtest | 🔧 broken | — | — |
| lmm-markov-representation | ❌ fail | ❌ 0.0 | ❌ 0.0 |
| lob-pc-signal | 🔧 broken | — | — |
| localvol-barrier | ✅ pass | ❌ 0.0 | ❌ 0.0 |
| lookback-options | ? | ❌ 0.0 | ✅ 1.0 |
| markowitz-efficient-frontier | ✅ pass | ❌ 0.0 | ❌ 0.0 |
| mc-greek-surface-1 | ✅ pass | ❌ 0.0 | ❌ 0.0 |
| mc-greeks-surface | ✅ pass | ❌ 0.0 | ❌ 0.0 |
| merton-cds-copula | ❌ fail | ✅ 0.9 | ✅ 0.9 |
| merton-jump-diffusion | 🔧 broken | — | — |
| minimum-cost-equity-etf-hedger | ❌ fail | ✅ 1.0 | ✅ 1.0 |
| ml-credit-scoring-fairness | ✅ pass | ❌ 0.0 | ❌ 0.0 |
| momentum-backtest | ✅ pass | ✅ 1.0 | ✅ 1.0 |
| mtm-xccy-basis-desk | solve_fail | ❌ 0.0 | ❌ 0.0 |
| multimodal-alpha-fusion-edgar-cot-gdelt | solve_fail | ❌ 0.0 | ❌ 0.0 |
| nelson-siegel-yield-curve-fit | ❌ fail | ❌ 0.0 | ❌ 0.0 |
| option-put-call-parity-forward-audit | build_fail | — | — |
| ou-jump-commodity | ? | ✅ 1.0 | ❌ 0.0 |
| ou-pairs-trading | 🔧 broken | — | — |
| pairs-cointegration-kalman | ❌ fail | ❌ 0.4 | ✅ 0.7 |
| pairs-trading-cointegration | ✅ pass | ❌ 0.0 | ❌ 0.0 |
| pca-factor-portfolio | ✅ pass | ✅ 1.0 | ✅ 1.0 |
| perpetual-funding-ledger-reconciliation | build_fail | — | — |
| polars-api-migration | 🔧 broken | — | — |
| portfolio-risk-attribution | ✅ pass | ❌ 0.0 | ❌ 0.0 |
| post-earnings-drift | 🔧 broken | — | — |
| power-options | ? | ❌ 0.0 | ❌ 0.0 |
| prediction-markets-cross-venue-dislocation | build_fail | — | — |
| quantamental-earnings-jumpfilter-committee | 🔧 broken | — | — |
| rainbow-option-pricing | ? | ❌ 0.0 | ❌ 0.0 |
| realized-vol-estimators | ✅ pass | ✅ 1.0 | ❌ 0.0 |
| regime-cta-vol-target | solve_fail | ❌ 0.3 | ❌ 0.4 |
| regime-riskparity-cvar | solve_fail | ❌ 0.3 | ❌ 0.4 |
| residual-momentum | ✅ pass | ❌ 0.0 | ✅ 1.0 |
| rough-vol-rbgergomi | 🔧 broken | — | — |
| sec-10k-report-long | 🔧 broken | — | — |
| sec-8k-event-alpha | ❌ fail | ✅ 1.0 | ✅ 0.5 |
| sector-neutral-residual-momentum | ✅ pass | ❌ 0.0 | ❌ 0.0 |
| sentiment-factor-alpha | solve_fail | ❌ 0.3 | ✅ 0.5 |
| shrinkage-meanvar-portfolio | ✅ pass | ❌ 0.0 | ❌ 0.0 |
| sma-crossover-spy | ✅ pass | ✅ 1.0 | ✅ 1.0 |
| spread-option-kirk-margrabe | ? | ❌ 0.0 | ✅ 1.0 |
| stable-residual | ✅ pass | ❌ 0.0 | ❌ 0.0 |
| stochvol-implied-surface-new | ✅ pass | ❌ 0.0 | ❌ 0.0 |
| structured-note-risk | 🔧 broken | — | — |
| swap-curve-bootstrap-ois | ✅ pass | ❌ 0.0 | ✅ 1.0 |
| trace-rate-flow-analysis | ✅ pass | ✅ 1.0 | ❌ 0.0 |
| treasury-curve-pca-butterfly | ✅ pass | ❌ 0.0 | ❌ 0.0 |
| ust-carry-roll-down-attribution | solve_fail | ❌ 0.0 | ✅ 1.0 |
| var-ebacktest-coverage | ✅ pass | ❌ 0.0 | ❌ 0.0 |
| variance-swap-pricing | ? | ✅ 1.0 | ✅ 1.0 |
| variance-swap-replication | ✅ pass | ✅ 1.0 | ✅ 1.0 |
| yield-curve-bond-immunization | ✅ pass | ❌ 0.0 | ❌ 0.0 |
| yield-curve-bootstrap-immunization | ✅ pass | ❌ 0.0 | ✅ 1.0 |
| yield-curve-pca-dynamics | ✅ pass | ✅ 1.0 | ❌ 0.0 |
| zero-coupon-bootstrapping | ✅ pass | ✅ 1.0 | ✅ 1.0 |

## Infrastructure

| Resource | Details |
|----------|---------|
| Cluster | Adobe Pluto (OD-Cluster) |
| CPU Worker | c6id.24xlarge (96 vCPU, 192GB RAM) |
| GPU Worker | p5en.48xlarge (8×H200) / g5.12xlarge (4×A10G) |
| Docker | DinD via Training job (`enable_docker=True`) |
| LLM API | AWS Bedrock |
| Eval Framework | [Harbor](https://github.com/harbor-framework/harbor) |

---
*Generated automatically at 2026-04-21 17:16 UTC*