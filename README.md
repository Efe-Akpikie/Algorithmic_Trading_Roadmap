# Applied Quantitative Finance & Algorithmic Trading

A structured four-course learning sequence progressing from foundational statistics and machine learning to advanced financial ML and professional-grade quant research practices.

---

## **Course 1 — Foundations of Statistical Learning and Quantitative Trading**

**Objective**  
Build core statistical intuition, basic machine learning understanding, and the ability to code and evaluate simple quantitative trading strategies.

**Primary Texts**
- *Statistics and Data Analysis for Financial Engineering by David Ruppert and David S. Matteson* 
- *An Introduction to Statistical Learning (ISLP) by Gareth James, Daniela Witten, Trevor Hastie and Robert Tibshirani*  
- *Quantitative Trading Strategies Using Python: Technical Analysis, Statistical Testing, and Machine Learning by Liu Peng*

**Key Topics**
- Probability, estimation, regression, and inference
- Bias–variance tradeoff and model validation
- Supervised learning fundamentals
- Market mechanics and basic trading rules
- Coding and backtesting introductory strategies

**Capstone Project**  
**Single-Asset Strategy Research Notebook**  
Students design, implement, and evaluate a single-asset trading strategy (e.g., momentum or mean reversion). The project must include:
- Data acquisition and cleaning
- Feature construction and exploratory analysis
- Strategy rules and basic ML enhancement (optional)
- Backtesting with clear assumptions
- Performance evaluation and discussion of overfitting risks

**Outcome**  
Students can analyze financial data, implement simple strategies in Python, and understand common sources of overfitting and statistical error.

---

## **Course 2 — Algorithmic Trading Systems and Machine Learning Workflows**

**Objective**  
Transition from toy strategies to realistic algorithmic trading systems with robust backtesting, execution awareness, and ML-driven workflows.

**Primary Texts**
- *Successful Algorithmic Trading by Michael L. Halls-Moore* 
- *Advanced Algorithmic Trading by Michael L. Halls-Moore*  
- *Machine Learning for Algorithmic Trading by Stefan Jansen*

**Key Topics**
- Backtesting bias, transaction costs, and slippage
- Walk-forward validation and time-series cross-validation
- Feature engineering for financial data
- Portfolio construction and evaluation
- Practical ML pipelines for trading systems

**Capstone Project**  
**Multi-Asset ML Trading System**  
Students build an end-to-end ML trading pipeline across multiple assets. Requirements include:
- Feature engineering across assets and time
- Model training with time-series-aware validation
- Portfolio construction logic
- Transaction cost and slippage modeling
- Walk-forward backtesting and performance attribution

**Outcome**  
Students can design, test, and evaluate algorithmic strategies with realistic assumptions and end-to-end ML workflows.

---

## **Course 3 — Financial Time Series, Portfolio Construction, and Risk Modeling**

**Objective**  
Develop a deep understanding of financial time series behavior, volatility dynamics, and portfolio-level risk management.

**Primary Texts**
- *Analysis of Financial Time Series by Ruey S. Tsay*  
- *The Elements of Quantitative Investing by Giuseppe A. Paleologo*

**Key Topics**
- Stationarity, ARMA, GARCH, and regime models
- Volatility modeling and diagnostics
- Portfolio optimization under constraints
- Estimation error, turnover, and transaction costs
- Risk metrics beyond Sharpe (drawdowns, tail risk)

**Capstone Project**  
**Risk-Aware Portfolio Strategy**  
Students construct and evaluate a portfolio strategy emphasizing risk control. The project must include:
- Time-series modeling of returns and volatility
- Portfolio optimization under constraints
- Explicit turnover and transaction cost controls
- Stress testing and drawdown analysis
- Comparison against naive benchmarks

**Outcome**  
Students can model asset dynamics, construct portfolios robustly, and manage risk at the system level.

---

## **Course 4 — Advanced Financial Machine Learning and Quantitative Research Methods**

**Objective**  
Master advanced ML theory and learn research practices that prevent false discoveries in financial ML.

**Primary Texts**
- *The Elements of Statistical Learning (ESL) by by Jerome Friedman, Trevor Hastie and Robert Tibshirani*  
- *Advances in Financial Machine Learning by by Marcos Lopez de Prado*
- *Machine Learning in Finance: from theory to practice by Igor Halperin, Matthew Dixon, and Paul A. Bilokon*

**Key Topics**
- High-dimensional ML and regularization
- Trees, ensembles, and nonlinear methods
- Financial labeling and meta-labeling
- Purged and embargoed cross-validation
- Research hygiene and overfitting control

**Capstone Project**  
**Research-Grade Alpha Discovery Study**  
Students conduct a full alpha research study with strict research hygiene:
- Hypothesis formulation and economic rationale
- Feature and label design
- Purged/embargoed cross-validation
- Statistical significance and robustness testing
- Clear documentation of assumptions and failure modes

**Outcome**  
Students can critically evaluate quant research, design scalable ML experiments, and apply advanced methods responsibly in financial markets.

---

## **Final Program Capstone — End-to-End Quantitative Trading System**

**Objective**  
Integrate all prior coursework into a single, coherent quantitative trading system.

**Capstone Description**  
Students design, document, and evaluate a complete systematic trading strategy, including:
- Data ingestion and preprocessing
- Feature engineering and model selection
- Signal generation and portfolio construction
- Transaction cost and risk modeling
- Walk-forward and stress-tested backtesting
- Performance attribution and post-mortem analysis

**Deliverables**
- Fully reproducible Python research repository
- Research report detailing methodology, results, and limitations
- Final presentation defending design decisions and risk controls

**Completion Outcome**  
Graduates demonstrate the ability to design, validate, and critique professional-grade quantitative trading systems with an emphasis on robustness and realism.
