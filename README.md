<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg">
  <img src="assets/header-light.svg" width="100%" alt="Salmane El Maazouzi, Generative AI Engineer : RAG, agents, LLMOps, évaluation. En recherche active d'un poste en IA générative.">
</picture>

<p align="center">
  <a href="https://www.linkedin.com/in/salmane-el-maazouzi"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:salmaneelmaazouzi@gmail.com"><img src="https://img.shields.io/badge/salmaneelmaazouzi@gmail.com-1f2328?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
  <img src="https://img.shields.io/badge/Paris%20·%20mobile%20France%20entière-1f2328?style=flat-square&logo=googlemaps&logoColor=white" alt="Paris, mobilité France entière">
  <img src="https://img.shields.io/badge/Français%20·%20Anglais%20·%20Arabe-1f2328?style=flat-square&logo=googletranslate&logoColor=white" alt="Langues : français, anglais, arabe">
</p>

Ingénieur IA & Data diplômé de l'**INSA Rouen Normandie** (2026), spécialisé en science des données.
J'ai conçu des systèmes d'IA générative, puis travaillé sur **l'évaluation et le monitoring de LLM en production** (LLMOps).
Je construis des applications **qui citent leurs sources, se testent et se mesurent** : RAG, agents, LLM-as-a-Judge.

