# Enquete sur le guide michelin 

# Introduction

Nous avons décidé de travailler sur le classement par étoiles des restaurants gastronomiques et avons étudié le jeu de données du Guide Michelin. Notre objectif était d’analyser la quantification de l’inquantifiable: c'est-à-dire la qualité culinaire. Ainsi, nous nous sommes retrouvés face à de nombreuses interrogations: Pourquoi une marque de pneumatiques s’est-elle retrouvée à classer des restaurants ?  Comment est-il possible de classer la nourriture des restaurants ? Quels sont les critères? Pourquoi le guide utilise des étoiles ? Comment le guide a-t-il évolué à l’heure du numérique ? Tout l’objet de ce site est donc de répondre à ces questions. 
Par ailleurs, notre enquête s’est avérée complexe étant donnée l’opacité du guide. La principale difficulté étant d’interviewer un acteur de ce monde. Après avoir essuyé de nombreux refus, nous avons pu interroger un haut gradé de l’équipe du restaurant une étoile, Joël Robuchon- Saint Germain. 

Ainsi, cette enquete est divisée en quatre parties: 1)une histoire du guide michelin, de 1900 à nos jours 2)une analyse quantitative du jeu de données 3) une analyse qualitative du phénomène des étoiles 4)l'évolution du guide à l'heure du numérique

# 1-Le Guide Michelin, de 1900 à nos jours

_Pourquoi l'entreprise de pneumatiques Michelin ?_

Le guide Michelin a été créé en 1900 par les frères Michelin, fondateurs de la marque de pneumatiques éponyme. Cette date n'est pas anodine: il s'agit de la date de la cinquième exposition universelle organisée à Paris. Ainsi, ce guide est offert avec l’achat de pneus et contient une partie technique très importante variant entre 25% et 50% du volume total du guide selon les années. La première année, il est publié à plus de 30 000 exemplaires. Au lendemain de la première guerre mondiale, qui est marqué par le développement de l’automobile, les frères Michelin décident d’enrichir le guide. Ainsi, le guide s’enrichit de cartes des routes françaises, des lieux de stations d’essence et de lieux de restauration ainsi que d’hébergement. 

