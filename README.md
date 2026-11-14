<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg">
  <img src="assets/header-light.svg" width="100%" alt="Salmane El Maazouzi, Generative AI Engineer : RAG, agents, LLMOps, évaluation. En recherche active d'un poste en IA générative.">
</picture>

<p align="center">
  <a href="https://www.linkedin.com/in/‹à-compléter›"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:salmane.maazouzi@gmail.com"><img src="https://img.shields.io/badge/salmane.maazouzi@gmail.com-1f2328?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
  <img src="https://img.shields.io/badge/France-1f2328?style=flat-square&logo=googlemaps&logoColor=white" alt="Basé en France">
  <img src="https://img.shields.io/badge/Français%20·%20English-1f2328?style=flat-square&logo=googletranslate&logoColor=white" alt="Langues">
</p>

Ingénieur IA & Data diplômé de l'**INSA Rouen Normandie**, je construis des applications d'IA générative **qui citent leurs sources, se testent et se mesurent** : RAG, systèmes multi-agents, évaluation et mise en production.
Ce qui me motive : faire passer un LLM du prototype qui impressionne en démo au système fiable sur lequel une équipe peut compter.

> [!TIP]
> **🟢 En recherche active : poste d'ingénieur IA générative / LLM Engineer** (‹CDI›) · ‹Paris / Lyon / télétravail› · disponible ‹immédiatement›
>
> RAG, agents, évaluation de LLM, LLMOps. Parlons-en : [salmane.maazouzi@gmail.com](mailto:salmane.maazouzi@gmail.com) · [LinkedIn](https://www.linkedin.com/in/‹à-compléter›)

## 🤖 `.well-known/agent-card.json`

Mes agents se présentent entre eux avec une *Agent Card* (protocole [A2A](https://a2a-protocol.org)). Voici la mienne :

```jsonc
{
  "name": "Salmane El Maazouzi",
  "description": "GenAI engineer: turns LLM prototypes into reliable, measurable systems.",
  "skills": [
    { "id": "rag",    "tags": ["retrieval", "pgvector", "reranking", "citation checks"] },
    { "id": "agents", "tags": ["LangGraph", "A2A", "tool calling", "human-in-the-loop"] },
    { "id": "llmops", "tags": ["evaluation", "cost & latency tracking", "CI", "typed Python"] },
    { "id": "deep-learning", "tags": ["PyTorch", "GANs", "CNN architectures", "HPC / Slurm"] }
  ],
  "languages": ["fr", "en"],
  "status": "open_to_work"   // ← voir ci-dessus 👆
}
```

## 🚧 En cours

<table>
<tr>
<td width="50%" valign="top">

### ⚖️ [DroitClair](https://github.com/selmaazouzi/droitclair-rag-travail)

**Assistant RAG sur le droit du travail français** : il répond uniquement à partir du Code du travail officiel et cite chaque article utilisé.

- 686 articles récupérés via l'**API Légifrance**, ingestion idempotente
- **bge-m3** + **pgvector** (HNSW), LLM interchangeable (OpenRouter ou Ollama en local)
- **Vérification automatique des citations**, réponses en streaming (FastAPI + SSE, Chainlit)
- 162 tests, `mypy --strict`, CI sur une vraie base pgvector
- **Prochaine étape :** recherche hybride, reranking et évaluation chiffrée

`Python` `FastAPI` `PostgreSQL` `pgvector` `OpenRouter` `Ollama`

</td>
<td width="50%" valign="top">

<img src="assets/droitclair-demo.png" alt="DroitClair répond à une question sur la période d'essai d'un cadre, en citant les articles du Code du travail">

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🛒 [Assistant d'achat multi-agents](https://github.com/achrafElFaiq/multi-agent-shopping-assistant)

**Trois agents LangGraph qui dialoguent via A2A** pour comprendre une demande, chercher dans le catalogue Shopify et acheter après validation humaine.

`LangGraph` `A2A` `PostgreSQL` `pgvector` `RAG`

</td>
<td width="50%" valign="top">

**Ma contribution** (contributeur principal, projet à 3) :
- l'agent **préférences utilisateur** (outils, appel de fonction, persistance PostgreSQL)
- la **pause d'approbation humaine** avant paiement
- le graphe LangGraph initial, les schémas Pydantic et la CI

</td>
</tr>
</table>

## 🗂️ Projets précédents

| Projet | Ce que j'ai fait | Stack |
|---|---|---|
| **RegNet** · reproduction de *Designing Network Design Spaces* (FAIR) | Implémentation de RegNetX et entraînement sur ImageNet, sur un cluster de calcul | PyTorch, Slurm |
| **EdgeConnect** · reconstruction d'images | Entraînement d'un GAN en deux étapes (contours, puis texture), comparaison de méthodes d'extraction de contours, évaluation PSNR / SSIM / FID sur CelebA | PyTorch, MLflow |
| **Générateur d'examens** | API qui compose des examens à partir d'une banque de questions, avec génération de questions par RAG | Flask, LangChain, FAISS, Ollama |
| **Robot autonome** | Suivi de ligne, détection d'obstacles, pilotage à la manette, sur Raspberry Pi | C, Raspberry Pi, I²C |
| **Compression de Huffman** | Compresseur et décompresseur de fichiers, avec tests unitaires | C |

## 🧭 Parcours

| | |
|---|---|
| **‹année›** | 🎓 **Diplôme d'ingénieur IA & Data**, INSA Rouen Normandie |
| **‹dates›** | 💼 **‹Poste›**, ‹Entreprise› · ‹une ligne sur ce que tu as livré› |
| **‹dates›** | 💼 **‹Poste›**, ‹Entreprise› · ‹une ligne sur ce que tu as livré› |

## 🧰 Outils

| | |
|---|---|
| **IA générative** | ![LangChain](https://img.shields.io/badge/LangChain-1f2328?style=flat-square&logo=langchain&logoColor=white) ![LangGraph](https://img.shields.io/badge/LangGraph-1f2328?style=flat-square&logo=langgraph&logoColor=white) ![Hugging Face](https://img.shields.io/badge/Hugging%20Face-1f2328?style=flat-square&logo=huggingface&logoColor=FFD21E) ![Ollama](https://img.shields.io/badge/Ollama-1f2328?style=flat-square&logo=ollama&logoColor=white) ![OpenRouter](https://img.shields.io/badge/OpenRouter-1f2328?style=flat-square&logo=openrouter&logoColor=white) ![A2A](https://img.shields.io/badge/A2A%20protocol-1f2328?style=flat-square) ![Chainlit](https://img.shields.io/badge/Chainlit-1f2328?style=flat-square) |
| **Recherche & ML** | ![PyTorch](https://img.shields.io/badge/PyTorch-1f2328?style=flat-square&logo=pytorch&logoColor=EE4C2C) ![pgvector](https://img.shields.io/badge/pgvector-1f2328?style=flat-square&logo=postgresql&logoColor=white) ![FAISS](https://img.shields.io/badge/FAISS-1f2328?style=flat-square&logo=meta&logoColor=white) ![sentence-transformers](https://img.shields.io/badge/sentence--transformers-1f2328?style=flat-square) ![MLflow](https://img.shields.io/badge/MLflow-1f2328?style=flat-square&logo=mlflow&logoColor=0194E2) ![NumPy](https://img.shields.io/badge/NumPy-1f2328?style=flat-square&logo=numpy&logoColor=4DABCF) |
| **Back-end & données** | ![Python](https://img.shields.io/badge/Python-1f2328?style=flat-square&logo=python&logoColor=FFD43B) ![FastAPI](https://img.shields.io/badge/FastAPI-1f2328?style=flat-square&logo=fastapi&logoColor=009688) ![Flask](https://img.shields.io/badge/Flask-1f2328?style=flat-square&logo=flask&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-1f2328?style=flat-square&logo=postgresql&logoColor=4169E1) ![Pydantic](https://img.shields.io/badge/Pydantic-1f2328?style=flat-square&logo=pydantic&logoColor=E92063) ![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-1f2328?style=flat-square&logo=sqlalchemy&logoColor=white) |
| **Ingénierie** | ![Docker](https://img.shields.io/badge/Docker-1f2328?style=flat-square&logo=docker&logoColor=2496ED) ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-1f2328?style=flat-square&logo=githubactions&logoColor=2088FF) ![uv](https://img.shields.io/badge/uv-1f2328?style=flat-square&logo=uv&logoColor=DE5FE9) ![pytest](https://img.shields.io/badge/pytest-1f2328?style=flat-square&logo=pytest&logoColor=0A9EDC) ![Ruff](https://img.shields.io/badge/Ruff-1f2328?style=flat-square&logo=ruff&logoColor=D7FF64) ![mypy](https://img.shields.io/badge/mypy%20strict-1f2328?style=flat-square) ![Slurm](https://img.shields.io/badge/Slurm%20%2F%20HPC-1f2328?style=flat-square) ![Linux](https://img.shields.io/badge/Linux-1f2328?style=flat-square&logo=linux&logoColor=white) |
| **Aussi** | ![C](https://img.shields.io/badge/C-1f2328?style=flat-square&logo=c&logoColor=A8B9CC) ![Java](https://img.shields.io/badge/Java-1f2328?style=flat-square&logo=openjdk&logoColor=white) ![Vue.js](https://img.shields.io/badge/Vue.js-1f2328?style=flat-square&logo=vuedotjs&logoColor=4FC08D) ![LaTeX](https://img.shields.io/badge/LaTeX-1f2328?style=flat-square&logo=latex&logoColor=white) |

---

<p align="center"><sub>Un projet d'IA générative à fiabiliser ? <a href="mailto:salmane.maazouzi@gmail.com">Écrivez-moi</a>.</sub></p>
