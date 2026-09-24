# Hi, I'm Deva Atturu

I build projects across **AI agents**, **machine learning**, **computer vision**, and **networking**, mostly in Python.

> [!IMPORTANT]
> **Published research (2025):** [*Deep Learning in Archiving Indus Script and Motif Information*](https://journal.caa-international.org/articles/10.5334/jcaa.175), peer reviewed in the *Journal of Computer Applications in Archaeology*. A deep-learning pipeline that reads the undeciphered Indus Valley script from ancient seals. **94.5% sign-recognition accuracy.**

## Publications

**Deep Learning in Archiving Indus Script and Motif Information**  
V. Dixit, N. Hussain, S. Basak, **D. Atturu**, D. Mitra, U. Bhattacharya  
*Journal of Computer Applications in Archaeology*, 8(1), 156–169, 2025 · Peer reviewed  
[Read the paper](https://journal.caa-international.org/articles/10.5334/jcaa.175) · DOI: [10.5334/jcaa.175](https://doi.org/10.5334/jcaa.175)

An end-to-end pipeline that reads the undeciphered Indus Valley script from ancient seal images, identifies the seal's motif, and archives both in a searchable database.

- **YOLOv3** finds each script sign, **MobileNet** identifies it against the Mahadevan sign list (**94.5% accuracy, 95% F1**, best of 15 architectures tested), and a custom CNN identifies 11 motif types.
- Built on 963 hand-annotated seal images; funded by the National Endowment for the Humanities.
- **My role:** ran the initial experiments and built the MySQL database and the end-to-end workflow.

**Deep Learning in Indus Valley Script Digitization** – Master's thesis, Florida Institute of Technology, 2024  
[Read the thesis](https://repository.fit.edu/etd/1416)

## Projects

| Project | What it does | Tech |
|---|---|---|
| **Android LLM Agent** | An AI agent that controls an Android phone from plain-English goals, with an evaluation framework comparing prompting strategies | Python, OpenAI API, Pydantic |
| [SARS-CoV-2 Sequence Clustering](https://github.com/datturu/sars-cov2-sequence-clustering) | Clusters virus DNA sequences with DBSCAN and Levenshtein distance | Python, scikit-learn |
| [Face Recognition Attendance](https://github.com/datturu/face-recognition-attendance) | Automatic classroom attendance on a Raspberry Pi using face recognition | Python, OpenCV, Raspberry Pi |
| [SDN DNS Cache](https://github.com/datturu/sdn-dns-cache) | Speeds up DNS lookups by caching responses in an SDN controller | Ryu, Mininet, BIND9 |
| [Python Ray Tracer](https://github.com/datturu/python-ray-tracer) | A ray tracer built from scratch that renders spheres on a plane | Python, NumPy |
| **Indus Script Digitization** | Deep-learning pipeline that reads Indus Valley script and motifs from seal images ([published paper](https://doi.org/10.5334/jcaa.175)) | TensorFlow, PyTorch, MySQL |

## Skills

- **Languages:** Python, SQL
- **AI / ML:** LLM agents, prompt engineering, TensorFlow, PyTorch, scikit-learn
- **Computer vision:** OpenCV, face recognition, object detection
- **Networking:** SDN (Ryu, Mininet), DNS
- **Tools:** Git, Jupyter, Raspberry Pi, MySQL
