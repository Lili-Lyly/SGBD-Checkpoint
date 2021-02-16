# SGBD-Checkpoint

Un SGBD permet de décrire les données des bases, de les interroger, de les mettre à jour, de transformer des représentations de données, d'assurer les contrôles d'intégrité, de concurrence et de sécurité.

1- MySQL est un système de gestion de base de données relationnelles (SGBDR) basé sur SQL (Structured Query Language).

MySQL fonctionne sur pratiquement toutes les plates-formes, y compris Linux, Unix et Windows. Il est entièrement multi-thread avec un noyau de threads, et fournit des API (Application Programming Interface) pour de nombreux langages de programmation, notamment C, C + +, Eiffel, Java, Perl, PHP, Python, et Tcl.

MySQL est utilisé dans une large gamme d'applications, Le commerce électronique, les bases de données Web...

Selon MySQL AB, avec plus de dix millions de serveurs MySQL installés dans le monde entier, MySQL est devenu le leader mondial du marché des Bases de Données. MySQL compte des clients prestigieux comme Google, la NASA ou Suzuki...

MySQL bénéficie d'un large public, car:

•	Il est facile à comprendre:
Sa syntaxe simple en fait un langage facile à comprendre pour les programmeurs et des débutants.

•	Le Langage est fonctionnel:
MySQL fonctionne sur de nombreuses plates-formes différentes.

•	Dispose d'une vaste bibliothèque de fonctions et d'API:
API pour C, C + +, Eiffel, Java, Perl, PHP, Python, Ruby et Tcl sont disponibles. Les fonctions SQL sont mises en place en utilisant une bibliothèque de classes optimisées.

•	Multi Thread:
Complètement multi-thread utilisant un noyau de threads.

•	Haute capacité de storage:
Pour vous donner une idée: De grosses entreprises actuelles utilisent le serveur MySQL avec plus de 100 000 tables et 1 000 000 000 d'enregistrements.

2- postgreSQL (prononcez postgrècecuelle ou postgrèce) est un SGBDR (système de gestion de base de données relationnelles) fonctionnant sur des systèmes de type UNIX (par exemple Linux, FreeBSD, AIX, HP-UX, IRIX, Solaris, ...).

L'une des principales qualités de PostgreSQL est d'être un logiciel libre, c'est-à-dire gratuit et dont les sources sont disponibles.

3- Microsoft SQL Server est un système de gestion de base de données (SGBD) en langage SQL incorporant entre autres un SGBDR relationnel développé et commercialisé par la société Microsoft. Il fonctionne sous les OS Windows et Linux (depuis mars 2016), mais il est possible de le lancer sur Mac OS via Docker, car il en existe une version en téléchargement sur le site de Microsoft.

///comparaison :

-------Avantages de MySQL-------

Installation gratuite. L’édition communautaire de MySQL est téléchargeable gratuitement. Avec un ensemble d'outils de base pour une utilisation individuelle, l' édition communautaire de MySQL est une bonne option pour commencer. Bien sûr, il existe d’autres options prépayées à des fins d’ entreprise ou de cluster , avec des fonctionnalités plus riches. Néanmoins, si votre entreprise est trop petite pour payer l’un d’entre eux, le modèle de téléchargement gratuit est le plus approprié pour un début.

Syntaxe simple et complexité faible. La structure et le style de MySQL sont très clairs. Les développeurs considèrent même MySQL comme une base de données avec un langage humain. MySQL est souvent utilisé en tandem avec le langage de programmation PHP, l’un des plus répandus dans le monde. Avec sa courbe d'apprentissage douce, vous n'avez pas besoin de faire appel à un développeur qualifié pour gérer votre base de données. MySQL est facile à utiliser. Par exemple, la plupart des tâches peuvent être exécutées directement dans la ligne de commande, ce qui réduit les étapes de développement.

Compatible avec le cloud. Orienté métier par nature et initialement développé pour le Web, MySQL est pris en charge par les fournisseurs de cloud les plus répandus. Il est disponible sur des plateformes de premier plan telles qu'Amazon, Microsoft Azure et d'autres. Cela rend MySQL encore plus attrayant et laisse aux entreprises qui l'utilisent une marge de croissance élevée.

-----Inconvénients de MySQL-----

Défis d'évolution. MySQL n'a pas été construit pour les évolutions rapides et infinies, c’est inhérente à son code. En théorie, vous pouvez faire évoluer MySQL, mais cela nécessitera davantage d’ingénierie par rapport aux bases de données NoSQL. Ainsi, si vous prévoyez un jour que votre base de données augmentera considérablement, gardez cette limitation à l'esprit ou choisissez une autre option de SGBD. Concrètement le nombre d’entrées est limité en nombre, Vous comprendrez que des applications telles que twitter ou facebook ne peuvent pas raisonablement les utiliser avec les million d’inputs qu’ils reçoivent tous les jours

Open Source partielle. Bien que MySQL soit en partie open-source, elle est principalement sous licence Oracle. Cela limite la communauté MySQL en termes d'amélioration du SGBD. Pourquoi s'en préoccuper? Parce que lorsque vous avez un support open-source, vous vous attendez à de nombreuses implémentations spécifiques à un problème et à une assistance communautaire. Ce n'est pas le cas lorsque le logiciel appartient aux propriétaires de l'entreprise et que vous devez payer pour une assistance...

Conformité limitée aux normes SQL. Le langage de requête structuré a des normes spécifiques. MySQL ne les suit pas complètement, c’est-à-dire que MySQL ne prend pas en charge certaines fonctionnalités SQL standard. D'autre part, MySQL possède des extensions et des fonctionnalités distinctes qui ne correspondent pas aux normes du langage de requête structuré. Ce n'est pas un gros problème pour les petites applications Web. Les problèmes peuvent apparaître lorsque vous devez passer à d'autres bases de données, ce qui est susceptible de se produire lorsque votre entreprise commence à se développer.

