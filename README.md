# Awesome-Enterprise-Prompt-Hub

# Top Enterprise Prompt Hub Platforms Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Prompt Versioning, LLM Observability, Evaluation, Playgrounds, Release Management & Collaborative Prompt Engineering*
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Enterprise Prompt Hubs** (prompt management + LLMOps). These systems help teams version, test, evaluate, deploy, and monitor prompts and LLM applications with collaboration, observability, and governance.

**Examples** include PromptLayer, Humanloop, Langfuse, Portkey, Promptitude, Agenta, Keywords AI, Braintrust, LangSmith, and Helicone (the category leaders).

**Open-source emphasis**: Prompt management and LLM observability have strong open-source options. **Langfuse**, **Agenta**, and **Helicone** offer self-hostable platforms covering prompts, traces, evals, and playgrounds. This section heavily expands those projects.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
- **[PromptLayer](https://www.promptlayer.com/)**  
  Dedicated prompt management platform with versioning, release labels, traffic-split A/B testing, evals, and collaboration for engineering and non-technical teams.

- **[Humanloop](https://humanloop.com/)**  
  Prompt engineering and evaluation platform (note: market status may have evolved—verify current availability) focused on iteration, evals, and team workflows.

- **[Langfuse](https://langfuse.com/)**  
  Open-source AI engineering platform (also available as managed cloud) for observability, prompt management, evals, playgrounds, and datasets—widely self-hosted.

- **[Portkey](https://portkey.ai/)**  
  AI gateway and LLMOps platform with prompt management, routing, observability, and governance for production LLM applications.

- **[Promptitude](https://www.promptitude.io/)**  
  Prompt management and optimization tooling for teams building and iterating on LLM applications.

- **[Agenta](https://agenta.ai/)**  
  Open-source LLMOps platform (MIT core) with prompt playground, versioning, evaluation, and observability—self-hostable and cloud options.

- **[Keywords AI](https://www.keywordsai.co/)**  
  LLM monitoring, prompt management, and analytics platform for production AI applications.

- **[Braintrust](https://www.braintrust.dev/)**  
  Evaluation-centric platform for LLM testing, datasets, and continuous evaluation with strong enterprise and VPC options.

- **[LangSmith](https://www.langchain.com/langsmith)**  
  LangChain’s platform for tracing, prompt versioning, evaluation, and debugging of LLM and agent applications.

- **[Helicone](https://www.helicone.ai/)**  
  Open-source LLM observability and gateway platform (also managed) for monitoring, prompt management, cost tracking, and experimentation.

## Open-Source GitHub Projects
- **[Langfuse](https://github.com/langfuse/langfuse)**  
  Leading open-source AI engineering platform—prompt management (versioning, labels, deployment), observability/tracing, evals, playground, and datasets; MIT-licensed core and fully self-hostable.

- **[Agenta](https://github.com/Agenta-AI/agenta)**  
  Open-source LLMOps platform with prompt playground, git-like variants, environments (dev/staging/prod), evaluation runners, and observability—designed for collaborative prompt engineering.

- **[Helicone](https://github.com/Helicone/helicone)**  
  Open-source LLM observability platform and AI gateway—one-line logging, tracing, cost/latency analytics, prompt management, and experimentation.

- **[Portkey Gateway (open components)](https://github.com/Portkey-AI)**  
  Open AI gateway elements for routing, fallbacks, and observability that integrate with prompt and LLMOps workflows.

- **[Promptfoo](https://github.com/promptfoo/promptfoo)**  
  Open-source CLI and framework for evaluating and red-teaming LLM prompts and applications (note: market evolution—verify current status).

- **[OpenLLM / local prompt experiment tools](https://github.com/)**  
  Community tools for local prompt testing and iteration without cloud dependency.

- **[LiteLLM and open proxy/gateway projects](https://github.com/BerriAI/litellm)**  
  Open proxies that unify LLM APIs and can sit alongside prompt hubs for routing and logging.

- **[Evaluation and dataset open frameworks](https://github.com/)**  
  Open libraries for LLM-as-judge, regression testing, and dataset management used with self-hosted prompt platforms.

- **[OpenTelemetry-based LLM tracing open integrations](https://github.com/)**  
  Instrumentation projects that feed traces into Langfuse and similar open observability stacks.

- **[Documentation and LLMOps open playbooks](https://langfuse.com/docs)**  
  Guides for self-hosting Langfuse, Agenta, or Helicone and integrating prompt versioning into CI/CD.

### Additional Strong Open-Source Options
- Self-hosting **Langfuse** as the default open platform for prompts + traces + evals.
- Using **Agenta** when a full open playground-to-production prompt workflow is the priority.
- Deploying **Helicone** for gateway-centric observability and prompt logging with minimal instrumentation.
- Accepting that polished non-technical editors, enterprise release governance, dedicated support, and some advanced collaboration features still favor commercial offerings (PromptLayer, LangSmith, Braintrust, Portkey Cloud, etc.).
- Focusing open-source efforts on data ownership, self-hosting, and transparent evaluation for AI engineering teams.

**Frameworks for building custom systems**: Instrument apps with Langfuse/Helicone SDKs → version prompts in the hub → run evals on datasets → promote labeled versions to production → monitor cost, latency, and quality. Suitable for engineering-led AI teams. Many organizations still use managed prompt hubs for convenience and collaboration features.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- Prompt and LLM platforms handle application data and model outputs. Open-source deployments require security, access control, and careful handling of sensitive prompts/logs. This list is not security or AI-governance advice.

---
**Made for AI engineers, LLMOps teams, and open-source prompt advocates.**
Let's keep prompts versioned, evaluated, and as open as practical.
