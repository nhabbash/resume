---
layout: cv
title: Resume
---

# Nassim Habbash

<div id="webaddress">
<a href="nhabbash.github.io/resume/" target="_blank">
Resume</a> |
<a href="https://www.linkedin.com/in/nhabbash/" target="_blank">
LinkedIn</a> |
<a href="https://github.com/nhabbash/" target="_blank">
Github</a>
</div>

## Work Experience

**Raft**
`May 2024 - Present`<br>
*ML Platform Team Lead*

- Led and managed a cross-functional team of 2 ML engineers, 2 data labeling specialists
- Designed and implemented a Prediction Store to track runtime prediction and configuration data across model servers and microservices, improving metric granularity and reducing ticket resolution times
- Built data labeling pipelines and integrations between Raft's customer-labeled data and third-party tooling, leveraging human-in-the-loop labeling and smart sampling strategies to increase the volume of high-confidence labeled data
- Developed and drove adoption of internal tooling that enhanced engineering efficiency in model evaluation and dataset management
- Led cross-functional collaboration between the ML Platform, ML Core, Data, and DevOps teams to align on technical requirements and drive execution for projects requiring multi-team coordination. Facilitated stakeholder discussions, ensuring clear communication of dependencies, priorities, and trade-offs. Acted as the bridge between teams, translating business needs into actionable engineering tasks and resolving blockers to accelerate delivery


`Jun 2023 - May 2024`<br>
*MLOps Tech Lead*

- Designed ML performance monitoring metrics, leveraging proxy measurements (e.g., user actions, edit rate) to assess real-world impact and detect regressions early
- Implemented standardized load testing CI jobs to mitigate traffic volume risks and ensure system stability under varying loads
- Reduced failure rates in FastAPI microservices by migrating from Gunicorn to Uvicorn, tuning configurations and optimizing IO-bound and CPU-bound task execution
- Established a Pre-Production environment across Kubernetes and data stores, mirroring Production states to improve rollout confidence through realistic pre-deployment metrics
- Introduced Data Warehousing for ML workflows, tracking critical data states in BigQuery to enhance analytical capabilities
- Improved Elasticsearch performance through resharding, reindexing, and automated downsampling, reducing query latency and storage overhead
- Designed and maintained Model Retraining and Evaluation DAGs, streamlining ML model iteration and continuous learning processes


`Sep 2021 - Jun 2023`<br>
*Machine Learning Engineer*

- Redesign and improve scalability of ML inference servers by repackaging legacy codebases and splitting business logic from model serving logic
- Build ETL pipelines to extract, version and label data extracted from trade documents for retraining and testing
- Build model retraining pipelines to improve extraction performance

**Trinity College Dublin • Distributed Systems Group**
`Sep 2020 - Feb 2021`<br>
*Machine Learning Research Intern*

- Worked on Reinforcement Learning and state space self-adaptation using self-organizing maps (Python, Numpy, Graph-Tool, OpenAI Gym, W\&B)
- Reworked the architecture of a state space learning framework, making it RL algorithm agnostic, refactoring the data flows and components, increasing maintainability
- Designed new mechanisms to address the pre-existing stability and convergence issue of the model, obtaining stable performance throughout standard benchmarks and increasing the total reward rate of the previous iteration by 104%

**Sinapto Srl**
`Sep 2016 - Dec 2018`<br>
*Junior Web Developer*
- Designed and implemented new administration and teaching modules, integrating the new components to the pre-existing platform and systems (PHP, PostgreSQL, JQuery, JS/HTML/CSS)
- Maintained the infrastructure, ported legacy and unmaintained codebase, improving its supportability and extendibility, ticket resolution, end-to-end testing


## Education

**University of Milano-Bicocca**
`Oct 2018 - Feb 2021`

- M.Sc in Computer Science with Honours
- Areas: Machine Learning, Deep Learning, Data Analytics, Data and Text Mining, Knowledge Representation, Simulations, Data Visualization
- GPA <a id="sutd-gpa">> GPA: 29.57/30</a>, Final Grade: 110/110 cum laude

**University of Milano-Bicocca**
`Sep 2015 - Oct 2018`

- B.Sc. in Computer Science
- GPA <a id="smu-gpa">> 27.15/30</a>, Final Grade: 105/110


<div style="page-break-after: always;"></div>


## Academic Publications

**Reinforcement Learning for Autonomous Agents Exploring Random Environments**
`Sep 2020 - Apr 2020`<br>
- [Paper](http://ceur-ws.org/Vol-2706/paper5.pdf), [GH](https://github.com/nhabbash/autonomous-exploration-agent)
- Co-authored the architecture of an autonomous agent able to avoid obstacles while searching for a target in randomly generated and unknown environments, using Reinforcement Learning (Unity3D, ML-Agents)
- Illustrated the issues with basic RL approaches and presented solutions to fill the gap
- Developed a live demo using React and WebGL, deploying it on GHPages
- Published and presented at the conference "From Objects to Agents, 2020 Edition" by University of Bologna