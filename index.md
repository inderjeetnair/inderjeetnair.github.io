---
layout: single
author_profile: true
author: Inderjeet Nair
toc: true
---
I am a fourth-year Ph.D. candidate at the [University of Michigan, Ann Arbor](https://umich.edu/), advised by [Prof. Lu Wang](https://web.eecs.umich.edu/~wangluxy/). My research focuses on investigating, mitigating, and evaluating scheming and deceptive behaviors in language models that may emerge from prevailing alignment methods. I am also interested in how preexisting dispositions and personas shape the emergence of specific (mis)behaviors and strategically misaligned actions. Previously, I worked across several areas of NLP and AI research, including complex data generation for tool-calling applications, LLMs in education, structured commonsense reasoning, and evaluating the consistency of value preferences in LLMs.

Before my Ph.D., I was a Research Associate at [Adobe Research, Bangalore](https://research.adobe.com/careers/bangalore/), where I worked on machine learning projects spanning document intelligence, natural language processing, information extraction, and legal AI. I received my B.Tech. in Electrical Engineering, with a minor in Computer Science and Engineering, from the [Indian Institute of Technology Bombay (IIT Bombay)](https://www.iitb.ac.in/) in 2021. In my spare time, I enjoy reading non-fiction and playing badminton and squash.


## Research

My research agenda in AI safety spans three threads:

- **Diagnostics Design:** Designing realistic, precise probes and honeypot scenarios that surface undesirable strategic behaviors such as scheming, alignment faking, reward seeking, and reward hacking. The goal is to characterize the conditions under which these behaviors arise and the forms they take, enabling rigorous comparison of alignment across models. 
- **Behavior Dynamics:** Understanding how training stages interact to shape a model's behavioral dispositions, for instance, how traits and personas acquired during pretraining interact with subsequent reward optimization, whether the rewards are correlated with or seemingly unrelated to those traits. This involves building model organisms with traits installed at controlled propensities, designing probes to measure behavioral drift, explaining why drift occurs, and developing actionable strategies to steer models toward favorable dispositions.
- **Monitoring and Auditing:** Developing control protocols and algorithms that monitor an agent's reasoning and action trajectories to prevent harmful actions. This also includes auditing methods that surface undesirable or idiosyncratic traits, particularly when the triggering distribution is narrow and such traits may evade standard evaluations. A central question is how such oversight can scale as agents operate with greater autonomy over longer horizons.

While these threads largely target settings deployed today, I am also interested in preemptively addressing problems likely to matter in the future. Native multi-agent optimization appears increasingly plausible and may substantially expand capabilities, but it also introduces new risks: multi-agent systems may game objectives more effectively, collude in pursuit of misaligned strategies, or amplify undesirable traits such as biased decision-making. I aim to build realistic model organisms of multi-agent systems that capture diverse optimization pressures and game-theoretic setups, and to assess their safety at both the interaction and system level. Such work could inform the community about potential harms and support safer training through well-designed diagnostics.


## Preprints

**Inderjeet Nair**, Jie Ruan, Lu Wang; [Value-Conflict Diagnostics Reveal Widespread Alignment Faking in Language Models](https://arxiv.org/abs/2604.20995); **Winner of [Best Student Paper Award](https://cse.engin.umich.edu/stories/cse-researchers-receive-best-paper-award-at-msld-2026) at [MSLD 2026](https://nlp.cs.illinois.edu/msld.html)**<br>

Manan Gupta, **Inderjeet Nair**, Lu Wang, Dhruv Kumar; [Context Over Content: Exposing Evaluation Faking in Automated Judges](https://arxiv.org/abs/2604.15224); <br>

## Publications

Jie Ruan\*, **Inderjeet Nair**\*, Shuyang Cao\*, Amy Liu, Sheza Munir, Micah Pollens-Dempsey, Tiffany Chiang, Lucy Kates, Nicholas David, Sihan Chen, Ruxin Yang, Yuqian Yang, Jasmine Gump, Tessa Bialek, Vivek Sankaran, Margo Schlanger, Lu Wang; [ExpertLongBench: Benchmarking Language Models on Expert-Level Long-Form Generation Tasks with Structured Checklists](https://arxiv.org/abs/2506.01241); Accepted to ICLR 2026<br>

**Inderjeet Nair**, Lu Wang; [Do Language Models Think Consistently? A Study of Value Preferences Across Varying Response Lengths](https://arxiv.org/abs/2506.02481); Accepted to ACL 2026 (Findings)<br>

**Inderjeet Nair**, Jiaye Tan, Xiaotian Su, Anne Gere, Xu Wang, Lu Wang; [Closing the Loop: Learning to Generate Writing Feedback via Language Model Simulated Student Revisions](https://arxiv.org/pdf/2410.08058); Accepted to EMNLP 2024 (Oral)<br>

**Inderjeet Nair**, Lu Wang; [MIDGARD: Self-Consistency Using Minimum Description Length for Structured
Commonsense Reasoning](https://arxiv.org/abs/2405.05189); Accepted to ACL 2024 (Oral), **Area Chair Award**<br>

**Inderjeet Nair**\*, Shwetha S.\*, Apoorva Saxena, Koustava Goswami; [Drilling Down into the Discourse Structure with LLMs for Long Document Question Answering](https://arxiv.org/pdf/2311.13565.pdf); Accepted to EMNLP 2023 Findings<br>

Adrian Kochsiek, Apoorv Umang Saxena, **Inderjeet Nair**, Rainer Gemulla; [Friendly Neighbors: Contextualized Sequence-to-Sequence Link Prediction](https://arxiv.org/pdf/2305.13059.pdf); Accepted to ACL 2023 Workshop RepL4NLP<br>

**Inderjeet Nair**, Natwar Modani; [Exploiting Language Characteristics for Legal Domain-Specific Language Model Pretraining](https://aclanthology.org/2023.findings-eacl.190.pdf); Accepted to EACL 2023 Findings<br>

**Inderjeet Nair**, Aparna Garimella, Balaji Vasan Srinivasan, Natwar Modani, Niyati Chhaya, Srikrishna Karanam, Sumit Shekhar; [A Neural CRF-based Hierarchical Approach for Linear Text Segmentation](https://aclanthology.org/2023.findings-eacl.65.pdf); Accepted to EACL 2023 Findings<br>

Aishwarya Agarwal, Anuj Srivastava, **Inderjeet Nair**, Swasti Shreya Mishra, Vineeth Dorna, Sharmila Reddy Nangi, Balaji Vasan Srinivasan; [SketchBuddy: Context-Aware Sketch Enrichment and Enhancement](https://dl.acm.org/doi/abs/10.1145/3587819.3590980); Accepted to 2023 ACM Multimedia Systems<br>

Shubham Anand Jain, Rohan Shah, Sanit Gupta, Denil Mehta, **Inderjeet Nair**, Jian Vora, Sushil Khyalia, Sourav Das, Vinay J Ribeiro, Shivaram Kalyanakrishnan; [PAC Mode Estimation using PPR Martingale Confidence Sequences](https://proceedings.mlr.press/v151/anand-jain22a/anand-jain22a.pdf); Accepted to the 2022 International Conference on Artificial Intelligence and Statistics<br>

Natwar Modani, Anurag Maurya, Gaurav Verma, **Inderjeet Nair**, Vaidehi Patil, Anirudh Kanfade; [Detecting Document Versions and Their Ordering in a Collection](https://gaurav22verma.github.io/assets/WISE2021_DocumentDetection.pdf); Accepted to the 2021 International Conference on Web Information Systems Engineering; **Best Paper Runners-up Award**


## Patents

**Inderjeet Nair**, Aparna Garimella, Balaji Vasan Srinivasan, Natwar Modani, Niyati Chhaya, Srikrishna Karanam, Sumit Shekhar ; Reader-driven Zoom in – Zoom out: Segmentation to enable non-linear navigation of long form documents; US Patent Application to be filed; Adobe Inc.

**Inderjeet Nair**, Anirudh Phukan, Aravind Veluri, Lakshya J., Mohar Kundu, Akhash Amarnath, Niyati Chhaya, Sumit Shekhar; Reflowing Infographics for Enhanced Cross-Device Consumption; US Patent Application to be filed; Adobe Inc.

**Inderjeet Nair**, Akshay Singhal, Kumud Lakara, Pritika Ramu, Vikas Balani, Anandhavelu N; Minimally Guided Semantic Extraction; US Patent Application to be filed; Adobe Inc.

**Inderjeet Nair**, Natwar Modani; Exploiting Legal Domain Characteristics for Legal Language Model Pretraining; US Patent Application to be filed; Adobe Inc.

**Inderjeet Nair**, Natwar Modani; Integrated Reading Experience for Contracts and their Amendments; US Patent Application 17/954,558; Adobe Inc.

Ayush Maheshwari, **Inderjeet Nair**, Navita Goyal, Natwar Modani, Ani Nenkova; Assisted Review of Text Content using a Machine Learning Model; US Patent Application 17/549,270; Adobe Inc.

Natwar Modani, Vaidehi Patil, **Inderjeet Nair**, Gaurav Verma, Anurag Maurya, Anirudh Kanfade; Systems for Generating Indications of Relationships between Electronic Documents; US Patent Application 17/534,744; Adobe Inc.
<br>

## Work Experience

### Bloomberg CTO office, New York
Research Intern - May 2025 - August 2025

### University of Michigan, Ann Arbor
Ph.D. Student -  September 2023 - Current

### Adobe Research Labs, Bangalore
Research Associate - July 2021 - August 2023

### Adobe, Research Labs, Bangalore
Research Intern — June 2020 - August 2020

### Stamp My Visa, Mumbai
Production Engineer — June 2019 - August 2019

## CV

[PDF]({{site.url}}/Inderjeet_nair_resume.pdf)

## Contact

### Email

inderjeetnair1 [at] gmail.com
<br />
inair [at] umich.com

