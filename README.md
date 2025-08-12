# High-Frequency BTCUSD Trading Bot with Probabilistic Ensemble Model
This repository contains an automated trading system for BTCUSD that combines a Bayesian Neural Network with logistic regression to predict one-minute price directions with uncertainty estimation. The system connects to MetaTrader 5 for live trading execution.

Key Features
Probabilistic ensemble model (BNN + Logistic Regression)

Monte Carlo dropout for uncertainty estimation

Comprehensive feature engineering (technical indicators, candlestick patterns)

Real-time trading through MetaTrader 5 API

Confidence-based trade filtering

Risk management with stop-loss/take-profit

```bash
# Install requirements
pip install -r requirements.txt
```
Please intall the MetaTrader 5 application on your pc and replace the path in the file.
```bash
MT5_CONFIG = {
    "path": r"C:\Program Files\MetaTrader 5\terminal64.exe", #This need to be replaced
    "login": account,
    "password": password,
    "server": server,
}
```
Finally, allow "AutoTrade" in the MetaTrader 5.
