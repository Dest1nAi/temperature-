Etude de l’évolution de la température dans une ville
Introduction
  L'urbanisation croissante des villes à travers le monde a un impact significatif sur l'environnement local, en particulier sur les conditions climatiques et la qualité de vie des habitants. L'effet d'îlot de chaleur urbain est un phénomène bien connu où les zones urbaines ont tendance à être plus chaudes que les zones rurales environnantes. Ce phénomène est principalement dû à l'absorption et à la rétention de la chaleur par les matériaux de construction et les surfaces asphaltées, ainsi qu'à la réduction de la végétation qui pourrait autrement fournir de l'ombre et refroidir l'air par évapotranspiration.
  Le changement climatique global amplifie cet effet, rendant les épisodes de chaleur extrême plus fréquents et plus intenses, ce qui a des conséquences directes sur la santé publique, la consommation d'énergie pour le refroidissement et même la biodiversité locale.
  Dans ce contexte, il est crucial de mieux comprendre les mécanismes qui influencent la température dans les villes pour développer des stratégies d'adaptation efficaces. Ce projet vise à étudier l'évolution de la température dans une ville en prenant en compte les principaux facteurs qui influencent les conditions climatiques urbaines, notamment l'urbanisation, la végétation et le relief. En combinant la modélisation numérique et l'analyse des données, nous cherchons à répondre à la question de savoir comment l'urbanisation et la végétation influencent l'évolution de la température dans une ville et comment ces connaissances peuvent être utilisées pour atténuer l'effet d'îlot de chaleur urbain et améliorer la qualité de vie en milieu urbain.
Ce projet présente donc un intérêt significatif non seulement pour les chercheurs et les urbanistes, mais aussi pour les décideurs politiques, les urbanistes et les habitants des villes qui sont directement touchés par les effets de l'urbanisation sur le climat local


Thème :L'impact de la ville et de la végétation sur la température locale.

Problématique :Comment l'urbanisation et la végétation influencent-elles l'évolution de la température dans une ville ?

Hypothèse principale :L'urbanisation conduit à une augmentation de la température locale en raison de l'effet d'îlot de chaleur urbain, tandis que la végétation peut atténuer cette augmentation en améliorant la régulation thermique.

Hypothèses secondaires :
-Les zones plus urbanisées présentent une plus grande augmentation de température par rapport aux zones moins urbanisées.
-Une augmentation de la couverture végétale dans la ville peut réduire l'effet d'îlot de chaleur urbain.

Objectif :Étudier l'évolution de la température dans une ville en tenant compte de l'urbanisation et de la couverture végétale.

Critère(s) d’évaluation :
-Variations de la température au fil du temps dans différents secteurs de la ville.
-Comparaison des températures entre les zones urbanisées et les zones avec couverture végétale.
-Identification des zones à risque élevé d'îlot de chaleur urbain et des zones où la végétation est efficace pour atténuer la chaleur.


Ces éléments fournissent un cadre pour mener une étude approfondie sur l'évolution de la température dans une ville, en prenant en compte les effets de l'urbanisation et de la végétation. La modélisation numérique peut être utilisée comme outil pour répondre à cette problématique et vérifier les hypothèses.





Séance Recherche Bibliographique 
(semaine du 26/02)

  La recherche bibliographique est une étape cruciale dans la réalisation de notre projet. Elle permet d'acquérir une compréhension approfondie des mécanismes physiques et des facteurs qui influencent la température dans une ville. Cette phase de recherche nous fournit également des formules et des modèles théoriques qui serviront de base à notre modélisation numérique. Voici les principaux éléments que nous avons identifiés lors de notre recherche bibliographique :

Formules Utiles:
-Équation de la chaleur
-Bilan radiatif entre le rayonnement solaire incident 
-Influence du relief sur le rayonnement solaire
-Effet du vent
-Équation de la diffusion thermique
Données et études pertinentes:
-Effet d'îlot de chaleur urbain:Des études comme celle de Oke (1982) ont fourni des insights sur les facteurs contribuant à l'effet d'îlot de chaleur urbain et les méthodes pour l’atténuer.
(Référence : Oke, T. R. (1982). "The energetic basis of the urban heat island". Quarterly Journal of the Royal Meteorological Society, 108(455), 1-24.)
-Influence de la végétation:Les études de Zhao et al. (2014) ont examiné l'impact de la couverture végétale sur la température urbaine.
(Référence : Zhao, L., Lee, X., Smith, R. B., & Oleson, K. (2014). "Strong contributions of local background climate to urban heat islands". Nature, 511(7508), 216-219.)
-Modélisation de la température urbaine:Des modèles comme celui développé par Martilli et al. (2002) offrent une approche détaillée pour modéliser l'évolution de la température dans les villes.
(Référence : Martilli, A., Clappier, A., & Rotach, M. W. (2002). "An urban surface exchange parameterisation for mesoscale models". Boundary-Layer Meteorology, 104(2), 261-304.)

  La recherche bibliographique a fourni une base solide pour la modélisation de l'évolution de la température dans une ville. Les formules et les modèles identifiés nous permettront de développer un modèle numérique robuste pour étudier l'impact de l'urbanisation et de la végétation sur la température urbaine. Il est important de noter que ces formules et modèles sont des simplifications de la réalité, 

