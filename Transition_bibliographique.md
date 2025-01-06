# La transition bibliographique, « des catalogues vers le web de données » 
## Introduction - Dans l'historique des catalogues : des _Principes de Paris_ à la transition bibliographique, une adaptabilité perpétuelle

« L’ "ouvrage bibliographique" a constamment été remis sur le métier » écrit en 2017 le conservateur général des bibliothèques Grégory Miura[^1], précisant que  « le catalogage reste une pierre angulaire de notre métier non par la permanence de sa structure, acquise de fraîche date, mais bien par **la vitalité d'un chantier intrinsèquement actif**. » En effet, conséquence de l'évolution des supports et canaux de la connaissance, l’histoire des catalogues de bibliothèque, à la fois outils de gestion et espaces d’interaction avec les usagers, est celle d’adaptations constantes pour rendre visibles et intelligemment accessibles les informations dont les bibliothèques disposent, physiquement ou numériquement. Car les catalogues actuels sont déjà la conséquence d’une première transition bibliographique visant à une **normalisation internationale du catalogage**, démarrée avec l’adoption des [**_Principes de Paris_**](https://www.ifla.org/files/assets/cataloguing/IMEICC/IMEICC1/statement_principles_paris_1961-fr.pdf) en octobre 1961, et concrétisée sur le territoire français par une série de normes (Z44) entre 1988 et 2007. D'après ces principes, le catalogue doit permettre (1) de savoir si la bibliothèque dispose d'un livre particulier, et (2) d'identifier les œuvres d'un auteur donné disponibles dans le fonds, en précisant l'édition. Pour cela, chaque livre est associé à une ou plusieurs notices descriptives, recensant toutes les indications jugées indispensables à l'identification d'un ouvrage. Mais ces standards apparaissent vite dépassés dès le tournant du XXIe siècle, alors que la multiplication des « nouveaux supports » (documents sonores, vidéocassettes…) et l’explosion du fait numérique reposent la question des formats bibliographiques et de leurs objectifs. En 1990, à Stockholm, le _Séminaire sur les notices bibliographiques_ commandé par la Fédération internationale des associations et institutions de bibliothèques ([IFLA](https://www.ifla.org/about/)) débouche ainsi sur la conceptualisation d'un modèle entité-association d'organisation des données bibliographiques, les règles **FRBR** (_Functional Requirements of Bibliographic Records_), achevées en 1997 et publiées l'année suivante. Depuis 2015, la France a ainsi engagé un programme de « Transition bibliographique », volet national d’un mouvement mondial initié au cours des années 90. Polysémique, le terme de **transition bibliographique** renvoie ainsi tout à la fois à un projet et à son application technique. Au sens restreint, en France, il s’agit du programme national, lancé depuis 2014, de traduction et d’adaptation de **RDA** pour adapter les normes de documentation à l’évolution d’Internet et notamment permettre la **FRBRisation des catalogues**

# I. Percer les secrets de la transition bibliographique
 
## I.1. Des objectifs parfois ambigus : s’adapter à l’évolution numérique pour mieux servir l’usager, ou répondre à l'appel du big data ? 

Pourquoi la transition bibliographique ? 

>  « La nature de l'information, jusque-là conceptualisée à partir du modèle de l'imprimé, se transforme sous l'influence de la production numérique, à la fois fluide, diversifiée dans ses sources, ses contenus, ses formats, massive et hypertextualisée. (…) L'enjeu de la TB [Transition bibliographique] étant au final de concevoir et d'appliquer les principes, les méthodes et les outils qui permettront d'**injecter dans l'univers des données l'ensemble des artefacts documentaires collectés et décrits à ce jour**, quelle que soit leur forme ou leur origine », David Aymonin, directeur de l'Abes (Arabesques, 2017, p. 03)

Comme le synthétise David Aymonin, la transition bibliographique poursuit deux objectifs complémentaires : une logique de service d'abord, restructurer la donnée bibliographique pour la rendre plus efficiente aux regards des demandes des utilisateurs. Par suite, il faut que ces données bibliographiques soient visibles sur le web. 
Vers la constitution d'un web sémantique, rendre visible les données bibliographiques  - approfondir les possibilités de recherche et de lien entre les ressources au sein des catalogues, et favoriser l'évolution des catalogues nationaux vers le web des données liées, améliorer l'expérience usager, utiliser et produire des données et métadonnées interopérables 
Avec la constitution et l’horizon d’un web de données ou web sémantique, l’enjeu est également de ne pas faire voir uniquement le reflet de la collection physique de la bibliothèque, mais de faire des catalogues des gisements de données complets, permettant la recherche et l’exploitation d’informations bien plus larges que l’étiquetage d’un exemplaire précis. « (…) quand l'usager demande un auteur, un lieu ou un titre, il importe de lui fournir ce qu'il demande, et non plus seulement une liste de notices décrivant des documents au sein de laquelle il découvrira peut-être sa réponse » (Frédérique Joannec-Seta et David Aymonin, p. 06). L'essor d'Internet remodèle en effet largement les pratiques de la recherche documentaire, les moteurs de recherche prenant largement le pas sur les applications dédiées, notamment en s'adaptant à la grande variété des formules de recherche employées. Dans une logique de service et afin de maintenir les catalogues de bibliothèques comme bases de connaissances et non uniquement comme des outils de gestion, il s’agit de pouvoir interroger le catalogue à la manière d’un moteur de recherche, pour accéder plus rapidement à une information précise, qu’elle porte directement sur les collections ou non : 
	 
> « - Pour ma thèse en histoire, j’ai besoin de la liste complète des éditions de Voltaire au XVIIIe siècle.  
\- _Il vous suffit de chercher la fiche Voltaire issue du fichier national des entités_"  
\- J’aimerais connaître les principaux auteurs ayant travaillé sur la chimie moléculaire   
\- _Une recherche par sujet me permettra de vous dire quels sont les auteurs les plus souvent associés à ce sujet_.  
\- Pour mon exposé sur Darwin, commençons par une recherche Google…   
\- _Tiens, il y a des documents sur le sujet à la bibliothèque. C’est donc à cela qu’elle sert ?_   
\- Ce livre a l’air intéressant, qu’en pense Google ?   
\- _Il est dans la bibliothèque près de chez moi !!_ »

= permettre des recherche plus intuitives, importance de l'interopérabilité des données 

« Dans le domaine du catalogage, le défi fondamental auquel les bibliothèques sont confrontées est l'exposition et la visibilité de leurs collections et de leurs métadonnées sur le web » peut-on lire dans le [communiqué de 2014](http://transition-bibliographique.fr/wp-content/uploads/2015/05/communique201411_transition_bibliographique.pdf) annonçant la transition bibliographique. Cette série de dialogues fictifs, issue d’une [infographie](https://www.transition-bibliographique.fr/wp-content/uploads/2022/10/infographie-TB.pdf) destinée à vulgariser les enjeux de la transition bibliographique auprès du grand public, démontre la multitude des enjeux liés à la transition bibliographique, relevant à la fois d’une logique de visibilité et d’exposition des données sur le web, mais aussi et surtout d’une restructuration globale des informations issues des catalogues. « La transition bibliographique doit ainsi concourir à améliorer notre compréhension de la construction/déconstruction des dispositifs de recherche d’information » (Grégory Miura), dans la continuité d'un mouvement naturel visant à adapter les catalogues aux évolutions des besoins des usagers et des technologies.

--Fiche pratique Enssib : Dans le cadre d'un web de données, les bibliothèques ont un rôle central à jouer dans la délivrance des identifiants pérennes et la constitution de référentiels d'autorités (auteurs, œuvres, matières, lieux, évènements) qui permettent la mise en relation de jeux de données de provenance variées. Il faut ainsi permettre une **interopérabilité des données** indispensable à la réalisation d'un web aux contenus véritablement sémantisés, rendus fouillables et exploitables à grande échelle par les moteurs de recherche. 
		 
## I.2. Les défis de la mise en œuvre technique en France 
	
Que l'objectif final soit la visibilité ou le service aux usagers (l'un n'excluant pas l'autre), l'intégration des catalogues de bibliothèque au web de données nécessite de nouveaux cadres conceptuels (FRBR, IFLA- tout autant que de nouveaux protocoles et de nouvelles opérations (production de métadonnées, utilisation de référentiels d'autorités). Définition et adoption de ces nouvelles manières de faire engendrent par voie de conséquence des mutations techniques, les systèmes informatiques de gestion des bibliothèques (SIGB) devant adapter leurs structures de bases de données pour les rendre compatibles. 

