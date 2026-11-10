<!-- ===================== HEADER ===================== -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=200&section=header&text=Mahmoud%20Amiri&fontSize=46&fontColor=ffffff&fontAlignY=36&desc=Retrieval%20%E2%80%A2%20RAG%20%E2%80%A2%20Text%20Mining%20for%20Chemistry%20Literature&descSize=16&descAlignY=58&animation=fadeIn" width="100%" alt="header"/>
</p>

<p align="center">
  <a href="https://github.com/mahmoud-amiri">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=3000&pause=800&color=4FC3F7&center=true&vCenter=true&multiline=false&width=640&height=40&lines=Researcher+%40+Leibniz+IPHT+%26+Uni+Jena+%F0%9F%A7%AA;Making+chemistry+literature+machine-readable;Building+chemistry-aware+RAG+pipelines;582%2C724+open+chemistry+articles+and+counting...;Reproducible+%E2%80%A2+License-aware+%E2%80%A2+Open" alt="typing intro"/>
  </a>
</p>

<p align="center">
  <a href="https://orcid.org/0009-0001-3826-1789"><img src="https://img.shields.io/badge/ORCID-0009--0001--3826--1789-A6CE39?style=for-the-badge&logo=orcid&logoColor=white" alt="ORCID"/></a>
  <a href="https://scholar.google.com/citations?user=vWPEHQIAAAAJ&hl=en"><img src="https://img.shields.io/badge/Google_Scholar-Profile-4285F4?style=for-the-badge&logo=googlescholar&logoColor=white" alt="Google Scholar"/></a>
  <a href="https://www.researchgate.net/profile/Mahmoud-Amiri"><img src="https://img.shields.io/badge/ResearchGate-Profile-00CCBB?style=for-the-badge&logo=researchgate&logoColor=white" alt="ResearchGate"/></a>
  <a href="https://linkedin.com/in/m-ami"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:mahmoud.amiri@uni-jena.de"><img src="https://img.shields.io/badge/Email-Say_hi-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=mahmoud-amiri&label=Profile%20views&color=2c5364&style=flat-square" alt="profile views"/>
  <img src="https://img.shields.io/github/followers/mahmoud-amiri?label=Followers&style=flat-square&color=203a43" alt="followers"/>
  <img src="https://img.shields.io/badge/📍-Jena,_Germany-0f2027?style=flat-square" alt="location"/>
</p>

---

## 🧬 About me

```python
class MahmoudAmiri:
    affiliation = ["Leibniz IPHT", "Friedrich Schiller University Jena", "Bocklitz Lab"]
    mission     = "Get chemistry literature into a form machines can search and reason over."
    interests   = ["Retrieval-Augmented Generation", "Scientific Text Mining",
                   "Embeddings & Chunking", "Reproducible Research Workflows"]
    values      = ["open data", "license-aware corpora", "reproducibility"]

    def current_focus(self):
        return "Chemistry-aware RAG on top of the Lit2Vec corpus"
```

---

## 🔬 Research pipeline

> How my projects fit together — GitHub renders this diagram live.

```mermaid
flowchart LR
    A[(S2ORC<br/>full-text papers)] -->|license screening| B[Lit2Vec corpus<br/>582,724 CC articles]
    B --> C[Structured Markdown]
    C --> D[Paragraph embeddings]
    C --> E[TL;DR summaries<br/>DistilBART]
    C --> F[Subfield labels<br/>MLP classifier]
    D --> G{{Chunk Twice,<br/>Embed Once}}
    G --> H[🔎 Chemistry-aware RAG]
    E --> H
    F --> H

    style B fill:#203a43,stroke:#4FC3F7,color:#fff
    style G fill:#2c5364,stroke:#4FC3F7,color:#fff
    style H fill:#4FC3F7,stroke:#0f2027,color:#0f2027
```

---

## 📄 Selected publications

<details open>
<summary><b>📚 Lit2Vec</b> — a reproducible workflow for building a license-screened full-text chemistry corpus</summary>
<br/>

A reproducible pipeline that turns S2ORC into an open corpus of **582,724 CC-licensed chemistry articles**, normalized to structured Markdown with paragraph embeddings, TL;DR summaries and topic labels.

<a href="https://arxiv.org/abs/2604.12498"><img src="https://img.shields.io/badge/arXiv-2604.12498-B31B1B?style=flat-square&logo=arxiv" alt="arXiv"/></a>
<a href="https://github.com/Bocklitz-Lab/Lit2Vec-code"><img src="https://img.shields.io/badge/Code-Lit2Vec--code-181717?style=flat-square&logo=github" alt="code"/></a>

</details>

<details>
<summary><b>✂️ Chunk Twice, Embed Once</b> — chunking and embedding choices for chemistry-aware RAG</summary>
<br/>

A systematic study of how chunking strategy and embedding model choice affect retrieval quality on chemistry text.

