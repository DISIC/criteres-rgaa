# Version 4.0 du référentiel général d'amélioration de l'accessibilité (RGAA v4.0)

Ce dépôt contient les __fichiers de référence__ de la version 4.0 du RGAA

Le RGAA 4.0 est mis à disposition sous plusieurs formats :
* un document téléchargeable en format ODT et en format PDF,
* une version HTML disponible uniquement en ligne et publiée sur le site web de la Direction interministérielle du numérique (DINUM).

__À noter__ : le site web de la DINUM met à disposition le RGAA pour la version _en cours_. Les fichiers de référence des versions antérieures du RGAA sont disponibles dans Github.

## Documents téléchargeables du RGAA 4.0
* ### Fichier [RGAA-v4.0.odt](RGAA-v4.0.odt "Télécharger le RGAA 4.0 au format ODT (261 Ko)")
Le fichier `RGAA-v4.0.odt` représente la version 4.0 de référence du RGAA en format ODT.

* ### Fichier [RGAA-v4.0.pdf](RGAA-v4.0.pdf "Télécharger le RGAA 4.0 au format PDF (2,97 Mo)")
Le fichier `RGAA-v4.0.pdf` représente la version 4.0 de référence du RGAA en format PDF. Il résulte d'une conversion du fichier ODT en format PDF.

* ### Fichier [rgaa4.0.modele-de-grille-d-audit.ods](rgaa4.0.modele-de-grille-d-audit.ods "Télécharger le modèle de grille d'audit RGAA 4.0 au format ODS (234 Ko)")

Le fichier `rgaa4.0.modele-de-grille-d-audit.ods` fournit un modèle de grille de vérification des critères du RGAA 4.0 sur un échantillon de pages pour la réalisation d'une inspection d'accessibilité numérique (_audit_) au format ODS.

* ### Fichier [rgaa4-2019-modele-rapport-audit.odt](rgaa4-2019-modele-rapport-audit.odt "Télécharger le modèle de rapport d'audit RGAA 4 au format ODT (49,4 Ko)")
Le fichier `rgaa4-2019-modele-rapport-audit.odt` fournit un modèle de rapport de résultats d'une inspection d'accessibilité numérique (_audit_) au format ODT.

* ### Fichier [rgaa4-2019-modele-rapport-audit.pdf](rgaa4-2019-modele-rapport-audit.pdf "Télécharger le modèle de rapport d'audit RGAA 4 au format PDF (1,9 Mo)")
Le fichier `rgaa4-2019-modele-rapport-audit.pdt` fournit un modèle de rapport de résultats d'une inspection d'accessibilité numérique (_audit_) au format PDF. Il résulte d'une conversion du fichier ODT en format PDF.

* ### Fichier [rgaa4-2019-exemple-declaration.odt](rgaa4-2019-exemple-declaration.odt "Télécharger l'exemple de déclaration d'accessibilité au format ODT (39,8 Ko)")
Le fichier `rgaa4-2019-exemple-declaration.odt` fournit un exemple pour la rédaction d'une déclaration d'accessibilité au format ODT.

* ### Fichier [rgaa4-2019-exemple-declaration.pdf](rgaa4-2019-exemple-declaration.pdf "Télécharger l'exemple de déclaration d'accessibilité au format PDF (202 Ko)")
Le fichier `rgaa4-2019-exemple-declaration.pdf` fournit un exemple pour la rédaction d'une déclaration d'accessibilité au format PDF. Il résulte d'une conversion du fichier ODT en format PDF.

*****************

## Version en ligne du RGAA 4.0

La version en ligne du RGAA est publiée sur le site de la DINUM dans la rubrique `Publications\rgaa_accessibilité`.
Les pages HTML sont organisées de la manière suivante :
* Accueil
* Obligations d'accessibilité
* Méthode technique
  * Critères et tests
  * Glossaire
  * Environnement de test
  * Références
  * Licence
* Kit d'audit
* Méthodologie de test
* Documentation
* Questions
* Notes de révision

## Création des pages HTML de la version web du RGAA 4.0

Les pages HTML `Accueil`, `Obligations d'accessibilité`, `Méthode technique`, `Kit d'audit`, `Méthodologie de test`, `Documentation`, `Questions` et `Notes de révision` sont générées à partir de fichiers en format Markdown (md).

