<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg">
  <img src="assets/header-light.svg" width="100%" alt="Salmane El Maazouzi, Generative AI Engineer. Je construis des applications LLM et je garantis leur qualité, mesures à l'appui. LLMOps, RAG, agents IA. En recherche active d'un poste en IA générative.">
</picture>

<p align="center">
  <a href="https://www.linkedin.com/in/salmane-el-maazouzi"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:salmaneelmaazouzi@gmail.com"><img src="https://img.shields.io/badge/salmaneelmaazouzi@gmail.com-1f2328?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
  <img src="https://img.shields.io/badge/Paris%20·%20mobile%20France%20entière-1f2328?style=flat-square&logo=googlemaps&logoColor=white" alt="Paris, mobilité France entière">
  <img src="https://img.shields.io/badge/Français%20·%20Anglais%20·%20Arabe-1f2328?style=flat-square&logo=googletranslate&logoColor=white" alt="Langues : français, anglais, arabe">
</p>

Ingénieur IA & Data diplômé de l'**INSA Rouen Normandie** (2026), spécialisé en science des données.
J'ai conçu des systèmes d'IA générative, puis travaillé sur **l'évaluation et le monitoring de LLM en production** (LLMOps).

> **En recherche active : poste d'ingénieur IA générative / LLM Engineer** · Paris ou France entière · disponible immédiatement<br>
> Contact : [salmaneelmaazouzi@gmail.com](mailto:salmaneelmaazouzi@gmail.com) · [LinkedIn](https://www.linkedin.com/in/salmane-el-maazouzi)

## Domaines

- **Deep learning** : conception et entraînement de modèles PyTorch (GANs, CNN), reproduction d'articles de recherche, entraînement sur GPU et sur cluster de calcul (CUDA, Slurm).
- **NLP** : embeddings et recherche sémantique (Sentence Transformers, référentiel ESCO), traitement de documents non structurés, anonymisation de données textuelles.
- **RAG** : ingestion de sources officielles, recherche vectorielle (pgvector, FAISS), réponses sourcées avec vérification automatique des citations, choix entre modèles hébergés et locaux.
- **Agents IA** : systèmes multi-agents LangGraph, appel d'outils, communication entre agents via le protocole A2A, validation humaine avant les actions sensibles.
- **LLMOps et évaluation** : LLM-as-a-Judge, références annotées par des humains, scores de risque pour prioriser la revue, traçabilité des prompts, des tokens et des coûts.

## Expériences

| Année | Poste | Entreprise | Tâches |
|---|---|---|---|
| **2026** | Ingénieur IA générative (stage) | **ALTEN** | • Monitoring de la qualité des résumés générés par LLM, pour un outil de recrutement en production<br>• Référence d'évaluation : 7 220 annotations par 9 annotateurs (Label Studio)<br>• LLM-as-a-Judge sur Azure OpenAI, embeddings enrichis par ESCO, score de risque<br>• Coût d'évaluation réduit de 13 % |
| **2025** | Ingénieur IA (stage) | **Norsys** | • Pipeline RAG (MiniLM, FAISS) qui génère QCM, questions ouvertes et exercices de code<br>• API Flask, inférence via OpenRouter avec repli automatique sur Ollama<br>• Préparation d'un examen ramenée d'une journée à quelques minutes |
| **2025&nbsp;–&nbsp;2026** | Développeur full stack & NLP | **Centre Henri Becquerel** (projet INSA) | • Application de suivi des prescriptions pour les pharmaciens cliniciens<br>• Fonctionnalités NLP sur des documents médicaux non structurés<br>• Équipe Agile Scrum de 8 personnes |

## Projets en cours

<table>
<tr>
<td width="50%" valign="top">

### [DroitClair](https://github.com/selmaazouzi/droitclair-rag-travail)
**Le droit du travail, sources à l'appui.**
Un assistant qui répond aux questions des salariés uniquement à partir du Code du travail officiel, et cite chaque article utilisé.

`RAG` `pgvector` `FastAPI` `OpenRouter` `Ollama` `vérification des citations`

</td>
<td width="50%" valign="top">

### [AI Shopping](https://github.com/achrafElFaiq/multi-agent-shopping-assistant)
**Trois agents IA qui font vos achats, avec votre accord.**
Ils comprennent la demande, comparent les produits et n'achètent qu'après validation humaine.

`LangGraph` `A2A` `multi-agents` `PostgreSQL` `human-in-the-loop`

</td>
</tr>
</table>

## Projets précédents

- **[EdgeConnect](https://github.com/selmaazouzi/edge-connect) · reconstruction d'images par GAN**<br>
  Modèle en deux étapes qui prédit d'abord les contours manquants, puis la texture. Comparaison de méthodes d'extraction de contours, évaluation PSNR, SSIM et FID sur CelebA.<br>
  `PyTorch` `CUDA` `OpenCV` `MLflow`
- **[RegNet](https://github.com/selmaazouzi/Projet_DLA_RegNet) · reproduction d'un article de recherche de FAIR**<br>
  Implémentation de RegNetX (*Designing Network Design Spaces*) et entraînement sur ImageNet, sur un cluster de calcul.<br>
  `PyTorch` `Slurm` `HPC`
- **[Robot autonome](https://github.com/selmaazouzi/robot-elec) · Raspberry Pi programmé en C**<br>
  Suivi de ligne, détection d'obstacles par ultrasons, affichage LCD et pilotage à la manette.<br>
  `C` `Raspberry Pi` `I²C` `capteurs`

## Outils

| | |
|---|---|
| **IA générative** | ![LangChain](https://img.shields.io/badge/LangChain-1f2328?style=flat-square&logo=langchain&logoColor=white) ![LangGraph](https://img.shields.io/badge/LangGraph-1f2328?style=flat-square&logo=langgraph&logoColor=white) ![Azure OpenAI](https://img.shields.io/badge/Azure%20OpenAI-1f2328?style=flat-square&logo=openai&logoColor=white) ![OpenRouter](https://img.shields.io/badge/OpenRouter-1f2328?style=flat-square&logo=openrouter&logoColor=white) ![Ollama](https://img.shields.io/badge/Ollama-1f2328?style=flat-square&logo=ollama&logoColor=white) ![Hugging Face](https://img.shields.io/badge/Hugging%20Face-1f2328?style=flat-square&logo=huggingface&logoColor=FFD21E) ![Ragas](https://img.shields.io/badge/Ragas-1f2328?style=flat-square) ![Label Studio](https://img.shields.io/badge/Label%20Studio-1f2328?style=flat-square) |
| **ML & recherche** | ![PyTorch](https://img.shields.io/badge/PyTorch-1f2328?style=flat-square&logo=pytorch&logoColor=EE4C2C) ![scikit-learn](https://img.shields.io/badge/scikit--learn-1f2328?style=flat-square&logo=scikitlearn&logoColor=F7931E) ![sentence-transformers](https://img.shields.io/badge/Sentence%20Transformers-1f2328?style=flat-square) ![FAISS](https://img.shields.io/badge/FAISS-1f2328?style=flat-square&logo=meta&logoColor=white) ![pgvector](https://img.shields.io/badge/pgvector-1f2328?style=flat-square&logo=postgresql&logoColor=white) ![pandas](https://img.shields.io/badge/pandas-1f2328?style=flat-square&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-1f2328?style=flat-square&logo=numpy&logoColor=4DABCF) ![MLflow](https://img.shields.io/badge/MLflow-1f2328?style=flat-square&logo=mlflow&logoColor=0194E2) |
| **Back-end** | ![Python](https://img.shields.io/badge/Python-1f2328?style=flat-square&logo=python&logoColor=FFD43B) ![FastAPI](https://img.shields.io/badge/FastAPI-1f2328?style=flat-square&logo=fastapi&logoColor=009688) ![Django](https://img.shields.io/badge/Django-1f2328?style=flat-square&logo=django&logoColor=white) ![Flask](https://img.shields.io/badge/Flask-1f2328?style=flat-square&logo=flask&logoColor=white) ![Pydantic](https://img.shields.io/badge/Pydantic-1f2328?style=flat-square&logo=pydantic&logoColor=E92063) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-1f2328?style=flat-square&logo=postgresql&logoColor=4169E1) ![SQL](https://img.shields.io/badge/SQL-1f2328?style=flat-square) |
| **Cloud & DevOps** | ![Docker](https://img.shields.io/badge/Docker-1f2328?style=flat-square&logo=docker&logoColor=2496ED) ![Azure DevOps](https://img.shields.io/badge/Azure%20DevOps-1f2328?style=flat-square&logo=azuredevops&logoColor=0078D7) ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-1f2328?style=flat-square&logo=githubactions&logoColor=2088FF) ![GitLab CI](https://img.shields.io/badge/GitLab%20CI-1f2328?style=flat-square&logo=gitlab&logoColor=FC6D26) ![Grafana](https://img.shields.io/badge/Grafana-1f2328?style=flat-square&logo=grafana&logoColor=F46800) ![pytest](https://img.shields.io/badge/pytest-1f2328?style=flat-square&logo=pytest&logoColor=0A9EDC) ![uv](https://img.shields.io/badge/uv-1f2328?style=flat-square&logo=uv&logoColor=DE5FE9) |
| **Aussi** | ![Vue.js](https://img.shields.io/badge/Vue.js-1f2328?style=flat-square&logo=vuedotjs&logoColor=4FC08D) ![Java](https://img.shields.io/badge/Java-1f2328?style=flat-square&logo=openjdk&logoColor=white) ![C](https://img.shields.io/badge/C-1f2328?style=flat-square&logo=c&logoColor=A8B9CC) ![Agile Scrum](https://img.shields.io/badge/Agile%20Scrum-1f2328?style=flat-square) |
