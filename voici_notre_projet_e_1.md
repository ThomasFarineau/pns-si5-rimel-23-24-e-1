\newpage
\vspace*{\fill}
\begin{center}

\Huge Voici notre projet \\[0.5em]
\Large Rétro-ingénierie, maintenance et évolution des logiciels\\[2em]
\LARGE \textbf{Groupe E - Sujet 1} \\[0.5em]
\Large \textbf{26/11/2023} \\[1em]  % Augmente la taille et ajoute un espace vertical après la date

\large \href{https://github.com/ThomasFarineau/}{Thomas FARINEAU} \\[0.5em]  % Augmente la taille et ajoute un espace vertical après le nom
\large \href{https://github.com/LeoKitabdjian}{Léo KITABADJIAN} \\[0.5em]
\large \href{https://github.com/Ludovic-BAILET}{Ludovic BAILET} \\[0.5em]
\large \href{https://github.com/Yaplupile}{Mohamed MAHJOUB} \\[0.5em]

\end{center}
\vspace*{\fill}
\newpage

## La question générale & pourquoi vous la trouvez intéressante

### 1. Signification et Impact de MLflow dans le Machine Learning
**Évolution de MLflow** : MLflow va au-delà d'un simple outil de Machine Learning (ML), évoluant vers une approche plus structurée et systématique pour la gestion des processus de ML.  
**Importance dans l'Expérimentation et l'Itération** : L'expérimentation et l'itération sont essentielles dans le domaine du ML, et la capacité de MLflow à tracer rigoureusement les expériences est vitale pour comprendre les variations de performance et les ajustements des modèles.  
**Fonctionnalités de MLflow** : MLflow offre un cadre pour le suivi des expériences, la gestion des modèles, et l'orchestration des workflows.  
**Application dans Divers Secteurs (quelques exemples)** :  
- Santé : Utilisé pour la prédiction de maladies et l'analyse d'images médicales.  
- Secteur Financier : Employé pour la détection de fraudes et la gestion des risques.  
- Commerce de Détail : Aide à personnaliser l'expérience client et à optimiser les chaînes d'approvisionnement.  

### 2. Rationalisation du Développement des Modèles
**Rationalisation du Développement de Modèles** : L'intégration de MLflow aide les organisations à rationaliser le développement de leurs modèles de Machine Learning (ML).  
**Amélioration de la Reproductibilité et Efficacité** : MLflow facilite une meilleure reproductibilité et efficacité dans le développement des modèles ML.  
**Favoriser la Collaboration entre Équipes** : MLflow améliore la collaboration entre les équipes travaillant sur des projets de ML.  
**Transformation des Pratiques de ML** : Avec MLflow, les pratiques de ML deviennent plus systématiques et alignées avec les principes de MLOps.  
**Gestion du Cycle de Vie des Modèles ML** : MLflow permet de gérer efficacement le cycle de vie complet des modèles ML, depuis leur conception jusqu'à leur déploiement et maintenance. (HORS SUJET???)  
**Qualité et Fiabilité des Solutions ML** : L'utilisation de MLflow assure une meilleure qualité et fiabilité des solutions de ML déployées.  

### 3. Gestion des Expériences avec MLflow
**Gestion des Cycles d'Expérimentation en ML** : MLflow aborde le défi de la gestion systématique et efficace des cycles d'expérimentation dans le Machine Learning (ML).  
**Solutions Offertes par MLflow** :  
- **Traçage et Documentation** : MLflow permet de tracer et de documenter les différentes étapes du développement de modèles ML.  
- **Suivi des Éléments Clés** : Il facilite le suivi des paramètres, des métriques, des résultats et des versions de modèles.  
- **Amélioration de la Reproductibilité et Traçabilité** : L'utilisation de MLflow dans les projets ML améliore la reproductibilité et la traçabilité.  
**Optimisation de la Collaboration** : MLflow aide à optimiser la collaboration entre les équipes de développement et de données.  

### 4. Ce qui nous intéresse
**Intégration du DevOps et du Machine Learning** : Le concept d'intégrer le DevOps dans le machine learning est intéressant, car il crée un lien entre deux domaines de l'ingénierie informatique habituellement considérés comme éloignés.  
**Suivi Structuré des Expériences** : L'outil MLflow propose un suivi des expériences bien structuré, ce qui est particulièrement pertinent étant donné que la programmation d'IA peut souvent manquer de structure.  
**Approche Méthodique avec MLflow** : MLflow facilite une approche plus méthodique dans le développement et la gestion des projets de machine learning.  
**Impact sur la Qualité et la Fiabilité** : MLflow est susceptible d'avoir un impact significatif sur la qualité et la fiabilité des projets de ML, en particulier dans des domaines où ces aspects sont essentiels, comme la santé et la finance.  

## Une première décomposition en sous-questions et les métriques/KPI/outils **envisagés** pour y répondre

Pour approfondir la gestion des expériences dans MLflow, nous pouvons décomposer la question principale en sous-questions spécifiques, tout en se concentrant sur des KPI (Key Performance Indicators) et outils spécifiques :

1. **Stockage des Informations** : Quelles sont les données d'expérience stockées dans MLflow, comment et où sont-elles stockées ?
   - KPI/Outils : Capacité de stockage (volume de données gérées), efficacité du stockage (temps d'accès aux données).
     - **Nature et Méthodes de Stockage** : Comment MLflow stocke-t-il les données et quelles sont les méthodes utilisées ?
     - **Capacité et Efficacité du Stockage** : Quelle quantité de données MLflow peut-il gérer et comment accède-t-il rapidement aux données ?
     - **Impact sur la Collaboration et la Reproductibilité** : Comment le stockage dans MLflow aide-t-il à la collaboration et à la reproductibilité des expériences ?

2. **Suivi des métriques et paramètres** : Comment MLflow suit-il les métriques et paramètres des expériences ?  
   - KPI/Outils : Précision du suivi (exactitude des données enregistrées), intégrité des données (cohérence et complétude des données).
     - **Comment MLflow fait le suivi** : Comment fonctionne le suivi des métriques et paramètres dans MLflow ?
     - **Vérifier la Précision** : Comment vérifier que les données enregistrées par MLflow sont précises ?
     - **Assurer l'Intégrité des Données** : Comment MLflow s'assure que les données sont complètes et cohérentes ?
     - **Métriques Clés à Suivre** : Quelles sont les métriques importantes à surveiller dans MLflow ?
     - **Ajouter des Métriques Personnalisées** : Est-il possible d'ajouter des métriques personnalisées dans MLflow ?
     - **Efficacité de la Mémorisation** : Quelles métriques MLflow enregistre-t-il bien et pourquoi sont-elles importantes ?

3. **Traçabilité des expériences** : MLFlow garantit-il une traçabilité des expériences ?  
KPI/Outils : Traçabilité des modifications (capacité à suivre les changements dans les expériences), transparence des processus (clarté dans la documentation des expériences), historique des versions (gestion et accessibilité de l'historique des expériences (pas des modèles).

4. **Reproductibilité des expériences** : La reproductibilité des expériences est-elle assurée par MLflow ?  
KPI/Outils : Taux de réussite de reproductibilité (pourcentage d'expériences reproduites avec succès), facilité de reconfiguration (temps et effort nécessaires pour répéter une expérience).

Ces sous-questions et KPI visent à évaluer en détail l'efficacité de MLflow dans la gestion des expériences de ML, en se concentrant sur la reproductibilité et la traçabilité, des éléments clés pour les pratiques de MLOps.

## La démarche prévue

1. **Exploration initiale de la documentation et des existants** : Nous débuterons par une immersion dans la documentation officielle de MLflow et des articles académiques pour construire une base théorique solide. En parallèle, nous explorerons les contributions de la communauté pour saisir les utilisations réelles et les défis rencontrés par les utilisateurs de MLflow (notamment grâce au topic GitHub disponible).

2. **Développement de cas d'utilisation** : Nous développerons des scénarios d'utilisation reflétant divers aspects de la gestion des expériences dans MLflow, en mettant l'accent sur le stockage des données, le suivi des métriques, et la reproductibilité.

3. **Tests pratiques et évaluation des outils** : Nous confronterons nos résultats aux standards de MLOps pour évaluer l'adéquation de MLflow avec les meilleures pratiques du secteur.

4. **Comparaison avec les standards de MLOps** : Confronter les résultats obtenus avec les standards de MLOps pour évaluer l'alignement de MLflow avec les meilleures pratiques de l'industrie.

5. **Synthèse et recommandations** : Enfin, nous rassemblerons nos découvertes pour obtenir une vue d'ensemble de la gestion des expériences dans MLflow et proposerons des recommandations pour son utilisation efficace dans divers contextes MLOps.

## Les sources dont au moins un article sur lesquels vous pensez vous baser pour répondre à la question.

- **Documentation officielle de MLflow** :  La documentation officielle est une ressource intéressante pour comprendre en profondeur les fonctionnalités et les mécanismes internes de MLflow. Elle offre des explications détaillées, des guides d'utilisation, et des exemples pratiques.
  - [Docs](https://mlflow.org/docs/latest/index.html)
  - [GitHub](https://github.com/mlflow/mlflow)
  
- **Articles académiques et de recherche** : Des articles provenant de Moodle et d'autres bases de données académiques fournissent une analyse théorique et des études de cas sur l'utilisation de MLflow, ses meilleures pratiques, et ses spécificités techniques.
  - Moodle:
	  - ieee_mlflow.pdf [(disponible ici)](https://people.eecs.berkeley.edu/~matei/papers/2018/ieee_mlflow.pdf)
	  - deem_mlflow.pdf [(disponible ici)](https://people.eecs.berkeley.edu/~matei/papers/2020/deem_mlflow.pdf)
	  
- **Article de blog** : Des articles de blog et publications en ligne offrent des perspectives pratiques, des retours d'expérience, et des analyses sur l'utilisation de MLflow dans différents contextes.
	- [Prise en main de MLflow, un outil pour tracer les résultats de vos expériences](https://blog.octo.com/prise-en-main-de-mlflow-un-outil-pour-tracer-les-resultats-de-vos-experiences)
	- [Gardez une trace de chacune de vos expériences avec MLFlow Tracking](https://www.kernix.com/article/gardez-une-trace-de-chacune-de-vos-experiences-avec-mlflow-tracking/)
	- [MLOps: How MLflow effortlessly tracks your experiments and helps you compare them?)](https://medium.com/hub-by-littlebigcode/mlops-how-mlflow-effortlessly-tracks-your-experiments-and-helps-you-compare-them-11da9be1fdb7)
	
- **Discussion instantanée** : Interagir avec la communauté MLflow peut fournir des insights précieux, des conseils pratiques, et des retours d'expérience directement des utilisateurs et développeurs de MLflow.
	- [Slack](https://go.mlflow.org/slack)
	
## Les sources (codes, données, ...) que vous pensez exploiter.
- [Topic MLFlow](https://github.com/topics/mlflow-projects)
- [GitHub MLFlow](https://github.com/mlflow/mlflow)
