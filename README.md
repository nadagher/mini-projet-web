
# Mini Projet Web : Gestion des membres de la station spatiale internationale

<br>


## Présentation Générale :

<br>
 Ce mini projet vise à créer une application web capable d'aider un administrateur à gérer les astronautes de l'ISS tout en respectant les contraintes définies , c'est un travail d'équipe de 3 étudiants , demandé par notre prof de programmation Web , Mme Naimi Sabrine , et pris comme le devoir surveillé de la 2éme semestre de l'AU 2020/2021 au but d'appliquer nos connaissances acquise en programmation Web et Conception des SI et de les enrichir .<br><br>


## Technologies utilisés : 

<br>
 Ce mini projet est réalisé grâce à l'utilisation des technologies suivantes :<br>

 - StarUML : 
StarUML est un modélisateur logiciel sophistiqué destiné à prendre en charge une modélisation agile et concise.

 - GIT : 
Git est un système de contrôle de version distribué gratuit et open source conçu pour gérer tout, des petits projets aux très grands projets avec rapidité et efficacité.

 - GitHub : 
GitHub est un service web d'hébergement et de gestion de développement de logiciels, utilisant le logiciel de gestion de versions Git.

 - VScode : 
Visual Studio Code est un éditeur de code extensible développé par Microsoft pour Windows, Linux et macOS .

- Balsamiq: 
Balsamiq est l’éditeur du produit Balsamiq Mockups, un outil permettant de créer facilement des prototypes d’IHM électronique.  Avec Balsamiq Mockups il est ainsi possible de prototyper tout type d’applications (desktop, web, smartphone, …).

 - MySQL Workbench: 
Vest un logiciel de gestion et d'administration de bases de données MySQL créé en 2004.Via une interface graphique intuitive, il permet, entre autres, de créer, modifier ou supprimer des tables, des comptes utilisateurs, et d'effectuer toutes les opérations inhérentes à la gestion d'une base de données.

- Adobe UX: 
XD est le nouvel outil d'Adobe pour aider les designers UX/UI à créer des applications Web et mobiles..<br><br>


## Table des matières :

<br>

* [Présentation Générale](#Présentation-Générale)
* [Technologies utilisés](#Technologies-utilisés)
* [Specification des besoins](#Specification-des-besoins)  
  * [Les besoins fonctionnels](#A---Les-besoins-fonctionnels)<br>
  * [Les besoins non fonctionnels](#B---Les-besoins-non-fonctionnels)
* [Analyse des besoins](#Analyse-des-besoins)
  * [Identification des acteurs](#Identification-des-acteurs)
  * [Langage de modélisation](#Langage-de-modélisation)
  * [diagramme de cas d’utilisation](#fig1)
* [Conception détaillée](#Conception-détaillée)
  * [Diagramme de séquences ](#fig2)
* [Conclusion générale](#Conclusion-générale)
<br><br>


## Specification des besoins :

<br>
Le but de cette partie indispensable , la specification des besoins , est de donner au lecteur une image claire et non ambigu du système étudié afin de comprendre son contexte et avoir , eventuellement , une application resultante optimale et satisfaisante .<br>
On doit ainsi déterminer les besoins fonctionnels et non fonctionnels de notre application :<br><br>

### A - LES BESOINS FONCTIONNELS:
<br>
Les services proposés par notre application se résument en quatre actions majeures qui permettra au chef du bureau des astronautes de
gérer l'équipage à bord de l'ISS et sont comme suit :<br>

* Ajouter un astronaute à l'ISS<br>
* Consulter tous les astronautes disponibles<br>
* Modifier les données des astronautes disponibles<br>
* Supprimer un astronaute de l'équipage à bord de l'ISS <br><br>

### B - LES BESOINS NON FONCTIONNELS :
<br>
Les besoins non fonctionnels décrivent toutes les contraintes auxquelles est soumis notre application pour sa réalisation et son bon fonctionnement dont on cite :

- **La Rapidité :**  
 L'application doit optimiser les traitements pour avoir un temps d'attente raisonnable.
 
- **Ergonomie et souplesse:**  
 L'application doit offrir une interface conviviale et ergonomique exploitable par l'utilisateur en envisageant toutes les interactions possibles à l'écran du support tenu. 
 
- **Maintenabilité et scalabilité:**  
 Le code de l'application doit être lisible et compréhensible afin d'assurer son état évolutif et extensible par rapport aux besoins du marché.
- **Sécurité:**  
 Le code de l'application doit tolérer , en dehors des solutions traditionnelles , l'incorporation des systèmes de reconnaissance faciale et biométrique afin de limiter son accés uniquement au personnel autorisé .  <br><br>

## Analyse des besoins :

<br>
 Cette étape est très importante puisque la réussite de toute application dépend de la qualité de son étude . Alors, il faut bien préciser les fonctions attendues par le système .<br><br>

- ### Identification des acteurs
 Notre application est dédiée uniquement au **Chef du bureau des astronautes**.<br>

- ### Langage de modélisation
 Pour la modélisation objet, nous avons choisi le langage commun,formel et normalisé UML «Unified Modeling Language» .<br>

- ### Diagramme des cas d'utilisation
Le système assure pour **l'administrateur** les fonctions mises en valeur à travers le diagramme de cas d'utilisation illustré par **la figure [1](#fig1)** :<br><br>
  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;![fig1](https://i.imgur.com/JCrQu49.jpg)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**fig1.Diagramme de cas d'utilisation**
<br><br>


## Conception détaillée :

<br>
Pour donner une meilleure visibilité du mode de fonctionnement du système, nous terminons ce rapport en déroulant un diagramme de séquence montrant l'exécution de quatre scénarios très simples et la communication entre les différents objets .<br><br>

- ### Diagramme de séquence
 Le diagramme de séquence représente la succession chronologique des opérations réalisées par un acteur. Il indique les objets que l'acteur va manipuler et les opérations qui font passer d'un objet à un autre. Pour notre application , on se limite à un seul D. de séquence des cas d'utilisations précédemment cité , représenté par **la figure [2](#fig2)** :<br><br>

![fig2](https://i.imgur.com/9oDe39x.jpg)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**fig2.Diagramme de séquence**
<br><br>


## Conclusion générale :

<br>

  Depuis le présent document , nous avons detaillé une partie des étapes suivies pour une réalisation réussie du travail demandé en spécifiant dans un premier lieu nos besoins , en analysant ces besoins à l'aide d'un diagramme des cas d'utilisation et enfin en élaborant une conception détaillée en se limitant à un diagramme de séquences .
  Pour conclure , ce mini projet a considérablement améliorer nos capacités , surtout dans les approches de résolution des problèmes au sein du groupe face aux difficultés inattendues ainsi il peut être sujet à des extensions .
