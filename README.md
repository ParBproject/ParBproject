<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/header-light.svg">
  <img alt="Par Bahrae, software developer. Forecasting and quant tools, benchmarked and tested. Python projects in time-series forecasting, portfolio and credit-risk modeling, and the dashboards that explain them." src="assets/header-dark.svg" width="100%">
</picture>

<p align="center">
  <a href="https://parbproject.github.io/"><img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-10B981?style=flat-square&labelColor=111827"></a>
  <a href="https://www.linkedin.com/in/parbahrae/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-10B981?style=flat-square&logo=linkedin&logoColor=white&labelColor=111827"></a>
</p>

<p align="center">
  Software developer building practical tools in Python, SQL, and AI.<br>
  Time-series forecasts, portfolio and credit-risk models, and dashboards that explain the results.<br>
  Forecasts and valuations are checked against naïve baselines or simple benchmarks, and committed results are pinned by tests.
</p>

<p align="center"><b>Seeking: Quantitative Analyst · Data Analyst · Forecasting / Valuation Analyst</b> · Toronto</p>

## About me

- 🔭 **I’m currently working on** Python projects for financial analysis: a DCF valuation model built from SEC filings, an equity research pitch, an energy-sector research explorer, and a commodity price forecaster. My focus is on reproducible analysis, meaningful benchmarks, and clear explanations of results.
- 🌱 **I’m currently learning** advanced time-series methods, walk-forward validation, portfolio risk management, and explainable machine learning for credit-risk assessment.
- 👯 **I’m looking to collaborate on** time-series forecasting, quantitative research, and interactive data dashboards that turn complex datasets into practical insights.
- 🤔 **I’m looking for help with** strengthening model validation, preventing data leakage, and incorporating realistic assumptions into financial backtests. I welcome thoughtful code reviews and feedback from experienced practitioners.
- 💬 **Ask me about** evaluating forecasts against naïve baselines, exploring portfolio allocation trade-offs, and building Streamlit dashboards to communicate analytical results.
- 📫 **How to reach me:** [githubproproject@proton.me](mailto:githubproproject@proton.me) or [LinkedIn](https://www.linkedin.com/in/parbahrae/).
- ⚡ **Fun fact:** I also tutor mathematics and science, and breaking down complex ideas is a skill I bring to both teaching and data analysis.

## Featured projects

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/ParBproject/dcf-valuation-model"><img src="assets/icons/models.svg" width="28" height="28" alt=""><br><b>DCF Valuation Model</b></a><br><br>
      Reproducible DCF for AAPL, MSFT, KO, JNJ, CAT and XOM from SEC EDGAR XBRL filings, with sensitivity grids, a 10,000-draw Monte Carlo, a reverse DCF and a React dashboard where every assumption is a slider.<br>
      The TypeScript engine matches the Python results to 0.01%; a calibration review explains why AAPL, MSFT and CAT value well below market instead of tuning it away.<br><br>
      <a href="https://parbproject.github.io/dcf-valuation-model/">Live demo</a>
      &nbsp;·&nbsp;
      <code>Python</code> <code>TypeScript</code> <code>React</code>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/ParBproject/stock-pitch"><img src="assets/icons/dashboard.svg" width="28" height="28" alt=""><br><b>UNH Stock Pitch</b></a><br><br>
      Long pitch on UnitedHealth built like a quant research project: frozen, hash-checked data, DCF and reverse DCF, a factor model, a walk-forward backtest and an interactive web deck.<br>
      Base-case value $526.64 vs $367.08 as-of price; the risks section shows the call flips to $321.29 with the full-sample beta.<br><br>
      <a href="https://parbproject.github.io/stock-pitch/">Live demo</a>
      &nbsp;·&nbsp;
      <code>Python</code> <code>JavaScript</code>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/ParBproject/energy-sector-deep-dive"><img src="assets/icons/series.svg" width="28" height="28" alt=""><br><b>Energy Sector Deep Dive</b></a><br><br>
      Point-in-time research on how 18 US oil &amp; gas companies in five segments trade against oil since 2015, with a linked React + ECharts explorer and an oil-scenario tool.<br>
      Producers carry the highest oil beta (0.55 per 1% WTI move) vs 0.27 for refiners; producers fell 78.7% in the 2020 crash.<br><br>
      <a href="https://parbproject.github.io/energy-sector-deep-dive/">Live demo</a>
      &nbsp;·&nbsp;
      <code>Python</code> <code>TypeScript</code> <code>ECharts</code>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/ParBproject/commodity-price-forecaster"><img src="assets/icons/forecast.svg" width="28" height="28" alt=""><br><b>Commodity Price Forecaster</b></a><br><br>
      Nine energy, metals and agriculture futures forecast with ARIMA and Prophet, scored in a 52-week rolling-origin leaderboard against naïve baselines.<br>
      A simple baseline won: Drift, average MASE 2.204, effectively tied with Naive; ARIMA and Prophet did not beat it at one week.<br><br>
      <a href="https://parbproject.github.io/commodity-price-forecaster/">Live demo</a>
      &nbsp;·&nbsp;
      <code>Python</code> <code>Streamlit</code> <code>Prophet</code>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/ParBproject/vol-forecast-ml"><img src="assets/icons/series.svg" width="28" height="28" alt=""><br><b>Volatility Forecasting (HAR vs ML)</b></a><br><br>
      Walk-forward next-day realized-volatility forecasts for SPY and nine sector ETFs: HAR-RV and GARCH vs gradient boosting and an LSTM, with Diebold-Mariano tests.<br>
      The LSTM has the lowest QLIKE on 10 of 10 ETFs (0.2968 vs 0.3262 for HAR), but no model beats HAR on MSE.<br><br>
      <a href="https://parbproject.github.io/vol-forecast-ml/">Live demo</a>
      &nbsp;·&nbsp;
      <code>Python</code> <code>PyTorch</code> <code>React</code>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/ParBproject/portfolio-risk-lab"><img src="assets/icons/portfolio.svg" width="28" height="28" alt=""><br><b>Portfolio Risk Lab</b></a><br><br>
      Mean-variance, risk parity and Black-Litterman on 21 ETFs, tested walk-forward with costs, plus VaR/CVaR and factor attribution.<br>
      Out of sample (2012-05 to 2026-09) no optimizer beat SPY (Sharpe 0.92); risk parity cut max drawdown to -12.72% vs -23.93%.<br><br>
      <a href="https://parbproject.github.io/portfolio-risk-lab/">Live demo</a>
      &nbsp;·&nbsp;
      <code>Python</code> <code>NumPy</code> <code>React</code>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/ParBproject/options-vol-surface"><img src="assets/icons/models.svg" width="28" height="28" alt=""><br><b>SPY Volatility Surface</b></a><br><br>
      Implied-volatility surface from a real SPY option chain: Black-Scholes-Merton inversion, raw SVI fits per expiry, butterfly and calendar arbitrage checks.<br>
      1,077 OTM quotes across 11 expiries; SVI errors 0.22 to 0.67 vol points, and all 11 slices are butterfly-arbitrage-free.<br><br>
      <a href="https://parbproject.github.io/options-vol-surface/">Live demo</a>
      &nbsp;·&nbsp;
      <code>Python</code> <code>SciPy</code> <code>React</code>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/ParBproject/portfolio-risk-performance-analyzer"><img src="assets/icons/dashboard.svg" width="28" height="28" alt=""><br><b>Portfolio Risk &amp; Performance Analyzer</b></a><br><br>
      Equal-weight and minimum-variance ETF portfolios vs SPY, 2006 to 2026: SQLite + SQL analysis layer, risk metrics, stress periods, Streamlit dashboard.<br>
      Equal weight cut volatility from 19.20% to 11.11% and max drawdown from -55.2% to -32.2%, at a similar Sharpe (0.52 vs 0.55).<br><br>
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

## More repositories

- **[Stroke](https://github.com/ParBproject/Stroke)** — Holdout study of the Kaggle stroke dataset: logistic regression versus tree models, calibration, and threshold choice. [Live casebook](https://parbproject.github.io/Stroke/)
- **[Generative AI Data](https://github.com/ParBproject/Generative-AI-Data)** — Browser demos for in-browser transformer sentiment, fraud exploration, a churn what-if, and data storytelling. [Live demos](https://parbproject.github.io/Generative-AI-Data/)
- **[Order fulfillment](https://github.com/ParBproject/E-commerce-Order-Fulfillment-Process-Improvement)** — Warehouse fulfillment case study on synthetic data: DuckDB SQL marts, window functions, and a before/after KPI board.
- **[Credit-risk case study](https://github.com/ParBproject/Portfolio-Risk-Analysis-Credit-Risk-Modeling)** — Written analysis of a synthetic 1,000-loan portfolio: default probability, stress tests, and a risk report.
- **[Stock screener and backtester](https://github.com/ParBproject/-Stock-Screener-Strategy-Backtester-Insider-Institutional-Signal-Tracker-)** — Streamlit equity research app for fundamental and technical screening, strategy backtests, and insider and institutional data.
- **[Algorithmic trading research](https://github.com/ParBproject/algo-trading-consultant)** — Framework to backtest, optimize, and paper-trade systematic strategies such as mean reversion, momentum, and pairs.

<sub><b>Archived:</b> [Portfolio Optimizer](https://github.com/ParBproject/Portfolio-Optimizer) · [Advanced Financial Models](https://github.com/ParBproject/Advanced-Financial-Models) · [Stock Price Predictor](https://github.com/ParBproject/stock-price-predictor) · [AI Investment Dashboard](https://github.com/ParBproject/AI-Investment-Dashboard) · [Crypto Trading Bot](https://github.com/ParBproject/Crypto-Trading-Bot) · [SkyCast](https://github.com/ParBproject/skycast) · [denly-uptime](https://github.com/ParBproject/denly-uptime) · [Cosmic Clock](https://github.com/ParBproject/-A-Real-Time-Astronomical-Cosmological-Timepiece-)</sub>

## Stack

<p align="center">
  <img alt="Python" src="https://img.shields.io/badge/Python-10B981?style=flat-square&logo=python&logoColor=white&labelColor=111827">
  <img alt="SQL" src="https://img.shields.io/badge/SQL-10B981?style=flat-square&labelColor=111827">
  <img alt="Streamlit" src="https://img.shields.io/badge/Streamlit-10B981?style=flat-square&logo=streamlit&logoColor=white&labelColor=111827">
  <img alt="scikit-learn" src="https://img.shields.io/badge/scikit--learn-10B981?style=flat-square&logo=scikitlearn&logoColor=white&labelColor=111827">
  <img alt="TensorFlow" src="https://img.shields.io/badge/TensorFlow-10B981?style=flat-square&logo=tensorflow&logoColor=white&labelColor=111827">
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
