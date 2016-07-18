
<!-- TOC depthFrom:1 depthTo:6 withLinks:1 updateOnSave:1 orderedList:0 -->

- [Traitements de texte](#traitements-de-texte)
	- [Vidéo 0 - Avant de démarrer](#vido-0-avant-de-dmarrer)
	- [Interface](#interface)
	- [La saisie](#la-saisie)
		- [Repérer les composants du texte](#reprer-les-composants-du-texte)
		- [Respecter des règles de base](#respecter-des-rgles-de-base)
	- [Vidéo 1 - Saisie des éléments de base](#vido-1-saisie-des-lments-de-base)
	- [Vidéo 2 - structurer son document](#vido-2-structurer-son-document)
	- [Vidéo 3 - Personnaliser les styles](#vido-3-personnaliser-les-styles)
	- [Vidéo 4 - insertions](#vido-4-insertions)
	- [Vidéos 5 - TOC](#vidos-5-toc)
	- [Video 6 - métadonnées](#video-6-mtadonnes)
	- [Vidéo 7 -](#vido-7-)

<!-- /TOC -->
# Traitements de texte

## Vidéo 0 - Avant de démarrer

Il existe de nombreux logiciels de traitement de textes et trois d'entre eux sont particulièrement répandus :
- `Microsoft Word` de la suite `Office`
- `Writer` de la suite `LibreOffice`
- `Writer` de la suite `OpenOffice`

Tous ces logiciels ont le même objectif et donc les mêmes capacités de traitement (appelées fonctionnalités). Ils présentent de petites différences d'interface en fonction des versions et des systèmes d'exploitation des ordinateurs. Notre objectif n'est pas de les présenter tous, ni même de présenter tout ce dont ils sont capables. Ce que nous voulons que vous reteniez et que vous maîtrisiez est très général et ne dépend pas d'un logiciel en particulier.

Chacun d'entre vous pourra faire les exercices avec le logiciel de son choix à condition de respecter un format de fichier interopérable.

En effet, le choix du logiciel est en fait beaucoup moins important que le format de fichier utilisé. Aujourd'hui 2 grands formats se font concurrence :
- le format `.odt`(*Open Document Text*) qui est un standard ouvert développé pour l'interopérabilité. Il n'est pas développé par une société particulière mais par un consortium international[^1]. 
- le format `.docx` qui est la réponse apportée par `Microsoft` au format `.odt`.
La plupart des logiciels récents savent manipuler (ouvrir et enregister) des fichiers dans les 2 formats.

Notons qu'il reste encore beaucoup de vielles versions de `Word` qui qui ne savent gérer que des fichiers au format `.doc`. Ce format est propriétaire, fermé, pas du tout interopérable et il est devenu obsolète, nous déconseillons vivement son utilisation.

Nous avons choisi d'utiliser :
- le format `.odt` pour l'enregistrement des fichiers
- le logiciel `LibreOffice` pour sa faciliter d'utilisation et la possibilité pour chacun de l'installer gratuitement et librement sur sa machine.

## Objectifs de ce cours
Toutes les interfaces de logiciels de traitement de texte se ressemblent. Nous trouvons au centre une grande zone représentant une page, en haut les menus et une zone de boutons-raccourcis. La forme, les dessins, les couleurs des boutons et des menus varient d'une version à une autre, d'une machine à une autre mais les fonctionnalités sont globalement les mêmes. Le **premier objectif** est la découverte de ces fonctionnalités générales, communes à tous les logiciels, mais qui permettent de comprendre ce qu'est un document numérique, et prendre le recul sur l'usage. 

Notons que tous les logiciels de ce type utilisent un abus de langage en parlant d'outils de styles car ce sont avant tout des outils qui permettent de structurer et de hiérarchiser le document. La mise en forme associée à ces styles introduit de la confusion dans les différentes vues. En premier lieu, les *styles* sont utilisés pour définir les niveaux de titres et de sous-titres pour déclarer la **structure** du document, les aspects de mise en forme liés à la vue de présentation seront également traités avec cet outil d'où la confusion.

Notons dès à présent que les boutons raccourcis qui sont en bonne place et prêts à être utilisés sont réservés à réaliser de la mise en forme directe. C'est une mise en forme au cas par cas et qui ne privilégie pas la définition de **règles de mise en forme** comme le permettent les définitions de style. Vous savez tous réaliser une mise en forme au cas par cas à l'aide ces boutons. Ce n'est donc pas l'objet de ce cours. Vous savez moins réaliser des règles et c'est précisément sur ce point que porte le **second objectif** de ce cours. Rappelez-vous que les règles de mise en forme sont essentielles pour la manipulation de grands documents et le travail en groupe. Elles permettent d'uniformiser la présentation et appliquer des thèmes ou une charte graphique. Mais puisqu'elles reposent sur la structuration du document, elles permettent d'initier de bonnes pratiques de déclaration de cette structure. Ainsi d'autres traitements permettant de *valoriser des corpus de documents* peuvent s'appliquer, comme par exemple la recherche et l'indexation d'information... 

## La saisie

La saisie est une fonctionnalité fondamentale. Elle dépend de nombreux paramètres dont la langue, des dispositifs techniques de saisie et des aides logicielles à la saisie. 

Dans certaines langues, l'ordre d'écriture est de gauche à droite dans d'autres de droite à gauche. La langue définit les caractères, symboles graphiques utilisés, la nature des mots, les règles typographiques, etc. Les documents peuvent être multilingues. Nous nous focalisons ici sur le français.

Les dispositifs techniques influencent la saisie. Le clavier reste le plus répandu, mais se développent aujourd'hui des acquisitions par la voix.  Sur de petits équipements, on pallie l'absence de clavier par des assistances logicielles qui complètent les mots, prévoient le prochain mot etc.

L'assistance logicielle, c'est justement l'ensemble de ces fonctionnalités qui permettent de corriger la frappe, les fautes d'orthographe, compléter ou suggérer les mots, remplacer des abréviations, etc.


### Repérer les composants du texte

Les **caractères**. La plupart sont visibles, mais certains sont invisibles en particulier les espaces. Certains caractères sont aussi interprétés par le logiciel comme une commande ou une déclaration, c'est par exemple le caractère qui marque la la fin de paragraphe, ou ceux qui marquent la fin d'un mot (espace[^2] ou ponctuation), celui qui ajoute une espace insécable (c'est-à-dire qui force à afficher les symboles à sa droite et à sa gauche sur une même ligne. C'est là une première difficulté, l'espace par exemple a plusieurs fonctions. Ajouter une espace typographique entre deux mots dans un soucis de présentation du document. Mais l'espace déclare également la séparation de deux mots. Dans la première fonction, on pourrait vouloir augmenter cette séparation dans le rendu visuel et donc se faire suivre deux espaces. Mais on perd le sens de la deuxième fonction puisqu'il n'y a pas de mot entre ces deux espaces. La convention qui est choisie est de ne pas se faire suivre deux espaces et faire confiance au logiciel pour réaliser la meilleure présentation. Lorsque deux ou plusieurs espaces sont saisis, les fonctions du traitement de texte qui proposent une bonne présentation sont mises en difficulté, car les conventions de saisie ne sont pas respectées. Le même raisonnement s'applique pour les paragraphes. 

Donc, visualiser tous les caractères, y compris ceux qui sont invisibles peut être intéressant pour bien comprendre ce qui a été saisi.

Les **mots**. Ils sont séparés par des espaces ou des signes de ponctuation. Certaines règles typographiques définissent l'espace qui doit être placé entre les mots, les symboles de ponctuation, les coupures de ligne. Ces règles sont propres à la langue, par exemple en français une espace précède le signe :, mais pas en anglais. 

Les **paragraphes**.  Ce sont des ensembles de mots séparés par des *fins de paragraphes* créés par l'appui sur la touche *Entrée*. La fin de ligne est calculée par le traitement de texte et donc la touche entrée ne marque pas la fin de ligne. Il est parfois nécessaire de forcer une fin de ligne dans certains paragraphes comme les poèmes. C'est la combinaison de Majuscule-Entrée qui permet de réaliser une fin de ligne tout en gardant le même paragraphe. Puisque chaque appui sur la touche *Entrée* crée un nouveau paragraphe, les titres et les sous-titres sont donc techniquement des paragraphes comme les paragraphes de texte. Comme indiqué ci-dessus, on évite à tout prix les paragraphes vides qui mettent en défaut de nombreuses fonctions du traitement de textes.

**Les titres**. Ce sont bien des paragraphes, mais le logiciel de traitement de texte permet de les déclarer comme titres en précisant leur niveau. Le niveau est la profondeur une hiérarchie titre (niveau 1), sous-titre (niveau 2), sous-sous-titre (niveau 3), etc. 

Les **listes**.  C'est une suite d'éléments reliés entre eux pour permettre une présentation cohérente. Pour assurer cette cohérence, beaucoup de caractéristiques sont définies sous forme de règles afin que le logiciel règle l'apparence des listes. C'est notamment les symboles utilisés pour les listes à puce, les espacements, la numérotation des éléments, etc. La logique est donc de déclarer la liste et laisser la machine régler l'apparence avec les règles de mise en forme que vous indiquez. 

Repérer les composants du texte permet de comprendre la structure d'un document, saisir à la fois le contenu et la structure d'un document et se préparer pour une mise en forme efficace et uniforme du document. 

[La saisie](https://owncloud.univ-lille3.fr/index.php/s/OKse8csySXs2GKL){: .lien_video }

[La saisie - Suite](https://owncloud.univ-lille3.fr/index.php/s/HjIIMzOYVPuYmsh){: .lien_video }


```activité
Reproduire l'exemple en vidéo.
{
#### On saisit le titre, puis on le déclare comme titre principal.  On saisit le sous titre, puis le titre de niveau 1,  et les premières phrases du premier paragraphe. On remarque que le paragraphe suivant est automatiquement en corps de texte. On remarque aussi l'assistance à la saisie qui a souligné un mot mal orthographié ou qui a proposé le mot en cours de saisie. On remarque également que les mots ont été identifiés car ils sont automatiquement sélectionnés lors de la correction orthographique. On a également la possibilité de se déplacer de mot en mot avec CTRL-droite ou gauche et de supprimer un mot avec CTRL-Retour arrière. Dans un premier temps, nous laissons la présentation par défaut. 
L'assistance à la saisie effectue des remplacements automatiques : elle a mis en majuscule le mot juste après le point, elle a inséré automatiquement un espace insécable.}
```

### Respecter des règles de base
Lorsqu'on récupère un texte à mettre en forme ou qu'on commence à saisir un nouveau texte, il est important de respecter scrupuleusement quelques règles élémentaires qui vont nous permettre à la fois de gagner beaucoup de temps et par ailleurs d'avoir un gage de qualité du résultat. L'élégance du document, sa valorisation, sa réutilisabilité, et votre efficacité pour toutes les opérations de mise à jour et transformation du document seront autant d'illustration de cette qualité. Si nous sommes les seuls responsables du contenu de notre texte, qualité du fond, de la structure, du niveau de langue et de l'orthographe, il vaut mieux laisser au logiciel le travail de mise en forme pour la vue de présentation. Les traitements automatiques sont en général de bien meilleure qualité qu'un travail *à la main*. Cela ne veut pas dire que nous ne pouvons pas choisir la forme du résultat, bien au contraire.
Voici 5 règles fondamentales :
- L'espace sépare les mots. On ne doit donc pas saisir plusieurs espaces l'une derrière l'autre.
- La touche entrée sépare les paragraphes. On ne doit donc pas saisir deux *fins de paragraphes* l'une derrière l'autre, c'est à dire aucune ligne vide. 
- Les interlignes, l'espace entre paragraphes, l'aération du texte, les alinéas, les marges, les décalages, les alignements sont bien mieux gérées par les outils de mise en forme.
- Éviter autant que possible la mise en forme directe au cas par cas, que ce soit par les menus (format) ou par les boutons-raccourcis. 
- Ne pas saisir des valeurs qui sont susceptibles de varier et peuvent être générées par le traitement de textes : numérotation des éléments de liste, des chapitres, des pages ; références, table des matières, bibliographies, indexes. Tous ces éléments dépendent du contenu principal du document et seront créés automatiquement par le logiciel grâce à des commandes spécifiques.


## Vidéo 1 - Saisie des éléments de base
- débuter un document, page blanche sans styleur
- saisir au kilomètre, uniquement les fins de paragraphes
- énoncer (voix off) les niveaux de titre sans mise en forme
- faire des fautes, utiliser le correcteur
- titre, sous-titre, titre1, titre2, plusieurs parag de contenu, une liste SANS mise en forme

> Cette vue est essentiellement séquentielle, les seuls éléments de structure présents sont les paragraphes, mais nous avons déjà utilisé le correcteur orthographique.
> Les traitements de texte sont des outils puissants qui proposent beaucoup de fonctionalités pour nous aider dans la rédaction, la conception et la présentation de notre travail. Par exemple les correcteurs orthographiques nous alertent en nous signalant des erreurs probables que nous pouvons corriger. Mais d'autres outils existent et s'appliquent parfois automatiquement, ce qui peut être perturbant. En particulier, il existe des fonctionnalités d'auto-correction qui peuvent s'appliquer pendant la frappe. Ces outils sont puissants, il sont capables de corriger à la volée des erreurs de saisie telles que l'oubli d'une majuscule en début de phrase, ou encore l'insertion d'espace insécable devant les ponctuation double afin de respecter les règles typographiques.
Cet outil est précieux et nous fait gagner du temps tout en amenant de la rigueur. Néanmoins, il faut bien avoir conscience qu'il peut être (dés)activer.
Par exemple il corrige systématiquement les fautes courantes à partir d'une liste, ou insére une majuscule en début de phrase, tous ces comportements sont paramétrés et nous pouvons choisir de les utiliser ou pas, ils sont en général une aide mais peuvent s'avérer gênants dans certains cas particulier, il est alors imortant de savoir comment les désactiver. Nous vous invitons à regarder de près le paramétrage de cet outil afin d'en comprendre le fonctionnement.

- montrer
 - la correction des maj en début de phrase (après point et espace).
 - la correction DOuble majuscule
 - l'insertion espace insécable devant ; (avec affichage des car non imprim)
 - correction d'un mot mal orthographié
- le panneau de config des paramètres
- qu'on peut (dés)activer quand on le veut

- enrigistrer (dossier / fichier / extension-format)

## Vidéo 2 - structurer son document
- reprendre à la fin de vidéo 1
- "On veut maintenant structurer le document"
- repérer la liste déroulante des styles et faire apparaître le styleur
- commencer à styler
"il suffit que le curseur soit placé dans un paragraphe pour que le style s'applique"
- montrer l'équivalence entre les deux outils
- présenter le bouton de liste ((dés)activer puces)
- détailler puce + retrait
> attention placer le texte en "corps de texte" et ne pas laisser style par défaut car tous les styles héritent de style par défaut

- présentation de la création de liste pendant la frappe
(* , - , 1), a), ...) Insister sur l'automatisation  
- enregistrer

## Vidéo 3 - Personnaliser les styles
- reprendre à la fin de vidéo 2
- modifier *corps de texte* pour le justifier, montrer l'héritage et expliquer pourquoi il ne vaut mieux pas utiliser "style par défaut".
- modifier les autres styles, espaces avant/après, couleur, interligne, alignement, enchaînements (veuves/orphelines et solidaires avec suivants)
- enregistrer

## Vidéo 4 - insertions
- insertion d'image
- notes de bas de page
- insertion de lien
- pied de page / entête
- numeros de page / champs

## Vidéos 5 - TOC
- numerotation automatique des chapitres
- génération d'une TOC

## Video 6 - métadonnées
- trouver les stats
- saisir les métadonnées

## Vidéo 7 -
- bibliographie
> surement en plusieurs fois


```activité recherche
comparer les formats odt et docx

décompresser un fichier .odt
```

[^1]: OASIS, dont font partie the Document Foundation qui développe LibreOffice, mais aussi de grands acteurs du logiciel comme Microsoft ou ORACLE, des universités, etc.
[^2]: l'espace en typographie est un nom féminin. 