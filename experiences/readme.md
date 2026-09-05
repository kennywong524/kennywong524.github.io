---
layout: single
title: "Research"
permalink: /experiences/
author_profile: false
classes: research-page
---

## Conference Proceedings

<article class="research-paper" markdown="1">

### [Do Large Language Models (LLMs) Understand Chronology?](https://ojs.aaai.org/index.php/AAAI/article/view/42295)
{: .research-entry__title}

**Wongchamcharoen, P. K.**, & Glasserman, P.
{: .research-entry__authors}

*AAAI 2026* · Oral (Student Abstract) · Poster (AI4TS Workshop)
{: .research-entry__venue}

<details class="paper-abstract" markdown="1">
<summary>Abstract</summary>

Large language models have shown great potential as forecasting tools in finance and economics, but backtesting performance is subject to look-ahead bias if the period overlaps with an LLM’s training window. Prompt-based attempts to avoid look-ahead bias require that LLMs understand chronology. We test LLMs’ ability to understand and enforce chronological order in three types of tasks: sorting randomly shuffled historical events; conditional sorting of events defined by some conditions; and anachronism detection based on intersections of multiple timelines. Our experiments use events that we first confirm are known to the LLM; this ensures that we test chronological understanding on an LLM’s pretrained internal knowledge. Across three LLM families— GPT-4.1 (standard), GPT-5 (hybrid-reasoning), and Claude 3.7 Sonnet (large-reasoning, with and without Extended Thinking), we find that performance degrades rapidly with problem complexity but improves greatly for reasoning models with test-time extended reasoning. These patterns are important for the real-time application of LLMs in finance.

</details>

<div class="paper-links">
  <a href="https://ojs.aaai.org/index.php/AAAI/article/view/42295">Proceedings</a>
  <a href="https://arxiv.org/abs/2511.14214">arXiv</a>
  <a href="https://github.com/kennywong524/chronollm">Code</a>
  <a href="https://underline.io/events/501/posters/21797/poster/145920-747-do-large-language-models-llms-understand-chronologyquestion-student-abstract?tab=poster">Poster</a>
  <a href="https://underline.io/lecture/138612-do-large-language-models-llms-understand-chronologyquestion-student-abstract">Talk</a>
  <a href="https://github.com/AI4TS/AI4TS.github.io/blob/main/Camera_ready_AAAI2026/10.AAAI_chronollms_AI4TS_camready_withcode.pdf">Extended paper</a>
</div>

<details class="paper-notes" markdown="1">
<summary>Presentations & recognition</summary>

