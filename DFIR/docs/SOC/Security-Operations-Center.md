#Bienvenue dans Security Operations Center


Tous les jours, nous faisons face aux menaces cyber qui deviennent de plus en plus sophistiquées. Les organisations, les nations, les hôpitaux, voire même les collectivités territoriales, cherchent sans cesse à se protéger de ces menaces. Mais malgré leurs efforts et leur vigilance, ils sont de plus en plus confrontés à ces menaces cybernétiques. Dans une telle situation, il serait judicieux de se préparer à l'avance afin de ne pas être pris au dépourvu en cas d'incident de sécurité ou d'une attaque informatique. Ainsi, la mise en place d'un système de **[supervision](https://fr.wikipedia.org/wiki/Supervision_(informatique))**, de **[détection](https://fr.wikipedia.org/wiki/Syst%C3%A8me_de_d%C3%A9tection_d%27intrusion)**, de **[prévention](https://fr.wikipedia.org/wiki/Syst%C3%A8me_de_pr%C3%A9vention_d%27intrusion)** et de **[remédiation](https://www.lpb-conseil.com/quest-ce-que-la-remediation/)** au sein d'un organisation devient indispensable pour assurer la pérennité de l'ensemble de nos infrastructures. 

C'est dans cette optique que nous parlerons du **Centre d'Opérations Cyber (SOC)** ainsi que de ses principaux objectifs, qui est la première ligne défensive d'une organisation. 

## I- Qu'est-ce qu'un SOC ?

Un **[SOC (Security Operations Center)](https://fr.wikipedia.org/wiki/Security_operations_center)** est un centre opérationnel de sécurité. Il s'agit d'une entité ou d'une équipe spécialisée ayant la responsabilité d'assurer la **supervision**, la **détection**, l'**analyse** et la **réponse aux incident de sécurité informatique** au sein d'une organisation. En quelque sorte, la sécurité et la survie d'une organisation repose sur l'équipe SOC. 

## II- Les principales mission d'un SOC

Les missions d'un SOC peuvent varier en fonction des besoins spécifiques de l'organisation qu'elle protège. Il faut cependant retenir que l'objectif ultime d'un SOC en général, c'est de **protéger** l'ensemble des actifs  informatiques de l'organisation, de **réduire** les risques liés aux incidents de sécurité et de **maintenir** un environnement informatioque sûr et sécurisé.

Quelque soit la taille ou la structure d'un SOC, son quotidien peut inclure les éléments suivants :

- **[la détection](https://www.juniper.net/fr/fr/research-topics/what-is-ids-ips.html)** : le SOC se doit d'effectuer une surveillance permanente de l'ensemble du **[système d'information](https://fr.wikipedia.org/wiki/Syst%C3%A8me_d'information)** de l'organisation, pour rapidement détecter toute forme d'activités suspectes telles que des intrusions ou des comportements anornaux ou malveillants au sein de l'environnement informatique de son organisation. 

- **[l'analyse des alertes de sécurité](https://clusif.fr/wp-content/uploads/2015/09/clusif-2011-gestion-des-incidents.pdf)** : une fois qu'une alerte de sécurité est détectée, l'équipe SOC doit procèder à son analyse détaillée, ce qui lui permettra de la classifier en fonction de sa gravité.

- **[la réaction](https://www.ziwit.com/fr/incident-response)** : si l'alerte s'avère réelle et conduit à un incident de sécurité, l'équipe SOC devra rapidement répondre à l'incident en se réferant aux différentes fiches reflexes et en mettant en place des contres-mesures pour atténuer ou éradiquer l'incident en cours.

- **[la veille sur les menaces cyber](https://www.ixxo.fr/la-veille-cybermenaces/)** : l'équipe SOC devra également effectuer une veille continue des nouvelles menaces cyber, sur les différentes vulnérabilités ainsi que sur les techniques d'attaques émergentes comme les **[TTPs(Tactiques, Techniques et Procédures)](https://tehtris.com/fr/blog/glossaire/ttps-tactiques-techniques-et-procedures)**.

-  **[l'amélioration continue](https://openclassrooms.com/fr/courses/1734201-definissez-la-politique-de-securite-de-votre-entreprise/6206398-adoptez-une-demarche-damelioration-continue-de-la-pssi)** : le SOC se doit faire une amélioration continue de la sécurité de l'ensemble des systèmes informatiques de son organisation.

- **[la collaboration et le partage d'informations](https://connect.ed-diamond.com/misc/misc-119/une-introduction-a-la-plateforme-libre-de-renseignements-misp)** : il est important pour les équipes SOC d'effectuer des partages d'informations avec les autres équipes de sécurité, que ce soit en interne ou externe pour échanger des renseignements sur les menaces auxquelles ils pourraient potentiellement faire face. Pour cela, ils pourraient utiliser des outils de renseignement comme **MISP**, **OpenCTI** ou d'autres moyens ou encore des partages d'informations inter **CERT**.


## III- Les différents types de SOC

Il existe différents types de SOC qui peuvent varier selon les exigences, la taille, les moyens et la complexité de l'organisation. Dans la vie de tous les jours, nous pouvons rencontrer ces types de SOC : 

- **[SOC interne](https://www.pandasecurity.com/fr/mediacenter/securite/soc-role-cybersecurite/)** : comme son nom l'indique, ce type de SOC est installé au sein même de l'organisation. Toute l'équipe SOC est constituée des employés propre à l'organisation.
- **[SOC externe ou externalisé](https://www.pandasecurity.com/fr/mediacenter/securite/soc-role-cybersecurite/)** : est un SOC géré par une société de service ou de prestation de sécurité spécialisée. Un contrat de sous-traitance lie les deux parties. Ainsi, la société de services aura pour mission d'assurer la sécurité de l'ensemble des actfis de l'organisation (selon le périmètre prédéfini). Le coût d'une telle prestation reste faible par rapport coût d'un SOC interne.
- **[SOC hybride](https://www.pandasecurity.com/fr/mediacenter/securite/soc-role-cybersecurite/)** : est la combinaison d'un **SOC interne et externe**. Dans ce modèle, certaines fonctions de surveillance et de réponse aux incidents sont gérées par l'équipe du SOC interne, tandis que d'autres sont externalisées à un prestataire de services de sécurité tiers.
- **[SOC virtuel](https://www.pandasecurity.com/fr/mediacenter/securite/soc-role-cybersecurite/)** : ce type de SOC n'a pas besoin d'installation physique propre. L'équipe de sécurité de ce modèle de SOC travaille généralement à distance.

## IV- Les équipes SOC

Un SOC peut regrouper différents membres avec des rôles et responsabilités diverses :

- **[le responsable SOC](https://guardia.school/metiers/responsable-du-soc-security-operation-center.html)** : planifie et supervise les opérations quotidiennes du SOC afin d’évaluer le niveau de vulnérabilité et de détecter des activités suspectes ou malveillantes.
 Analsye réseau :

- **[les analystes SOC]()**

- **[les analystes de la menace]()**

- **[les analyste de réponse aux incidents de sécurité]()**

## V- Les outils utilsés dans un SOC

Les équipes SOC utilisent une multitude d'outils dans l'exercice de leur fonction, ce qui leur permet d'assurer au mieux la sécurité de l'ensemble du parc informatique de leurs organisations. En fonction des moyens, de la maturité et des exigeances de l'organisation, les équipes SOC peuvent se doter des outils très chèr et même en développer certains (en interne). 

Néanmoins, quelque que soit les moyens financiers ou la taille d'une organisation, tous les SOC doivent en premier lieu se doter d'un **[SIEM(Security information and event management)](https://fr.wikipedia.org/wiki/Security_information_and_event_management)**. Cet outil reste **indispensable** à tout centre opérationnel de sécurité (SOC).

### a- Qu'est-ce qu'un SIEM


**Coming soon.........**

### b- Qu'est-ce qu'un EDR

**Coming soon.........**

### c- 

**Coming soon.........**