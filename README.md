<div align="center">

# Nikolas Markou

**Machine Learning & AI: Strategy, Architecture, Implementation**

*Mission-critical AI systems fail for two reasons: flawed architecture or flawed implementation. I correct both.*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-30K%2B_Followers-0A66C2?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/nikolasmarkou/)
[![Electi Consulting](https://img.shields.io/badge/Electi_Consulting-electiconsulting.com-0057B8?style=flat-square)](https://electiconsulting.com/)
[![Email](https://img.shields.io/badge/Email-nikolas.markou%40electiconsulting.com-EA4335?style=flat-square&logo=gmail)](mailto:nikolas.markou@electiconsulting.com)

</div>

## About

Managing Partner & Head of AI at [Electi Consulting](https://electiconsulting.com/) (Limassol / London). 14+ years building and fixing AI systems across shipping, telecom, IoT, autonomous driving, computational photography, blockchain, and finance for clients including the [European Central Bank](https://www.ecb.europa.eu/), [MSC Mediterranean Shipping](https://www.msc.com/), [Hellenic Bank](https://www.hellenicbank.com/), and [EuroBank](https://www.eurobank.gr/). Each domain enforces different engineering constraints. The accumulation is what makes the solutions hold.

Technical range spans real-time computer vision and object detection pipelines, novel neural architectures, GPU-optimized inference in C++/CUDA/TensorRT, LLM/RAG frameworks, agentic system architecture, and containment for high-stakes GenAI deployments. I also conduct AI due diligence for M&A and startup valuations.

35+ open-source repositories. I ship code, not papers. [US patent holder](https://patents.google.com/patent/US10051414B2/). MSc with Distinction from [Imperial College London](https://www.imperial.ac.uk/). Expert Advisor to the [Cyprus National AI Taskforce](https://dmrid.gov.cy/).

## When to Reach Out

Most engagements fall into one of four shapes:

**AI audit or technical due diligence.** You need a defensible, forensic read on an ML pipeline, model, or data system. Typical triggers: pre-funding, M&A target assessment, post-incident review, or a board asking hard questions about a production model.

**Remediation of a failing system.** Silent model drift, pipelines that break under load, a GenAI deployment that cannot ship safely, unstable training runs, or reproducibility loss. I diagnose root cause and re-architect what actually needs to change, not what is merely easy to change.

**GenAI architecture for high-stakes use cases.** LLM, RAG, or agentic systems where accuracy, privacy, or reputational risk matter. Evaluation harnesses, containment, prompt-injection defense, and system design from day one rather than bolted on later.

**GPU and inference optimization.** Models work but are too slow or too expensive in production. CUDA, TensorRT, ONNX, graph surgery, quantization, and architecture refactoring.

If any of that fits, [email me](mailto:nikolas.markou@electiconsulting.com) with a short description of the problem and the constraints. I respond within 48 hours.

## Core Technologies

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

**ML / Deep Learning**

![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![ONNX](https://img.shields.io/badge/ONNX-005CED?style=flat-square&logo=onnx&logoColor=white)
![TensorRT](https://img.shields.io/badge/TensorRT-76B900?style=flat-square&logo=nvidia&logoColor=white)

**Infrastructure & Tools**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-244c5a?style=flat-square&logo=google&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

## Open Source

### Frameworks

### [dl_techniques](https://github.com/NikolasMarkou/dl_techniques)
Production-ready deep learning framework consolidating 150+ model implementations, 290+ specialized layers, and 20+ loss functions into a single Keras 3 / TensorFlow library. Factory system for single-line component swapping (15+ attention mechanisms, 10+ FFN types). Includes the novel AnyLoss framework for direct metric optimization on imbalanced datasets and a six-dimensional ModelAnalyzer for training diagnostics. 600+ tests. Sponsored by Electi Consulting.

### [fsm_llm](https://github.com/NikolasMarkou/fsm_llm)
Python framework combining Finite State Machines with Large Language Models for structured, stateful conversational AI. FSMs defined declaratively in JSON, JsonLogic-based conditional transitions, hierarchical FSM stacking, and lifecycle hooks. Supports 100+ LLM providers via LiteLLM. Built-in prompt injection defense and token-aware history management.

### Research and Novel Architectures

### [crystal](https://github.com/NikolasMarkou/crystal)
Novel deep learning weight initialization based on N-dimensional regular simplex geometry. An exact analytic eigenvalue calibration formula ensures the scaled Gram matrix has lambda_max ≈ 1.0, preventing vanishing and exploding gradients. O(N³) Givens rotations tested up to 1000 dimensions. Framework-agnostic (pure NumPy output).

### [multiscale_variational_autoencoder](https://github.com/NikolasMarkou/multiscale_variational_autoencoder)
Hierarchical VAE that decomposes images into a pyramid of per-scale latent representations, a learnable alternative to wavelet decomposition. Each resolution level has its own encoder and decoder with configurable blocks (Squeeze-Excite, MobileNet V2/V3, Self-Attention, ResNet). Reconstructs coarse-to-fine via residual merging with a composite multi-component loss.

### [blind_image_denoising](https://github.com/NikolasMarkou/blind_image_denoising)
Bias-free CNN library for blind image denoising, based on the CVPR 2020 bias-free CNN paper. Removing all bias terms makes every output a pure weighted combination of input pixels, providing full interpretability. Multi-scale processing via Laplacian and Gaussian pyramids, with three custom regularizers (soft orthogonal, effective receptive field). Up to 57% MAE reduction across noise levels 20 to 80. Deployable via TFLite.

### AI Engineering Tooling

### [iterative-planner](https://github.com/NikolasMarkou/iterative-planner)
Claude Code skill that replaces linear AI coding execution with a disciplined state-machine cycle: Explore, Plan, Execute, Reflect, Re-plan. Filesystem-based persistent memory survives context window exhaustion. Enforces complexity budgets, a 2-fix autonomy leash, decision anchoring in code, and cross-plan knowledge transfer. Designed to prevent the runaway fix accumulation and context rot that derail complex AI-assisted tasks.

### [epistemic-deconstructor](https://github.com/NikolasMarkou/epistemic-deconstructor)
Claude Code skill implementing a 6-phase scientific protocol for reverse engineering unknown systems: boundary mapping, causal analysis, parametric identification, and validated model synthesis. Backed by 7 Python CLI tools (~6,300 lines), Bayesian hypothesis tracking with calibrated evidence rules, conformal prediction, and 27 reference documents. 191 unit tests. Scales across five tiers from 30-minute claim validation to 20+ hour comprehensive analysis.

### Applied Systems

### [cashflow-app](https://github.com/NikolasMarkou/cashflow-app)
Multi-account cash flow forecasting engine with a 5-layer pipeline: transfer netting, autonomous recurrence discovery (corrects corrupted upstream flags), decomposition into deterministic and residual components, multi-model competition (ETS, SARIMA, SARIMAX, TiRex ONNX), and trend-adjusted recomposition. Generates structured JSON explainability payloads designed for LLM consumption. 89.2% pass rate across 120 systematic validation runs at 10.2% average WMAPE. Ships with FastAPI web interface, CLI, and Python API.

## Credentials

- **US Patent**, [Wireless terminal location](https://patents.google.com/patent/US10051414B2/) (2018)
- **Expert Advisor**, [Cyprus National AI Taskforce](https://dmrid.gov.cy/) (2025 to present)
- **MSc Advanced Computing (Distinction)**, [Imperial College London](https://www.imperial.ac.uk/). Thesis under Prof. Maja Pantic
- **BEng/MEng Computer Engineering**, [University of Patras](https://www.upatras.gr/)
- **UCL Centre for Blockchain Technologies**, Industry Associate and co-author of the Internet of Value Report
- **First Lieutenant (Reserve)**, National Guard of Cyprus (2003 to 2005)

## Writing and Talks

I publish long-form analysis on AI engineering failure patterns, architecture trade-offs, and what production ML actually looks like under load. Most of it lives on [LinkedIn](https://www.linkedin.com/in/nikolasmarkou/) (30K+ followers).

Recent talks:
- *AI from the Trenches*, IMH / CYIT, March 2025
- *HPC for Hyperparameter Search*, NCC Romania, March 2024

---

<div align="center">

For AI strategy, architecture review, or technical due diligence:

[nikolas.markou@electiconsulting.com](mailto:nikolas.markou@electiconsulting.com) | [electiconsulting.com](https://electiconsulting.com/) | [LinkedIn](https://www.linkedin.com/in/nikolasmarkou/)

</div>