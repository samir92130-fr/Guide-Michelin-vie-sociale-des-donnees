# Enquete sur le guide michelin 

# Introduction

Nous avons décidé de travailler sur le classement par étoiles des restaurants gastronomiques et avons étudié le jeu de données du Guide Michelin. Notre objectif était d’analyser la quantification de l’inquantifiable: c'est-à-dire la qualité culinaire. Ainsi, nous nous sommes retrouvés face à de nombreuses interrogations: Pourquoi une marque de pneumatiques s’est-elle retrouvée à classer des restaurants ?  Comment est-il possible de classer la nourriture des restaurants ? Quels sont les critères? Pourquoi le guide utilise des étoiles ? Comment le guide a-t-il évolué à l’heure du numérique ? Tout l’objet de ce site est donc de répondre à ces questions. 
Par ailleurs, notre enquête s’est avérée complexe étant donnée l’opacité du guide. La principale difficulté étant d’interviewer un acteur de ce monde. Après avoir essuyé de nombreux refus, nous avons pu interroger un haut gradé de l’équipe du restaurant une étoile, Joël Robuchon- Saint Germain. 

Ainsi, cette enquete est divisée en quatre parties: 1)une histoire du guide michelin, de 1900 à nos jours 2)une analyse quantitative du jeu de données 3) une analyse qualitative du phénomène des étoiles 4)l'évolution du guide à l'heure du numérique

# 1-Le Guide Michelin, de 1900 à nos jours

_Pourquoi l'entreprise de pneumatiques Michelin ?_

Le guide Michelin a été créé en 1900 par les frères Michelin, fondateurs de la marque de pneumatiques éponyme. Cette date n'est pas anodine: il s'agit de la date de la cinquième exposition universelle organisée à Paris. Ainsi, ce guide est offert avec l’achat de pneus et contient une partie technique très importante variant entre 25% et 50% du volume total du guide selon les années. La première année, il est publié à plus de 30 000 exemplaires. Au lendemain de la première guerre mondiale qui est marquée par le développement de l’automobile, les frères Michelin décident d’enrichir le guide. Ainsi, le guide s’enrichit de cartes des routes françaises, des lieux de stations d’essence et de lieux de restauration ainsi que d’hébergement. 