> [!TIP]
> **En recherche active : poste d'ingénieur IA générative / LLM Engineer** · Paris ou France entière · disponible immédiatement
>
> Contact : [salmaneelmaazouzi@gmail.com](mailto:salmaneelmaazouzi@gmail.com) · [LinkedIn](https://www.linkedin.com/in/salmane-el-maazouzi)

## Domaines

- **Évaluation et LLMOps** : LLM-as-a-Judge, références annotées par des humains, scores de risque, suivi des prompts, tokens et coûts.
- **RAG** : ingestion de sources, recherche vectorielle (pgvector, FAISS), réponses sourcées avec vérification des citations.
- **Agents** : graphes LangGraph, appel d'outils, agents qui communiquent via le protocole A2A, validation humaine avant les actions sensibles.
- **Deep learning et NLP** : PyTorch, GANs, architectures CNN, traitement de documents non structurés.

## Expériences

| Période | Poste |
|---|---|
| **Fév&nbsp;–&nbsp;Août&nbsp;2026** | **Ingénieur IA générative (stage), ALTEN**<br>Monitoring de la qualité des résumés générés par LLM pour un outil interne de recrutement en production (50 consultants par semaine) : référence d'évaluation de **7 220 annotations** (9 annotateurs, Label Studio), trois modes d'évaluation (règles, embeddings enrichis par ESCO, **LLM-as-a-Judge** sur Azure OpenAI), score de risque pour prioriser la revue humaine, **coût d'évaluation réduit de 13 %**. |
| **Mai&nbsp;–&nbsp;Août&nbsp;2025** | **Ingénieur IA (stage), Norsys**<br>Génération d'examens techniques de recrutement par **RAG** (MiniLM, FAISS) : QCM, questions ouvertes et exercices de code. API Flask, inférence via OpenRouter avec repli automatique sur un modèle local (Ollama). Préparation d'un examen ramenée **d'une journée à quelques minutes**. |
| **2025&nbsp;–&nbsp;2026** | **Développeur full stack & NLP, Centre Henri Becquerel** (projet INSA certifié)<br>Application de suivi des prescriptions pour les pharmaciens cliniciens, au sein d'une équipe Scrum de 8 personnes, avec des fonctionnalités NLP sur des documents médicaux non structurés. |

## Projets en cours

<table>
<tr>
<td width="50%" valign="top">

### [DroitClair](https://github.com/selmaazouzi/droitclair-rag-travail)

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

### [AI Shopping : agents d'achat personnalisé](https://github.com/achrafElFaiq/multi-agent-shopping-assistant)

**Trois agents LangGraph qui dialoguent via A2A** pour comprendre une demande, comparer les produits du catalogue Shopify et acheter après validation humaine.

`LangGraph` `A2A` `OpenRouter` `Pydantic` `PostgreSQL`

</td>
<td width="50%" valign="top">

**Ma contribution** (contributeur principal, projet à 3) :
- l'agent **préférences utilisateur** (outils, appel de fonction, persistance PostgreSQL)
- la **pause d'approbation humaine** avant paiement
- le graphe LangGraph initial, les schémas Pydantic et la CI

</td>
</tr>
</table>

## Projets précédents

| Projet | Ce que j'ai fait | Stack |
|---|---|---|
| **EdgeConnect** · reconstruction d'images par GAN | Entraînement d'un GAN en deux étapes (contours, puis texture), comparaison de méthodes d'extraction de contours, évaluation PSNR / SSIM / FID sur CelebA | PyTorch, CUDA, OpenCV, MLflow |
| **RegNet** · reproduction de *Designing Network Design Spaces* (FAIR) | Implémentation de RegNetX et entraînement sur ImageNet, sur un cluster de calcul | PyTorch, Slurm |
| **Robot autonome** | Suivi de ligne, détection d'obstacles, pilotage à la manette, sur Raspberry Pi | C, Raspberry Pi |

## Formation

| Période | Diplôme |
|---|---|
| **2023&nbsp;–&nbsp;2026** | **Diplôme d'ingénieur, INSA Rouen Normandie** · Informatique et Technologies de l'Information, spécialisation science des données |
| **2021&nbsp;–&nbsp;2023** | **Classes préparatoires MP** (mathématiques, physique), Lycée Ibn Timiya |

## Outils

| | |
|---|---|
| **IA générative** | ![LangChain](https://img.shields.io/badge/LangChain-1f2328?style=flat-square&logo=langchain&logoColor=white) ![LangGraph](https://img.shields.io/badge/LangGraph-1f2328?style=flat-square&logo=langgraph&logoColor=white) ![Azure OpenAI](https://img.shields.io/badge/Azure%20OpenAI-1f2328?style=flat-square&logo=openai&logoColor=white) ![OpenRouter](https://img.shields.io/badge/OpenRouter-1f2328?style=flat-square&logo=openrouter&logoColor=white) ![Ollama](https://img.shields.io/badge/Ollama-1f2328?style=flat-square&logo=ollama&logoColor=white) ![Hugging Face](https://img.shields.io/badge/Hugging%20Face-1f2328?style=flat-square&logo=huggingface&logoColor=FFD21E) ![Ragas](https://img.shields.io/badge/Ragas-1f2328?style=flat-square) ![Label Studio](https://img.shields.io/badge/Label%20Studio-1f2328?style=flat-square) |
| **ML & recherche** | ![PyTorch](https://img.shields.io/badge/PyTorch-1f2328?style=flat-square&logo=pytorch&logoColor=EE4C2C) ![scikit-learn](https://img.shields.io/badge/scikit--learn-1f2328?style=flat-square&logo=scikitlearn&logoColor=F7931E) ![sentence-transformers](https://img.shields.io/badge/Sentence%20Transformers-1f2328?style=flat-square) ![FAISS](https://img.shields.io/badge/FAISS-1f2328?style=flat-square&logo=meta&logoColor=white) ![pgvector](https://img.shields.io/badge/pgvector-1f2328?style=flat-square&logo=postgresql&logoColor=white) ![pandas](https://img.shields.io/badge/pandas-1f2328?style=flat-square&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-1f2328?style=flat-square&logo=numpy&logoColor=4DABCF) ![MLflow](https://img.shields.io/badge/MLflow-1f2328?style=flat-square&logo=mlflow&logoColor=0194E2) |
| **Back-end** | ![Python](https://img.shields.io/badge/Python-1f2328?style=flat-square&logo=python&logoColor=FFD43B) ![FastAPI](https://img.shields.io/badge/FastAPI-1f2328?style=flat-square&logo=fastapi&logoColor=009688) ![Django](https://img.shields.io/badge/Django-1f2328?style=flat-square&logo=django&logoColor=white) ![Flask](https://img.shields.io/badge/Flask-1f2328?style=flat-square&logo=flask&logoColor=white) ![Pydantic](https://img.shields.io/badge/Pydantic-1f2328?style=flat-square&logo=pydantic&logoColor=E92063) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-1f2328?style=flat-square&logo=postgresql&logoColor=4169E1) ![SQL](https://img.shields.io/badge/SQL-1f2328?style=flat-square) |
| **Cloud & DevOps** | ![Docker](https://img.shields.io/badge/Docker-1f2328?style=flat-square&logo=docker&logoColor=2496ED) ![Azure DevOps](https://img.shields.io/badge/Azure%20DevOps-1f2328?style=flat-square&logo=azuredevops&logoColor=0078D7) ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-1f2328?style=flat-square&logo=githubactions&logoColor=2088FF) ![GitLab CI](https://img.shields.io/badge/GitLab%20CI-1f2328?style=flat-square&logo=gitlab&logoColor=FC6D26) ![Grafana](https://img.shields.io/badge/Grafana-1f2328?style=flat-square&logo=grafana&logoColor=F46800) ![pytest](https://img.shields.io/badge/pytest-1f2328?style=flat-square&logo=pytest&logoColor=0A9EDC) ![uv](https://img.shields.io/badge/uv-1f2328?style=flat-square&logo=uv&logoColor=DE5FE9) |
| **Aussi** | ![Vue.js](https://img.shields.io/badge/Vue.js-1f2328?style=flat-square&logo=vuedotjs&logoColor=4FC08D) ![Java](https://img.shields.io/badge/Java-1f2328?style=flat-square&logo=openjdk&logoColor=white) ![C](https://img.shields.io/badge/C-1f2328?style=flat-square&logo=c&logoColor=A8B9CC) ![Agile Scrum](https://img.shields.io/badge/Agile%20Scrum-1f2328?style=flat-square) |
