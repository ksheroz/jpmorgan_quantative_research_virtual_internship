# JPMorgan Chase Quantitative Research — Job Simulation

Four-task [Forage](https://www.theforage.com/simulations/jpmorgan/quantitative-research-11oc) QR simulation: natural gas price forecasting, storage contract pricing, credit risk (PD/expected loss) modeling, and FICO score bucketing via dynamic programming.

- **Task 1:** OLS trend + seasonal (sin/cos) model for gas price interpolation/extrapolation, validated with walk-forward RMSE and residual diagnostics.
- **Task 2:** Event-simulation pricer for multi-date storage contracts with a full auditable cash-flow ledger.
- **Task 3:** Logistic regression PD model (caught and fixed a quasi-separation issue) with explicit calibration checking, wrapped into an expected-loss function.
- **Task 4:** Optimal FICO bucketing via dynamic programming, comparing MSE vs. log-likelihood objectives.

Each notebook includes data validation, out-of-sample checks, and documented scope limitations.
