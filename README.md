# Hi, I'm Zacharie 👋

I build **open-source AI/ML developer tools** in Python — the missing utilities for anyone working with LLMs.

Everything is **pip-installable, zero-dependency, works offline, and has comprehensive test suites.**

---

## 🔥 Flagship Projects

### [🔍 lmscan](https://github.com/stef41/lmscan) — Open-source GPTZero alternative

[![PyPI](https://img.shields.io/pypi/v/lmscan?color=blue)](https://pypi.org/project/lmscan/)
[![Downloads](https://img.shields.io/pypi/dm/lmscan)](https://pypi.org/project/lmscan/)
[![Tests](https://img.shields.io/badge/tests-193%20passed-brightgreen)]()

> Detect AI-generated text and fingerprint which LLM wrote it. 12 statistical features, 9 model signatures, multilingual support. <50ms, zero dependencies.

```bash
pip install lmscan
lmscan "paste any text here"
# → 82% AI probability, likely GPT-4 (confidence: high)
```

### [🎵 vibescore](https://github.com/stef41/vibescore) — Grade your vibe-coded project

[![PyPI](https://img.shields.io/pypi/v/vibescore?color=blue)](https://pypi.org/project/vibescore/)
[![Downloads](https://img.shields.io/pypi/dm/vibescore)](https://pypi.org/project/vibescore/)
[![Tests](https://img.shields.io/badge/tests-201%20passed-brightgreen)]()

> One command, instant letter grade (A+ through F). Security, code quality, deps, testing. Python, JS/TS, Rust, Go.

```bash
pip install vibescore
vibescore .
# → Overall Grade: B+
```

---

## 🧰 AI/ML Developer Toolkit

### 📐 Data & Training

| Package | What it does | Install |
|---------|-------------|---------|
| [**datacruxai**](https://github.com/stef41/datacruxai) | Training data quality — dedup, PII detection, benchmark contamination | `pip install datacruxai` |
| [**castwright**](https://github.com/stef41/castwright) | Synthetic instruction data generation for fine-tuning | `pip install castwright` |
| [**datamix**](https://github.com/stef41/datamix) | Dataset mixing & curriculum optimization for LLM training | `pip install datamix` |
| [**trainpulse**](https://github.com/stef41/trainpulse) | Training health monitor — loss spikes, gradient explosions, plateaus | `pip install trainpulse` |

### 🔬 Models & Inference

| Package | What it does | Install |
|---------|-------------|---------|
| [**infermark**](https://github.com/stef41/infermark) | LLM inference benchmarking — TTFT, throughput, tail latencies | `pip install infermark` |
| [**ckptkit**](https://github.com/stef41/ckptkit) | Checkpoint Swiss Army knife — inspect, diff, merge SafeTensors/GGUF | `pip install ckptkit` |
| [**modeldiffx**](https://github.com/stef41/modeldiffx) | Behavioral regression testing — diff model outputs across versions | `pip install modeldiffx` |
| [**quantbenchx**](https://github.com/stef41/quantbenchx) | Quantization quality analyzer — layerwise sensitivity, mixed-precision | `pip install quantbenchx` |

### 🔤 Tokenization & Cost

| Package | What it does | Install |
|---------|-------------|---------|
| [**tokonomix**](https://github.com/stef41/tokonomix) | Token counting & cost management across all LLM providers | `pip install tokonomix` |
| [**toksight**](https://github.com/stef41/toksight) | Tokenizer analysis — vocab coverage, compression, fertility comparison | `pip install toksight` |

### 🛡️ Safety & Security

| Package | What it does | Install |
|---------|-------------|---------|
| [**injectionguard**](https://github.com/stef41/injectionguard) | Prompt injection detection for LLM apps (OWASP LLM Top 10) | `pip install injectionguard` |
| [**vibesafex**](https://github.com/stef41/vibesafex) | Catch bugs in AI-generated code — secrets, hallucinated imports, vulns | `pip install vibesafex` |

---

## 📊 By the Numbers

| Metric | Value |
|--------|-------|
| Packages on PyPI | **14** |
| Total tests | **3,000+** |
| Python versions | **3.9 — 3.13** |
| CI | Green on every repo |
| External deps | Zero (most packages) |
| License | Apache 2.0 (all) |

## Urban exploration

[Urbexology](https://urbexology.com/) is an interactive map for exploring abandoned places.

## 💡 Philosophy

1. **Ship real tools, not demos.** Every project has a CLI, Python API, tests, CI, and is on PyPI.
2. **Zero deps where possible.** No dependency hell. Pure Python stdlib.
3. **Offline first.** Your code, your data, your machine. No API keys, no telemetry.
4. **Citable.** Every repo has `CITATION.cff` for academic use.

---

⭐ If any of these tools are useful to you, a star helps others find them!
