# Lionsgate AI Lab 🦁

**Independent AI research lab exploring local LLM inference, model quantization, agentic systems, and software architecture.**

We run practical experiments to understand what language models can reliably do on local hardware. Our focus is on reproducible results, real workloads, and the trade-offs between model quality, memory, throughput, and end-to-end task completion.

## Areas of exploration

- **Local inference & quantization** — running and optimizing models on NVIDIA DGX Spark and other local hardware.
- **Agentic evaluation** — measuring coding-agent behavior with real tasks, recorded configurations, and independent verification.
- **Software architecture** — studying orchestration, context engineering, tool use, and dependable agentic workflows.

## Published work

- [**MiMo-V2.6-Flash-MOPD · EXL3 2.52 bpw**](https://huggingface.co/Lionsgate-AI-Lab/MiMo-V2.6-Flash-MOPD-EXL3-2.52bpw) — a locally quantized checkpoint with deployment notes and agentic benchmark evidence. The October 2026 release includes an independently validated layer-8 correction, with credit to contributor emkey1. See the model card for validation evidence and limitations.

Additional experiments and supporting material will appear here as they are ready to share.

## How we approach experiments

We aim to make results understandable and reproducible: record the model and quantization, the serving runtime, hardware, configuration, and the evaluation method. We care about **verified task outcomes**, not just tokens per second, and we document limitations alongside results.

**Evidence over hype. Reproducibility over anecdotes.**

## Find us

- [Hugging Face — Lionsgate AI Lab](https://huggingface.co/Lionsgate-AI-Lab)
- **Contact:** [contact@lionsgatelab.com](mailto:contact@lionsgatelab.com)

Reproducible bug reports, technical feedback, and thoughtful contributions are welcome.