-----------Avantages de Postgre---------

Évolutif. L’évolutivité verticale est une caractéristique de PostgreSQL, contrairement au SGBD MySQL. Étant donné que presque toutes les solutions logicielles personnalisées ont tendance à croître, ce qui entraîne une extension de la base de données, cette option prend très bien en charge la croissance et le développement des entreprises.

Prise en charge des types de données personnalisés. PostgreSQL supporte de manière native un grand nombre de types de données par défaut, tels que JSON, XML, H-Store, etc. PostgreSQL en tire parti, car elle est l’une des rares bases de données relationnelles offrant une prise en charge solide des fonctionnalités NoSQL. De plus, il permet aux utilisateurs de définir leurs propres types de données. Étant donné que votre modèle commercial de logiciel peut nécessiter différents types de bases de données tout au long de son existence pour améliorer les performances ou l'exhaustivité des applications, cette option apporte une flexibilité accrue à la table de données.

Outils tiers faciles à intégrer. Le système de gestion de base de données PostgreSQL prend en charge des outils supplémentaires , à la fois gratuits et commerciaux.Par exemple, ClusterControl fournit une assistance impressionnante pour la gestion, la surveillance et la mise à l'échelle des bases de données open source SQL et NoSQL. Pour rendre la comparaison et la synchronisation des données plus efficaces, envisagez d'utiliser “DB Data Difftective”. Si vous envisagez de transformer vos données en charges de travail lourdes, la sauvegarde et la restauration du système avec pgBackRest seront une option intéressante.

Open-source et communautaire. Postgres est complètement open-source et soutenu par sa communauté, ce qui le renforce en tant qu'écosystème complet. En outre, les développeurs peuvent toujours compter sur une assistance communautaire rapide et gratuite.

-------Inconvénients de Postgre--------

Documentation incohérente. Bien que PostgreSQL compte une grande communauté et offre un support solide à ses utilisateurs, la documentation manque toujours de cohérence et d’exhaustivité. La communauté PostgreSQL étant hétérogène, la documentation ne suit pas les mêmes normes pour toutes les fonctionnalités de Postgre.

Manque d'instruments de reporting et d'audit. Une lacune importante de PostgreSQL est l'absence d'outils de révision permettant de visualiser l'état actuel d'une base de données. Vous devez vérifier en permanence si quelque chose ne va pas. Il y a toujours un risque que les ingénieurs de base de données remarquent un échec trop tard.

Cas d'utilisation

Grâce à des requêtes complexes et à un large choix d'interfaces personnalisées réalisées avec des fonctions prédéfinies, PostgreSQL™ est parfaitement adapté à l'analyse de données et à l'entreposage. Si vous construisez un outil d'automatisation de base de données, PostgreSQL ™ convient parfaitement en raison de ses puissantes capacités d'analyse, de sa conformité ACID et de son puissant moteur SQL. Tout en un, il accélère considérablement le traitement de grandes quantités de données. Ce SGBD est populaire auprès des institutions financières et des systèmes de télécommunication.

----------Avantages de SQL SERVER----------

Variété de versions. Microsoft SQL Server offre un large choix d'options avec diverses fonctionnalités. Par exemple, l'édition Express avec une base de données gratuite offre des outils d'entrée de gamme, parfaitement adaptés à l'apprentissage et à la création d'applications basées sur les données pour les ordinateurs de bureau ou les petits serveurs. L'option Développeurs permet de créer et de tester des applications comprenant certaines fonctionnalités de l'entreprise, mais sans licence de serveur de production. Pour les projets plus importants, il existe également des éditions Web, Standard et Enterprise, avec une étendue variable de capacités administratives et de niveaux de service.

Solution de données d'entreprise intégrale. MSSQL, cible principalement les solutions commerciales, offre de nombreuses fonctionnalités à forte valeur ajoutée pour l'entreprise. La sélection facultative de composants permet de créer des solutions ETL, de constituer une base de connaissances et de mettre en œuvre la suppression des données. En outre, il fournit des outils pour l’administration générale des données, le traitement analytique et l’exploration de données, ainsi que des options pour la génération de rapports.

Documentation riche et assistance communautaire. Microsoft SQL Server visant une maintenance de la base de données, la documentation en ligne est complète. Les directives ainsi structurées, les nombreux livres blancs et les démos donnent une image complète du système de données MSSQL. En outre, Microsoft Premier fournit un accès au support dédié de la communauté Microsoft, ce qui est un avantage lorsqu'un ingénieur de base de données a besoin d'assistance.

Support de base de données en Cloud. Faisant partie de l'écosystème Microsoft, MSSQL peut être intégré à Microsoft Cloud, à la base de données Azure SQL ou à SQL Server sur les machines virtuelles Azure. Les solutions permettent de déplacer l’administration de base de données vers le cloud si la base de données de votre logiciel d’entreprise devient vraiment trop lourde et difficile à administrer.

-------------Inconvénients de SQL SERVER----------

Coût élevé. Utilisé par les entreprises, MSSQL Server reste l'une des solutions les plus chères. L'édition Enterprise coûte actuellement plus de 14 000 USD par “cœur”.

Conditions de licence peu claires et flottantes. Un autre problème concerne le processus de licence en constante évolution. La stratégie de tarification elle-même est difficile à comprendre et les éléments inclus dans une édition particulière peuvent évoluer.

Processus de réglage compliqué. Pour les débutants qui doivent exploiter des ensembles de données volumineux, l’optimisation des requêtes et le réglage des performances peuvent poser problème. Comme le processus n’est pas si évident, il peut créer rapidement des goulots d’étranglement importants.


