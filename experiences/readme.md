---
layout: single
title: "Research"
permalink: /experiences/
author_profile: true
classes: research-page
---

## Conference Proceedings
[Do Large Language Models (LLMs) Understand Chronology?](https://arxiv.org/abs/2511.14214)
{: .research-entry__title}

**Wongchamcharoen, P. K.**, & Glasserman, P.
{: .research-entry__authors}

<details>
<summary>[View Abstract]</summary>

Large language models have shown great potential as forecasting tools in finance and economics, but backtesting performance is subject to look-ahead bias if the period overlaps with an LLM’s training window. Prompt-based attempts to avoid look-ahead bias require that LLMs understand chronology. We test LLMs’ ability to understand and enforce chronological order in three types of tasks: sorting randomly shuffled historical events; conditional sorting of events defined by some conditions; and anachronism detection based on intersections of multiple timelines. Our experiments use events that we first confirm are known to the LLM; this ensures that we test chronological understanding on an LLM’s pretrained internal knowledge. Across three LLM families— GPT-4.1 (standard), GPT-5 (hybrid-reasoning), and Claude 3.7 Sonnet (large-reasoning, with and without Extended Thinking), we find that performance degrades rapidly with problem complexity but improves greatly for reasoning models with test-time extended reasoning. These patterns are important for the real-time application of LLMs in finance.

</details>

- *Proceedings of the 2026 AAAI Conference on Artificial Intelligence (AAAI-26)* [[paper]](https://ojs.aaai.org/index.php/AAAI/article/view/42295), [[code]](https://github.com/kennywong524/chronollm)  
  🏆 **Oral Presentation** - Student Abstract & Poster Program (**Top 11%**) [[poster]](https://underline.io/events/501/posters/21797/poster/145920-747-do-large-language-models-llms-understand-chronologyquestion-student-abstract?tab=poster), [[talk]](https://underline.io/lecture/138612-do-large-language-models-llms-understand-chronologyquestion-student-abstract)
- Extended paper also accepted at [*AI4TS: AI for Time Series Analysis (AAAI-26 Workshop)*](https://ai4ts.github.io/aaai2026) [[extended paper]](https://github.com/AI4TS/AI4TS.github.io/blob/main/Camera_ready_AAAI2026/10.AAAI_chronollms_AI4TS_camready_withcode.pdf)
- Invited presentation at *Yale Undergraduate Research Conference (YURC 2026)*, *IISE Annual Conference 2026*, *2026 Berkeley IEOR Annual Advisory Board Meeting*
- *Featured as foundational literature in OpenAI’s ["Scaling Social Science Research" (2026)](https://openai.com/index/scaling-social-science-research/) paper - [GPT as a measurement tool](https://cdn.openai.com/pdf/7517a586-5bfa-4b87-bd3d-6ea0e9e844c7/GPT-as-a-measurement-tool.pdf).*
{: .research-entry__notes}

## Working Paper & Preprints
Decoding Human-AI Augmentation: Measuring the Value of LLM Assistance on Professional Tasks Using Simulation
{: .research-entry__title}

**Wongchamcharoen, P. K.**, Gulati, K., Fong, M. M., & Nagaraj, A.
{: .research-entry__authors}

<details>
<summary>[View Abstract]</summary>

Static LLM leaderboards measure end-to-end task execution, yet many real world deployments rely on centaur workflows where one model provides structured assistance to a human or another model. We investigate whether a model’s direct task-solving ability (”automation”) correlates with its capacity to guide a weaker worker (”augmentation”), proposing an evaluation framework that treats assistance as a distinct capability. Across diverse professional tasks grounded in O\*NET and the Anthropic Economic Index (e.g., operations research, counseling, and creative writing), we compare direct model performance against assistant-to-worker pipelines using a fixed worker (GPT-3.5 Turbo) and varying scaffold models. LLM-based rubric grading reveals that scaffolding reliably improves output structure and usefulness. However, model rankings diverge sharply depending on the task: for open-ended professional tasks, models that are weak standalone solvers often serve as highly effective ”teachers.” Expert human validation confirms the directional benefits of scaffolding but highlights calibration gaps in LLM-as-a-judge scoring, emphasizing the need for robust evaluation protocols. Ultimately, our findings demonstrate that supervisory skill is distinct from direct execution capability and represents an economically meaningful dimension of LLM performance missed by conventional benchmarks.

</details>

- Working Paper, February 2026
{: .research-entry__notes}

## Contributions as an RA
[Calyber: A Ridesharing Game.](https://pubsonline.informs.org/doi/full/10.1287/ited.2025.0163ca)
{: .research-entry__title}

Shen, Y., Yan, C. and Yan, J.
{: .research-entry__authors}

*INFORMS Transactions on Education.*
{: .research-entry__venue}

<details>
<summary>[View Abstract]</summary>

This case introduces Calyber, a simulation-based game designed to provide a hands-on and engaging experience in developing real-time pricing and matching decisions for shared ride services, where multiple riders are pooled into a single vehicle. Students design and implement dynamic pricing and matching policies using a rich historical ridesharing data set, competing for top performance on a holdout test set. Through this case, students gain practical insight into stochastic dynamic decision making within a modern, relevant, and data-driven context. Results from previous class implementations provide strong evidence of enhanced learning and engagement.

</details>

- 🏆 *Runner-up, 2025 INFORMS Case Competition* [[case]](https://pubsonline.informs.org/doi/10.1287/ited.2025.0163cs)
{: .research-entry__notes}

[On-Off Systems with Strategic Customers](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5202068)
{: .research-entry__title}

Sun, Y., Liu, Z., Yan, C.
{: .research-entry__authors}

<details>
<summary>[View Abstract]</summary>

Motivated by applications such as urban traffic control and make-to-order systems, we study a fluid model of a single-server, on-off system that can accommodate multiple queues. The server visits each queue in order: when a queue is served, it is "on", and when the server is serving another queue or transitioning between queues, it is "off". Customers arrive over time, observe the state of the system, and decide whether to join. We consider two regimes for the formation of the on and off durations. In the exogenous setting, each queue's on and off durations are predetermined. We explicitly characterize the equilibrium outcome in closed form and give a compact linear program to compute the optimal on-off durations that maximizes total reward collected from serving customers. In the endogenous setting, the durations depend on customers' joining decisions under an exhaustive service policy where the server never leaves a non-empty queue. We show that an optimal policy in this case extends service beyond the first clearance for at most one queue. Using this property, we introduce a closed-form procedure that computes an optimal policy in no more than 2n steps for a system with n queues.

</details>

- *Under revision.*
{: .research-entry__notes}

## Other Research & Awards
Data-Driven Evaluation of Board of Directors Effectiveness: Unsupervised Learning and Predictive Modeling of "Skills Matrices"
{: .research-entry__title}

**Wongchamcharoen, P. K.**, Stringer, C., Hwang B., Liu, I., & Li, K. [[poster]](https://cdss.berkeley.edu/project/measuring-board-effectiveness)
{: .research-entry__authors}

- 🏆 *Best Data Visualization Award* at *the 2025 Berkeley CDSS Data Discovery Symposium*
{: .research-entry__notes}

Mixed-Integer Linear Program for Options Pricing and Portfolio Optimization
{: .research-entry__title}

Bin Abdulla, Q. M., **Wongchamcharoen, P. K.**, Jamari, A., Lee J. [[code]](https://github.com/Qamil-Mirza/badss-2025-options-alpha-strategy/tree/main), [[poster]](https://drive.google.com/file/d/1xZiLPutwOY4EdhwzPEcP0V7GRSoi1qjC/view?usp=sharing)
{: .research-entry__authors}

- 🏆 *1st Runner-Up* at *the 2025 Wells Fargo & Berkeley IEOR Bay Area Decision Sciences Summit*
- Also presented at *the 2025 Berkeley IEOR Community Celebration & Alumni Achievement Ceremony*
{: .research-entry__notes}

## Works in Progress
*Flex or Fast?* Incentive-Compatible Demand Allocation in Destination-Mode Ride-Hailing Networks
{: .research-entry__title .research-entry__title--terminal}

Please refer to my [CV](https://kennywong524.github.io/files/Kenny_CV_2026_updated.pdf) for more detailed and complete research assistantships & publications.
{: .research-note}

## Professional Experience

Please refer to my [resume](https://drive.google.com/file/d/1OvByTf_bYpJS-wfEsPA8PVdvtgcyBM4z/view?usp=drive_link) for more recent industry experiences.
{: .research-note}
