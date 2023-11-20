# Rendu 1
**Groupe E - Sujet 1**

Thomas FARINEAU<br>
Léo KITABADJIAN<br>
Ludovic BAILET<br>
Mohamed MAHJOUB<br>

## La question générale & pourquoi vous la trouvez intéressante

### 1. Signification et Impact de MLflow dans le Machine Learning
MLflow transcende la notion d'un simple outil pour devenir un mouvement vers une gestion plus structurée et systématique des processus en machine learning (ML). Cette évolution est essentielle dans un domaine où le ML est fondamentalement expérimental et itératif. La nécessité d'une traçabilité rigoureuse des expériences est cruciale pour comprendre les variations de performance et les ajustements des modèles. MLflow répond à ce besoin en offrant un cadre pour le suivi des expériences, la gestion des modèles, et l'orchestration des workflows, ce qui est indispensable pour gérer les complexités croissantes des projets d'apprentissage automatique.
### 2. Rationalisation du Développement des Modèles
L'intégration de MLflow dans les projets de ML permet aux organisations de rationaliser le développement de leurs modèles. En facilitant une meilleure reproductibilité, efficacité et collaboration entre les équipes, MLflow transforme les pratiques de ML, les rendant plus systématiques et alignées avec les principes de MLOps. Cela permet de gérer plus efficacement le cycle de vie complet des modèles de ML, depuis leur conception jusqu'à leur déploiement et maintenance, assurant ainsi une meilleure qualité et fiabilité des solutions de ML déployées.
### 3. Gestion des Expériences avec MLflow
L'étude de la gestion des expériences par MLflow est particulièrement captivante, car elle aborde un défi clé du ML : la gestion systématique et efficace des cycles d'expérimentation. MLflow offre des solutions pour tracer, documenter et comparer les différentes étapes du développement de modèles ML, y compris le suivi des paramètres, des métriques, des résultats et des versions de modèles. Comprendre comment MLflow facilite ces processus permet d'améliorer la reproductibilité et la traçabilité des projets ML et d'optimiser la collaboration entre les équipes de développement et de données.

## Une première décomposition en sous-questions et les métriques/KPI/outils **envisagés** pour y répondre


Pour approfondir la gestion des expériences dans MLflow, nous pouvons décomposer la question principale en sous-questions spécifiques, tout en se concentrant sur des KPI (Key Performance Indicators) et outils spécifiques :

1. **Stockage des Informations** : Quelles, comment et où les données d'expérience sont-elles stockées dans MLflow ?<br>
KPI/Outils : Capacité de stockage (volume de données gérées), efficacité du stockage (temps d'accès aux données).

2. **Suivi des métriques et paramètres** : Comment MLflow suit-il les métriques et paramètres des expériences ?<br>
KPI/Outils : Précision du suivi (exactitude des données enregistrées), intégrité des données (cohérence et complétude des données).

3. **Reproductibilité des expériences** : La reproductibilité des expériences est-elle assurée par MLflow ?<br>
KPI/Outils : Taux de réussite de reproductibilité (pourcentage d'expériences reproduites avec succès), facilité de reconfiguration (temps et effort nécessaires pour répéter une expérience).

4. **Traçabilité des expériences** : MLFlow garantit-il une traçabilité des expériences ?<br>
KPI/Outils : Traçabilité des modifications (capacité à suivre les changements dans les expériences), transparence des processus (clarté dans la documentation des expériences), historique des versions (gestion et accessibilité de l'historique des expériences et des modèles).

Ces sous-questions et KPI visent à évaluer en détail l'efficacité de MLflow dans la gestion des expériences de ML, en se concentrant sur la reproductibilité et la traçabilité, des éléments clés pour les pratiques de MLOps.
## La démarche prévue
La démarche prévue consiste en une série d'analyses et de tests pratiques. Premièrement, une exploration documentaire du fonctionnement interne de MLflow, en particulier sur sa gestion des expériences, sera effectuée. Cette analyse inclura l'examen de la documentation officielle de MLflow et des articles académiques pertinents. Ensuite, des tests pratiques seront menés pour évaluer comment MLflow gère le stockage des données, le suivi des métriques, et assure la reproductibilité des expériences. Ces tests impliquent la mise en œuvre de diverses expériences de machine learning en utilisant MLflow, suivies d'une évaluation de la performance des outils et des méthodes utilisées. L'objectif est de valider les affirmations théoriques par des preuves pratiques, assurant ainsi une compréhension approfondie et pragmatique de la gestion des expériences dans MLflow.

## Les sources dont au moins un article sur lesquels vous pensez vous baser pour répondre à la question. Les articles proposés se trouvent dans le sujet lui-même et sur moodle, d'autres sont possibles après consultation des encadreurs.

- **Documentation Officielle de MLflow** :  La documentation officielle est une ressource intéressante pour comprendre en profondeur les fonctionnalités et les mécanismes internes de MLflow. Elle offre des explications détaillées, des guides d'utilisation, et des exemples pratiques.
  - [Docs](https://mlflow.org/docs/latest/index.html)
  - [GitHub](https://github.com/mlflow/mlflow)

- **Articles académiques et de recherche** : Des articles provenant de Moodle et d'autres bases de données académiques fournissent une analyse théorique et des études de cas sur l'utilisation de MLflow, ses meilleures pratiques, et ses spécificités techniques.
  - Moodle:
	  - ieee_mlflow.pdf [Disponible Ici](https://people.eecs.berkeley.edu/~matei/papers/2018/ieee_mlflow.pdf)
	  - deem_mlflow.pdf [Disponible ici](https://people.eecs.berkeley.edu/~matei/papers/2020/deem_mlflow.pdf)

- **Article de blog** : Des articles de blog et publications en ligne offrent des perspectives pratiques, des retours d'expérience, et des analyses sur l'utilisation de MLflow dans différents contextes.
	- [Prise en main de MLflow, un outil pour tracer les résultats de vos expériences](https://blog.octo.com/prise-en-main-de-mlflow-un-outil-pour-tracer-les-resultats-de-vos-experiences)
	- [Gardez une trace de chacune de vos expériences avec MLFlow Tracking](https://www.kernix.com/article/gardez-une-trace-de-chacune-de-vos-experiences-avec-mlflow-tracking/)
	- [MLOps: How MLflow effortlessly tracks your experiments and helps you compare them?)](https://medium.com/hub-by-littlebigcode/mlops-how-mlflow-effortlessly-tracks-your-experiments-and-helps-you-compare-them-11da9be1fdb7)

- **Discussion instantanée** : Interagir avec la communauté MLflow peut fournir des insights précieux, des conseils pratiques, et des retours d'expérience directement des utilisateurs et développeurs de MLflow.
	- [Slack](https://go.mlflow.org/slack)

## Les sources (codes, données, ...) que vous pensez exploiter.
- [Topic MLFlow](https://github.com/topics/mlflow-projects)
