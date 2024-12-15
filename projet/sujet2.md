# Sujet 2 : Application de gestion de données médicales

**Contexte de l’entreprise :**

Un hôpital public, dans le cadre d’un plan de transformation numérique, souhaite développer une application centralisée pour la gestion de ses dossiers médicaux électroniques (DME). Actuellement, l’hôpital utilise plusieurs systèmes isolés pour la gestion des patients, la prise de rendez-vous, et le suivi des résultats d’examens, ce qui provoque des inefficacités, des pertes de temps, et des risques d’erreurs médicales. L’objectif de cette application est de regrouper toutes ces fonctionnalités dans un système unique, sécurisé et conforme aux réglementations en vigueur.

L'application devra être utilisée à la fois par les professionnels de santé (médecins, infirmiers, techniciens) et les patients. Elle devra garantir un accès rapide aux informations critiques, tout en assurant un haut niveau de sécurité pour protéger les données personnelles et médicales.

**Attentes détaillées de l’entreprise :**

- Gestion centralisée des dossiers patients :
    - Une base de données unique pour stocker toutes les informations médicales des patients, incluant leurs antécédents, traitements, examens, et prescriptions.
    - Des fonctions pour visualiser, modifier, et partager ces dossiers entre les différents départements de l’hôpital.

- Prise de rendez-vous optimisée :
    - Un calendrier interactif pour la gestion des rendez-vous, incluant des notifications automatiques pour les patients et le personnel.
    - Intégration avec les horaires des médecins et des ressources de l’hôpital (salles d’examen, équipements).

- Résultats médicaux en ligne :
    - Un accès sécurisé pour que les patients puissent consulter leurs résultats d’examens (analyses sanguines, radiographies, etc.).
    - Des alertes automatiques pour informer les patients et les médecins de la disponibilité des résultats.

- Support des réglementations :
    - Conformité aux normes de confidentialité et de sécurité des données médicales, telles que le RGPD (Règlement Général sur la Protection des Données) et la HIPAA (Health Insurance Portability and Accountability Act).
    - Gestion des autorisations et des accès aux données, selon les rôles (ex. : les infirmiers n’ont pas accès aux prescriptions confidentielles des patients).

- Performance et disponibilité :
    - Une disponibilité de 99,9% pour garantir que l’application reste accessible 24/7.
    - Un temps de réponse maximal de 3 secondes pour toutes les actions.

- Extensibilité et interopérabilité :
    - Possibilité d’intégrer d’autres établissements hospitaliers dans le futur.
    - Interfaces pour communiquer avec d'autres systèmes externes, comme les laboratoires privés, les pharmacies, ou les assureurs.

- Sécurité renforcée :
    - Authentification forte des utilisateurs (par exemple, via biométrie ou double facteur).
    - Cryptage des données en transit et au repos.
    - Sauvegarde régulière des données pour prévenir les pertes en cas de panne.

- Suivi et reporting :
    - Tableaux de bord pour le personnel administratif, permettant de suivre les performances de l’hôpital (taux d’occupation, délai moyen des rendez-vous, etc.).
    - Outils d’analyse pour identifier les inefficacités et optimiser les processus.


**Contraintes de l’entreprise :**

- **Délais** : Le projet doit être déployé dans un délai de 18 mois, avec une première version fonctionnelle disponible dans les 12 mois.

- **Budget** : Budget serré en raison des restrictions budgétaires de l’hôpital, mais avec un financement possible pour des fonctionnalités essentielles.

- **Infrastructure existante** : L’hôpital dispose d’une infrastructure IT vieillissante qui devra être partiellement mise à jour ou intégrée avec le nouveau système. Une faible expertise des équipes internes en termes de technologies modernes, ce qui nécessitera une formation ou une externalisation partielle.

- **Conformité** : L'application doit respecter strictement les réglementations locales et internationales en matière de protection des données médicales.

- **Accès utilisateur** : Prévoir une interface utilisateur accessible à un public varié, allant des experts médicaux aux patients moins familiers avec la technologie.

- **Système existant** : Les différents systèmes actuels devront être intégrés ou remplacés progressivement sans interrompre les opérations courantes.

**Description du projet**

Chaque groupe doit, à partir de cette situation, produire un document d’architecture technique détaillé qui proposera une solution répondant aux besoins exprimés par l’entreprise. Ce document devra inclure une analyse approfondie des différentes couches d’architecture : fonctionnelle, applicative, infrastructure et opérationnelle. Il est attendu que chaque groupe décrive les processus métiers principaux, les interactions entre les composants, ainsi que les moyens techniques permettant d’assurer la scalabilité, la sécurité et la haute disponibilité de la plateforme.

Le document devra contenir des diagrammes explicatifs, notamment sur l’architecture applicative, l’architecture des données, l’intégration des systèmes tiers, et les éventuels processus DevOps pour automatiser les déploiements et garantir un fonctionnement continu. Les étudiants devront également justifier leur choix d’architecture (par exemple, monolithique, microservices, ou autre) en comparant les différentes options possibles et en expliquant en quoi leur solution est la mieux adaptée aux besoins exprimés.

Enfin, une analyse des coûts sera nécessaire, incluant les coûts de développement, de maintenance, et d’infrastructure. Les groupes devront démontrer que leur solution est viable à long terme, tout en respectant les contraintes de budget et de délai imposées par l’entreprise. Une conclusion synthétisera leurs recommandations et mettra en avant les atouts de l’architecture choisie pour répondre aux défis de l’entreprise.

**Rendu : Document d'architecture technique sous forme de presentation où il faut défendre le choix d'archietcture technique**
