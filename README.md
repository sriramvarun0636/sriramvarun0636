
# Hi, I'm Sri Ram Varun Dittakavi 👋

Building high-performance backend architectures, concurrent systems, and scalable software infrastructure.

B.Tech Computer Science undergraduate at MNNIT Allahabad (Class of 2027), passionate about systems programming, concurrent software, and quantitative trading infrastructure.

---

### 🚀 Current Interests

- Low-latency trading systems
- Concurrent backend architecture
- Quantitative research & market microstructure
- Modern C++ for performance-critical systems

---

### 🛠️ Technical Skillset

*   **Languages:** C++, Python, MQL5, SQL (Postgres), Java, Bash
*   **Systems Programming:** POSIX, Multithreading, Actor Model, Socket Programming, FastAPI, SQLite
*   **Infrastructure & Security:** Docker (Container Sandboxing), Linux, Git, Prometheus, Grafana
*   **Quantitative & Math:** Options Pricing (Black–Scholes, Greeks), Systematic Strategy Backtesting, Volatility-Adaptive Risk Management

---

###  Highlighted Projects

#### 1. [SentinelPrime](https://github.com/sriramvarun0636/SentinelPrime) (Python)
An autonomous, multi-threaded, regime-aware options trading system engineered for the Indian derivatives market.
*   **Decoupled Architecture:** Built around a Planner–Executor architecture that isolates analytical workloads from latency-sensitive execution loops using the Actor pattern.
*   **Memory-Safe Pipeline:** Implements a low-overhead concurrent pipeline utilizing auto-trimming `collections.deque` and thread-safe queues for O(1) ingestion of WebSocket tick data.
*   **API Protection:** Governs broker requests using an asynchronous Token Bucket rate-limiting algorithm within the execution thread to prevent rate-limit bans during market volatility.

#### 2. [HydraPrime](https://github.com/sriramvarun0636/HydraPrime) (MQL5)
A systematic, object-oriented gold (XAUUSD) trading strategy and risk management system built for MetaTrader 5.
*   **State Recovery:** Implements a persistent state recovery system using Terminal Global Variables (`GlobalVariableSet`) to survive VPS reboots or terminal crashes without desynchronizing open positions.
*   **Sizing & Risk Engine:** Features volatility-adaptive position sizing (ATR-driven), multi-layered drawdown circuit breakers, and programmatic spread checks.
*   **Backtest Summary:** Evaluated across 530 historical trades (99% real tick data, May 2024–May 2026), achieving a 1.37 Profit Factor, 252% net return, and 13.8% maximum drawdown.

#### 3. [AutoPatch-AI](https://github.com/sriramvarun0636/AutoPatch-AI) (Python)
An autonomous, event-driven code-remediation agent designed for secure execution environments.
*   **Sandbox Isolation:** Spawns ephemeral, network-disabled Docker containers with strict resource quotas (256MB RAM, 128 PIDs) to safely execute and validate untrusted LLM-generated code.
*   **Self-Healing Loop:** Leverages a LangGraph DAG to recursively run test suites, catch execution errors, and feed `stdout/stderr` back into the model for iterative patch correction.

---

### 📬 Connect with Me

*   **LinkedIn:** [sri-ram-varun-dittakavi](https://www.linkedin.com/in/sri-ram-varun-dittakavi-4103a428a/)
*   **Email:** sriramvarun636@gmail.com
```
