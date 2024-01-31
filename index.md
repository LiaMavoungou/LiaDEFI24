# LiaDEFI24
# M2 DEFI 2023 - Data Visualisation

## Devoir de M2 DEFI - Data Visualisation

## SOMMAIRE : 
1. [Projet de datavisualisation des jeux olympiques modernes](#Projet)
2. [Jeu de données](#Jeu)
3. [Les outils](#Outils)
4. [LES FEMMES MÉDAILLÉES D'OR EN ATHLÉTISME AUX JEUX DE RIO 2016](#Femmes)
5. [LES NATIONS LEADERS AUX JEUX OLYMPIQUES DE 2004 À 2016](#Nations)
6. [LES MEDAILLES FRANÇAISES DE 1896 À 2016](#Médailles)
7. [LES LOGOS DES JEUX OLYMPIQUES DEPUIS 1996 À 2028](#Logos)
8. [Conclusion](#Conclu)


## Projet de datavisualisation des jeux olympiques modernes <a name="Projet"></a>

J'ai décidé de choisir ce jeu de données qui me semblait très complet sur les différents jeux olympiques qui se sont déroulés entre 1896 et 2016. Tous les athlètes participants sont inscrits ainsi que les différents pays. On remarque que suite à des changements politiques certains pays n'existent plus tel que l'Allemagne de l'EST. On remarque également que les débuts des jeux olympiques modernes montre que les équipes étaient différentes ce n'était pas des pays. Un même pays pouvait avoir plusieurs équipes pour une même discipline. Au fil du temps, les équipes se sont unifiées pour devenir des équipes nationales comme les jeux actuels. Grâce à ce jeu de données nous avons pu étudier quels étaient les athlètes ayant remportés telles médailles, les nations qui se distinguaient le mieux lors des jeux, les logos des villes organisatrices. 

![](https://www.mchampetier.com/sitephp/img_png/oeuvres_XL/2_Allen_Jones_affiche_fev201.jpg)


## Jeu de données <a name="Jeu"></a>
J'ai exploité une base de données exhaustive regroupant les données historiques des Jeux Olympiques modernes, englobant les éditions estivales et hivernales, depuis les Jeux d'Athènes en 1896 jusqu'à ceux de Rio en 2016. La qualité de ce jeu de données s'est avérée particulièrement robuste, nécessitant ainsi peu d'interventions substantielles lors du processus de validation, soulignant ainsi sa bonne organisation préalable.
Jeu de données des jeux olympiques modernes : 

![Lien WeTransfer](https://we.tl/t-RgDpOJDPlu)


## Les outils <a name="Outils"></a>

Pour ce travail, j'ai utilisé OpenRefine pour nettoyer et filtrer mes données. Pour une visualtion j'ai crée un excel. 
Pour la création des visualisations j'ai utilisé datawrapper pour afficher une map, j'ai utilisé flourish pour effectuer un line chart dynamique et une cards pour afficher des logos. Enfin pour une dernière visualisation j'ai utilisé rawgraph pour faire un linechart qui lui n'est pas dynamique. 


### LES FEMMES MÉDAILLÉES D'OR EN ATHLÉTISME AUX JEUX DE RIO 2016 <a name="Femmes"></a>

<iframe title="[ Femmes médaillées d'or en athlétisme Rio 2016] " aria-label="Map" id="datawrapper-chart-Ow3Ay" src="https://datawrapper.dwcdn.net/Ow3Ay/2/" scrolling="no" frameborder="0" style="border: none;" width="600" height="436" data-external="1"></iframe>


Pour l'harmonisation des données, j'ai effectué une réconciliation des cellules en associant les équipes via Wikidata, en utilisant le pays comme référence, tout en restreignant les jeux uniquement aux Jeux Olympiques d'été de 2016. Cette démarche a permis d'assurer une cohérence dans la représentation des équipes participantes.
Par la suite, lors de la facettage textuelle, j'ai concentré l'analyse sur les performances des femmes dans le domaine de l'athlétisme. En filtrant les données en fonction du genre,de l'âge et en se limitant à la colonne "Sport" dédiée à l'athlétisme, j'ai pu mettre en lumière les réalisations spécifiques de cette discipline. J'ai affiné la sélection en ne retenant que les médailles d'or, soulignant ainsi les performances des athlètes féminines.
Pour une visualisation plus détaillée et une communication efficace des résultats, j'ai extrait ces données filtrées dans un fichier CSV, prêt à être utilisé dans divers outils d'analyse. En particulier, nous avons exploité ce fichier pour créer une carte significative via Datawrapper, offrant ainsi une perspective visuelle interactive des performances des athlètes féminines médaillées d'or en athlétisme lors des Jeux Olympiques d'été de 2016.

Pour cette visualisation le choix d'une carte permetlocaliser la nationalité des athlètes permet d'afficher également leur âge et la sous-discipline à laquelle elles ont pris part.

### LES NATIONS LEADERS AUX JEUX OLYMPIQUES DE 2004 À 2016  <a name="Nations"></a>

<iframe src='https://flo.uri.sh/visualisation/16565200/embed' title='Interactive or visual content' class='flourish-embed-iframe' frameborder='0' scrolling='no' style='width:100%;height:600px;' sandbox='allow-same-origin allow-forms allow-scripts allow-downloads allow-popups allow-popups-to-escape-sandbox allow-top-navigation-by-user-activation'></iframe>
<div style='width:100%!;margin-top:4px!important;text-align:right!important;'>
<a class='flourish-credit' href='https://public.flourish.studio/visualisation/16565200/?utm_source=embed&utm_campaign=visualisation/16565200' target='_top' style='text-decoration:none!important'><img alt='Made with Flourish' src='https://public.flourish.studio/resources/made_with_flourish.svg' style='width:105px!important;height:16px!important;border:none!important;margin:0!important;'> </a></div>

Au cours de cette analyse, OpenRefine est utilisé pour affiner les données et concentrer les éléments spécifiques. Initialement, j'ai appliqué des facettes textuelles pour sélectionner les pays clés tels que les États-Unis, la Chine, l'Allemagne, le Royaume-Uni, la Russie et la France. Pour ensuite restreindre l'analyse aux Jeux Olympiques d'été, en précisant les années 2004, 2008, 2012 et 2016. Pour garantir la cohérence des résultats, j'ai également exclu les données de médailles manquantes (N/A) à l'aide d'une facette textuelle.

Par la suite, j'ai utilisé Flourish pour créer un line chart, permettant une visualisation claire de la progression ou de la régression des pays au cours de ces 12 années. Chaque année est représentée, fournissant des informations sur le nombre de médailles remportées par chaque pays. L'analyse du line chart a révélé une baisse de médailles en 2012 pour les États-Unis mais ils demeurent en tête, marquant une nette distinction. En contraste, la France maintient une position moins favorable par rapport aux autres nations, soulignant ainsi les variations dans les performances sportives au fil du temps. Cette approche visuelle a grandement contribué à la compréhension des tendances et des dynamiques des médailles olympiques pour ces pays spécifiques.

### LES MEDAILLES FRANÇAISES DE 1896 À 2016 <a name="Medailles"></a>

Visualisation des médailles remportées par la France de 1896 à 2016 incluant les jeux olympiques d'hiver et d'été. 

![Visu3Finale](https://github.com/LiaMavoungou/LiaDEFI24/assets/156092166/921bbaf8-986e-46f3-af40-2110dc85c9fc)


Pour cette visualisation j'ai initié une série d'étapes avec OpenRefine pour assurer la qualité et la pertinence de l'ensemble de données. Tout d'abord, OpenRefine a été utilisé pour éliminer efficacement les valeurs manquantes (N/A), garantissant ainsi une base de données complète. Une fois cette étape accomplie, le fichier a été exporté au format CSV pour une manipulation ultérieure.
Dans le fichier CSV j'ai  supprimer les lignes qui ne correspondait pas aux athlètes français. Ce fichier CSV, désormais épuré et adapté aux besoins, a été réimporté dans OpenRefine pour la poursuite de l'analyse.
Au sein d'OpenRefine, mise en place d'une de facette textuelle , se concentrant spécifiquement sur les années qui incluent le type de jeux, à savoir été et hiver. Cette facette textuelle a permis de catégoriser les données en offrant une vision plus approfondie des événements en fonction de leur nature saisonnière.
Suite à l'affinage de la selection 50 options spécifiques s'affichent. Ces options soigneusement choisies ont été extraites et copiées dans un nouveau fichier CSV, prêt à être utilisé pour des analyses plus ciblées.
Enfin, afin de structurer encore davantage les  données, j'ai utilisé l'opération SPLIT sur le fichier CSV. Cette opération a été réalisée avec l'intention de diviser les données textuelles en colonnes distinctes, en utilisant l'espace comme délimiteur. Cette étape a contribué à une organisation plus claire et à une meilleure interprétation des informations contenues, facilitant ainsi notre analyse ultérieure.
J'ai fais le choix d'utiliser RawGraph pour faire ce line chart,pour organiser le graph j'ai utilisé l'année pour X Axis et le nombre de médailles pour Y Axis. Pour les lignes ainsi que pour les couleurs j'ai utilisé le type ( type de jeux : été ou hiver). 


### LES LOGOS DES JEUX OLYMPIQUES DEPUIS 1996 À 2028 <a name="Logo"></a>

<iframe src='https://flo.uri.sh/visualisation/16640261/embed' title='Interactive or visual content' class='flourish-embed-iframe' frameborder='0' scrolling='no' style='width:100%;height:600px;' sandbox='allow-same-origin allow-forms allow-scripts allow-downloads allow-popups allow-popups-to-escape-sandbox allow-top-navigation-by-user-activation'></iframe>
<div style='width:100%!;margin-top:4px!important;text-align:right!important;'>
<a class='flourish-credit' href='https://public.flourish.studio/visualisation/16640261/?utm_source=embed&utm_campaign=visualisation/16640261' target='_top' style='text-decoration:none!important'><img alt='Made with Flourish' src='https://public.flourish.studio/resources/made_with_flourish.svg' style='width:105px!important;height:16px!important;border:none!important;margin:0!important;'> </a></div>

Pour cette quatrième visualisation, en amont j'ai crée un fichier excel dans lequel j'ai intégrer les villes organisatrices des jeux olympiques puis j'ai utilisé des données sur wikipédia pour trouver les images des logos et j'ai ajouté les trois derniers jeux après Rio 2016.

## Conclusion <a name="Conclu"></a>
En synthèse, les analyses méthodiques ont abouti à une harmonisation des données, mettant en lumière les performances  des athlètes féminines en athlétisme aux Jeux Olympiques d'été de 2016. Les visualisations créées avec des outils comme Datawrapper, Flourish, et RawGraph ont offert des perspectives claires et interactives, facilitant la compréhension des variations par pays et des tendances saisonnières sur une période de 12 ans.

L'utilisation d'OpenRefine a contribué à la qualité des données en éliminant les valeurs manquantes, en affinant la sélection, et en structurant le fichier CSV. L'intégration d'informations sur les villes organisatrices et l'ajout d'images ont enrichi la représentation visuelle.

En somme, votre approche analytique a permis une exploration approfondie des performances olympiques, offrant des insights significatifs sur les succès des équipes, les évolutions au fil du temps, et les particularités saisonnières. Ces résultats visuels et structurés constituent un atout précieux pour une compréhension approfondie des dynamiques sportives aux Jeux Olympiques.

---



