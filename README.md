<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/header-light.svg">
  <img alt="Par Bahrae. Dark banner with an emerald accent and a small forecast chart." src="assets/header-dark.svg" width="100%">
</picture>

<p align="center">
  <a href="https://parbproject.github.io/"><img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-10B981?style=flat-square&labelColor=111827"></a>
  <a href="https://www.linkedin.com/in/parbahrae/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-10B981?style=flat-square&logo=linkedin&logoColor=white&labelColor=111827"></a>
</p>

I'm Par Bahrae, in Toronto. I write Python and SQL for forecasting, valuation, and portfolio risk, usually on public market data. If a simple baseline wins, I leave that result in the repo.

I have an honours BSc in Mathematics and Its Applications from Toronto Metropolitan University. I also tutor math and science. CAPM is in progress.

I'm looking for data analyst, quantitative analyst, or project-management roles.

## Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/ParBproject/dcf-valuation-model"><img src="assets/icons/models.svg" width="28" height="28" alt=""><br><b>DCF Valuation Model</b></a><br><br>
      A DCF for AAPL, MSFT, KO, JNJ, CAT, and XOM from SEC EDGAR filings, with sensitivity grids, a 10,000-draw Monte Carlo, a reverse DCF, and a React page where the assumptions are sliders.<br>
      The TypeScript version matches the Python results within 0.01%. AAPL, MSFT, and CAT come out well below the market price. The calibration note explains that gap instead of closing it by changing the inputs.<br><br>
      <a href="https://parbproject.github.io/dcf-valuation-model/">Live demo</a>
      &nbsp;·&nbsp;
      <code>Python</code> <code>TypeScript</code> <code>React</code>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/ParBproject/stock-pitch"><img src="assets/icons/dashboard.svg" width="28" height="28" alt=""><br><b>UNH Stock Pitch</b></a><br><br>
      A long note on UnitedHealth. The data is frozen and hash-checked. It has a DCF, a reverse DCF, a factor model, a walk-forward backtest, and a small web deck.<br>
      The base-case value is $526.64 against a $367.08 price. With the full-sample beta, the value falls to $321.29, which is under the price.<br><br>
      <a href="https://parbproject.github.io/stock-pitch/">Live demo</a>
      &nbsp;·&nbsp;
      <code>Python</code> <code>JavaScript</code>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/ParBproject/energy-sector-deep-dive"><img src="assets/icons/series.svg" width="28" height="28" alt=""><br><b>Energy Sector Deep Dive</b></a><br><br>
      How 18 US oil and gas companies, in five segments, moved with oil since 2015. There is a React and ECharts explorer and a small oil-scenario tool.<br>
      Producers had the highest oil beta (0.55 per 1% WTI move) and refiners the lowest (0.27). Producers fell 78.7% in the 2020 crash.<br><br>
      <a href="https://parbproject.github.io/energy-sector-deep-dive/">Live demo</a>
      &nbsp;·&nbsp;
      <code>Python</code> <code>TypeScript</code> <code>ECharts</code>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/ParBproject/commodity-price-forecaster"><img src="assets/icons/forecast.svg" width="28" height="28" alt=""><br><b>Commodity Price Forecaster</b></a><br><br>
      Weekly forecasts for nine energy, metals, and agriculture futures. ARIMA and Prophet are scored on a 52-week rolling-origin board against naïve baselines.<br>
      Drift won, with an average MASE of 2.204, basically tied with naïve. ARIMA and Prophet did not beat it at a one-week horizon.<br><br>
      <a href="https://parbproject.github.io/commodity-price-forecaster/">Live demo</a>
      &nbsp;·&nbsp;
      <code>Python</code> <code>Streamlit</code> <code>Prophet</code>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/ParBproject/vol-forecast-ml"><img src="assets/icons/series.svg" width="28" height="28" alt=""><br><b>Volatility Forecasting (HAR vs ML)</b></a><br><br>
      Next-day realized-volatility forecasts for SPY and nine sector ETFs, run walk-forward. HAR-RV and GARCH against gradient boosting and an LSTM, with Diebold-Mariano tests.<br>
      The LSTM has the lowest QLIKE on all 10 ETFs (0.2968 vs 0.3262 for HAR). On MSE, nothing beats HAR.<br><br>
      <a href="https://parbproject.github.io/vol-forecast-ml/">Live demo</a>
      &nbsp;·&nbsp;
      <code>Python</code> <code>PyTorch</code> <code>React</code>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/ParBproject/portfolio-risk-lab"><img src="assets/icons/portfolio.svg" width="28" height="28" alt=""><br><b>Portfolio Risk Lab</b></a><br><br>
      Mean-variance, risk parity, and Black-Litterman on 21 ETFs, tested walk-forward with costs, plus VaR/CVaR and factor attribution.<br>
      From May 2012 to September 2026, none of the optimizers beat SPY (Sharpe 0.92). Risk parity cut the max drawdown to −12.72%, from −23.93% for SPY.<br><br>
      <a href="https://parbproject.github.io/portfolio-risk-lab/">Live demo</a>
      &nbsp;·&nbsp;
      <code>Python</code> <code>NumPy</code> <code>React</code>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/ParBproject/options-vol-surface"><img src="assets/icons/models.svg" width="28" height="28" alt=""><br><b>SPY Volatility Surface</b></a><br><br>
      An implied-volatility surface from one SPY option chain: Black-Scholes-Merton inversion, a raw SVI fit per expiry, and butterfly and calendar checks.<br>
      1,077 out-of-the-money quotes across 11 expiries. SVI error is 0.22 to 0.67 vol points, and all 11 slices are free of butterfly arbitrage.<br><br>
      <a href="https://parbproject.github.io/options-vol-surface/">Live demo</a>
      &nbsp;·&nbsp;
      <code>Python</code> <code>SciPy</code> <code>React</code>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/ParBproject/portfolio-risk-performance-analyzer"><img src="assets/icons/dashboard.svg" width="28" height="28" alt=""><br><b>Portfolio Risk &amp; Performance Analyzer</b></a><br><br>
      Equal-weight and minimum-variance mixes of six ETFs against SPY, 2006 to 2026. Prices go into SQLite, the summary queries are SQL, and a Streamlit page shows the risk stats.<br>
      Equal weight cut volatility from 19.20% to 11.11% and max drawdown from −55.2% to −32.2%. Sharpe stayed about the same (0.52 vs 0.55).<br><br>
      <a href="https://parbproject.github.io/portfolio-risk-performance-analyzer/">Live demo</a>
      &nbsp;·&nbsp;
      <code>Python</code> <code>SQL</code> <code>Streamlit</code>
    </td>
  </tr>
