# Stochastic Consumption Forecasting

This project explores probabilistic demand forecasting for small, volatile inventory based on a QC environment. I modeled weekly consumption as an overdispersed count process and generated forecast distributions (not just point estimates) and selected forecast values based on a decision rule. The probabilistic model was stress-tested using rolling-origin evaluation.

**The key result**
Consumption inherently had tight stock caps, high variance across windows, and short shelf-life. The overdispersed count model did not produce stable, decision-grade forecasts. The key insight learned was that this small inventory consumption was best managed primarily with expert oversight and benefited from real time usage metrics rather than longer term forecasts.


Project URL: https://thefifthpostulate.github.io/Stochastic-Consumption-Forecasting/InventoryProject.html
