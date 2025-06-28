# z_score_spread_trading
Rolling Z score trading

Hypothesis: 2 fairly correlated assets i.e USDTHB EURTHB should trade closely in line as most of driving factors are due to base ccy (USD EUR) so their cumulative returns should not defer too much. Hence rolling z-score of return and spot rate differential and execute spread trade when differential hits trader defined X standard deviations.

TODO:
Add drawdown, TP/SL conditions
