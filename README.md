# Antje Barth

**AI product strategy · Performance engineering · Developer experience**

I work at the intersection of AI systems and product decisions: what the technology can deliver, how to evaluate it, and what makes it useful to people.

My current focus is writing about AI performance engineering. I explore how models run on real hardware, what limits their performance, and how choices in inference, GPU kernels, and serving systems affect latency, throughput, and cost. My writing combines clear explanations, diagrams, and reproducible experiments so readers can understand the mechanisms and check the results.

I bring a product management perspective to this work: choosing meaningful metrics, understanding user needs, testing assumptions, and deciding which improvements are worth building. My background spans nearly 20 years across data center infrastructure, data platforms, and AI.

## Current work

**[AI performance research](https://github.com/antje/research)**  
Technical articles and runnable experiments on inference systems, GPU performance, scheduling, and serving economics. Each article starts with a specific question, explains the mechanism, and provides the evidence behind its conclusions.

A few places to start:

- **[More batch won’t make decode compute-bound](https://github.com/antje/research/tree/main/posts/2026-09-28-pm-decode-wants-sram)** — How KV-cache traffic limits decode performance, even as batch size grows.
- **[Why a bad guesser can’t skew what your model says](https://github.com/antje/research/tree/main/posts/2026-10-25-pm-bad-guesser-same-answer)** — How speculative decoding preserves the target model’s output distribution while changing its speed.

**[bakeoff](https://github.com/antje/bakeoff)**  
A model evaluation tool built around your own agent workloads. Compare accuracy, latency, and cost, then use cost per correct call to inform model selection.

**[product-coach](https://github.com/antje/product-coach)**  
A project exploring how product teams can review decisions and learn from their outcomes. Coaching skills challenge assumptions using the team’s own evidence; a companion app is in development to track whether that advice holds up.

## Product strategy and practice

My product work spans strategy, developer experience, adoption, analytics, and experimentation. I’m interested in how teams turn an uncertain opportunity into a clear decision: what to build, what evidence to gather, how to measure success, and when to change direction.

Selected case studies from my Product School capstone work:

- **[AI product strategy](https://github.com/antje/product-school-ai-product-strategy-for-leaders)** — A strategy for product-coach covering positioning, pricing, a data flywheel, and criteria for stopping the investment.
- **[Product analytics and experimentation](https://github.com/antje/product-school-product-analytics-and-experimentation)** — An activation and experimentation strategy for a SaaS product with stalled trial conversion.
- **[AI evaluations](https://github.com/antje/product-school-ai-evals)** — An evaluation of whether a competitive-intelligence agent is ready to ship, with a recommendation to hold and explicit conditions for reconsidering.

## Books and teaching

I co-authored two O’Reilly books:

- **[Generative AI on AWS](https://www.amazon.com/Generative-AWS-Context-Aware-Multimodal-Applications/dp/1098159225)** — Building generative AI applications.
- **[Data Science on AWS](https://www.amazon.com/Data-Science-AWS-End-End/dp/1492079391)** — Building data science and machine learning workflows.

I’m also a DeepLearning.AI instructor and curriculum developer for **[Generative AI with Large Language Models](https://www.deeplearning.ai/courses/generative-ai-with-llms/)** and **Practical Data Science**.

## Speaking and community

I speak about AI systems, developer experience, and applied AI. My speaking and conference work includes AI Engineer World’s Fair, O’Reilly AI Superstream, Open Source Summit North America, and MCP Dev Summit.

- **[Perception Agents](https://www.youtube.com/watch?v=2JX6JYyQG4Y)** — My AI Engineer World’s Fair 2026 keynote on agents that see and act on a screen.
- Co-host of the **[AI Performance Engineering Meetup](https://www.meetup.com/ai-performance-engineering/)**.
- Co-founder of the Düsseldorf chapter of **[Women in Big Data](https://www.womeninbigdata.org/)**.

---

San Francisco Bay Area · [Website](https://antje.dev) · [LinkedIn](https://www.linkedin.com/in/antje-barth) · [YouTube](https://www.youtube.com/@AIPerformanceEngineering) · [X](https://x.com/anbarth)