Programmation
Nous allons utiliser Python pour simuler l'évolution de la température dans la ville.
Développement : 
1-Modélisation de la Température dans une Ville
  Pour modéliser l'évolution de la température dans une ville, nous allons commencer par créer un modèle simplifié d'une ville sans considérer le relief ou la végétation. Nous allons définir des paramètres simples pour calculer la température à chaque position de la ville. Les formules et les paramètres seront basés sur les principes de base de la diffusion thermique, du bilan radiatif et de l'effet d'îlot de chaleur urbain.


Cette modélisation initiale nous permet de comprendre comment la température évolue dans une ville simple en utilisant les paramètres et les formules de base. Dans les sections suivantes, nous pourrons intégrer des éléments supplémentaires comme le relief et la végétation pour affiner notre modèle et étudier l'impact de ces facteurs sur la température urbaine.





2-Modélisation Dynamique de la Température dans une Ville avec Trois Facteurs Principaux
  Dans cette deuxième partie de la modélisation, nous allons intégrer les trois facteurs principaux qui influencent la température dans une ville : la conduction thermique due aux bâtiments, aux routes et aux autres surfaces, le bilan radiatif prenant en compte le rayonnement solaire et le rayonnement thermique, ainsi que l'effet du vent et de la convection. Nous allons développer un système dynamique pour étudier l'évolution de la température dans la ville en tenant compte de ces facteurs.


  Cette modélisation dynamique intègre maintenant les trois facteurs principaux influençant la température dans une ville : la conduction thermique due aux bâtiments, aux routes et aux autres surfaces, le bilan radiatif prenant en compte le rayonnement solaire et le rayonnement thermique, ainsi que l'effet du vent et de la convection. Le modèle nous permet d'étudier l'évolution de la température dans la ville en tenant compte de ces facteurs, offrant ainsi une représentation plus réaliste de la dynamique thermique urbaine


3-Modélisation Dynamique de la Température dans une Ville avec Prise en Compte de la Végétation
Dans cette troisième partie de la modélisation, nous allons ajouter un nouveau facteur important qui influence la température dans une ville : la végétation. Nous allons intégrer la végétation dans le modèle en tenant compte de sa capacité à absorber le rayonnement solaire et à influencer la convection et la circulation de l'air. Le modèle final nous permettra d'étudier l'évolution de la température dans la ville en prenant en compte les quatre facteurs principaux : la conduction thermique, le bilan radiatif, l'effet du vent et de la convection, ainsi que la végétation.

Comparaison des Résultats
Comparons maintenant les trois modèles pour évaluer l'influence de la végétation et de l'urbanisation sur la température urbaine.


En utilisant trois modèles différents, nous avons pu observer l'évolution de la température dans une ville en tenant compte des différents facteurs :
 -Modèle initial : Le modèle initial nous a fourni une base pour comprendre comment la température évolue dans une ville simple sans prendre en compte la végétation et d'autres facteurs.
-Modèle sans végétation : Ce modèle a montré une augmentation générale de la température dans la ville, avec des valeurs plus élevées près du centre de la ville en raison de l'effet d'îlot de chaleur urbain.
-Modèle avec végétation : L'intégration de la végétation a eu un effet significatif sur la réduction de la température dans la ville. La végétation a aidé à absorber une partie du rayonnement solaire, réduisant ainsi le bilan radiatif positif et la température globale dans la ville. De plus, la végétation a également amélioré l'efficacité de la convection et de la circulation de l'air, contribuant à une meilleure régulation thermique.

Conclusion Générale
L'intégration de la végétation dans notre modèle a montré son importance dans la régulation thermique urbaine. La végétation joue un rôle crucial dans la réduction de l'effet d'îlot de chaleur urbain en absorbant une partie du rayonnement solaire et en améliorant la convection et la circulation de l'air. Il est donc essentiel d'incorporer des espaces verts et de la végétation dans la planification urbaine pour atténuer les effets néfastes de la chaleur urbaine et améliorer le confort thermique des citoyens.
En conclusion, cette étude nous permet de mieux comprendre les mécanismes complexes qui influencent la température dans les villes et souligne l'importance de la végétation dans la régulation thermique urbaine. Des études supplémentaires peuvent être réalisées pour affiner le modèle et intégrer d'autres facteurs, tels que le relief et la densité de la ville, afin d'obtenir des résultats plus précis et fiables.
