---
layout: default
title : Modèle de chapitre pour 2023-24
date:   2023-11
---

---

   **Date de rendu finale : fin février**
   - Respecter la structure pour que les chapitres soient bien indépendants
   - Remarques :
        - La structure proposée est là pour vous aider, mais peut-être adaptée à votre projet
        - Les titres peuvent être modifiés pour être en adéquation avec votre étude. 
        - Utiliser des références pour justifier votre argumentaire, vos choix, etc.
        - Vous avez le choix d'utiliser le français ou l'anglais.

    Dans l'article de Blog [Debret 2020], l'auteure donne les éléments principaux de la démarche d'une manière simple et très facile à lire, dans la partie [Quelles sont les étapes d’une bonne démarche scientifique ?](https://www.scribbr.fr/article-scientifique/demarche-scientifique/#:~:text=La%20d%C3%A9marche%20scientifique%20permet%20d,de%20nouvelles%20hypoth%C3%A8ses%20%C3%A0%20tester.)

---

**_février 2024_**

## Authors

We are four students in M2 or in last year of Polytech' Nice-Sophia specialized in Software Architecture :

* thomas.farineau@etu.univ-cotedazur.fr
* leo.kitabdjian@etu.univ-cotedazur.fr
* ludovic.bailet@etu.univ-cotedazur.fr
* mohamed.mahjoub@etu.univ-cotedazur.fr

     :bulb: Les chapitres restant accessibles longtemps, si vous le souhaitez, vous pouvez utiliser ici une adresse pérenne pour être contacté ultérieurement.

## I. Research context /Project

La question générale porte sur la gestion des expériences dans MLflow. Cette question est particulièrement intéressante car elle touche au cœur de MLOps, explorant comment l'intégration et la gestion efficace des expériences de machine learning peuvent améliorer la qualité, la rapidité et la fiabilité du développement des modèles. En comprenant mieux cette gestion, nous pouvons déduire des pratiques optimales pour la conduite d'expériences en machine learning, essentielles pour toute avancée significative dans ce domaine. Cette compréhension est cruciale pour les organisations cherchant à adopter des pratiques de MLOps pour accélérer et fiabiliser leurs projets d'apprentissage automatique.


## II. Observations/General question

1. Commencez par formuler une question sur quelque chose que vous observez ou constatez ou encore une idée émergente. 
    
2. Préciser pourquoi cette question est intéressante de votre point de vue.

Attention pour répondre à cette question, vous devrez être capable d'émettre des hypothèses vérifiables, de quantifier vos réponses, ...

### Question générale

#### Comment MLFlow permet de gérer la traçabilité ainsi que la reproductibilité des expériences ?

### Lien avec les principes DevOps
- Versioning
- Logging
- CI (Hypothèse : Peu probable car trop coûteux)

### Intérêt de la question
- Emergence de MLOps
- La capacité à retracer et centraliser des expériences qui peuvent être nombreuses et issues de plusieurs collaborateurs
- La notion de reproductibilité, qui dans le contexte de machine learning paraît complexe donc intéressant de creuser comment MLFlow s'y prend

_Quels sont les principes nécessaires à la traçabilité des expériences de ML et s'inscrivent-ils dans une logique de reproductibilité des expériences ?_
**Quels sont les besoins liés à la traçabilité des expériences de ML ?**
_Quels sont les principes DevOps utilisés pour tracer les expériences de ML et y en a-t-il d'autres ?_

### Définitions de traçabilité et reproductibilité
- Traçabilité :
- Reproductibilité : 

     :bulb: Cette première étape nécessite beaucoup de réflexion pour définir la bonne question qui permet de diriger la suite de vos travaux.

## III. Information gathering

Préciser vos zones de recherches en fonction de votre projet, les informations dont vous disposez, ... 

Voici quelques pistes : 

1. les articles ou documents utiles à votre projet 
2. les outils que vous souhaitez utiliser
3. les jeux de données/codes que vous allez utiliser, pourquoi ceux-ci, ...

- Doc de MLFlow
- Repos Git utilisant MLFlow et disposant d'informations publiques

     :bulb: Cette étape est fortement liée à la suivante. Vous ne pouvez émettre d'hypothèses à vérifier que si vous avez les informations. inversement, vous cherchez à recueillir des informations en fonction de vos hypothèses. 
 
## IV. Hypothesis & Experiences

1. Il s'agit ici d'**énoncer sous forme d'hypothèses** ce que vous allez chercher à démontrer. Vous devez définir vos hypothèses de façon à pouvoir les _mesurer/vérifier facilement._ Bien sûr, votre hypothèse devrait être construite de manière à _vous aider à répondre à votre question initiale_. Explicitez ces différents points.
2. Vous **explicitez les expérimentations que vous allez mener** pour vérifier si vos hypothèses sont vraies ou fausses. Il y a forcément des choix, des limites, explicitez-les.

     :bulb: Structurez cette partie à votre convenance : 
     Par exemples : 
        Pour Hypothèse 1 => 
            Nous ferons les Expériences suivantes pour la démontrer
        Pour Hypothèse 2 => Expériences 
        
        ou Vous présentez l'ensemble des hypothèses puis vous expliquer comment les expériences prévues permettront de démontrer vos hypothèses.

### Informations stockées par MLFlow

- Versions de code
- Paramètres
- Environnement (Containers...)
- Dépendances (Mettre l'accent, nécessaire de les avoir tout le long de la chaîne)

Réponse grâce à la documentation de MLFlow

### Centralisation des informations stockées

- Serveur de base de données commun

Réponse grâce à la documentation de MLFlow

### Statistiques d'utilisation

- En fonction des résultats des informations stockées, les utilisateurs d'MLFlow utilisent ces fonctionnalités

Script analysant les repos pour chercher la présence d'enregistrement de ces données, afin de faire des stats

### Reproductibilité / Executabilité

Ces informations vont nous permettre de relancer une expérience (issue d'un repo git par exemple)

Nous allons cloner un repo git public disposant de toutes les informations et tenter de reproduire l'expérience

Malheureusement on ne peut pas pousser plus loin la reproductibilité car cela nécessiterait des tests statistiques un peu trop complexes et nocifs à notre planète (que les allemands s'occupent déjà à détruire avec leur charbon)

## V. Result Analysis and Conclusion

1. Présentation des résultats
2. Interprétation/Analyse des résultats en fonction de vos hypothèses
3. Construction d’une conclusion 

Les besoins sont-ils les mêmes que ceux que l'on avait envisagés ? 
Sont-ils pertinents (statistiques) ?
Prise de recul sur la seule utilisation de MLFlow (potentiellement d'autres non pris en compte par MLFlow)


     :bulb:  Vos résultats et donc votre analyse sont nécessairement limités. Préciser bien ces limites : par exemple, jeux de données insuffisants, analyse réduite à quelques critères, dépendance aux projets analysés, ...

## VI. Tools \(facultatif\)

Précisez votre utilisation des outils ou les développements \(e.g. scripts\) réalisés pour atteindre vos objectifs. Ce chapitre doit viser à \(1\) pouvoir reproduire vos expérimentations, \(2\) partager/expliquer à d'autres l'usage des outils.

![Figure 1: Logo UCA, exemple, vous pouvez l'enlever](assets/images/logo_uca.png){:height="12px"}


## VI. References

[Debret 2020] Debret, J. (2020) La démarche scientifique : tout ce que vous devez savoir ! Available at: https://www.scribbr.fr/article-scientifique/demarche-scientifique/ (Accessed: 18 November 2022).


