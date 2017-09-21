---
copyright: 'CC-By-SA 4.0'
robots: 'index, follow'
title: 'Inkscape for Noobs – Part I: The Basics'
viewport: 'width=device-width, initial-scale=1.0'
---

# DAO - Inkscape for Noobs part I: INTRO
  {:.no_toc}
  
Étiez-vous à la recherche d' [Inkscape pour Noobs Part I: INTRO](noobs1_fr.md)? `¯\_(ツ)_/¯`

Étiez-vous à la recherche d' [Inkscape pour Noobs Part II: HANDS-ON](noobs2_fr.md)?

Étiez-vous à la recherche d' [Inkscape pour Noobs Part III: EXERCISE](noobs3_fr.md)?

## Table of Contents
  {:.no_toc}

  * TOC
  {:toc}

---

![](https://filipgoc.github.io/hep-cad/assets/media/noob-imgs/stars.jpg)

<img src="/assets/media/noob-imgs/stars.jpg" width="650" />

<img src="/assets/media/noob-imgs/stars.jpg" width="650" />

![](/assets/media/noob-imgs/stars.jpg)

### Fabrication numérique: nouvelle classe d'art

La fabrication numérique est la nouvelle classe d'art. Les outils qui étaient autrefois chers et disponibles uniquement pour les ingénieurs et les professionnels du design sont maintenant à notre disposition. Les gens ordinaires.

Ceci est habilitant. Nous pouvons créer des objets physiques de haute qualité, professionnels, précis avec facilité. Et ça va bien.

Dans vos nombreux cours ACPR, vous créez des projets ayant des résultats physiques. Vous devez utiliser des imprimantes laser et des imprimantes 3D et des imprimantes jet d'encre ordinaires pour créer des objets.

Au rez-de-chaussée en HEP, nous avons une lasercutter, des imprimantes 3D, des coupeurs de vinyle et plus encore. Mais ce ne sont que des outils contrôlés par ordinateur et, par conséquent, ils ont besoin d'instructions très précises.

Les outils 2D ont besoin d'instructions 2D, et c'est ce que nous faisons ici.

### Cette classe

Dans cette classe, ACPR 2.1, nous allons apprendre à utiliser Inkscape pour réaliser des dessins 2D numériques. Formes. C'est tout.

Cette classe s'intéresse au logiciel. Nous allons faire de petits projets, mais ce n'est pas notre objectif principal. Notre objectif est de pouvoir utiliser le logiciel afin que vous puissiez travailler sur les projets pour vos autres classes.

L'année prochaine, dans l'ACPR 3.1, vous aurez une classe similaire à apprendre à créer un fichier numérique en 3D. Modèles 3D.

### Importance de l'autoapprentissage

Cette classe est par NO signifie une formation complète. Cela ne peut pas être.

C'est une introduction axée sur les objectifs, conçue pour vous permettre de faire des choses.

Vous avez probablement besoin d'au moins dix heures avant d'être raisonnablement compétent avec ce logiciel. Nous n'avons pas beaucoup de temps.

Si vous avez besoin d'une compétence, nous ne couvrons pas ou si vous voulez devenir bon, vous devrez faire de l'apprentissage par vous-même. Je vous enverrai une liste de bonnes ressources, mais il est souvent préférable de trouver la vôtre.

À la fin de la journée, googler une vidéo ou un didacticiel sur la façon de faire une chose spécifique peut être la façon la plus authentique d'apprendre. Internet est plein de guides.

## Qu'est-ce qu'Inkscape?

[Inkscape](https://inkscape.org/) est un programme graphique qui peut être utilisé pour créer **des graphiques vectoriels** . C'est **une source ouverte** (c'est-à-dire que tout le monde peut se pencher sur [le code du programme](http://bazaar.launchpad.net/~inkscape.dev/inkscape/trunk/files) ), il est sous **licence gratuite** , ce qui permet à tous de modifier le code du programme, d'utiliser le programme à des fins spécifiques et de le partager avec d'autres, et il est constamment amélioré par une **communauté de développeurs bénévoles engagés**. Beaucoup d'utilisateurs supportent également Inkscape, par exemple en aidant d'autres utilisateurs.

Cela signifie que, contrairement à de nombreux autres programmes informatiques, il n'y a **pas d'entreprise** derrière Inkscape, mais une communauté de bénévoles du monde entier, avec un comité de conseil élu et une organisation parapluie ( [Software Freedom Conservancy](http://sfconservancy.org/) ), qui crée une [loi](http://sfconservancy.org/) judiciaire sécuritaire contexte pour les activités des contributeurs (par exemple, afin de permettre que le projet puisse accepter des dons).

Tous ceux qui contribuent à ce projet fait partie intégrante du **monde entier [communauté Inkscape](https://inkscape.org/community/)** .

## Qu'est-ce qu'un graphique vectoriel?

Les graphiques vectoriels se composent d' **objets** distincts . Ceux-ci sont définis par leurs **propriétés géométriques** , par exemple un cercle par la position de son centre et la taille de son rayon. Pour les lignes courbes, des propriétés spécifiques sont sauvegardées, qui décrivent la position de certains points et la courbure des lignes qui relient ces points les unes aux autres.

<img src="/assets/media/noob-imgs/stars.jpg" width="650" />

<img src="/assets/media/noob-imgs/stars.jpg" width="650" />

![](/assets/media/noob-imgs/stars.jpg)

Les objets dans un graphique vectoriel ont tous un ensemble bien défini **d'attributs** , dont chacun peut être facilement modifié. Cela vous permet de modifier la couleur du remplissage ou de la ligne de contour avec un seul clic sur une couleur complètement différente, pour l'enlever ou même le remplacer par un motif.

**Des exemples de ces attributs** sont: couleur de remplissage, motif de remplissage, remplissage d'un dégradé de couleur, couleur du contour (trame), largeur du contour, motif de contour, type de ligne de contour (p.ex. pointillé, pointillé, ...) ou le type de marqueurs (p. ex. flèches ou autres symboles) utilisés au cours du chemin.

## Une comparaison: Graphique vectoriel par rapport au graphisme de trame

### Always Crisp

<img src="/assets/media/noob-imgs/crisp_vs_pixelated.jpg" width="650" />

Un graphique vectoriel se comporte de manière **très différente de, par exemple, une photo** , qui a été prise avec un appareil photo numérique. Les photos numériques sont **des graphiques raster** , et sont donc constitués d'un grand nombre de points colorés, disposés dans un ordre spécifique (le raster). Lorsque la distance est assez grande, tous ces petits points forment ensemble une image. Mais dès que la photo est agrandie un peu trop, tous ces points simples deviennent visibles - l'image apparaît 'pixelée'.

Étant donné que les graphiques vectoriels sont enregistrés comme instructions pour la construction géométrique des objets qu'ils contiennent (tout comme un ensemble d'affectations de devoir de géométrie), l'ordinateur doit d'abord calculer tous les objets pour pouvoir les afficher sur l'écran.

Lors de la visualisation d'une image vectorielle, peu importe combien vous agrandissez - il ne sera jamais pixelisé. L'ordinateur peut calculer précisément tous les pixels nécessaires pour afficher l'image sur votre moniteur, pour chaque niveau de zoom. C'est pourquoi un graphique vectoriel est **toujours croquant** (sauf si vous ajoutez intentionnellement un flou, bien sûr).

### Facile à changer

<img src="/assets/media/noob-imgs/change.jpg" width="650" />

Par rapport aux graphiques raster, il est très facile de **modifier radicalement** l'apparence d'un graphique vectoriel en modifiant seulement très peu de propriétés (voir image). Dans un graphique raster, pour changer la couleur, vous devriez essentiellement trouver un moyen de peindre sur l'ancienne couleur - comme avec une brosse physique sur une peinture physique.

### Taille de fichier plus petite - plus de travail de calcul

Les graphiques vectoriels - pourvu qu'ils contiennent seulement un nombre raisonnable d'objets - ne nécessitent que **très peu d'espace disque** , car les informations sur les couleurs n'ont pas besoin d'être sauvegardées pour chaque pixel, mais **une** seule **fois par objet** . C'est un avantage pour les images qui sont destinées à être utilisées sur les pages Web, ce qui entraîne une plus petite quantité de données transférées et la page Web à charger rapidement.

D'autre part, il peut prendre plus de temps pour **préparer** des images vectorielles très complexes pour les afficher sur un moniteur.

### Différents types d'images à des fins différentes

Le graphisme et les graphiques vectoriels sont utilisés à des fins différentes qui se **complètent** .

<img src="/assets/media/noob-imgs/photo_raster_und_vektor-o.jpg" width="650" />

**Les images raster** sont utilisées pour les images avec **une grande quantité de contenu irrégulier et de couleur différente** , principalement pour les **photos**. Si nous voulions les sauvegarder dans un format vectoriel, essayer de les rendre sur un moniteur prendrait très longtemps.** Selon la façon dont nous aurions alors besoin de simplifier l'image en raison d'un rendu lent, il y aurait aussi une moindre quantité de couleurs différentes et la qualité serait bien pire.** En plus de cela, au même niveau de qualité d'image, la taille du fichier serait énorme, comme pour chaque couleur qui apparaît dans l'image, il faudrait créer un objet distinct (cela pourrait atteindre jusqu'à 1,9 million d'objets pour une normale Photo de taille 1600x1200 pixels, si chaque pixel avait une couleur différente).

C'est pourquoi les **images vectorielles** sont le plus souvent utilisées pour les **logos, les cliparts, les boutons, les icônes** et autres graphiques, qui sont constitués de **grandes zones cohérentes de couleur unique** ou peuvent facilement être divisés en **objets uniques** . Bien sûr, en fonction du sujet du dessin, il est également possible de créer des dessins de recherche très réalistes, qui créent l'impression de profondeur 3D par l'utilisation habile des gradients de couleurs.

Donc, avant de sauter directement dans Inkscape pour créer l'image de vos rêves, vous devriez d'abord penser si Inkscape est l' **outil approprié pour la tâche** . Si votre objectif est de modifier une photo ou de dessiner une grande image réaliste comme vous le feriez avec un pinceau sur toile, il existe un autre logiciel qui convient (par exemple, [The Gimp](http://gimp.org) pour éditer des photos ou [Krita](http://krita.org/) pour dessiner des tableaux numériques en utilisant différents pinceaux. Les deux sont - comme Inkscape - projets open source.).

## Qu'est-ce que SVG?

SVG est un **format de fichier pour les graphiques vectoriels** . L'abréviation signifie "Scalable Vector Graphics" - images redimensionnables qui sont constituées de données vectorielles. Inkscape utilise ce format de fichier car il s'agit d'un **standard ouvert** , de sorte que les fichiers que vous créez avec Inkscape peuvent être **utilisés universellement** . Les navigateurs Web, par exemple Mozilla Firefox, Google Chrome ou Microsoft Edge, mais aussi beaucoup d'autres programmes, prennent en charge cette norme.

Cela offre l'avantage que les images que vous avez créées dans Inkscape ne sont pas «perdues» lorsque Inkscape n'est pas disponible. Dans la plupart des cas, ces images peuvent, par exemple, être **intégrées directement dans une page Web** sans avoir besoin de modifier, ou d' **autres programmes** (par exemple, une suite bureautique ou un programme de publication assistée par ordinateur) peuvent ouvrir les fichiers et vous pouvez continuer à Modifiez-les là-bas.

L'organisation qui définit la norme svg, est le **\[World Wide Web Consortium [W3C](http://www.w3.org/)** - cette même organisation qui fonctionne également sur les normes HTML ou CSS (les langues utilisées pour écrire et concevoir des pages Web).

L'un des développeurs Inkscape est membre du groupe de travail SVG du W3C. Là, il représente Inkscape et ses intérêts et aide à améliorer encore plus le standard SVG.

### Éléments basiques

<img src="/assets/media/noob-imgs/elements.jpg" width="650" />

Le format de fichier SVG prend en charge un certain nombre d' **éléments** de **base** , à partir desquels des images peuvent être construites. Il s'agit, entre autres , de **lignes droites** , de **polylignes** (constituées de plusieurs lignes droites reliées l'une à l'autre), des **chemins** (composés d'une ou plusieurs lignes courbes), des **cercles** , des **ellipses** , des **rectangles** , des **polygones** , des **textes** , **des graphiques raster** (oui, ceux-ci peuvent également être utilisés à l'intérieur d'un \[SVG\]!) et des **copies d'autres objets** (le même objet est utilisé plusieurs fois dans le dessin, mais seul l'original peut être modifié de manière substantielle).

> Inkscape n'utilise pas tous les éléments disponibles - par exemple, des lignes droites ou des polygones sont également enregistrés sous forme de «chemins d'accès». En échange, Inkscape propose des éléments supplémentaires. Par exemple, il y a des étoiles et des spirales - qui sont enregistrées en deux formats en parallèle par Inkscape: d'abord comme un chemin d'accès normal (pour permettre à d'autres programmes de les lire correctement), d'autre part comme une étoile / spirale avec des propriétés spécifiques (longueur de Astuces, nombre de tours en spirale, etc., qui permet de modifier ces propriétés en quelques clics de souris).

### Ordre d'empilement

Les objets dans une image SVG sont empilés les uns sur les autres dans un **ordre** spécifique - tout comme dans un collage, par exemple. C'est pourquoi il est possible qu'il y ait des objets dans votre dessin complètement **cachés** par un autre objet (voir image).

Même s'il peut sembler que deux objets se trouvent juste à côté l'un de l'autre, chacun d'entre eux «sait» exactement à quel **niveau dans l'ordre d'empilement** il est actuellement. Un objet ne peut jamais être en même temps **au**** - **dessus** ***et*** **au** ***-*** **dessous d'** un autre objet (pensez à une boucle dans un noeud). Si vous souhaitez dessiner quelque chose comme ça, vous devez composer l'objet à **partir de plusieurs parties** , qui peuvent ensuite être placées au-dessus et en dessous de l'autre objet.

L'animation montre comment un objet qui a d'abord été recouvert par d'autres objets devient visible lorsque les autres objets sont éloignés et que l'ordre d'empilement est conservé même après avoir arraché les objets.

Bien sûr, vous pouvez modifier l'ordre d'empilement dans Inkscape. Les objets nouvellement créés sont toujours placés en haut.

### Texte brut / structure arborescente

Et à quoi ressemble une image SVG maintenant?

Comme ça:

<img src="/assets/media/noob-imgs/svgcode-rect.svg" width="650" />

Ou, dans un éditeur de texte, la même image ressemblera à ceci:

*(Ne plaisante pas. Ce code ci-dessous rend effectivement ce rectangle. Notez que j'ai supprimé manuellement toutes sortes de métadonnées et d'informations utiles, mais cela fonctionne toujours. Simple.)*

```
<svg
  xmlns="http://www.w3.org/2000/svg"
  xmlns:inkscape="http://www.inkscape.org/namespaces/inkscape" >

  <rect
  style="opacity:1;vector-effect:none;fill:#3465a4;fill-opacity:0.96832581;fill-rule:evenodd;stroke:none;stroke-width:0.238125;stroke-linecap:round;stroke-linejoin:round;stroke-miterlimit:4;stroke-dasharray:none;stroke-dashoffset:0;stroke-opacity:1"
  id="rect44547"
  width="103.70058"
  height="42.763123"
  x="78.042702"
  y="45.766644"
  rx="0.20325899"
  ry="0.20325899" />
</svg>
```

Tout le monde qui a déjà regardé le **code source d'une page Web** reconnaîtra probablement la structure du fichier - la raison pour laquelle les deux types de fichiers, HTML et SVG sont fondés sur **XML** . Il s'agit d'un langage de balisage, qui a une **structure en forme d'arbre** (éléments imbriqués l'un dans l'autre) et où chaque élément commence `<something>`et se termine avec `</something>`- ou il peut également ressembler `<something and-a-long-list-of-properties />`, lorsqu'il n'a plus de contenu, mais seulement Propriétés.

L'avantage de ce type de formatage est qu'il peut être lu raisonnablement bien **à la fois par un ordinateur et un humain** (comme la langue SVG utilise les noms anglais, vous devriez pouvoir lire l'anglais, cependant). Vous avez probablement réalisé à l'heure actuelle qui `<rect...`définit un rectangle et ses propriétés.

Il peut être facilement édité **automatiquement** par différents types de programmes. Cela permet, par exemple, d' échanger **rapidement et de façon programmée** des noms dans les passages de visiteurs ou des numéros dans les tickets d'entrée que vous souhaitez imprimer. Il existe une foule de petits programmes auxiliaires qui peuvent vous accompagner dans une telle tâche.

Il est également possible de faire de petits changements à la main dans un tel fichier, par exemple, pour le préparer à faire des animations.

Pourtant, la plupart des gens préfèrent probablement éditer leurs dessins à **l'** aide de **la souris ou d'une tablette graphique** , afin qu'ils puissent voir tout de suite comment leur image change - et c'est ce que vous pouvez utiliser **Inkscape** pour;)

## Exemples

Pour vous donner une petite impression de ce genre d'images possibles avec Inkscape, ci-dessous, il y a un ensemble d' **exemples** pour vous. Si vous êtes curieux de voir plus d'informations, vous devez absolument visiter la **[galerie avec des dessins réalisés par des utilisateurs d'Inkscape](https://inkscape.org/gallery/)** sur le site Inkscape et consulter un peu dans la **[bibliothèque OpenClipart](https://openclipart.org/)** . En particulier, ce dernier offre une excellente occasion d' **apprendre des autres utilisateurs** , en téléchargeant les images et en les **"disséquant" dans Inkscape** , pour savoir comment créer des effets spécifiques.

### Objets simples

<img src="/assets/media/noob-imgs/things.jpg" width="650" />

### Boutons et icônes avec gradients de couleur

<img src="/assets/media/noob-imgs/things2.jpg" width="650" />

### Dessins complexes avec l'ombrage principalement naturel

<img src="/assets/media/noob-imgs/things4.jpg" width="650" />

### Animations

Des applications telles que [sozi](http://sozi.baierouge.fr/) , les extensions Inkscape comme JessyInk ou différentes bibliothèques JavaScript permettent de créer des **animations** ou des **présentations** , qui peuvent être visualisées à l'aide d'un navigateur Web. Les langages de balisage **CSS** et **SMIL** peuvent également être utilisés pour animer des images SVG. Une introduction à ce sujet peut être trouvée [sur le site Inkscape](https://inkscape.org/en/learn/animation/) .

*Merci à [Jordan Wade de CodeSchool d'](https://www.codeschool.com/blog/2014/11/04/inline-svg-animations/) avoir animé ce logo svg pour nous.*

### Plotters, Cutters and Co.

Il y a beaucoup de gens qui n'utilisent pas Inkscape pour créer de beaux graphismes, mais pour moudre, couper automatiquement, peindre, etc. **des objets physiques** . Par exemple, vous pouvez utiliser Inkscape (avec une extension Inkscape) pour contrôler **les appareils de coupe de film** ou pour graver des **décorations dans du bois à l'aide d'un laser** . C'est aussi un excellent outil à utiliser pour **peindre des oeufs**  ;-)

## Pouvons-nous enfin commencer maintenant?

Dans cet article, nous avons jeté les **bases** de la compréhension des graphiques vectoriels. Ceux-ci vous aideront à ne pas être confondus avec les différences par rapport aux graphiques / édition photo rares familiers lorsque vous travaillez dans Inkscape.

À l'étape suivante, vous devez **installer** Inkscape sur votre ordinateur. La **version actuelle** pour **Windows** et **Mac OS** peut être téléchargée gratuitement [sur le site Web Inkscape](https://inkscape.org/download/) . Pour les **distributions Linux** , le site Web offre le [code source](https://inkscape.org/download/) , et il existe une [ppa](https://launchpad.net/~inkscape.dev/+archive/ubuntu/stable) pour Ubuntu et ses dérivées dans le launchpad.

> Si vous rencontrez des problèmes lors de l'installation, vous devez d'abord lire à nouveau les instructions sur la page de téléchargement. Si cela ne vous aide pas, et une recherche sur Internet ne renvoie pas d'informations utiles, vous pouvez demander de l'aide dans un [forum Inkscape](https://inkscape.org/community/) , dans la section [Chat](https://inkscape.org/community/) ou dans la [section des réponses](https://answers.launchpad.net/inkscape) à la barre de lancement.

------------------------------------------------------------------------

Après avoir terminé l'installation, nous nous reverrons volontiers pour la **[Partie II - Pratique](noobs2_fr.md)**.

------------------------------------------------------------------------

## Licence

Ce travail est sous licence [Creative Commons Attribution-ShareAlike 4.0](http://creativecommons.org/licenses/by-sa/4.0/) License. Vous pouvez **partager** et **adapter** le contenu, pourvu que vous publiez le résultat **sous la même licence** et que vous obteniez **un crédit approprié** .

[![Petit coeur avec le logo inkscape, ruban d'or CC-By-SA, Martin Owens et Andy Fitzsimon](http://vektorrascheln.de/theme/images/icons/inkscape-donate-icon-64.png)](https://inkscape.org/support-us/donate/)

Si vous souhaitez utiliser **Inkscape** et que vous souhaitez prendre en charge le développement du programme, envisagez [de devenir un membre actif](https://inkscape.org/contribute/) de la communauté Inkscape ou [faire un don](https://inkscape.org/support-us/) . Votre effort aidera à rendre Inkscape **encore plus génial** !

<span class="site-footer-owner">[hep-cad a](http://github.com/filipgoc/hep-cad) été créé et est géré par filipgoc. </span> <span class="site-footer-credits">Cette page a été générée par [GitHub Pages](https://pages.github.com) .</span>
