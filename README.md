# Hi, I'm Deva Atturu

**GenAI & Cloud Engineer** · 4+ years building production AI systems, data pipelines, and cloud infrastructure across financial services and applied research.

I build LLM-powered RAG systems and multi-agent workflows, run cloud-native MLOps on AWS and GCP, and write high-throughput Python/SQL data pipelines. I care about shipping models faster, scaling distributed systems, and keeping cloud costs efficient.

> [!IMPORTANT]
> **Published research (2025):** [*Deep Learning in Archiving Indus Script and Motif Information*](https://journal.caa-international.org/articles/10.5334/jcaa.175), peer reviewed in the *Journal of Computer Applications in Archaeology*. A deep-learning pipeline that reads the undeciphered Indus Valley script from ancient seals. **94.5% sign-recognition accuracy.**

## What I Work On

- **GenAI / LLM apps** – RAG (chunking, hybrid search), agentic workflows, structured outputs, prompt engineering
- **Cloud & MLOps** – model deployment on AWS and GCP with Docker, Kubernetes, Terraform, and CI/CD
- **Data engineering** – high-volume Python/SQL pipelines on BigQuery and PostgreSQL
- **Computer vision** – detection and classification with YOLO, MobileNet, and GAN-based augmentation

## Experience

| Role | Company | Dates | Highlights |
|---|---|---|---|
| **AI Specialist** | Alliance Data Solutions | Nov 2025 – Present | Agentic GenAI workflows with Claude driving web automation and API integrations: **+40%** data collection speed, **1.2M+** data points parsed daily, **95%** less manual review |
| **Software Engineer** | Kurras LLC (contracted to PNC Bank) | Apr 2025 – Nov 2025 | Cloud AI/ML pipelines for real-time fraud models: **+14%** detection accuracy; **35%** lower query latency for batch risk models |
| **Software Engineer Intern** | TekSharks Inc | Aug 2024 – Apr 2025 | ML operations on AWS and GCP: **25%** faster provisioning, **30%** fewer security compliance flags |
| **Research Assistant** | Florida Institute of Technology | Mar 2023 – May 2024 | Computer vision pipeline for archaeological imagery: **+18%** detection precision; React + Flask research portal with **50%** faster model updates |
| **Developer** | Wipro | Jul 2021 – Dec 2022 | Multi-cloud SDN features on Juniper Contrail: **25%** lower config latency; **15%** better Kubernetes resource use |

## Selected Work

> Most of my professional work is proprietary, so the code isn't public. These summaries describe the problems and results without confidential details.

### Agentic data-collection pipeline · Alliance Data Solutions

**Problem:** Collecting data from many websites and APIs was slow, and every record needed manual review before it could be used.

**Approach:** Built agentic workflows with Claude that drive multi-threaded Python web automation and REST API integrations. Every LLM response is validated against a strict schema, so bad output is caught before it reaches the pipeline.

**Results:** **40%** faster data collection · **1.2M+** data points parsed daily · **95%** less manual review · near-zero ingestion errors

`Python` `Claude` `Structured outputs` `Playwright` `REST APIs`

### Real-time fraud detection · Financial services (via Kurras LLC)

**Problem:** Fraud models needed higher accuracy, but real fraud examples are rare, and batch risk queries were slow.

**Approach:** Built cloud AI/ML pipelines on AWS and GCP using MobileNet-based models, with GAN-generated synthetic data to fill in the rare fraud cases. Deployed as containerized microservices with CI/CD, and tuned the SQL/Python workflows in BigQuery and PostgreSQL.

**Results:** **14%** better fraud detection accuracy · **35%** lower query latency for batch risk models

`TensorFlow` `PyTorch` `GANs` `Docker` `Kubernetes` `BigQuery` `PostgreSQL`

### Multi-cloud ML operations · TekSharks Inc

**Problem:** Setting up ML infrastructure was slow and inconsistent across AWS and GCP, which caused frequent security compliance alerts.

**Approach:** Standardized access controls and deployment patterns across both clouds, and worked with DevOps to automate infrastructure monitoring and security hardening.

**Results:** **25%** faster infrastructure provisioning · **30%** fewer security compliance flags

`AWS` `GCP` `IAM` `Lambda` `Pub/Sub`

### Archaeological computer vision portal · Florida Institute of Technology

**Problem:** Researchers classified artifact images by hand, and updating models was slow.

**Approach:** Built a computer vision pipeline with YOLOv3 and MobileNet, using GAN-based augmentation to make up for limited training data. Shipped a React + Flask portal where researchers correct predictions, and those corrections feed model retraining. Deployed on Cloud Run with Cloud Build.

**Results:** **18%** better detection precision · **50%** faster model deployment and updates · led to the [published paper](https://doi.org/10.5334/jcaa.175)

`YOLOv3` `MobileNet` `React` `Flask` `Docker` `Cloud Run`

## Publications

**Deep Learning in Archiving Indus Script and Motif Information**  
V. Dixit, N. Hussain, S. Basak, **D. Atturu**, D. Mitra, U. Bhattacharya  
*Journal of Computer Applications in Archaeology*, 8(1), 156–169, 2025 · Peer reviewed  
[Read the paper](https://journal.caa-international.org/articles/10.5334/jcaa.175) · DOI: [10.5334/jcaa.175](https://doi.org/10.5334/jcaa.175)

- **YOLOv3** finds each script sign, **MobileNet** identifies it against the Mahadevan sign list (**94.5% accuracy, 95% F1**, best of 15 architectures tested), and a custom CNN identifies 11 motif types.
- Built on 963 hand-annotated seal images; funded by the National Endowment for the Humanities.
- **My role:** ran the initial experiments and built the MySQL database and the end-to-end workflow.

**Deep Learning in Indus Valley Script Digitization** – Master's thesis, Florida Institute of Technology, 2024 · [Read the thesis](https://repository.fit.edu/etd/1416)

## Projects

Personal, academic, and research projects.

| Project | What it does | Tech |
|---|---|---|
| **Android LLM Agent** | An AI agent that controls an Android phone from plain-English goals, with an evaluation framework comparing prompting strategies | Python, OpenAI API, Pydantic |
| [SARS-CoV-2 Sequence Clustering](https://github.com/datturu/sars-cov2-sequence-clustering) | Clusters virus DNA sequences with DBSCAN and Levenshtein distance | Python, scikit-learn |
| [Face Recognition Attendance](https://github.com/datturu/face-recognition-attendance) | Automatic classroom attendance on a Raspberry Pi using face recognition | Python, OpenCV, Raspberry Pi |
| [SDN DNS Cache](https://github.com/datturu/sdn-dns-cache) | Speeds up DNS lookups by caching responses in an SDN controller | Ryu, Mininet, BIND9 |
| [Python Ray Tracer](https://github.com/datturu/python-ray-tracer) | A ray tracer built from scratch that renders spheres on a plane | Python, NumPy |

## Tech Stack

| Area | Tools |
|---|---|
| **GenAI / LLM** | RAG, LangChain, LlamaIndex, FAISS, Pinecone, Claude, GPT-4-class models, structured outputs, agentic workflows |
| **ML & Data** | Python, SQL, TensorFlow, PyTorch, scikit-learn, Pandas, NumPy, PostgreSQL, BigQuery |
| **AWS** | EKS, Lambda, SageMaker, Bedrock, S3, EC2, IAM, CloudWatch |
| **GCP** | Cloud Run, BigQuery, Pub/Sub, Cloud Storage, Cloud Build |
| **DevOps** | Docker, Kubernetes, Terraform, GitHub Actions, Jenkins, Prometheus, Grafana |
| **Automation** | Selenium, Playwright, REST APIs |
| **Ways of working** | GitHub, Jira, Agile/Scrum, code reviews |