### I.2.1. FRBR, IFLA-LRM, RDA-FR… au cœur de la machine 

Dans un [communiqué de presse de novembre 2023](https://www.bnf.fr/sites/default/files/2023-11/cp_Transition_bibliographique_2023.pdf), l'Agence bibliographique de l'enseignement supérieur ([Abes](https://abes.fr/l-abes/presentation/)) et la Bibliothèque nationale de France ([BnF](https://www.bnf.fr/fr/missions-et-organisation-de-la-bnf)) résument en trois axes le programme de la transition bibliographique : 

> « 1. **Améliorer l'exposition des données bibliographiques françaises** dans le web de données par l'application du modèle international de données IFLA-LRM ; 
   2. Adopter pour ce faire de **nouvelles règles de signalement et de description des documents et des autorités** y étant liées (auteurs, sujets, lieux…), dérivées du code de catalogage international RDA, le code RDA-FR ;
   3. Préparer l'ensemble des acteurs de l'écosystème national à cette transition normative et technologique par des actions de communication, de sensibilisation et de formation » 


**À la source : [le modèle FRBR](http://www.enssib.fr/bibliotheque-numerique/documents/65520-comprendre-le-modele-frbr-et-ses-extensions.pdf), texte fondateur de la transition bibliographique** : ni norme ni format de catalogage, les FRBR publiées par l'IFLA en 1998 sont une [modélisation conceptuelle](https://www.transition-bibliographique.fr/wp-content/uploads/2016/01/support_formation_modelisation_frbr.pdf) de l'information contenue dans les notices bibliographiques, pensée pour l'utilisateur afin de répondre aux enjeux précédemment évoqués. Jusqu'alors, une notice bibliographique correspondait à un gisement d'information décrivant une ressource physique donnée (CD, livre, affiche…) disponible au sein d'une institution. Progressivement se sont également constitués, pour certains systèmes, des fichiers dits "d'autorités" recensant des entités normalisées (par exemple des personnes ou des collectivités) et liés aux notices bibliographiques. C'est cette mise en relation d'entités que développent les FRBR, en déployant en entités distinctes et liées la description d'un seul objet bibliographique. On identifie trois groupes d'entités. D'abord, il y a un regroupement par œuvre des ressources imprimées ou numériques. Ce premier niveau de modélisation (et le plus important) est synthétisé par le sigle OEMI (Œuvre, Expression, Manifestation et Item) : une œuvre donnée (par exemple Notre-Dame de Paris, de Victor Hugo) peut s'exprimer sous différentes formes. 

<center><I>Passage d'une logique de notices ...</I></center>  

![alt text](NoticeBib_OEMI1.jpg)   

<center><I>... à une logique d'entités et de relations (catalogage par entités OEMI appliquant les règles RDA-FR</I></center>  

![alt text](NoticeBib_OEMI2.jpg)  

_Source : site de la Transition bibliographique_




« (…) si le catalogue d'une bibliothèque constituait auparavant une **base de notices attachées à des "documents", il se compose désormais d'un ensemble hétérogène de "données" prises dans des relatons signifiantes conceptualisées au moyen de la syntaxe RDF (…). **Plus qu'une simple description de documents isolés, le catalogage devient une opération de conceptualisation de liens** : les bibliothèques engagées dans la Transition bibliographique avancent de fait vers cet objectif de "sémantisation" des données de leurs catalogues. » ([Fiche pratique de l'Enssib](https://www.enssib.fr/bibliotheque-numerique/documents/67445-comprendre-les-enjeux-de-la-transition-bibliographique.pdf), Gabriel Raupp, 2016) 

En 2009 puis 2010, deux n

[IFLA-LRM](http://library.ifla.org/1763/7/078-riva-fr.pdf) 


**"L'adopter, c'est l'adapter", de RDA à [RDA-FR](https://www.transition-bibliographique.fr/enjeux/definition-rda/)** : De nouvelles règles ont donc vocation à progressivement remplacer les [normes de catalogage Afnor](https://www.bnf.fr/fr/normes-afnor-de-catalogage) en cours, pour répondre au modèle IFLA-LRM, augmentation de FRBR. En effet, puisqu'il ne s'agit plus de créer des liens entre des pages mais de « **lier des données structurées**, si possibles ouvertes et identifiées de manière pérenne » (selon la formulation de la fiche pratique de l'Enssib), il faut disposer d'une syntaxe normalisée : RDA, _Ressource Description Framework_

**Un temps long nécessaire** : État intermédiaire entre deux paradigmes par définition, la « transition » bibliographique s'inscrit nécessairement dans le temps long, l'un de ses piliers fondamentaux étant l'idée de progressivité. La norme RDA-FR est rédigée et publiée chapitre après chapitre, au fur et à mesure de sa validation par le groupe AFNOR CN46-9, et doit être intégrée dans les formats de catalogage existants, nécessitant de nécessaires adaptations techniques ("les outils doivent tenir compte aussi bien des évolutions normatives que du changement de paradigme dans la production et la gestion des données"). Il s'agit aussi de former les catalogueurs au nouveau code, et de sensibiliser public et responsables d'établissements aux impacts de la transition bibliographiques et aux enjeux stratégiques, alors que le terme d'open data commence à s'imposer dans le débat courant. 

> « Le temps de la transition bibliographique est d'autant plus complexe que le contexte est celui de l'automatisation partielle des processus afin de traiter des lots de données de plus en plus volumineux ; ce travail sort du quotidien des informaticiens pour devenir celui des data librarians ; la production des métadonnées se répartie sur un nombre croissant d'acteurs » (Frédérique Joannic-Seta, David Aymonin)


### I.2.2. L’infrastructure institutionnelle 

Outre l'Abes et la BnF (mandatée en sa qualité d'Agence bibliographique nationale), qui supervisent le projet, les acteurs de la transition bibliographique sont nombreux, regroupant tant des professionnels de bibliothèques et de centres d'archives que des éditeurs d'applications et de logiciels professionnels.

### I.2.3. « MARC must die » : les métadonnées de l’avenir  

Outre le cadre de la description bibliographique (FRBR et IFLA-LRM) et les normes de catalogage (RDA-FR), le programme de la transition bibliographique invite également à réinterroger le format dans lequel les données sont gérées (Unimarc, Intermarc, MARC21). La visibilité des données sur le web dépend largement des formats MARC, encore peu compréhensibles par les machines et donc peu compétitifs dans le web de données. 

+Imaginer des formats permettant la production native de données FRBRisées 
				 
## I.3. Vision aérienne 
### I.3.1. Quel bilan en 2024 ?
### I.3.2. Au-delà de la France, la transition bibliographique dans le monde 
				 
# II. Transition bibliographique et science ouverte : des visions sécantes ?

> « Sous l’impulsion du Ministère de l’Enseignement supérieur et de la recherche et du Ministère de la Culture, [le Programme national de la Transition bibliographique] vise à faire évoluer les formats de production et de diffusion des données bibliographiques vers un modèle entités/relations favorisant la découvrabilité des contenus scientifiques et culturels français sur le web, leur bonne réutilisation par les intelligences artificielles et leur contribution à l’économie de la connaissance, au niveau national et européen »

Voici ce qu'on peut lire sur le site de la BnF
	 
## II.1. La transition bibliographique et les données FAIR 
## II.2. La transition bibliographique, accélérateur ou frein à la science ouverte ? 



[^1]: Arabesques 2017