<a href="https://arxiv.org/abs/2506.17277"><img src="https://img.shields.io/badge/arXiv-2506.17277-B31B1B?style=flat-square&logo=arxiv" alt="arXiv"/></a>
<a href="https://github.com/Bocklitz-Lab/chunk_twice_embed_once"><img src="https://img.shields.io/badge/Code-chunk__twice__embed__once-181717?style=flat-square&logo=github" alt="code"/></a>

</details>

<details>
<summary><b>🧠 Metabolic Minds and Machine Models</b> — a comparative review of efficiency mechanisms</summary>
<br/>

<a href="https://github.com/Bocklitz-Lab/Metabolic-Minds-and-Machine-Models"><img src="https://img.shields.io/badge/Repo-Metabolic--Minds-181717?style=flat-square&logo=github" alt="repo"/></a>

</details>

<p align="right"><a href="https://scholar.google.com/citations?user=vWPEHQIAAAAJ&hl=en">→ Full list on Google Scholar</a></p>

---

## 🚀 Featured projects

<p align="center">
  <a href="https://github.com/Bocklitz-Lab/Lit2Vec-code">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=Bocklitz-Lab&repo=Lit2Vec-code&theme=tokyonight&hide_border=true&border_radius=12" alt="Lit2Vec-code"/>
  </a>
  <a href="https://github.com/Bocklitz-Lab/chunk_twice_embed_once">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=Bocklitz-Lab&repo=chunk_twice_embed_once&theme=tokyonight&hide_border=true&border_radius=12" alt="chunk_twice_embed_once"/>
  </a>
  <br/>
  <a href="https://github.com/Bocklitz-Lab/lit2vec-subfield-classifier">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=Bocklitz-Lab&repo=lit2vec-subfield-classifier&theme=tokyonight&hide_border=true&border_radius=12" alt="lit2vec-subfield-classifier"/>
  </a>
  <a href="https://github.com/Bocklitz-Lab/lit2vec-tldr-bart">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=Bocklitz-Lab&repo=lit2vec-tldr-bart&theme=tokyonight&hide_border=true&border_radius=12" alt="lit2vec-tldr-bart"/>
  </a>
</p>

---

## 🛠️ Toolbox

<p align="center">
  <img src="https://skillicons.dev/icons?i=py,pytorch,sklearn,tensorflow,postgres,docker,linux,bash,git,github,vscode,latex&perline=12" alt="skills"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/🤗_Hugging_Face-Transformers-FFD21E?style=flat-square" alt="HF"/>
  <img src="https://img.shields.io/badge/LangChain-RAG-1C3C3C?style=flat-square&logo=langchain" alt="LangChain"/>
  <img src="https://img.shields.io/badge/FAISS-Vector_Search-0467DF?style=flat-square&logo=meta" alt="FAISS"/>
  <img src="https://img.shields.io/badge/Jupyter-Notebooks-F37626?style=flat-square&logo=jupyter&logoColor=white" alt="Jupyter"/>
  <img src="https://img.shields.io/badge/spaCy-NLP-09A3D5?style=flat-square&logo=spacy&logoColor=white" alt="spaCy"/>
</p>

---

## 📊 GitHub stats

<details open>
<summary><b>Click to expand / collapse</b></summary>
<br/>

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=mahmoud-amiri&show_icons=true&include_all_commits=true&count_private=true&theme=tokyonight&hide_border=true&border_radius=12" alt="stats"/>
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=mahmoud-amiri&layout=compact&langs_count=6&theme=tokyonight&hide_border=true&border_radius=12" alt="top languages"/>
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=mahmoud-amiri&theme=tokyonight&hide_border=true&border_radius=12" alt="streak"/>
</p>

<p align="center">
  <img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=mahmoud-amiri&theme=tokyo-night&hide_border=true&area=true&radius=12" alt="activity graph"/>
</p>

</details>

---

## 🐍 Contribution snake

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)"  srcset="https://raw.githubusercontent.com/mahmoud-amiri/mahmoud-amiri/output/github-contribution-grid-snake-dark.svg"/>
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/mahmoud-amiri/mahmoud-amiri/output/github-contribution-grid-snake.svg"/>
    <img alt="contribution snake" src="https://raw.githubusercontent.com/mahmoud-amiri/mahmoud-amiri/output/github-contribution-grid-snake.svg"/>
  </picture>
</p>

---

## 🤝 Let's collaborate

<details>
<summary><b>I'm open to collaborations on…</b></summary>
<br/>

- 🧪 Scientific literature mining & information extraction
- 🔎 Retrieval evaluation and RAG for domain-specific science
- 📦 Building open, license-clean research corpora
- ♻️ Reproducible ML workflows

📬 Reach me at **mahmoud.amiri@uni-jena.de**

</details>

<!-- ===================== FOOTER ===================== -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=120&section=footer" width="100%" alt="footer"/>
</p>

