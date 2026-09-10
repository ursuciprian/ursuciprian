# Ciprian Ursu 🐻

DevOps engineer and solutions architect. I build cloud infrastructure, automate operations, and work on the security and observability needed to keep it running.

Lately, much of my time goes into running large language models locally, measuring how they behave under load, and building tools for day-to-day work with coding agents.

## Current work

- **LLM inference on two NVIDIA DGX Sparks.** Serving models with SGLang and vLLM; testing quantization, speculative decoding, prefix caching, and multi-node setups. I compare latency, throughput, memory use, and correctness across workloads.
- **BenchTTY.** A terminal UI for running inference benchmarks and inspecting results alongside GPU telemetry.
- **Agent tooling and memory.** Working with MCP, searchable session history, curated notes, and code graphs so useful context survives between sessions.
- **Infrastructure and operations.** Cloud networking, Kubernetes, Terraform, CI/CD, access management, and Prometheus/Grafana monitoring.

## Selected projects

- [Qwen3.8-Flash-Next on two DGX Sparks](https://github.com/ursuciprian/qwen3.8-flash-next-dgx-spark-tp-2) — SGLang and vLLM serving recipes, benchmark results, and workload-specific tradeoffs.
- [DeepSeek-v4-Flash on DGX Spark](https://github.com/ursuciprian/DeepSeek-v4-Flash-DSpark-DGX-Spark-TP2) — DSpark setup across two nodes.
- [GLM-5.3-Flash on two DGX Sparks](https://github.com/ursuciprian/GLM-5.3-Flash-2x-DGX-Spark) — another part of my local inference work.
- [access-core](https://github.com/ursuciprian/access-core) — a self-service VPN access and operations portal for OpenVPN.

## Tools I work with

AWS, Azure, GCP · Terraform, CloudFormation · Kubernetes, Docker · Prometheus, Grafana · Python, Bash, Go · SGLang, vLLM, MCP

I prefer small, readable changes and repeatable measurements. A benchmark result needs its workload and settings next to it.

[LinkedIn](https://www.linkedin.com/in/ursuciprian/) · [X](https://twitter.com/cipursu)
