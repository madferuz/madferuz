<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:1a0533,50:4c1d95,100:6d28d9&height=200&section=header&text=Feruzbek&fontSize=70&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Integrated%20Systems%20Engineer%20%7C%20ML%20Engineering&descAlignY=58&descAlign=50" />

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&pause=1000&color=A78BFA&center=true&vCenter=true&width=600&lines=Machine+Learning+Engineer+in+the+making;Semantic+Search+%26+Information+Retrieval;Building+real+systems%2C+not+just+notebooks;Integrated+Systems+Engineering+%40+Inha" alt="Typing SVG" />
</a>

<br/>

![Inha University](https://img.shields.io/badge/Inha_University-Integrated_Systems_Engineering-4c1d95?style=for-the-badge&labelColor=1a0533)
![Location](https://img.shields.io/badge/Incheon-South_Korea-6d28d9?style=for-the-badge&labelColor=1a0533)

<br/>

<a href="https://madferuz.github.io">
  <img src="https://img.shields.io/badge/Portfolio-6d28d9?style=for-the-badge&logo=vercel&logoColor=white&labelColor=1a0533" />
</a>
<a href="https://github.com/madferuz">
  <img src="https://img.shields.io/badge/GitHub-4c1d95?style=for-the-badge&logo=github&logoColor=white&labelColor=1a0533" />
</a>

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=madferuz&style=for-the-badge&color=6d28d9&labelColor=1a0533)
![Followers](https://img.shields.io/github/followers/madferuz?style=for-the-badge&color=4c1d95&labelColor=1a0533&logo=github)
![Stars](https://img.shields.io/github/stars/madferuz?style=for-the-badge&color=7c3aed&labelColor=1a0533&logo=github)

</div>

---

## About

I'm an **Integrated Systems Engineering** student at **Inha University** (Incheon, South Korea), focused on **machine learning engineering** — with a working preference for building systems that actually run over collecting tutorial certificates.

My core interest is **information retrieval and semantic search**: representing meaning as vectors, indexing at scale, and evaluating retrieval quality rigorously. Alongside that, I work across the ML stack — data preparation, supervised/unsupervised learning, deep learning (CNNs, RNNs, transformers), and the surrounding tooling (PyTorch, sentence-transformers, FAISS, Hugging Face).

I approach ML the way an engineer approaches a system: refactor prototypes into proper packages, write tests, measure performance, and be honest about what a project does and doesn't do.

**Open to:** ML engineering internships · research lab positions · Korean AI startup roles · Kaggle collaboration

---

## Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**Machine Learning & Deep Learning**

<img src="https://skillicons.dev/icons?i=pytorch,tensorflow,sklearn&theme=dark" />

![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![FAISS](https://img.shields.io/badge/FAISS-4c1d95?style=flat-square&logo=meta&logoColor=white)
![sentence--transformers](https://img.shields.io/badge/sentence--transformers-6d28d9?style=flat-square)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white)

**Data & Scientific Computing**

<img src="https://skillicons.dev/icons?i=&theme=dark" />

![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4c1d95?style=flat-square)

**Tooling & Environment**

<img src="https://skillicons.dev/icons?i=git,github,vscode,linux,bash&theme=dark" />

**Robotics**

![ROS](https://img.shields.io/badge/ROS-22314E?style=flat-square&logo=ros&logoColor=white)

---

## ML / Engineering Focus

| Domain | Level | Details |
|:---|:---:|:---|
| **Semantic Search & Retrieval** | Working | Dense embeddings, FAISS indexing, retrieval evaluation (precision@k) |
| **Deep Learning** | Studying → Applying | CNNs, RNNs, transformers; PyTorch as primary framework |
| **NLP** | Working | Sentence embeddings, transformer models via Hugging Face |
| **Classical ML** | Working | Supervised/unsupervised methods, model evaluation, scikit-learn |
| **Robotics / Navigation** | Contributor | ROS navigation stack, move_base, tf2 |
| **ML Foundations** | Solid | Statistics (variance, correlation), linear algebra, data preparation |

---

## Featured Projects

<details open>
<summary><b>arXiv Semantic Search</b> — dense-retrieval search over ML research abstracts</summary>

<br/>

A semantic search engine over machine learning papers, refactored from a prototype into a proper Python package with tests. Embeds paper abstracts into a dense vector space and retrieves by meaning rather than keywords.

| Attribute | Detail |
|:---|:---|
| **Stack** | Python · PyTorch · sentence-transformers · FAISS · Hugging Face `datasets` |
| **Scale** | Index built over 20,000 abstracts from `CShorten/ML-ArXiv-Papers` |
| **Structure** | Packaged as `src/arxiv_search/` (config, embedder, index) with `build_index.py` and `search.py` |
| **Testing** | pytest suite (`tests/test_index.py`) with `conftest.py` fixtures |
| **Status** | Verified working; retrieval evaluation (precision@k) in progress |
| **Repository** | [madferuz/arxiv-semantic-search](https://github.com/madferuz/arxiv-semantic-search) |

Querying *"neural networks for image classification"* returns relevant results with cosine similarity scores around 0.68. Built on a pinned, reproducible dependency stack. Current work extends the project with a retrieval-evaluation module measuring precision@k over a labelled query set.

</details>

<details>
<summary><b>Campus Delivery Robot</b> — ROS navigation package for autonomous delivery</summary>

<br/>

Contribution to a ROS-based campus delivery robot. My work is the **navigation package** — the piece that turns a delivery request into an executed route.

| Attribute | Detail |
|:---|:---|
| **Stack** | Python · ROS · move_base · tf2 |
| **My contribution** | `waypoint_action_server_node.py` (DeliveryMission action server) and `global_planner_helper_node.py` |
| **Scope** | Action-server orchestration of navigation goals; global planning helpers |
| **Documentation** | Contribution scope documented in `MY_CONTRIBUTION.md` |
| **Repository** | [madferuz/campus-delivery-robot](https://github.com/madferuz/campus-delivery-robot) |

The action server accepts a delivery mission and drives navigation through `move_base`, using `tf2` for frame transforms. The repository is a fork of an existing project — the navigation package reflects my own contribution, documented transparently.

</details>

<details>
<summary><b>IELTS Speaking Coach</b> — speech-to-feedback practice tool</summary>

<br/>

A speaking-practice application scaffolded around an incremental roadmap: CLI → Whisper transcription → LLM feedback → pronunciation scoring → web UI.

| Attribute | Detail |
|:---|:---|
| **Stack** | Python · Kivy · Whisper (planned) |
| **Current state** | Scaffolded CLI with a Whisper transcription stub (`transcribe.py`) |
| **Roadmap** | v1 CLI → v2 Whisper → v3 LLM feedback → v4 pronunciation scoring → v5 web UI |
| **Repository** | [madferuz/IELTS-Speaking-Coach](https://github.com/madferuz/IELTS-Speaking-Coach) |

Designed to grow in well-scoped stages rather than as one large build, so each version is completable and testable on its own.

</details>

---

## Currently Learning & Building

```yaml
learning:
  - Deep learning architectures (transformers, GANs) via roadmap.sh ML curriculum
  - Retrieval evaluation methodology (precision@k, ranking metrics)
building:
  - Retrieval-evaluation module for arXiv Semantic Search
  - Incremental IELTS Speaking Coach (Whisper + LLM feedback)
exploring:
  - Kaggle competitions to build a practical track record
  - Korean AI-startup and university-lab opportunities
open_to:
  - ML engineering internships
  - Research assistant / lab positions
  - Collaboration on retrieval & NLP projects
```

---

## GitHub Analytics

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=madferuz&show_icons=true&theme=react&hide_border=true&bg_color=1a0533&title_color=A78BFA&icon_color=7c3aed&text_color=ffffff&include_all_commits=true&count_private=true" />
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=madferuz&layout=compact&theme=react&hide_border=true&bg_color=1a0533&title_color=A78BFA&text_color=ffffff&langs_count=8" />

<br/>

<img src="https://streak-stats.demolab.com?user=madferuz&theme=react&hide_border=true&background=1a0533&ring=A78BFA&fire=7c3aed&currStreakLabel=A78BFA" />

</div>

---

## Contribution Graph

<div align="center">

<img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=madferuz&bg_color=1a0533&color=A78BFA&line=7c3aed&point=ffffff&area=true&hide_border=true" />

</div>

---

<div align="center">

*"Build systems you can explain, measure, and defend — the honest version is already strong enough."*

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:6d28d9,50:4c1d95,100:1a0533&height=120&section=footer" />

</div>

