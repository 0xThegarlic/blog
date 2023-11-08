#Bienvenue dans Security Operations Center


Tous les jours, nous sommes confrontés à des cybermenaces qui deviennent de plus en plus sophistiquées. Les organisations, les nations, les hôpitaux, les PME, voire même les collectivités territoriales, cherchent sans cesse à se protéger. Malgré leurs efforts et leur vigilance, ils sont de plus en plus confrontés à ces menaces cybernétiques. Dans une telle situation, il serait judicieux de se préparer à l'avance afin de ne pas être pris au dépourvu lors d'une attaque informatique. Ainsi, la mise en place d'un système de **[supervision](https://fr.wikipedia.org/wiki/Supervision_(informatique))**, de **[détection](https://fr.wikipedia.org/wiki/Syst%C3%A8me_de_d%C3%A9tection_d%27intrusion)**, de **[prévention](https://fr.wikipedia.org/wiki/Syst%C3%A8me_de_pr%C3%A9vention_d%27intrusion)** et de **[remédiation](https://www.lpb-conseil.com/quest-ce-que-la-remediation/)** au sein de nos organisations devient indispensable pour assurer la pérennité de l'ensemble de nos infrastructures.

Dans ce cours, nous parlerons du **Centre d'Opérations Cyber (SOC)** ainsi que de ses principaux objectifs.

## Qu'est-ce qu'un SOC ?

Un **[SOC (Security Operations Center)](https://fr.wikipedia.org/wiki/Security_operations_center)** est un centre opérationnel de sécurité. Il s'agit d'une entité ou d'une équipe spécialisée ayant la responsabilité d'assurer la supervision, la détection, l'analyse et la réponse aux incident de sécurité informatique au sein d'une organisation. En quelque sorte, la sécurité et la survie d'une organisation repose sur cette équipe. 

## Les principales mission d'un SOC

Les missions d'un SOC peuvent varier en fonction des besoins spécifiques de l'organisation qu'elle protège. Il faut cependant retenir que l'objectif ultime d'un SOC est de **protéger l'ensemble des actifs informatiques de l'organisation, de réduire les risques liés aux incidents de sécurité et de maintenir un environnement informatioque sûr et sécurisé**.

Néanmoins, le quotidien d'un SOC peut inclure les éléments suivants :

- **[Détection](https://www.juniper.net/fr/fr/research-topics/what-is-ids-ips.html)** : effectuer une surveillance permanente de l'ensemble des **[SI](https://fr.wikipedia.org/wiki/Syst%C3%A8me_d'information)** de l'organisation pour rapidement détecter toute forme d'activités suspectes telles que des intrusions ou des comportements malveillants au sein de l'environnement informatique de l'organisation. 

- **[Analyse des incident de sécurité](https://clusif.fr/wp-content/uploads/2015/09/clusif-2011-gestion-des-incidents.pdf)** : une fois l'incident détecter, le SOC procède à son analyse détaillée lui permettant de le classifier en fonction de sa gravité.
- **[Réaction](https://www.ziwit.com/fr/incident-response)** : si l'incident s'avère réel à la suite de son analyse approfondie, le SOC devrait répondre à l'incident en mettant en place des contres-mesures pour atténuer ou éradiquer l'incident en cours.

- **[Veille sur les menaces cyber](https://www.ixxo.fr/la-veille-cybermenaces/)** : le SOC devrait effectuer une veille constante sur les nouvelles menaces cyber, sur les différentes vulnérabilités ainsi que sur les techniques d'attaques émergentes comme les **[TTPs](https://tehtris.com/fr/blog/glossaire/ttps-tactiques-techniques-et-procedures)**.

-  **[Amélioration continue](https://openclassrooms.com/fr/courses/1734201-definissez-la-politique-de-securite-de-votre-entreprise/6206398-adoptez-une-demarche-damelioration-continue-de-la-pssi)** : le SOC doit faire une amélioration continue de la sécurité de l'ensemble des systèmes informatiques de l'organisation.

- **[Collaboration et partage d'informations](https://connect.ed-diamond.com/misc/misc-119/une-introduction-a-la-plateforme-libre-de-renseignements-misp)** : il est important d'effectuer des partages d'informations avec les autres équipes de sécurité, que ce soit en interne ou externe pour échanger des renseignements sur les potentielles menaces qu'ils peuvent faire face. Pour cela, ils pourrait utiliser des outils de renseignement comme **MISP** ou encore **OpenCTI**.


## Les différents types de SOC

Il existe différents types de SOC qui peuvent varier selon les exigences, la taille et la complexité de l'organisation. Nous pourons citer ici quelques types retrouvés au sein des organisations :

- **[SOC interne](https://www.pandasecurity.com/fr/mediacenter/securite/soc-role-cybersecurite/)** : comme son nom l'indique, ce type de SOC est installé au sein même de l'organisation. Toute l'équipe SOC est constituée des employés propre à l'organisation.
- **[SOC externe ou externalisé](https://www.pandasecurity.com/fr/mediacenter/securite/soc-role-cybersecurite/)** : est un SOC géré par une société de service / de prestation de sécurité spécialisée. Un contrat de sous-traitance lie les deux parties. La société de services a pour mission d'assurer la sécurité des actfis de l'organisation. Le coût d'une telle prestation reste faible par rapport à un SOC interne.
- **[SOC hybride](https://www.pandasecurity.com/fr/mediacenter/securite/soc-role-cybersecurite/)** : est la combinaison d'un **SOC interne et externe**. Dans ce modèle, certaines fonctions de surveillance et de réponse aux incidents sont gérées par l'équipe du SOC interne, tandis que d'autres sont externalisées à un prestataire de services de sécurité tiers.
- **[SOC virtuel](https://www.pandasecurity.com/fr/mediacenter/securite/soc-role-cybersecurite/)** : ce type de SOC n'a pas besoin d'installation physique propre. L'équipe de sécurité de ce modèle de SOC travaille généralement à distance.

## Les équipes SOC

Un SOC peut regrouper différents membres avec des rôles et responsabilités diverses :

- **[Responsable SOC](https://guardia.school/metiers/responsable-du-soc-security-operation-center.html)** : planifie et supervise les opérations quotidiennes du SOC afin d’évaluer le niveau de vulnérabilité et de détecter des activités suspectes ou malveillantes.
 Analsye réseau :

- **[Analyste SOC]()**

- **[Analyste de la menace]()**

- **[Analyste de réponse aux incidents de sécurité]()**

## Les outils utilsés dans un SOC