Les pages HTML `Critères et tests` sont générées à partir du fichier `criteres.json` au format JSON.
Les pages HTML `Glossaire`, `Environnement de test`, `Références` et `Licence` sont générées à partir du fichier `glossaire.json` au format JSON.

Chaque fichier en format Markdown est mis à disposition individuellement ou regroupé dans un ensemble (_package_).
Les fichiers en format JSON sont mis à disposition individuellement.

## Package RGAA 4 initial version web

* ### Fichier [package RGAA 4 initial version web.zip](https://github.com/DISIC/RGAA/blob/master/package.RGAA.4.initial.version.web.zip "Télécharger le package de la version web du RGAA 4.0 (143 Ko)")
Le fichier `package RGAA 4 initial version web.zip` contient les fichiers suivants

| NOM du fichier    | OBJET du fichier |
|:------------------|:-------|
|rgaa-accessibilite.html    | pour la création du menu de navigation dans les pages HTML du RGAA
|accueil.md        | pour la page d'accueil de la publication du RGAA
|obligations.md    | pour les pages de règles de mise en œuvre des obligations en matière d'accessibilité numérique du RGAA
|methode.md        | pour la page d'introduction de la méthode technique du RGAA
|criteres.html     | pour la page de critères et tests de la méthode technique du RGAA avec un filtre d'affichage des critères du RGAA
|kit.md            | pour la page du kit d'audit du RGAA
|methodologie.md   | pour la page de méthodologie de tests du RGAA
|documentation.md  | pour la page de documentation du RGAA
|questions.md       | pour la page questions du RGAA
|notes-revision.md | pour la page des notes de révision du RGAA 3 2017 vers le RGAA 4

## Consultation unitaire des fichiers

* ### Fichier [rgaa-accessibilite.html](rgaa-accessibilite.html "Voir le fichier rgaa-accessibilite.html (2,71 Ko)")
Le fichier `rgaa-accessibilite.html` permet de créer le menu de navigation dans les pages HTML du RGAA 4.0

* ### Fichier [accueil.md](accueil.md "Voir le fichier accueil.md (3,97 Ko)")
Le fichier `accueil.md` correspond à la page d'accueil qui permet de télécharger le document du RGAA 4.0 au format ODT ou au format PDF, et d'aller consulter le RGAA 4.0 en version HTML

* ### Fichier [obligations.md](obligations.md "Voir le fichier obligations.md (54 Ko)")
Le fichier `obligations.md` correspond à la rubrique Règles de mise en œuvre des obligations en matière d'accessibilité numérique du RGAA 4.0 en version HTML.

* ### Fichier [methode.md](methode.md "Voir le fichier methode.md (2,85 Ko)")
Le fichier `methode.md` correspond à la page d'introduction de la rubrique Méthode technique du RGAA 4.0 en version HTML.

* ### Fichier [criteres.html](criteres.html "Voir le fichier criteres.html (56,9 Ko)")
Le fichier `criteres.html` permet de proposer un filtre d'affichage des critères du RGAA 4.0 avec un filtrage par thématique, avec ou sans les tests, par niveau A ou AA des WCAG. La page affiche la liste des critères et des tests qui est mise à jour à partir de criteres.json.

* ### Fichier [kit.md](kit.md "Voir le fichier kid.md (2,69 Ko)")
Le fichier `kit.md` correspond à la page Kit d'audit qui permet de télécharger :
* un modèle de grille de vérification des critères du RGAA 4.0 sur un échantillon de pages pour la réalisation d'une inspection d'accessibilité numérique (_audit_) au format ODS ;
* un modèle de rapport de résultats d'une inspection d'accessibilité numérique (_audit_) au format ODT ou au format PDF ;
* un exemple pour la rédaction d'une déclaration d'accessibilité au format ODT ou au format PDF.

* ### Fichier [methodologie.md](methodologie.md "Voir le fichier methodologie.md (417 Ko)")
Le fichier `methodologie.md` correspond à la page Méthodologie de test du RGAA 4.0 en version HTML.

* ### Fichier [documentation.md](documentation.md "Voir le fichier documentation.md (1,66 Ko)")
Le fichier `documentation.md` correspond à une page _temporaire_ Documentation RGAA.