![michelin1](https://github.com/samir92130-fr/enquete-vie-sociale-des-donnees/assets/152915097/e2ecc6ad-748f-401c-b18d-86fabdb7af59)
![Guide Michelin en 1931: sur ces deux pages, on observe la mention de restaurants, d'hôtels ainsi que d’agents motoristes et constructeurs.  ] 

_L'utilité du guide_

L’un des objectifs du guide est alors de créer une base de données de toutes les routes françaises. Ces routes sont dès lors classées selon plusieurs abréviations comme “ennuyeuses” ou “pittoresques”. Le second objectif, qui se développe tout au long du XXème siècle, est le classement des lieux de restauration et d’hébergement. Les cartes sont extremements précises; au point que les alliés, durant la libération de la France en 1944-1945, l'ont utilisé. 
Tous ces éléments s'accompagnent de la création de schémas d'excursion, qui forment des tracés qui permettent de visiter les différents lieux, que le guide considère comme intéressants, dans une région donnée. Par ailleurs, les lieux cités sont classés en étoiles. Ainsi, le guide va permettre le développement d’un phénomène large de tourisme. Après la seconde guerre mondiale, le guide est divisé en deux: le rouge pour le classement des lieux de restaurations et le guide vert pour le tourisme. 

_Évolution au cours de l'histoire et émergence des étoiles…_

En 1920, le guide devient payant car selon l'un des frères Michelin "l'homme ne respecte que ce qu'il paye". De plus, pour classer les restaurants, apparaît en 1926 la première étoile. Puis en 1931 est créée la deuxième et troisième étoile. Par ailleurs, la partie technique a été de plus en plus réduite, au point de ne plus être présente aujourd’hui dans le guide rouge. Enfin, les fondateurs insistent sur la probité du classement; principe encore fortement présent aujourd’hui: 

![Michelin 2](https://github.com/samir92130-fr/enquete-vie-sociale-des-donnees/assets/152915097/c8a48331-ba7a-4b59-8c7f-9c9384378e7c)

_Du guide michelin aux guides rouge et vert_

La division du guide michelin en deux guides semblent illustrer une division sociale. En effet, les restaurants classés dans le guide rouge sont des restaurants gastronomiques accessibles seulement à la bourgeoisie tandis que le guide vert répond aux attentes d’une clientèle bien plus populaire. 

_L'internationalisation du guide_

Très rapidement le guide Michelin s’est exporté à l’international. Ainsi, une version Belge est publiée en 1904 puis une version britannique en 1911. Au lendemain de la seconde guerre, le guide s’exporte de l’autre côté de l’Atlantique: direction les Etats-Unis.
Aujourd’hui, le guide est publié dans chacun des pays de l’Europe de l’Ouest, aux Etats-Unis, ainsi que dans certaines grandes villes d’Asie notamment au Japon ou encore à Singapour! 

# 2-Analyse quantitative du jeu de données

A)Les méthodes, critères du guide, comment quantifier l’inquantifiable de la gastronomie

Le système des étoiles michelins est par définition une méthode quantitative assez opaque. En effet, il n’existe pas vraiment une équation pour calculer le nombre d’étoiles michelins d’un restaurant. Cela s’explique par 2 raisons : 
-la gastronomie est difficilement quantifiable en terme de notes puisque les goûts sont plutôt subjectifs
-De par la nature de son classement, le guide Michelin ne souhaite pas dévoiler ses critères de manière transparente aux restaurateurs. Sinon ces derniers pourraient s’adapter aux critères pour s’assurer des étoiles. L’identité des inspecteurs est préservée par l’anonymat ainsi que la date de leur visite. Le principe est d’avoir une expérience la plus objective possible afin de pouvoir noter les restaurants. 
Cependant, le guide Michelin a tout de même présenté les grands axes de ces critères. Sur son site il est précisé qu’ “Il n’existe aucun secret, aucune formule”. Les étoiles peuvent être décernées aussi bien pour récompenser une cuisine traditionnelle que innovante. L’idée pour le guide Michelin est d’étudier la régularité de la qualité des plats, la qualité des produits, les techniques culinaires, la personnalité du chef ainsi que l’harmonie des saveurs. Le guide Michelin précise bien que le service n’est pas pris en compte dans la notation et les restaurants peuvent donc choisir librement le style qu’ils souhaitent. De la même façon, le décor du restaurant n’est pas regardé par les inspecteurs pour les étoiles. Il s’agit seulement de récompenser la qualité culinaire et non l’expérience autour. 
La méthode d’évaluation est la suivante. Différents inspecteurs anonymes se rendent plusieurs fois dans le restaurant comme des clients afin d’établir un jugement. Ces derniers sont souvent des anciens professionnels de l’hôtellerie ou de la restauration. Après cela, ces derniers se réunissent, partagent leurs expériences et prennent une décision finale concernant l’attribution d’étoiles ou non. L’idée de cet agrégat des étoiles est de proposer aux consommateurs un panel de restaurants dont la qualité a été certifié afin que ces derniers choisissent en fonction de leur goût et de leurs préférences.

B)Les étoiles : autant critiqué que célébré. L’évolution du nombre de restaurants par étoile

Le classement par étoiles est très simple puisqu’il existe 3 différents niveaux : 
-1 étoile : cela signifie que le restaurant propose une carte de haut niveau de manière régulière. Le restaurant est considéré comme “très bon dans sa catégorie” selon le guide Michelin. 
-2 étoiles : La différence principale ici est qu’il s’agit d’une cuisine inspirée et raffinée qui témoigne du talent et de la personnalité du chef.
-3 étoiles :  cela récompense une cuisine remarquable pour des chefs au sommet de leur talent. Ces plats peuvent être vus comme des classiques et cette cuisine est considérée comme un art. 
Le nombre de restaurants a évolué dans le temps comme en témoigne le graphique suivant construit avec les listes publiées par le guide Michelin.

Nous constatons donc que dans le temps le nombre de restaurants 2 et 3 étoiles semble plutôt stable. Cependant c’est le nombre de restaurants 1 étoile qui semble augmenter de plus en plus.
Il est important également de noter la répartition géographique des restaurants. En effet, les restaurants étoilés semblent concentrés dans certaines zones géographiques plus que d’autres.

![statistic_id1352928_nombre-de-restaurants-etoiles-par-region-2022](https://github.com/samir92130-fr/enquete-vie-sociale-des-donnees/assets/153020927/54b25284-cf02-4a0d-85f9-149731936907)


Les restaurants étoilés sont également présents à l’étranger. Si l’on regarde les villes qui concentrent le plus de restaurants étoilés, nous retrouvons Tokyo, Paris, Kyoto, New York mais aussi Osaka, Hong Kong et San Francisco. Nous remarquons que le Japon concentre de nombreux restaurants étoilés.
Il peut être intéressant également de regarder l’impact pour les nouveaux restaurants étoilés. L’attribution d’une étoile ne garantit pas le maintien de celle-ci les années suivantes. En effet, chaque année, certains perdent leurs étoiles et de nouveaux restaurants sont étoilés. En 2023, 44 nouveaux restaurants ont été étoilés où ont reçu une étoile supplémentaire. Cela a bien sûr un impact sur l'affluence et la popularité de ces restaurants. Une étude sur google trends peut donner un aperçu de l’impact de ces nouvelles étoiles sur la visibilité donnée au restaurant. 

<img width="449" alt="graphique 2" src="https://github.com/samir92130-fr/enquete-vie-sociale-des-donnees/assets/153020927/4dbd6d6f-5a14-407b-90f5-8a664ceda55c">

Sur ce graphique, la courbe bleue montre le nombre de recherches effectuées sur le restaurant la Marine qui est le nouveau restaurant 3 étoiles Michelin en 2023. La courbe rouge montre les données pour le restaurant Astrance qui a décroché sa première étoile en 2023. Nous constatons bien un pic de visite à l’annonce du guide Michelin le 6 mars 2023. Cependant, il est important de nuancer que les recherches google vont continuer d’augmenter pour le 3 étoiles tandis qu’elles resteront stables pour le 1 étoile. Ainsi, nous pouvons imaginer que pour un restaurant déjà étoilé comme l’était la Marine une nouvelle étoile apporte encore plus de visibilité que pour un restaurant qui vient de décrocher sa première étoile.


# 3-Analyse qualitative

# 4-L'évolution du guide à l'heure du numérique

