# Mini Projet Web : Phase 3
## Description design Adobe XD

### Les éléments communs :

comprenant :<br>
*   La barre de présentation generale pour l'administrateur contenant le logo et le nom de la division , des mots de bienvenue et un bouton d'ajout des candidats à la liste des membres disponibles (présent seulement dans la landing page) qui charge la page insert contenant un formulaire rempli par l'administrateur .
*  Une liste défilable présantant des photos miniaturisées et les noms complets des astronautes disponibles surmonté d'une barre de recherche pour ces derniers . <br>


### Landing page :

![landing](https://user-images.githubusercontent.com/78099799/114548475-b6eceb80-9c57-11eb-8ade-f297600ae57d.png)


c'est la page d'accueil qui presente des informations sur l'équipe en cours à bord de la station spatiale y compris des graphiques représentant les scores et les états de santé (psychologie , generale , niveaux de radiations suite aux spacewalks ...) mis à jour des membres de l'équipe , la statut de la mission (niveau d'achèvement, niveau d'oxygène restant , niveau de synchronisation de groupe , temps écoulé ) et quelques informations sur l'équipe de surveillance et de controle de la mission actuelle .


### On hover :


En survolant un membre de la liste des astronautes disponibles (nom ou photo), un pop-up apparait , il contient une photo élargi , le nom et des informations générales sur cet astronaute .

### On click :


![on click](https://user-images.githubusercontent.com/78099799/114548550-d552e700-9c57-11eb-8dc5-7a47374a72b9.png)


Lorsqu'on clique sur un astronaute le bouton d'ajout des candidats présent dans la barre de présentation generale devient le bouton de suppression de l'astronaute selectionné de la liste des astronautes disponibles . Tous les informations de ce dernier apparaient au-dessous sous differentes formes (nom , alias , drapeau de son pays d'origine , à bord l'iss ? , infos generales , citation favorite , constellation favorite , traits de personalité , compétences techniques , tâches terminées avec succès , rapport complet , qui l'a recommandé (si c'est le cas) , coéquipiers recommandés , infos de contact) à l'addition d'une partie présentant les membres choisis pour la prochaine mission (appelé la barre d'équipage de l'expédition prochaine) avec la possiblité d'ajouter l'astronaute selectionné et/ou soustraire un ou plus des autres membres à travers un drag and drop (glisser et déposer) un bouton de retour vers la landing page et un bouton d'edition des informations sont aussi présents .

### On Delete :


![on delete](https://user-images.githubusercontent.com/78099799/114548664-f9162d00-9c57-11eb-9ef3-31199fd4bc27.png)


Un message temporaire de validation confirmant la suppression d'un astronaute de la liste d'équipage de l'expédition prochaine .

### On add :

![on add](https://user-images.githubusercontent.com/78099799/114548855-3975ab00-9c58-11eb-91af-85d04beb60a0.png)

Un message temporaire de validation confirmant l'ajout de l'astronaute selectionné à la liste d'équipage de l'expédition prochaine .

### After add or delete :


![after add or delte](https://user-images.githubusercontent.com/78099799/114549080-7cd01980-9c58-11eb-9eab-aa6b61cbe6b0.png)

après un drag and drop sur un astronaute nous restons dans la même page mais avec une petite différence, l'astronaute ajouté est en fait présent dans l'équipage de l'expédition suivante. et après suppression, l'astronaute supprimé n'est plus dans l'équipage.

### On modif :

![on modif](https://user-images.githubusercontent.com/78099799/114549196-a25d2300-9c58-11eb-9d28-fd0b9c92d890.png)

lors d'un clique sur l'icône d'édition (présent dans la barre d'équipage de l'expédition prochaine) on sera redirigé vers la page des modifications des informations de l'astronaute déja affiché. Après les changements , si on veut les valider on clique simplement sur le bouton de confirmation , sinon on clique sur reset et tous les modifications seront annulées .

### On insert : 


![on insert](https://user-images.githubusercontent.com/78099799/114549316-c1f44b80-9c58-11eb-8d86-7d33660b8684.png)


la page insert qui contient un formulaire contenant plusieurs champs rempli par l'administrateur permettant l'ajout d'un candidat a la liste des astronautes disponibles qui devient ensuite prét a être ajouté aux membres choisis pour la prochaine expedition (via la barre d'équipage de l'expédition prochaine) . Ii on veut valider on clique simplement sur le bouton de confirmation , sinon on clique sur reset et tous les champs deviennent vide de nouveau . 2 boutons de navigation sont aussi présent en bas de page l'un pour retour a l'accueil et l'autre pour retour en haut de page .
