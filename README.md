# AgentEDI

### Projet de Détection de Biais dans un Contexte RH

Création d'un système intégré destiné à simuler et détecter les biais dans les interviews de recrutement augmentées par IA. 
Voici les principaux composants et fonctionnalités abordés:

#### Contexte et Objectif
- Développement d'un système utilisant des Modèles de Langage à Grande Échelle (LLM) pour simuler des entrevues de recrutement et auditer ces interactions en quête de biais potentiels.
- Objectif d'assurer la conformité avec les politiques d'Équité, Diversité et Inclusion (EDI).

#### Composantes Techniques
1. **Architecture Technique**:
   - Utilisation de Python et des notebooks Google Colab pour développer et déployer le projet.
   - Utilisation des API de OpenAI pour simuler les rôles de recruteur et de candidat via des prompts optimisés (zero-shot prompting).

2. **LLM et Modèles de Classification**:
   - Génération de conversations synthétiques entre recruteur et candidat, incluant l'introduction contrôlée de biais via l'ingénierie de prompt.
   - Emploi de modèles LLM comme OpenAI pour la génération et Mistral.AI pour l'audit.
   - Intégration des modèles FlauBERT et SVM pour une analyse de biais fine et la classification basée sur l'apprentissage supervisé.

3. **Expérimentation et Validation**:
   - Création de datasets synthétiques pour entraîner et tester les modèles.
   - Analyse de performance des modèles via des métriques comme la précision et le score F1, utilisant des techniques avancées de traitement de texte telles que LIME pour expliquer les décisions des modèles.

#### Interface Utilisateur
- Développement d'une interface utilisateur via Gradio pour simuler des entrevues de recrutement et permettre aux utilisateurs de tester le système en temps réel.
- Présentation en direct permettant d'interagir avec le système, répondre aux prompts et recevoir des évaluations d'audits de biais.

#### Conclusion et Perspectives
- Le système démontre une capacité notable à identifier et expliquer les biais dans les conversations simulées.
- Suggestion de futurs développements pour étendre l'utilisation de ces techniques à d'autres aspects des RH comme l'analyse des CV et les évaluations de performances.

### Termes Techniques Clés Expliqués
- **LLM (Large Language Models)** : Modèles d'apprentissage profond conçus pour comprendre et générer du texte naturel.
- **Fine-tuning** : Processus d'ajustement d'un modèle pré-entraîné sur un dataset spécifique pour améliorer sa précision sur des tâches particulières.
- **Prompt Engineering** : Technique de formulation de questions ou d'instructions à un modèle de langue pour induire une réponse spécifique.
- **Zero-shot Learning** : Capacité d'un modèle à exécuter des tâches pour lesquelles il n'a pas été explicitement entraîné.
- **BERT et FlauBERT** : Modèles de traitement automatique du langage naturel basés sur l'architecture Transformer, optimisés pour comprendre le contexte d'un texte.
- **SVM (Support Vector Machine)** : Modèle d'apprentissage supervisé utilisé pour la classification et la régression.

Ce résumé offre une vue d'ensemble exhaustive des objectifs, de l'architecture, des méthodes utilisées, et des résultats obtenus dans le projet.

**NB** : ce projet s'inscrit dans le cadre d'un mémoire de maîtrise en IA décrit ci-dessous.

### Présentation du sujet de recherche
#### Titre
Pour une IA plus responsable dans le domaine des ressources humaines, détection et analyse des biais dans le processus de recrutement des candidats et dans l'évaluation de performances des employés.
#### Résumé
Dans le secteur des ressources humaines (RH), l'intégration de l'intelligence artificielle (IA) dans les processus de recrutement et d'évaluation de la performance devient de plus en plus courante. Cela soulève des interrogations sur la capacité à identifier les biais, qu'ils soient introduits de manière intentionnelle ou non, dans les systèmes automatiques impliquant des IA. L'importance de ces questions éthiques est reconnue et prise très au sérieux par la communauté scientifique en IA.

Le sujet de cette recherche s'aligne avec ce futur proche où des agents intelligents pourraient se substituer aux humains,  totalement ou en partie, dans la conduite des entretiens de recrutement ou d'évaluation de la performance.

Avec l'utilisation d'agents IA dans un contexte RH:
- Quelles sont les menaces pour l'équité ?
- Quelles sont les meilleures approches pour détecter les biais et prendre des mesures correctives ?
- Quelles sont les solutions à utiliser dans la mise en oeuvre des agents IA pour parer à ces menaces ?

Autant de questions auxquelles nous tenterons de répondre dans ce travail de recherche.

La structure du mémoire est la suivante :
![Structure mémoire EDI](https://raw.githubusercontent.com/delemarchand2020/AgentEDI/main/Structure_memoire_Denis_Lemarchand_Agent_EDI.png)
