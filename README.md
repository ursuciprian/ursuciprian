# Hi, I'm Ciprian 🐻 👋

I'm a cloud platform architect and cloud engineer based in Iași, Romania, working in financial technology. My background is in production support, networking, and DevOps. These days I spend more time on architecture, but I still write Terraform, build pipelines, and troubleshoot deployments.

I like a good architecture diagram. I like it even more when it matches what's actually deployed.

## Cloud and platform engineering

I help design and run an AWS platform spanning more than 60 accounts. My work includes:

- Automating account provisioning and configuration with AWS Control Tower, AFT, and Terraform.
- Defining governance controls, security baselines, and shared services that engineering teams can use consistently.
- Designing cloud networks, including Transit Gateway, centralized egress, Direct Connect, and traffic inspection.
- Improving cloud cost visibility and allocation, including Kubernetes costs.
- Building deployment pipelines and observability tooling, and helping teams put architecture decisions into practice.

I've also worked across Azure, Kubernetes, ECS, and on-premises environments. I enjoy the planning and design work, but I want to see it through to a working deployment.

## GenAI and model serving

I'm involved in GenAI projects from planning and deployment through to serving and tuning open-weight models. The goal is to support multiple agents and teams with good response times and enough capacity to handle concurrent requests.

I work on prompt processing (PP), token generation (TG), and concurrency, testing the tradeoffs between throughput, latency, memory use, and correctness. That includes SGLang, vLLM, quantization, speculative decoding, prefix caching, and multi-node serving.

A lot of my hands-on testing runs on two NVIDIA DGX Sparks. “Just one more benchmark” has become an unreliable estimate of when I'll finish.

## Projects

- [Qwen3.8-Flash-Next on two DGX Sparks](https://github.com/ursuciprian/qwen3.8-flash-next-dgx-spark-tp-2): SGLang and vLLM serving recipes with benchmark results for different workloads.
- [DeepSeek-v4-Flash on DGX Spark](https://github.com/ursuciprian/DeepSeek-v4-Flash-DSpark-DGX-Spark-TP2): a DSpark setup across two nodes.
- [GLM-5.3-Flash on two DGX Sparks](https://github.com/ursuciprian/GLM-5.3-Flash-2x-DGX-Spark): local model serving experiments.
- [access-core](https://github.com/ursuciprian/access-core): a self-service VPN access and operations portal for OpenVPN.

I'm also building BenchTTY, a terminal UI for inference benchmarks and GPU telemetry, and working on tools that give coding agents access to session history, notes, and code graphs. Repeating a three-hour investigation is a poor use of anyone's afternoon.

## Get in touch

Happy to compare notes on cloud platforms, model serving, or something you've built.

[LinkedIn](https://www.linkedin.com/in/ursuciprian/) · [X](https://twitter.com/cipursu)