![michelin1](https://github.com/samir92130-fr/enquete-vie-sociale-des-donnees/assets/152915097/e2ecc6ad-748f-401c-b18d-86fabdb7af59)
![Guide Michelin en 1931: sur ces deux pages, on observe la mention de restaurants, d'hôtels ainsi que d’agents motoristes et constructeurs.  ] 

_L'utilité du guide_

L’un des objectifs du guide est alors de créer une base de données de toutes les routes françaises. Ces routes sont dès lors classées selon plusieurs abréviations comme “ennuyeuses” ou “pittoresques”. Les cartes sont extremements précises; au point que les alliés, durant la libération de la France en 1944-1945, l'ont utilisé. Le second objectif, qui se développe tout au long du XXème siècle, est le classement des lieux de restauration et d’hébergement. 
Tous ces éléments s'accompagnent de la création de schémas d'excursion, qui forment des tracés qui permettent de visiter les différents lieux, que le guide considère comme intéressants, dans une région donnée. Par ailleurs, les lieux cités sont classés en étoiles. Ainsi, le guide va permettre le développement d’un phénomène large de tourisme. Après la seconde guerre mondiale, le guide est divisé en deux: le rouge pour le classement des lieux de restaurations et le guide vert pour le tourisme. 

_Évolution au cours de l'histoire et émergence des étoiles…_

En 1920, le guide devient payant car selon l'un des frères Michelin "l'homme ne respecte que ce qu'il paye". De plus, pour classer les restaurants, apparaît en 1926 la première étoile. Puis en 1931 est créée la deuxième et troisième étoile. Par ailleurs, la partie technique a été de plus en plus réduite, au point de ne plus être présente aujourd’hui dans le guide rouge. Enfin, les fondateurs insistent sur la probité du classement; principe encore fortement présent aujourd’hui: 

![Michelin 2](https://github.com/samir92130-fr/enquete-vie-sociale-des-donnees/assets/152915097/c8a48331-ba7a-4b59-8c7f-9c9384378e7c)

_Du guide michelin aux guides rouge et vert_

La division du guide michelin en deux guides semblent illustrer une division sociale. En effet, les restaurants classés dans le guide rouge sont des restaurants gastronomiques accessibles seulement à la bourgeoisie tandis que le guide vert répond aux attentes d’une clientèle bien plus populaire. 

_L'internationalisation du guide_

Très rapidement le guide Michelin s’est exporté à l’international. Ainsi, une version belge est publiée en 1904 puis une version britannique en 1911. Au lendemain de la seconde guerre, le guide s’exporte de l’autre côté de l’Atlantique: direction les Etats-Unis.
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

<img width="452" alt="graphique 1" src="https://github.com/samir92130-fr/enquete-vie-sociale-des-donnees/assets/153020927/5c2696b7-8a68-4095-8db5-6a5cba29c7d7">


Nous constatons donc que dans le temps le nombre de restaurants 2 et 3 étoiles semble plutôt stable. Cependant c’est le nombre de restaurants 1 étoile qui semble augmenter de plus en plus.
Il est important également de noter la répartition géographique des restaurants. En effet, les restaurants étoilés semblent concentrés dans certaines zones géographiques plus que d’autres.

![statistic_id1352928_nombre-de-restaurants-etoiles-par-region-2022](https://github.com/samir92130-fr/enquete-vie-sociale-des-donnees/assets/153020927/54b25284-cf02-4a0d-85f9-149731936907)


Les restaurants étoilés sont également présents à l’étranger. Si l’on regarde les villes qui concentrent le plus de restaurants étoilés, nous retrouvons Tokyo, Paris, Kyoto, New York mais aussi Osaka, Hong Kong et San Francisco. Nous remarquons que le Japon concentre de nombreux restaurants étoilés.
Il peut être intéressant également de regarder l’impact pour les nouveaux restaurants étoilés. L’attribution d’une étoile ne garantit pas le maintien de celle-ci les années suivantes. En effet, chaque année, certains perdent leurs étoiles et de nouveaux restaurants sont étoilés. En 2023, 44 nouveaux restaurants ont été étoilés où ont reçu une étoile supplémentaire. Cela a bien sûr un impact sur l'affluence et la popularité de ces restaurants. Une étude sur google trends peut donner un aperçu de l’impact de ces nouvelles étoiles sur la visibilité donnée au restaurant. 

<img width="449" alt="graphique 2" src="https://github.com/samir92130-fr/enquete-vie-sociale-des-donnees/assets/153020927/4dbd6d6f-5a14-407b-90f5-8a664ceda55c">


Sur ce graphique, la courbe bleue montre le nombre de recherches effectuées sur le restaurant la Marine qui est le nouveau restaurant 3 étoiles Michelin en 2023. La courbe rouge montre les données pour le restaurant Astrance qui a décroché sa première étoile en 2023. Nous constatons bien un pic de visite à l’annonce du guide Michelin le 6 mars 2023. Cependant, il est important de nuancer que les recherches google vont continuer d’augmenter pour le 3 étoiles tandis qu’elles resteront stables pour le 1 étoile. Ainsi, nous pouvons imaginer que pour un restaurant déjà étoilé comme l’était la Marine une nouvelle étoile apporte encore plus de visibilité que pour un restaurant qui vient de décrocher sa première étoile.


# 3-Analyse qualitative

"Les étoiles, on vit très bien sans, mais beaucoup mieux avec." 

Cette citation du chef Alain Ducasse qui a obtenu trois étoiles dans trois restaurants différents, témoigne des rapports en dents de scie qu’entretiennent les chefs avec le guide Michelin. La tension autour de cette quantification de la qualité de la cuisine est le fil rouge de notre enquête car elle soulève de nombreuses questions. Si le caractère opaque et arbitraire de sa méthodologie sont souvent pointés du doigt par les chefs, cette quantification n'est pas sans conséquences sur la vie des chefs et de leurs restaurants. Quelle est la nature de ces dernières ? Dans quelle mesure peuvent-elles représenter la critique et participer à une remise en cause du guide Michelin ?
	Nous avons donc décidé, au travers de cette enquête, de donner la parole à ces chefs qui sont à la fois les premiers bénéficiaires mais aussi les premières victimes de cette quantification étoilée. A ce sujet, il est important de préciser la difficulté que nous avons rencontré pour avoir accès aux, chefs car sur les treize que nous avons contactés, seul Éric Frechon a donné suite à nos sollicitations, malheureusement par une réponse négative. C’est lorsque nous nous sommes déplacés en personne à « l’Atelier Saint-Germain de Joël Robuchon », une étoile au guide Michelin, que nous avons eu la chance de pouvoir nous entretenir avec un des seconds de cuisine. Ce dernier a accepté de répondre à nos questions sous couvert d’anonymat. Nous avons ensuite fait le choix de croiser les données recueillis avec des enquêtes académique et des entretiens accordés par des chefs dans la presse afin de comparer leurs visions sur le guide Michelin.  Il en ressort que, si l’attribution ou la perte d’une étoile par le guide Michelin a des conséquences économiques sur les restaurants (I), elle n’est pas sans conséquences psychologiques pour les chefs (II). 

     ** I - Les coûts économiques des étoiles du guide Michelin**

Le chef que nous avons interviewé nous l’affirme : « Certains chefs recherchent une étoile car c’est une justification pour augmenter les prix sur la carte ». Toutefois, une étude statistique d’Olivier Gergaud sur l’impact économique des étoiles Michelin sur les restaurants, vient remettre en perspective cette déclaration. Effectivement, le chiffre d’affaires semble très sensible à une promotion par le guide Michelin (+80%) et beaucoup moins à une rétrogradation (+4%). Les profits des restaurants eux augmentent peu avec une promotion mais chute excessivement en cas de rétrogradation (-100%). Il faut rajouter à ces coûts, deux facteurs importants comme le précise le chef Alain Senderens dans un entretien pour Le journal de l’École de Paris et du Management. D’une part, il estime en effet que ses étoiles lui coutaient 350 000 euros par an en frais somptuaires, qui n’ont pas de lien avec la qualité avec la cuisine. D’autre part, suivant la même logique, les équipes des restaurants étoilés comptent plus de personnes que les restaurants classiques alors qu’ils servent moins de couverts. Ainsi les déclarations des chefs rejoignent les conclusions statistiques d’Olivier Gergaud, qui mettent en lumière le fait que la rentabilité commerciale des restaurants étoilés, est non seulement inférieure à celle des restaurants classiques mais elle diminue drastiquement lors d’une rétrogradation alors qu’elle n’augmente que très peu en cas de promotion par le guide Michelin.  

      **II - Les coups psychologiques des étoiles du Guide Michelin**

	S’il semble que leurs coûts économiques soit plus élevés que les profits potentiels qu’elles apportent aux restaurateurs, les étoiles Michelin s’apparenteraient aussi à des coups psychologiques pour ces derniers. S’il y a bien un point sur lequel le chef de l’Atelier Saint-Germain de Joël Robuchon a insisté dans l’entretient qu’il nous a accordé, c’est bien la pression qui pèse sur les chefs à la suite de l’obtention du statut de restaurant étoilé au guide Michelin. Selon lui, cette distinction s’accompagne d’une hausse des exigences des chefs, des clients, des médias mais aussi et surtout des inspecteurs du guide. En effet, comme cela est précisé sur son site, le guide Michelin invite les restaurateurs à ne pas se reposer sur leurs lauriers car une étoile n'est jamais acquise. Ainsi, le guide Michelin envoie régulièrement, ses inspecteurs dans les restaurants étoilés pour y faire des contrôles de qualité de manière inopinées et surtout sous couvert d’anonymat. Les chefs sont donc sous la menace perpétuelle d’une rétrogradation ce qui rajoute une pression psychologique, quasi paranoïaque, dans un milieu de la gastronomie rendu très compétitif, notamment du fait du Guide Michelin. Alors, en plus d’un coût économique important pour les restaurants, ces pertes d’étoiles affectent surtout profondément la santé mentale des chefs. Si bien que l’émission « C à Vous : la frustration des rétrogradés du Guide Michelin » du 28 février 2023 voit témoigner des chefs renommés qui illustrent les conséquences psychologiques terribles d’un tel déclassement. Michel Sarran, chef médiatisé par l’émission populaire « Top Chef » a avoué avoir pleuré à la suite de la perte de sa deuxième étoile dans son restaurant de Toulouse. Le chef excentrique Marc Veyrat a été l’un des premiers à subir une rétrogradation de trois à deux étoiles en 2019 qui l’a plongé dans une dépression nerveuse pendant plus d’un an. Il a même attaqué le guide Michelin en justice à ce sujet. Ces histoires sont malheureusement monnaie courante et l’étreinte psychique du guide Michelin avait même été pointé du doigt par la profession dans une affaire encore plus tragique qui avait ébranlé le monde de la gastronomie française. En 2003, le chef triplement étoilé Bernard Loiseau mettait fin à ses jours à l’aide d’un fusil de chasse alors qu’il était seulement âgé de 52 ans. Atteint de bipolarité, il n’aurait plus supporté la pression médiatique à son encontre, alimentée indirectement par la quantification du Guide Michelin. 

  Lorsque l’addition des étoiles Michelin devient trop salée et les coups psychologiques du Guide Rouge trop lourds à encaisser, certains chefs préfèrent se marginaliser pour prendre un nouveau départ. Le chef Alain Senderens en est l’exemple parfait. En 2005, pour s’émanciper de la pression, redynamiser sa créativité culinaire et rendre la gastronomie plus accessible, il « rend volontairement » ses trois étoiles obtenues dans la cuisine de son restaurant Lucas Carton devenu une véritable institution à Paris. Fini le luxe et les problèmes d’étiquette, fini le loup à la sauce au caviar ou la poularde de Bresse. La qualité de la cuisine redevient l’unique préoccupation de son nouveau restaurant qui a pour seule devise « Faire toujours aussi bon mais bien moins cher ! » Avec ce choix, Alain Senderens s’est lancé un grand défi créatif mais il a aussi pris un risque important en s’éloignant du Guide Michelin, juge de paix de la renommée des cuisiniers. Pourtant le jeu en valait la chandelle car un an plus tard, le « Senderens » tourne à plein régime. Avec des assiettes passées de 400 à 100 euros par personne, il attire plus de clients, fait plus de couverts, pour une meilleure de rentabilité et moins de pression psychologique. Le chef avait trouvé la nouvelle recette du succès. Ironie du sort, le Guide Michelin lui a attribué 2 étoiles pour sa nouvelle formule. La décision et la réussite d’Alain Senderens qui s’est éloigné des sentiers battus par le guide rouge viennent remettre en question la quantification étoilée au sujet de laquelle l’intéressé fait même quelques suggestions de modifications : 

  « Voici ce que je ferais : je garde la couleur rouge, je change la typographie et je revois les symboles. Je conserve bien sûr les trois macarons mais je distingue plusieurs dimensions dans la notation. Le luxe du restaurant n’a rien à voir avec la cuisine ; je les sépare. (…) Il faut un sigle spécifique pour la qualité de la cave, comme il en faut un pour le décor, la cuisine et l’assiette, le service. »

  Il conclue ensuite avec des mots pleins de sens qui souligne l’importance historique du Guide Michelin tout en soulevant les enjeux et la complexité de la quantification d’un objet culturel comme la gastronomie :  

  « C’est grâce au Michelin que la gastronomie française est ce qu’elle est. Il a été un véritable moteur pour nous. Aujourd’hui, je n’ai rien contre le Michelin – et je n’ai pas fait cela contre lui – mais je pense que nous sommes à la fin d’une civilisation, au début d’une autre, en ayant encore les mots et la culture d’hier pour penser demain. Tant mieux si ma décision peut faire évoluer les choses ».


# 4-L'évolution du guide à l'heure du numérique

L'Expansion Internationale et les partenariats commerciaux :

Pour continuer, nous nous sommes intéressés aux évolutions du guide Michelin, aux tendances qu’il adopte pour rester un outil de référence, en particulier lorsque sa place de prescripteur et de référence peut être perçue comme menacée par le numérique. Tout d’abord, nous avons identifié que le guide Michelin est clairement toujours dans une posture de développement international et est pleinement intégré à la galaxie du grand groupe Michelin. Ce fut vrai au cours de son histoire, comme nous l’avons vu précédemment, et cela reste d’actualité. Le directeur du guide, Gwendal Poullennec, dans un article pour les Annales des Mines, nous dit ainsi que l'expansion du Guide Michelin au Japon, se situe dans une stratégie, capitalisant sur la renommée mondiale de la marque Michelin. Cette crédibilité initiale est ce qui a permis d’établir rapidement la notoriété du guide dans une société japonaise pourtant réticente aux évaluations subjectives. La rapide appropriation du guide par les professionnels et le grand public démontre son impact culturel significatif. Le guide Michelin pour la ville fut en effet un succès d’édition avec 90 000 ventes recensées le jour de sa sortie. 

En parallèle, le guide a établi des partenariats stratégiques avec d'autres marques, cherchant à étendre son influence et à apporter son image d'excellence à des domaines connexes. En effet, en 2018, le Groupe Michelin a lancé une gamme d'ustensiles de cuisine en partenariat avec le groupe majeur de mercerie en France : FDG Group. Les partenariats commerciaux établis avec le guide sont nombreux et sont recensés sur son site internet : Président, San Pellegrino, Petrossian sont des entreprises partenaires du guide auxquelles celui-ci apporte son image d’excellence. 

L'adaptation au Numérique :

Ces partenariats peuvent être identifiés comme d’autant plus stratégiques, lorsqu’ils portent sur les nouveaux enjeux du numérique. Ainsi, le Guide Michelin, émergé au début du XXe siècle, s'adapte aujourd’hui aux enjeux contemporains du numérique et aux évolutions socioculturelles. La diffusion du guide imprimé a connu un déclin significatif, passant de 600 000 exemplaires en 1999 à 150 000 dans les années 2000, reflétant les nouvelles habitudes de consommation axées sur les critiques en ligne.  Pour vivre et continuer de se développer, le guide Michelin doit évoluer et s’adapter au numérique. 

a) De nouveaux indicateurs…

Les étoiles ne sont plus ainsi plus les seuls indicateurs, avec l'introduction du Bib'Gourmand en 1997 et de l'étoile verte en 2020. Cette dernière marque la volonté de mettre en lumière les établissements engagés dans des pratiques durables, encourageant ainsi la responsabilité écologique au sein de l'industrie de la restauration. Le Bib'Gourmand, quant à lui, récompense un excellent rapport qualité-prix. Il traduit la volonté du Guide Michelin de s'écarter de l'image d'un guide exclusivement orienté vers la haute gastronomie, caractérisée par des prix élevés et un public plus restreint. Ces codes se rapprochent de ceux établis par d’autres guides moins prestigieux, mais qui adoptent d’autres formes de signalisation et de curation. 
En effet, les auteurs Beauvisag, Beuscart, Mellet et  Trespeuch, parlent d’un véritable élitisme du Guide Michelin qui structure le marché en valorisant les restaurants. gastronomiques. L'échelle de qualité du guide est orientée vers la haute gastronomie et valorise les restaurants les plus prestigieux.  À l’inverse, certains guides, comme Le Guide du Routard, élargissent le marché en ciblant un public moins fortuné et introduisant des contraintes budgétaires. Une pluralisation des critères d'évaluation émerge, remettant en question l'échelle de valeur unique. Un autre exemple, est le guide Zagat qui élimine simplement la figure de l'expert, en confiant l'évaluation à des critiques amateurs. Le guide Le Fooding a pour ligne directrice de mettre en avant la diversité culinaire. Ces nouvelles formes de classification viennent ainsi questionner le guide.

b) … pour s’adapter aux enjeux du numérique

L'intégration de ces formes d'évaluation vise ainsi à répondre aux nouvelles attentes des consommateurs en termes de curations. Sur le site web du Guide Michelin, des filtres facilitent la sélection des restaurants, ce filtrage est d’autant plus essentiel que le nombre de restaurants référencés est grand : 16 850, à la date du 4 novembre 2023. Les codes des leaders du conseil en hôtellerie-restauration se retrouvent ici. Il est en effet possible de voir que les standards établis par les leaders du marché comme Tripadvisor ont été en partie intégré et adopté par le site web du guide Michelin. Ainsi, le guide Michelin offre la capacité de filtrer, notamment par prix, de bon marché aux restaurants les plus onéreux. Il permet d’avoir des favoris et de se faire un compte en ligne. Une application existe également. Il est possible de visualiser la localisation des restaurants, des recommandations sont proposées en fonction du type de restaurants précédemment visités ou de la localisation. 

Toutefois, des différences sont notables, qui permettent au guide Michelin de se différencier, le texte de Vincent Cardon examine ainsi la manière dont TripAdvisor traite les contributions des utilisateurs, en mettant en évidence l'importance des métriques telles que la note globale et la position dans le classement. Malgré la possibilité d'explorer des niveaux d'agrégation variés, l'évaluation des internautes sur TripAdvisor se révèle très hétérogène, tant au niveau du lexique que des rhétoriques utilisées. Le texte souligne que la note prévaut dans l'organisation de l'information, mais elle renvoie à des modes d'évaluation et des registres de qualité différents en fonction de celui qui la laisse. À l’inverse, le guide Michelin ne possède pas d’expérience communautaire étant donné que seul l’avis du guide est indiqué. L’esthétique adopté par le site web est également beaucoup plus sobre que celle de Tripadvisor, pour renvoyer une nouvelle fois une image de distinction. Le seul commentaire est celui du guide Michelin qui montre que celui-ci n’a pas abandonné son rôle de prescripteur et 
Tous ces éléments nous montrent l’adaptation interne du guide pour suivre les évolutions et se détacher du papier. Ils sont d’autant plus importants à souligner que le Guide Michelin, TripAdvisor et TheFork ont établi un partenariat stratégique en 2019. Dans le cadre de cette collaboration, tous les restaurants sélectionnés par le Guide Michelin sont clairement identifiés sur les plateformes de TripAdvisor et TheFork, offrant ainsi une accessibilité accrue à la sélection Michelin. En outre, Michelin vend à Booktable, un service de réservation de restaurant en ligne, précédemment acheté en 2016, à TheFork. Cette collaboration vise à accroître la visibilité des chefs et des restaurants du Guide Michelin, tout en favorisant les réservations grâce aux principales plateformes de réservation en ligne. Le site web du guide Michelin apparaît également comme pleinement intégré au groupe Michelin. Le Bibendum, image emblématique de la marque, est bien mis en avant et si le guide met en avant ses partenariats avec d’autres marques, il revoit également vers les autres activités du groupe Michelin, en particulier ViaMichelin et les pneus Michelin, toujours complémentaire de l’activité de recommandations de restaurants. Le guide Michelin est ainsi toujours un instrument de promotion de la marque Michelin, pour mettre en avant une image d’excellence et s’intégrer dans une stratégie plus globale autour du voyage et de la route. 


**Bibliographie**

Bonnet, E. (2004). Les critiques gastronomiques : quelques caractéristiques d’une activité experte. Sociétés contemporaines, 53(1), 135. https://doi.org/10.3917/soco.053.0135

Drucker-Godard, C., Bouty, I. & Gomez, M. (2011). De la France au monde: Le Guide Michelin, vecteur du rayonnement de la marque France ?. Revue française de gestion, 218-219, 53-66. https://www.cairn.info/revue—2011-9-page-53.htm.

Karpik, L. (2000). Le guide rouge Michelin. Sociologie Du Travail, 42(3), 369‑389. https://doi.org/10.4000/sdt.36855

Le guide MICHELIN - le site officiel. (s. d.). MICHELIN Guide. https://guide.michelin.com/fr/fr

Poullennec, G. (2011). Le guide Michelin : une référence mondiale de la gastronomie locale. Dans Le guide Michelin : une référence mondiale de la gastronomie locale.

Poullennec, G. (2016). Les raisons de la réussite du guide Michelin au Japon. Monde chinois, 47(3), 52. https://doi.org/10.3917/mochi.047.0052

Senderens, A. (2007). La créativité sans les étoiles. Journal de l’Ecole de Paris du management, 63(1), 31. https://doi.org/10.3917/jepam.063.031


# Athénaïs HUET, Samir AKLI, Roméo Bernhart et Vianney Menard


