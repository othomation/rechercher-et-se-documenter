# Rechercher, se documenter.
-  Les recherches sont faites en anglais.
-  Les recherches dont la capture d'écran est fournie sont toutes, systématiquement, effectuées en navigation privée, sans cache, pour ne pas tronquer les résultats. C'est normalement le même résultat, peu importe la machine ou l'historique d'utilisation de votre navigateur, sur une même tranche horaire et une même langue.
- Vous êtes invités à tester au fur et à mesure du cours, des captures d'écrans n'étant par systématiquement faites, pour une question de lisibilité.
- Vous pouvez contribuer à ce cours en effectuant une [Pull Request](https://github.com/othomation/rechercher-et-se-documenter/pulls) ou en ouvrant une [Issue](https://github.com/othomation/rechercher-et-se-documenter/issues).

## RECHERCHER 

### Introduction
Retenir des choses, c'est **dur**. 
Ça l'est davantage lorsqu'on essaye de le faire volontairement, c'est à dire dans le cadre d'un effort, conscient, de mémorisation et d'intégration de telle ou telle bribe d'information.

La **pratique**, elle, permet de rendre la mémorisation plus innée, plus fluide.
Cependant, cela reste encore **compliqué** et **ardu** de l'intégrer dans notre _flux de travail_ au quotidien.

Retenir des choses, ça **prends de la place** dans notre cerveau.
Cette place là, on pourrait l'utiliser pour autre chose, par exemple pour nos idées, nos questions, nos dynamiques d'architecture et de pensée de manière générale.

Le chemin **vers** l'information, lui, peut s'**apprendre**, mais surtout se **comprendre**.

Disons que chercher une information revient en fait se déplacer à un point X [Xbis, Xter, etc...] (une adresse), sans forcément connaître le chemin parfait qu'un GPS pourrait fournir, en lisant les panneaux sur la route (si le parallèle ici vous parle). 

L'idée est de **tendre** vers le point, en vectorisant notre trajet. Cela revient donc à _aller vers_ le point, en appliquant une méthode bien définie (à laquelle certaines libertés peuvent se greffer, évidemment).

### Okay, mais comment on applique ton charabia ?
"Pour être plus **concret** : il est inutile de retenir color:red, si on sait retrouver ce set `propriété: valeur` avec une recherche Google (ou autre moteur de recherche).

Dans ce cas, on pourrait taper sur Google :
> _**`CSS COLOR ON TEXT`**_
 
Ce qui nous amène à : 
![Capture d'écran recherche CSS COLOR ON TEXT](https://i.imgur.com/Ayn7rmh.png)

Le premier lien [W3Schools](https://www.w3schools.com/css/css_text.asp) nous donne déjà la réponse.
Evidemment, ce cas-là est très simple, mais l'idée est là.

Dans le cadre du développement web, nos questions portent souvent, au début, sur de la syntaxe; sur **comment** écrire les choses.

Si l'on décompose la recherche (c'est trivial, mais pertinent je pense.) :
## `CSS` 
C'est le **langage** qu'on utilise. 

On aurait pu préciser `HOW TO STYLE TEXT ON HTML`, on aurait sûrement eu notre réponse également.
Mais, cette précision permet de mieux filtrer des recherches. Nous pourrons étendre notre champ de résultats souhaités lorsque notre problème sera plus spécifique. 
Par exemple, si l'on souhaite savoir comment créer un BLOG (sur le plan technique), de manière générale, on pourrait juste taper `HOW TO MAKE A BLOG FROM SCRATCH` et les solutions proposées iront du _nocode_ (Wix, Wordpress (plus ou moins), Squarespace) aux tutoriels _PHP_ avec _SYMFONY_ par Example, ou _JS_ avec _EXPRESS_. 
Ce n'est pas important pour le moment de comprendre ces termes, ce sont des exemples : nous pouvons avoir nos réponses en étant vague, également. 

Mais ici, nous savons que nous voulons donner une couleur à un texte, en CSS, donc nous précisons CSS. 

Un autre exemple pertinent serait pour les langages de programmation. Mettons que nous cherchons à convertir un entier (_0_, _1_, _2_,_3_, _4_, etc...) en chaîne de caractères (_"0"_, _"1"_ _"2"_, _"3"_, _"4"_, etc...). 
Nous travaillons, disons, en JAVA. Nous **devons** préciser `JAVA` dans notre recherche. Car cette opératios est faisable sur à peu près n'importe quel langage de programmation. 
Essayez ! 
Tapez `JAVA CONVERT INT TO STRING` puis `PHP CONVERT INT TO STRING`. Puis tapez simplement `CONVERT INT TO STRING`. Rien ne vaut le test sois même !

## `COLOR` 
C'est la **propriété** qu'on cherche. 
Nous remarquons que sur les résultats plus haut (image), nous avons également `Background Color` : c'est une propriété approchante, donc Google nous la propose aussi.
Cela nous est **précieux** : nous savons que même si nous ne connaissant pas le nom **exact** d'une propriété, nous pouvons la **retrouver**.

## `ON TEXT`
Ici, le `ON` permet de spécifier sur quelle entité nous souhaitons appliquer notre propriété. Si l'on avait marqué `CSS COLOR ON DIV`, nous aurions eu des résultats concernant... le fond ! Car on ne peut pas _colorer_ une div à proprement parler, mais nous pouvons lui changer le fond. Sinon, nous colorons le texte qui est enfant/inclus dans la div.
![Capture d'écran de la recherche CSS COLOR ON DIV](https://i.imgur.com/9JqzxQN.png)

---

#### Examples de recherches possibles :
`CENTER VERTICAL CSS`
`JS HTML CHANGE CLASS`
`CSS DEFAULT VALUE FLEX DIRECTION`
`THREE COLUMN FLEX`

---

### Super, mais c'est un peu léger, non ?
Oui. C'est pour cela qu'on peut être très précis avec nos recherches.
Voici une liste, non-exhaustive, des **tips & astuces** pour être plus rigoureux(se) lors d'une recherche Google (certains sont utilisables sur d'autres moteurs, mais, si tout va bien, vous pourrez les retrouver en appliquant la méthodologie de recherche !).
Il y a certains opérateurs que nous éclipseront volontairement car ils n'ont pas forte utilité dans le cadre de notre écosystème de travail, mais à vous de les... chercher !

### Qu'est ce qui n'est _pas_ pris en compte par Google ?
Bonne question !

- La **casse**, c'est à dire si votre mot est en minuscule, majuscule, ou ponctué de majuscules au milieu (BanANe par exemple). Sauf exceptions, c'est une chose à savoir. J'ai fait mes recherches plus haut en majuscule pour mettre l'emphase dessus, mais cela ne change absolument **RIEN** à notre recherche. (Si vous voulez savoir pourquoi, [cliquez moi](https://www.labnol.org/internet/search/case-sensitive-Google-search/6279/#:~:text=There%20are%20however%20instances%20when,can%20change%20with%20the%20case.&text=Unfortunately%2C%20Google%20searches%20are%20not,about%20the%20%E2%80%9Ctemporary%E2%80%9D%20memory.) (et y'a un petit tips pour forcer la prise en compte :) )

- La plupart des **caractères spéciaux** (*UNICODE*, *AINSI*, etc..) sauf `+ @ & % $ # - _` (et encore heureux, nous utilisons souvent ça en programmation).

- Les **signes de ponctuation**. Pas besoin de taper `CSS, COLOR ON: TEXT`.

### Qu'est ce que Google _permet_ de prendre en compte ?
Vous n'avez que des bonnes question, c'est fou !

Alors, c'est très pratique et facile à retenir.

- Les `""` (_guillemets_) : permet d'obliger Google à forcément prendre en compte ce qu'ils englobent. 
Par exemple, voici deux captures d'écrans. 
La **première** contient : `HTML DIV DYNAMIC`. Le premier résultat ne contient pas `DYNAMIC` dans son titre (mais peut être qu'il le contient plus tard dans son contenu, dans la page elle même, dans une réponse, un commentaire. Ou alors ne contient que `HTML` et `DIV`. Mais `DYNAMIC` se retrouve dans `DYNAMICALLY`. C'est comme ça que Google fonctionne. Il peut vous retourner un résultat ne contenant pas un élément de votre recherche, tant qu'il considère son taux [_le résultat_] de pertinence satisfaisant.
La **seconde** contient : `HTML DIV "DYNAMIC"`. Le premier résultat (qui était le second pour la précedente recherche par ailleurs) contient exactement le mot `DYNAMIC`.

![Capture d'écran de la recherche HTML DIV DYNAMIC sans guillemets](https://i.imgur.com/TRuJu9u.png)

![Capture d'écran de la recherche HTML DIV DYNAMIC avec guillemets](https://i.imgur.com/Rh9HmVf.png)
- Le `-` (tiret) : permet d'exclure (penser 'moins') un terme de la recherche.
Voici un exemple, avec `HTML DIV -DYNAMIC`
![Capture d'écran de la recherche HTML DIV -DYNAMIC](https://i.imgur.com/UIrTTjL.png)
- Le `*` : permet de dire à Google : Là je ne sais pas quel mot irait dans ma recherche, alors met ce que tu trouve à la place. Example non technique : `SYSTEM * DOWN` donnerait **System `of a` Down** ou **System `is` Down**.

### Aparté :
Si vous souhaitez avoir des résultats non-personalisés par vos habitudes de navigation (admettons que vous ayez passés une semaine sur un sujet et que vous arrivez aux bout des solutions) et que vous ne voulez pas forcément utiliser de navigation privée.

Mais que vous souhaitez un algorithme _à neuf_, ajouter `&pws=0` à la fin d'une URL.
C'est peut être surtout utile pour vérifier le positionnement d'une entreprise, en tant que référenceur (car peut être qu'a force de tester, on pense à tord que l'entreprise est en première page de Google, alors que la réalité est toute autre).
Mais au moins, vous savez.

### Et si je veux être encore plus précis ?

Que de curiosité !

Vous pouvez utiliser `OUTILS` (à droite en haut) pour restreindre à une intervalle temporel (que les résultats qui ont moins d'une année par exemple : très utile lorsque vous travaillez sur une technologie naissante, ou simplement qui a beaucoup de mises à jour comme `ReactJS`)

Vous pouvez restreindre une recherche à un site web ou une extension de fichier. (astuce : l'extension JSON peut être pratique pour certaines recherches :D)

- Restreinte à une extension : `filetype:EXT`
![Capture d'écran de la recherche PHP filetype:PDF](https://i.imgur.com/bQzTgnY.png)

- Restreindre à un site web particulier :`site:URL.DOMAIN`.
Exemple : `PHP site:devdocs.io` .
A noter qu'ici la recherche est très simple et aurait pu largement fonctionner sans l'opérateur `site:`. Mais ça semble parlant.
![Capture d'écran de la recherche PHP site:devdocs.io](https://i.imgur.com/TU3pSa5.png)

Cela nous permet une transition vers la seconde partie importante de ce cours : lire une documentation.

---
Mais avant, petit point sur [Stack Overflow](https://stackoverflow.com/).

Ce site est une communauté de développeurs en tout genre. 
Il permet de poser une question, et de laisser autrui répondre à sa question.
Il embarque un système de notation des réponses, et de niveau de crédibilité d'un(e) utilisateur(ice). Vous ne pourrez pas répondre à toutes les questions (littéralement, ne pas pouvoir appuyer sur le bouton `envoyer votre message`).
Mais ce n'est pas grave, nous voulons poser des questions, n'est-ce pas ?

Lorseque, vraiment, vous ne trouvez **rien** avec vos recherches, et rien non plus sur la documentation (c'est la prochaine partie du cours, _promis_.); posez votre question sur _Stack Overflow_.

Je dois faire une remarque avant tout : la communauté _Stack Overflow_ est loin d'être la plus aimable, ni la plus compréhensive envers les débutant(e)s. Si votre question est trop triviale (et c'est normal, ne vous en inquiétez pas : toute question est bonne à poser), il se peut que votre sujet soit fermé, et qu'on ne puisse plus vous répondre.
Çaarrive. Essayez de refaire un sujet, en étant plus précis(e), en donnant un maximum d'informations.
Vous trouvez ici un guide très complet sur comment poser une question de la **bonne** manière : https://stackoverflow.com/help/how-to-ask.
Si vous souhaitez qu'il soit traduit, ouvrez une **Issue** sur ce repo' github.

Voici un cheminement de recherche où l'on utilisera _Stack Overflow_ :

 

 1. Faire une recherche Google avec les bons mots clefs. Ici je souhaite itérer à travers un tableau (_array_) en Javascript. ![Capture d'écran de la recherche JS iterate array](https://i.imgur.com/J2oJGQ0.jpeg)
 2. Nous arrivons sur la page de la question. Tout **en haut**, le **titre** de la **question** `Loop through an array in Javascript` : cela **rejoint notre problématique**. Notre recherche n'était volontairement pas très précise pour arriver à un résultat facilement explicable pour les besoins de ce cours. Puis, nous avons la **date de publication** puis la **date du dernier message**.Ici, ça date de _10 ans_, et le dernier message posté remonte à seulement _12 jours_. Puis, nous avons les `tags` : ce sont des libellés qui donnent la ou les catégories de la question : ici `javascript` (le langage), `arrays` (tableaux en anglais, c'est l'entité de stockage d'informations), `loops` et `for-loop` (c'est les opérations que cherche à faire la personne qui a posée la question, ici `Mark Szymanski`). Ensuite, nous avons les **commentaires** liés au **message** spécifique à la question. Ce sont **en général** des réponses courtes, ou des critiques sur la forme du message (si une personne n'a pas compris sa question par exemple ou souhaite la rediriger ailleurs). Ils sont également notés. Finalement, nous avons les **réponses** (ici _40_) qui sont simplement des messages, notés également. On voit ici que cette réponse est notée `4121` ce qui est plutôt très très bon signe. On remarque un bouton `Run code snippet` : il permet d'exécuter le bout de code que la personne répondante a mis, dans un tout petite environnement d'exécution fourni par _Stack Overflow_. ![Capture d'écran de la page Stack Overflow](https://i.imgur.com/xn4VDmx.png)
 3. Ici, vous **pourriez** reprendre ce _snippet_ et **réfléchir** à comment **l'intégrer à votre propre code**. Aussi, pensez, lorsqu'il est question de choses **plus complexes**, d'éventuellement **inclure** le lien _Stack Overflow_ en **commentaire** dans votre propre code, pour permettre à la personne qui reprendra votre code (ça peut être vous même dans 6 mois !) de comprendre ce qu'il fait, ou le faire évoluer si le reste du code (externe au _snippet_) a changé. Effectivement, les réponses _Stack Overflow_ proposent souvent d'autres manière de faire une même chose (et c'est bien.) et vous parlent des limites de telle ou telle solution. Ici, on nous montre comment itérer à travers un tableau. Mais, peut être qu'avec un tableau de _999999999_ éléments, cette solution ne sera pas tout à fait adaptée !

## SE DOCUMENTER
Car l'on aura pas toujours un(e) mentor pour nous expliquer, nous aiguiller, nous devons être capables de lire une documentation, et comprendre ce que nous y lisons.

En général, elle est en anglais, disponible en ligne et en version téléchargeable. Les deux sont bonnes à avoir, sais-t-on jamais. On peut également l'intégrer à notre éditeur de texte (du type VScode !), pour ne jamais quitter notre fenêtre (mais ne soyons pas casaniers, baladons nous sur internet). 

Par ailleurs, si vous effectuer un `hover` sur une propriété dans VScode, vous remarquerez qu'un petit encart apparaît, avec des mini explications et une visualisation des potentielles valeurs que vous pourriez attribuer à cette propriétés. Et vous avez un lien vers la documentation en général.
![Capture d'écran de mini doc sur VScode](https://i.imgur.com/HiMqRrv.png)
Si j'appuie sur `MDN Reference`, je suis redirigé sur : https://developer.mozilla.org/fr/docs/Web/CSS/transform-origin .



La première étape, c'est trouver la documentation qu'il nous faut.

Pour `HTML` et `CSS`, c'est un cas particulier car il n'y a pas de fonctions à proprement parler (il y a évidemment des choses comme `calc()` en `CSS` mais bon.), de classes, de scopes, d'environnements de développements spécifiques. En général, pour nos amis `HTML` et `CSS`, une simple recherche Google suffit.

Donc, nous irons plutôt sur `JAVASCRIPT` (ou `JS`) pour les besoins de ce cours.

La première étape est d'aller sur Google et de taper `JAVASCRIPT DOC`.

Normalement, vous arrivez sur https://developer.mozilla.org/en-US/docs/Web/JavaScript par exemple.

Le Mozilla Developer Network est un ensemble de documentations, sur divers langages, librement accessible. Ils comprennent, en général, un tutoriel bien écrit, expliqué, et une partie plus barbare, appelée `Référence`.

C'est cette dernière qui va nous intéresser.

On va donc sur https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference
Vous arrivez sur une page assez longue répertoriant, par catégories, les différents mots-clefs et concepts présents en `JS`.

Baladez-vous. Ou consultez plutôt la page Reference pour HTML : https://developer.mozilla.org/en-US/docs/Web/HTML/Element si vous préférez !

### C'est bien joli tout ça, mais comment je... cherche et trouve ?

Question légitime. 
Mettons que vous chercher à interagir avec du `JSON`. 
Faites une recherche Google pour savoir ce que c'est, vous êtes armé(e)s maintenant !

Vous chercher JSON dans la page Reference par exemple (ou vous tapez `JSON DOC JAVASCRIPT` sur Google !).

Vous arrivez sur cette page : https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/JSON

![Capture d'écran de la page JSON sur la doc JS de MDN](https://i.imgur.com/yJtB2B4.png)

A gauche, vous avez la `Table des matières` (On This Page). C'est la liste parties abordés dans cette page.

Toujours à gauche, vous avez les autres choses susceptibles de vous intéresser : les méthodes lié à l'objet JSON (comme `JSON.parse()`) ou d'autres liens.

Et plus bas, toujours à gauche, les méthodes natives de `JS` qui sont applicables à JSON. 
Si nous cliquons sur `Object.prototype.hasOwnProperty()`, nous arrivons sur la page lié à la méthode `hasOwnProperty()`.
Comme son nom l'indique, elle permet de vérifier si telle clé à telle valeur. Et comme cette méthode était présente sur le flanc gauche de la page sur JSON, alors, à priori, on sait qu'elle est **compatible**.

### Okay...

Si vous préférez des choses plus old-school, intéressons-nous à la documentation `PHP`.
Ils parlent de **manuel** d'ailleurs !

Vous pouvez y accéder ici : https://www.php.net/manual/en/.
C'est une loooooongue table des matières, bien fournie.

D'abord, des informations comme le Copyright ou la liste des contributeur(ice)s.

Ensuite, une partie sur comment installer et configurer PHP, selon votre environnement.

Ensuite, la fameuse partie Reference. Elle regroupe ici la syntaxe, les types, variables, fonctions, classes, etc... 
Tout plein de choses, qui forment la partie **élémentaire** de `PHP`. Et de tout autre langage en réalité, ce sont des concepts partagés par la majorité des langages.

Puis, une partie sur la sécurité, mais aussi une partie consacré au cœur même de `PHP`: comment c'est construit, comment faire nos propres fonctions natives, comment contribuer au code source de `PHP`.

Il faut noter quelque chose : les documentations spécifiques aux langages n'expliquent pas forcément le concept associé à leur explication, mais surtout comment ce concept est exploité dans le cadre du langage lui même.
Ainsi, si vous cherchez comment additionner deux nombres en `JS`, il n'y aura sans doute pas d'explication sur ce qu'est une addition.
Les documentations sont là pour répondre au besoin précis du langage, et non pas là pour (même s'il y a des documentations très gentilles <3) donner un cours et aller au fond des notions.
C'est, en somme, un manuel d'utilisation au sens large.

### Et concrètement ?
Mettons que vous chercher à comprendre comment on déclare une `variable` en `PHP`.

Vous devriez suivre ce chemin :
`Language Reference` > `Variables` > `Basics` 

Vous arrivez normalement sur https://www.php.net/manual/en/language.variables.basics.php.

Le premier bloc explique la structure d'une variable et ses limitations générales.
On apprends ici qu'une variable est précédé par un signe dollar `$` et qu'elle est sensible à la casse.

Plus bas, il y a un _snippet_ qui montre les différentes (principales) manières de déclarer une variable, avec des commentaires.

```php
<?php  
$var = 'Bob';  
$Var = 'Joe';  
echo "$var, $Var"; // outputs "Bob, Joe"  
  
$4site = 'not yet'; // invalid; starts with a number  
$_4site = 'not yet'; // valid; starts with an underscore  
$täyte = 'mansikka'; // valid; 'ä' is (Extended) ASCII 228.  
?>
```

Lisez la page (ou du moins parcourez-là), vous aurez un bon aperçu de la structure générale d'une page de documentation.

Dans ce cas, la doc `PHP` permet l'ajout de commentaires de la part d'utilisateurs. Dans notre cas, en octobre 2020, il y a 4 commentaires (avec des notes, allant de +67 à -25 ici) qui viennent ajouter leur avis sur la dite page.

---

C'est la fin de ce mini-cours sur `Rechercher, se documenter`.

Je laisse quelques ressources pratiques :

[Can I Use It](https://caniuse.com/) - Vérification de compatibilité de règles CSS. (principalement)
[DevDocs](https://devdocs.io/) - Collection de documentations diverses, maintenu par diverses communautés.
[MDN](https://developer.mozilla.org/fr/) - Mozilla Developer Netfowrk : des tutoriels, de la doc, des outils.
[Stack Overflow](https://stackoverflow.com/) - Des questions-réponses.
[VScode DOC](https://code.visualstudio.com/docs) - La documentation de VScode.
