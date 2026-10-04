# Hi, I'm Jatin Sihag 👋
### AI Engineer & Agent Benchmark Specialist
**Long-Horizon Reasoning | SWE-bench & TerminalBench Authoring | RLVR & Model Failure Analysis**

[![GitHub followers](https://img.shields.io/github/followers/jatinsihag2345?style=social)](https://github.com/jatinsihag2345)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat&logo=linkedin)](https://linkedin.com)
[![Email](https://img.shields.io/badge/Email-Contact_Me-red?style=flat&logo=gmail)](mailto:clyfergamer@gmail.com)
[![Status](https://img.shields.io/badge/Status-Open_for_Eval_Contracts-success?style=flat)]()

---

## 🔬 Core Focus & Expertise

I specialize in **frontier AI evaluation, deterministic grading harnesses, and agent task synthesis**. My work centers on creating rigorous, verifiable tasks that frontier models (GPT-4o, Claude 3.5 Sonnet, DeepSeek-V3/R1, Gemini 1.5/2.0) fail on—specifically in multi-step agentic trajectories and code intelligence.

- 🎯 **Long-Horizon Agent Trajectories (15–30+ steps):** Designing multi-turn interactive environments testing context retention, backtracking, tool error recovery, and constraint stability.
- 💻 **Terminal & OS Benchmarks (TerminalBench / OSWorld style):** Authoring realistic Linux/CLI debugging scenarios, system administration puzzles, and network edge cases evaluated with isolated Docker containers and deterministic pytest assertions.
- 🛠️ **SWE-bench Task Creation:** Extracting real-world GitHub issues and PRs into standardized SWE-bench instances (clean base commit, problem statement, reproducible fail-to-pass test patches).
- 🧪 **RLVR (Reinforcement Learning with Verifiable Rewards):** Engineering automated deterministic grading environments where model outputs can be verified programmatically without human ambiguity.
- 🚨 **Model Red-Teaming & Failure Taxonomy:** Systematic failure mode categorization (sycophancy, context window degradation, tool loop hallucination, subtle numerical/boundary drift).

---

## 🏆 Flagship Evaluation Suites & Benchmarks

### 1. [`terminal-bench-eval`](https://github.com/jatinsihag2345/terminal-bench-eval)
> **Comprehensive CLI & OS Agent Benchmark with Sandboxed Docker Environments**
- **8+ Production Tasks:** Hard real-world terminal challenges (corrupted git HEADs, socket deadlocks, C-extension build failures, DNS search leaks, SQLite WAL checkpoint locks).
- **Isolated Sandboxing:** Containerized execution harness ensuring reproducibility and zero host side-effects.
- **Deterministic Grading:** Automated pytest & bash assertion suite computing Pass@1, step cost, and execution latency.
- **Model Baselines:** Tested against Claude 3.5 Sonnet (75.0%), GPT-4o (62.5%), and DeepSeek-V3 (62.5%).

### 2. [`swe-bench-task-forge`](https://github.com/jatinsihag2345/swe-bench-task-forge)
> **Automated Pipeline for SWE-bench Task Authoring, Extraction, and F2P/P2P Verification**
- End-to-end task generation pipeline from raw GitHub issues to valid SWE-bench JSON task schemas.
- Automated validation runner ensuring fail-to-pass (F2P) tests strictly fail on the base commit and pass on the gold patch.
- Bundled with verified task instances across popular Python open-source repos (`requests`, `flask`, `scikit-learn`).

### 3. [`long-horizon-agent-stress-bench`](https://github.com/jatinsihag2345/long-horizon-agent-stress-bench)
> **Multi-Step Agentic Stress-Test Harness Designed to Induce Frontier Model Failures**
- Targets agent failure modes across 15–30 tool-calling turns: context forgetting, circular error recovery, state synchronization drift.
- Includes automated rubric evaluation, trajectory replay visualizer, and quantitative failure rate metrics.

### 4. [`rlvr-math-verifiers`](https://github.com/jatinsihag2345/rlvr-math-verifiers)
> **Deterministic Verification Environments for Reinforcement Learning with Verifiable Rewards (RLVR)**
- High-throughput LaTeX parsing, nested `\boxed{...}` extraction, and fraction/rational equivalence engine.
- Zero-dependency verification for PPO and GRPO reasoning model training loops on MATH-500 and GSM8K.

### 5. [`model-redteam-atlas`](https://github.com/jatinsihag2345/model-redteam-atlas)
> **Adversarial Prompt Evaluation, Jailbreak Defense & Red-Teaming Harness**
- 250+ structured adversarial vectors evaluating Indirect Prompt Injections, System Prompt Leaks, Delimiter Escaping, and Factual Sycophancy.
- Comparative defense score leaderboard across Claude 3.5 Sonnet, GPT-4o, and DeepSeek-V3.

### 6. [`agentic-tool-use-eval`](https://github.com/jatinsihag2345/agentic-tool-use-eval)
> **Function Calling, Nested JSON Schema Compliance & Multi-Tool Orchestration Benchmark**
- Evaluates schema conformance, parameter type enforcement, argument hallucination rates, and multi-tool planning.

---

## 📊 Benchmark Design Matrix

| Benchmark Domain | Environment Type | Primary Failure Modes Tested | Verification Method |
| :--- | :--- | :--- | :--- |
| **CLI / Sysadmin** | Docker (Alpine / Ubuntu) | File descriptor leaks, missing ENV vars, socket timeouts | Deterministic exit code & FS assertion |
| **SWE (Code Fixes)** | Git repo + virtualenv | Regression in unrelated tests, partial patch application | Pytest Fail-to-Pass & Pass-to-Pass |
| **Long-Horizon Tool Use** | Multi-API Mock Server | Tool argument drift, context window overflow, state loss | State-machine log auditor |
| **RLVR Reasoning** | Python Sandbox | Step-by-step logic errors, boundary drift, rational equivalence | Pure Python AST & fraction match |
| **Red-Teaming / Safety** | Adversarial Harness | Jailbreaks, prompt leaks, sycophancy, tool privilege escalation | Refusal classifier & canary detector |

---

## 🛠️ Technical Stack & Tooling

```
Languages:        Python 3.10+, Bash / Shell, SQL, JavaScript / TypeScript
Agent Harnesses:  Docker, Pytest, vLLM, LiteLLM, LangChain, LangGraph, SWE-bench CLI
Eval Frameworks:  OpenAI Evals, DeepEval, Promptfoo, Inspect AI, Ragas
Data & Modeling:  Hugging Face (datasets, transformers), SymPy, Pandas, NumPy
Infrastructure:   Git, Linux / Unix Internals, Systemd, Cgroups, Networking (cURL, Nginx, DNS)
```

---

## 📈 GitHub Metrics

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=jatinsihag2345&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="Jatin's GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=jatinsihag2345&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" />
</p>

---

## 📬 Contact & Engagements
- Open for **AI Evaluation Specialist, Task Authoring, and Model Red-Teaming** contracts on Mercor, Turing, Scale AI, and frontier AI research labs.
- Reach out: **[clyfergamer@gmail.com](mailto:clyfergamer@gmail.com)**