- *Proceedings of the 2026 AAAI Conference on Artificial Intelligence (AAAI-26)* [[proceedings]](https://ojs.aaai.org/index.php/AAAI/article/view/42295), [[arXiv]](https://arxiv.org/abs/2511.14214), [[code]](https://github.com/kennywong524/chronollm)<br>
  🏆 **Oral Presentation** - Student Abstract & Poster Program (**Top 11%**) [[poster]](https://underline.io/events/501/posters/21797/poster/145920-747-do-large-language-models-llms-understand-chronologyquestion-student-abstract?tab=poster), [[talk]](https://underline.io/lecture/138612-do-large-language-models-llms-understand-chronologyquestion-student-abstract)
- Extended paper presented as a poster at [*AI4TS: AI for Time Series Analysis (AAAI-26 Workshop)*](https://ai4ts.github.io/aaai2026) [[extended paper]](https://github.com/AI4TS/AI4TS.github.io/blob/main/Camera_ready_AAAI2026/10.AAAI_chronollms_AI4TS_camready_withcode.pdf)
- Invited presentation at *Yale Undergraduate Research Conference (YURC 2026)*, *IISE Annual Conference 2026*, *2026 Berkeley IEOR Annual Advisory Board Meeting*
- *Featured as foundational literature in OpenAI’s ["Scaling Social Science Research" (2026)](https://openai.com/index/scaling-social-science-research/) paper - [GPT as a measurement tool](https://cdn.openai.com/pdf/7517a586-5bfa-4b87-bd3d-6ea0e9e844c7/GPT-as-a-measurement-tool.pdf).*

</details>

</article>

## Working Papers & Preprints

<article class="research-paper" markdown="1">

### [CentaurBench: Benchmarking LLM Capabilities on Augmenting vs. Automating Real-World Work Tasks](https://www.nber.org/papers/w35663)
{: .research-entry__title}

**Wongchamcharoen, P. K.**, Gulati, K., Fong, M. M., & Nagaraj, A.
{: .research-entry__authors}

*NBER Working Paper #35663*, 2026
{: .research-entry__venue}

<details class="paper-abstract" markdown="1">
<summary>Abstract</summary>

Most LLM benchmarks rank models on their ability to automate work tasks. In practice, however, models are often used to assist other (human or LLM) agents. The question that drives model selection is therefore not only which model produces the best output, but which model most improves the work of another (weaker) agent. We introduce a unified framework that evaluates the capability of models to automate and augment another agent's performance. Across seven economically grounded real-world tasks, an assistant model writes assistance text for a standardized lower-capacity worker model, which produces the deliverable. In automation mode, the assistant produces the output directly. Outputs are scored through blind pairwise comparisons by an LLM judge panel with task-specific rubrics, replicated across ten runs. Rankings across the two regimes are only modestly correlated, and the automation winner loses augmentation on five of seven tasks. Assistance is not reliably positive. The unaided worker outranks every assisted condition on three tasks, and only one model's guidance beats no guidance on average. These results suggest that automation ability is an incomplete proxy for assistance quality, motivating benchmarks that evaluate models according to the roles they play in human-AI and multi-agent systems.

</details>

<div class="paper-links">
  <a href="https://www.nber.org/papers/w35663">NBER</a>
  <a href="https://arxiv.org/abs/2608.18554">arXiv</a>
  <a href="https://x.com/abhishekn/status/2092758268850655459">Tweetstorm</a>
  <a href="https://kennywong524.github.io/centaur-benchmark/">Interactive dashboard</a>
</div>

<details class="paper-notes" markdown="1">
<summary>Conference presentation</summary>

- NBER Working Paper #35663 [[nber]](https://www.nber.org/papers/w35663), [[arXiv]](https://arxiv.org/abs/2608.18554), [[tweetstorm]](https://x.com/abhishekn/status/2092758268850655459), [[interactive dashboard]](https://kennywong524.github.io/centaur-benchmark/)
- Presented at *the 2026 Wharton Generative AI & Business Conference.*

</details>

</article>

## Contributions as an RA

<article class="research-paper" markdown="1">

### [Calyber: A Ridesharing Game.](https://pubsonline.informs.org/doi/full/10.1287/ited.2025.0163ca)
{: .research-entry__title}

Shen, Y., Yan, C. and Yan, J.
{: .research-entry__authors}

*INFORMS Transactions on Education*
{: .research-entry__venue}

<details class="paper-abstract" markdown="1">
<summary>Abstract</summary>

This case introduces Calyber, a simulation-based game designed to provide a hands-on and engaging experience in developing real-time pricing and matching decisions for shared ride services, where multiple riders are pooled into a single vehicle. Students design and implement dynamic pricing and matching policies using a rich historical ridesharing data set, competing for top performance on a holdout test set. Through this case, students gain practical insight into stochastic dynamic decision making within a modern, relevant, and data-driven context. Results from previous class implementations provide strong evidence of enhanced learning and engagement.

</details>

<div class="paper-links">
  <a href="https://pubsonline.informs.org/doi/full/10.1287/ited.2025.0163ca">Paper</a>
  <a href="https://pubsonline.informs.org/doi/10.1287/ited.2025.0163cs">Case</a>
</div>

<details class="paper-notes" markdown="1">
<summary>Notes & recognition</summary>

- 🏆 *Runner-up, 2025 INFORMS Case Competition* [[case]](https://pubsonline.informs.org/doi/10.1287/ited.2025.0163cs)

</details>

</article>

<article class="research-paper" markdown="1">

### [On-Off Systems with Strategic Customers](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5202068)
{: .research-entry__title}

Sun, Y., Liu, Z., Yan, C.
{: .research-entry__authors}

*Under revision*
{: .research-entry__venue}

<details class="paper-abstract" markdown="1">
<summary>Abstract</summary>

Motivated by applications such as urban traffic control and make-to-order systems, we study a fluid model of a single-server, on-off system that can accommodate multiple queues. The server visits each queue in order: when a queue is served, it is "on", and when the server is serving another queue or transitioning between queues, it is "off". Customers arrive over time, observe the state of the system, and decide whether to join. We consider two regimes for the formation of the on and off durations. In the exogenous setting, each queue's on and off durations are predetermined. We explicitly characterize the equilibrium outcome in closed form and give a compact linear program to compute the optimal on-off durations that maximizes total reward collected from serving customers. In the endogenous setting, the durations depend on customers' joining decisions under an exhaustive service policy where the server never leaves a non-empty queue. We show that an optimal policy in this case extends service beyond the first clearance for at most one queue. Using this property, we introduce a closed-form procedure that computes an optimal policy in no more than 2n steps for a system with n queues.

</details>

<div class="paper-links">
  <a href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5202068">Paper</a>
</div>

</article>

## Other Research & Awards

<article class="research-paper" markdown="1">

### [Data-Driven Evaluation of Board of Directors Effectiveness: Unsupervised Learning and Predictive Modeling of "Skills Matrices"](https://cdss.berkeley.edu/project/measuring-board-effectiveness)
{: .research-entry__title}

**Wongchamcharoen, P. K.**, Stringer, C., Hwang B., Liu, I., & Li, K.
{: .research-entry__authors}

*Berkeley CDSS Data Discovery Symposium*, 2025
{: .research-entry__venue}

<div class="paper-links">
  <a href="https://cdss.berkeley.edu/project/measuring-board-effectiveness">Poster</a>
</div>

<details class="paper-notes" markdown="1">
<summary>Notes & recognition</summary>

- 🏆 *Best Data Visualization Award* at *the 2025 Berkeley CDSS Data Discovery Symposium*

</details>

</article>

<article class="research-paper" markdown="1">

### [Mixed-Integer Linear Program for Options Pricing and Portfolio Optimization](https://github.com/Qamil-Mirza/badss-2025-options-alpha-strategy/tree/main)
{: .research-entry__title}

Bin Abdulla, Q. M., **Wongchamcharoen, P. K.**, Jamari, A., Lee J.
{: .research-entry__authors}

*Wells Fargo & Berkeley IEOR Bay Area Decision Sciences Summit*, 2025
{: .research-entry__venue}

<div class="paper-links">
  <a href="https://github.com/Qamil-Mirza/badss-2025-options-alpha-strategy/tree/main">Code</a>
  <a href="https://drive.google.com/file/d/1xZiLPutwOY4EdhwzPEcP0V7GRSoi1qjC/view?usp=sharing">Poster</a>
</div>

<details class="paper-notes" markdown="1">
<summary>Notes & recognition</summary>

- 🏆 *1st Runner-Up* at *the 2025 Wells Fargo & Berkeley IEOR Bay Area Decision Sciences Summit*
- Also presented at *the 2025 Berkeley IEOR Community Celebration & Alumni Achievement Ceremony*

</details>

</article>

## Works in Progress

<article class="research-paper" markdown="1">

### *Flex or Fast?* Incentive-Compatible Demand Allocation in Destination-Mode Ride-Hailing Networks
{: .research-entry__title}

</article>

Please refer to my [CV]({{ "/files/kenny_cv_september_2026.pdf" | relative_url }}) for more detailed and complete research assistantships & publications.
{: .research-note}

## Research interests

<div class="research-directions">
<details class="research-toggle">
<summary><span class="research-toggle__title">Data-Driven Service Operations</span><span class="research-toggle__teaser">Information and market design in service systems with strategic interactions.</span></summary>

<div class="research-toggle__body">
<p>I study the design of dynamic service systems in which information is asymmetric and participants respond strategically to prices, incentives, and system conditions. I combine tools from stochastic optimization, game theory, and empirical methods to model and analyze operational decisions, focusing primarily on public-sector problems such as urban transportation, as well as pricing and matching in online platforms.</p>

<p>On the application side, I developed dwell-time allocation policies for <a href="https://www.bart.gov/">San Francisco Bay Area Rapid Transit (BART)</a> that helped improve throughput on its Yellow Line while accounting for strategic passenger arrivals. I also helped design <a href="https://pubsonline.informs.org/doi/full/10.1287/ited.2025.0163ca?af=R"><em>Calyber: A Ridesharing Game</em></a> (<a href="https://www.informs.org/Recognizing-Excellence/INFORMS-Prizes/INFORMS-Case-Competition"><strong>2025 INFORMS Case Competition Runner-up</strong></a>), a case study deployed in a graduate-level supply chain course at Berkeley, where students develop dynamic pricing and matching policies for a Chicago ride-hailing company.</p>

<p>I believe research can and should extend beyond theory. I am particularly interested in designing and improving routing and matching systems across logistics, transportation, marketplaces, and exchanges because they shape how people, goods, and resources are allocated. Looking ahead, I hope to collaborate with practitioners and policymakers to translate my research into socially impactful solutions to real-world challenges.</p>
</div>
</details>

<details class="research-toggle">
<summary><span class="research-toggle__title">Frontier and Limits of AI in Operations</span><span class="research-toggle__teaser">What is AI capable of in operations, and where does it fall short?</span></summary>

<div class="research-toggle__body">
<p>I investigate the reliability of generative AI in high-stakes decision systems. My recent work (<a href="https://arxiv.org/abs/2511.14214"><em>AAAI 2026</em></a>) empirically audits the limits of LLMs in chronological reasoning, with implications for mitigating lookahead bias in forecasting tasks.</p>

<p>As AI capabilities advance, I believe interdisciplinary research on how AI augments human judgment will become increasingly important. Models can be seen solving complex, well-specified problems, but they cannot yet determine which questions are <em>worth asking</em>, which assumptions matter, or how technical decisions will affect people. In my recent talk (<a href="https://kennywong524.github.io/files/BESMART-talk-2026.pdf"><strong><em>Research Perspectives on the Capabilities, Limits, and Future of AI</em></strong></a>), I explore these questions and their future implications for the field.</p>
</div>
</details>

<details class="research-toggle research-toggle--human-ai">
<summary><span class="research-toggle__title">Human–AI Operations</span><span class="research-toggle__teaser">Allocating work across humans, autonomous models, and AI assistants.</span></summary>

<div class="research-toggle__body">
<p>I study how firms should optimally design workflows and allocate tasks among humans, autonomous models, and AI assistants given differences in their capabilities, costs, speeds, and reliability. In <a href="https://www.nber.org/papers/w35663"><em>CentaurBench</em></a>, we show that a model's ability to automate a task is distinct from its ability to <em>assist</em> another agent. Some frontier models excel at automation but perform poorly as assistants, highlighting the need to benchmark models for the roles they play within a workflow, not just their standalone performance.</p>

<p>More broadly, I view integrating intelligence into enterprise workflows as a multifaceted operations problem, and not just a model selection problem. Tasks arrive dynamically and must be matched to heterogeneous agents whose performance may vary with workload, context, and time. Through the lenses of operations management and research, I hope to formalize and optimize these complex, evolving systems.</p>
</div>
</details>
</div>

## Professional Experience

Please refer to my [resume](https://drive.google.com/file/d/1OvByTf_bYpJS-wfEsPA8PVdvtgcyBM4z/view?usp=drive_link) for more recent industry experiences.
{: .research-note}