* ### Fichier [questions.md](questions.md "Voir le fichier questions.md (1 Ko)")
Le fichier `questions.md` correspond à la page Questions du RGAA 4.0 en version HTML.

* ### Fichier [notes-revision.md](notes-revision.md "Voir les notes de révision (902 Ko)")
Le fichier `notes-revision.md` correspond à la page des notes de révision du RGAA 3 2017 vers le RGAA 4.0 en version HTML.

**********************
## Les fichiers au format JSON du RGAA 4.0
Les fichiers au format JSON correspondent __uniquement à la méthode technique__ du RGAA 4.0. Ils permettent de générer les pages HTML suivantes :
  * Critères et tests
  * Glossaire
  * Environnement de test
  * Références
  * Licence

### Fichier [criteres.json](criteres.json "Télécharger le fichier criteres.json (288 Ko)")
Le fichier `criteres.json` contient la liste des 106 critères du RGAA 4.0 regroupés par thématiques.
Il permet la création des pages HTML relatives aux critères et tests de la méthode technique du RGAA 4.0

Chaque critère RGAA contient les informations suivantes :
* Numéro ;
* Titre ;
* Liste des tests associés, certains tests pouvant contenir eux-mêmes une liste de conditions d'application ;
* Section note technique (optionnelle) ;
* Section cas particuliers (optionnelle) ;
* Section références divisée en deux parties :
  * Références aux critères WCAG associés ;
  * Références aux techniques WCAG associées.

### Fichier [glossaire.json](glossaire.json "Télécharger le fichier glossaire.json (147 Ko)")
Le fichier `glossaire.json` contient les entrées de glossaire utilisées dans le fichier `criteres.json`.
Il permet la création des pages HTML de la méthode technique du RGAA 4.0 relatives aux rubriques Glossaire, Environnement de test, Références et Licence.

Ces entrées sont regroupées par ordre alphabétique à la manière d'un abécédaire.
Chaque entrée de glossaire contient un ou plusieurs paragraphes explicatifs qui peuvent être assortis de liens et d'exemples.

#### Structure des contenus des fichiers JSON

Il est à noter que pour le fichier `criteres.json` :
* La propriété `tests` a pour contenu un objet qui regroupe l'ensemble des tests du critère.
* Chaque test est référencé directement par son numéro (`1`, par exemple) et a pour valeur : 
  * Soit une chaîne de caractères lorsque le test ne possède pas de conditions ;
  * Soit un tableau de chaînes de caractères lorsqu'il possède des conditions. Dans ce cas, le premier élément du tableau correspond à l'intitulé du test et les éléments suivants aux conditions associées.
* Les sections `technicalNote` et `particularCases` ont pour valeur un tableau avec pour éléments :
  * Soit une chaîne de caractères correspondant à l'équivalent d'un paragraphe ;
  * Soit un objet avec pour contenu une propriété `ol` ou `ul` correspondant à l'équivalent d'une liste ordonnée ou non ordonnée et ayant pour valeur un tableau contenant soit une chaîne de caractères, soit un objet avec pour contenu une propriété `ol` ou `ul` correspondant alors à un tableau imbriqué.

Il est à noter que pour le fichier `glossaire.json` :
* La description de l'entrée de glossaire est référencée par une propriété `dd` qui a pour valeur un tableau avec pour éléments :
  * Soit une chaîne de caractères correspondant à l'équivalent d'un paragraphe;
  * Soit un objet avec pour contenu une propriété `ol` ou `ul` correspondant à l'équivalent d'une liste ordonnée ou non ordonnée et ayant pour valeur un tableau contenant soit une chaîne de caractères, soit un objet avec pour contenu une propriété `ol` ou `ul` correspondant alors à un tableau imbriqué.

De manière générale, le contenu de certaines propriétés JSON contient un balisage interne en markdown :
* Les liens qu'ils soient internes ou externes; par exemple, le renvoi vers un critère du fichier `criteres.json` est représenté ainsi : `[critère 9.1](#crit-9-1)`.
* L'indication d'un terme ou d'une instruction relevant d'un langage informatique est signalée au moyen du délimiteur accent grave (`).

********************

## Licence

Le contenu de ce dépôt est publié sous [licence Ouverte 2.0](LICENSE.md).