</table>

<p align="center">
  <a href="https://parbproject.github.io/dcf-valuation-model/"><img src="https://raw.githubusercontent.com/ParBproject/dcf-valuation-model/main/docs/screenshots/m7-overview-1440.png" alt="DCF dashboard overview" width="32%"></a>
  <a href="https://parbproject.github.io/stock-pitch/"><img src="https://raw.githubusercontent.com/ParBproject/stock-pitch/main/docs/img/hero.png" alt="UNH stock pitch web deck" width="32%"></a>
  <a href="https://parbproject.github.io/energy-sector-deep-dive/"><img src="https://raw.githubusercontent.com/ParBproject/energy-sector-deep-dive/main/docs/img/hero.png" alt="Energy sector explorer" width="32%"></a>
</p>

## Other repositories

- **[Stroke](https://github.com/ParBproject/Stroke)** — Holdout look at the Kaggle stroke file: logistic regression against tree models, plus calibration and a threshold. [Live casebook](https://parbproject.github.io/Stroke/)
- **[Generative AI Data](https://github.com/ParBproject/Generative-AI-Data)** — Browser demos: in-browser transformer sentiment, a fraud view, a churn what-if, and a short data story. [Live demos](https://parbproject.github.io/Generative-AI-Data/)
- **[Order fulfillment](https://github.com/ParBproject/E-commerce-Order-Fulfillment-Process-Improvement)** — Warehouse case on synthetic data: DuckDB SQL, window functions, and a before/after KPI board.
- **[Credit-risk case study](https://github.com/ParBproject/Portfolio-Risk-Analysis-Credit-Risk-Modeling)** — Write-up of a synthetic 1,000-loan book: default probability, stress tests, and a short risk report.
- **[Stock screener and backtester](https://github.com/ParBproject/-Stock-Screener-Strategy-Backtester-Insider-Institutional-Signal-Tracker-)** — Streamlit app for fundamental and technical screens, strategy backtests, and insider and institutional data.
- **[Algorithmic trading research](https://github.com/ParBproject/algo-trading-consultant)** — Code to backtest, tune, and paper-trade simple rules such as mean reversion, momentum, and pairs.

<sub><b>Archived:</b> [Portfolio Optimizer](https://github.com/ParBproject/Portfolio-Optimizer) · [Advanced Financial Models](https://github.com/ParBproject/Advanced-Financial-Models) · [Stock Price Predictor](https://github.com/ParBproject/stock-price-predictor) · [AI Investment Dashboard](https://github.com/ParBproject/AI-Investment-Dashboard) · [Crypto Trading Bot](https://github.com/ParBproject/Crypto-Trading-Bot) · [SkyCast](https://github.com/ParBproject/skycast) · [denly-uptime](https://github.com/ParBproject/denly-uptime) · [Cosmic Clock](https://github.com/ParBproject/-A-Real-Time-Astronomical-Cosmological-Timepiece-)</sub>

## Tools

<p align="center">
  <img alt="Python" src="https://img.shields.io/badge/Python-10B981?style=flat-square&logo=python&logoColor=white&labelColor=111827">
  <img alt="SQL" src="https://img.shields.io/badge/SQL-10B981?style=flat-square&labelColor=111827">
  <img alt="Streamlit" src="https://img.shields.io/badge/Streamlit-10B981?style=flat-square&logo=streamlit&logoColor=white&labelColor=111827">
  <img alt="scikit-learn" src="https://img.shields.io/badge/scikit--learn-10B981?style=flat-square&logo=scikitlearn&logoColor=white&labelColor=111827">
  <img alt="PyTorch" src="https://img.shields.io/badge/PyTorch-10B981?style=flat-square&logo=pytorch&logoColor=white&labelColor=111827">
  <br>
  <img alt="Plotly" src="https://img.shields.io/badge/Plotly-10B981?style=flat-square&logo=plotly&logoColor=white&labelColor=111827">
  <img alt="DuckDB" src="https://img.shields.io/badge/DuckDB-10B981?style=flat-square&logo=duckdb&logoColor=white&labelColor=111827">
  <img alt="GitHub Actions" src="https://img.shields.io/badge/GitHub_Actions-10B981?style=flat-square&logo=githubactions&logoColor=white&labelColor=111827">
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-10B981?style=flat-square&logo=typescript&logoColor=white&labelColor=111827">
  <img alt="React" src="https://img.shields.io/badge/React-10B981?style=flat-square&logo=react&logoColor=white&labelColor=111827">
  <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-10B981?style=flat-square&logo=javascript&logoColor=white&labelColor=111827">
</p>

## Contact

[githubproproject@proton.me](mailto:githubproproject@proton.me) · [LinkedIn](https://www.linkedin.com/in/parbahrae/)
