## About
C'est un thème dotclear personnalisé en se basant sur le theme Grayscale http://themes.dotaddict.org/galerie-dc2/details/simplegrayscale

## Fonctionnement du thème
### Paramétrage des catégories
Ce thème n'est pas respectueux des conventions habituelles de Dotclear:
* L'organisation en catégories du site est imposée par le thème, les Billets dans une catégorie non prévue n'apparaitront nulle part.
* Certaines fonctionnalités de dotclear (dont les pages) sont rendues inutiles. 

Pour commencer, vous devez créer quatre catégories:
* header (url: header)
* Bottom (url: Bottom)
* Breves (url: Brèves)
* Accueil du site (url: Accueil-du-site)

#### Catégorie header
Elle ne doit pas contenir directement de billets, mas des sous catégories. Ces dernières s'afficheront sous forme de boutons de navigation déroulables en haut à droite.
* Evitez de mettre uun trop grand nombre de billets
* L'URL des sous catégories ne doit pas contenir de caracteres accentués, car elles sont réutilisés pour définir les id d'élements HTML, et bootstrap/ jquery n'aiment pas les accents.

#### Catégorie Bottom
C'est le contraire, elle ne peut pas contenir de sous catégorie (à tester remarque...), directement quelques billets, qui seront mis en lien en petit en pied de page.

#### Catégorie Brèves
C'est le flux d'actualité. la catégorie qui justifie d'avoir utilisé un moteur de blog :p.
Elle contient des billets, pas de sous catégorie.

#### Catégorie Accueil du site
Elle ne contient qu'un billet, c'est la sorte d'éditorial qui apparaitra sur la home page

## Organisation de la page
![str](/doc/screen.png)

### 1) Le titre du site
Paramétrable dans l'interface d'admin de Doctclear
### 2)Navigation
Ici sont effichées les sous catégorie de la catégorie nommée header
### 3)les billets qui ont vocation à rester
lorsqu'on déroule, ce sont les billets de chacune des sous catégories
### 4)Titre
Sur la home page, le titre du site est repris ici, ailleurs, ce sera le titre du billet ou de la catégorie.
Il disparait lors d'un scroll vers le bas.
### 5)description complémentaire.
### 6)Message d'accueil - éditorial
Le billet le plus récent de la catégorie Accueil-du-site est présenté ici
### 7) Les n dernières brèves 
En mode aperçu avec gestion de {{tpl:EntryFirstImage}}
### 8) Bottom
Les billets de la catégorie Bottom

### 9 )Liens réseaux sociaux
Ils ont été codés en dur dans le template (je corrigerai peut etre plus tard).
Editez le fichier tpl/_footer.html pour les modifier 


## Creator

Rémi Passerieu, pour le centre hospitalier du Bois Petit.

En réutilisant les travaux suivants:

Simple Grayscale: Start Bootstrap and Philippe aka amalgame
Start Bootstrap was created by and is maintained by **David Miller**, Managing Parter at [Iron Summit Media Strategies](http://www.ironsummitmedia.com/).
* https://twitter.com/davidmillerskt
* https://github.com/davidtmiller

## Copyright and License

Code released under the [Apache 2.0](https://github.com/IronSummitMedia/startbootstrap-grayscale/blob/gh-pages/LICENSE) license.

