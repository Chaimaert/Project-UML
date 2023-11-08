# Project-UML
We want to realize Pinterest's specification document, starting with the design phase, including the creation of the use case diagram, class diagram and sequence diagram
La modélisation des cas d'utilisation (use case modeling) dans UML suit généralement un processus structuré qui implique plusieurs étapes. Voici les étapes typiques pour créer un diagramme de cas d'utilisation :

1- Définir le Système : Tout d'abord, il faut comprendre le système ou l'application que vous modélisez. Identifiez les acteurs qui interagissent avec le système et les fonctionnalités qu'il offre.
2- Identifier les Acteurs : Listez tous les acteurs qui interagissent avec le système. Il peut s'agir d'utilisateurs humains, de systèmes externes ou d'autres entités qui ont un rôle dans le système.
3-Identifier les Cas d'Utilisation : Pour chaque acteur, identifiez les actions ou les fonctionnalités que l'acteur peut effectuer dans le système. 

------Réaslisation------

- Rechercher des Épingles : Les utilisateurs peuvent rechercher des images et des vidéos en utilisant des mots-clés.

- Créer une Épingle : Les utilisateurs peuvent ajouter de nouvelles images ou vidéos à Pinterest.

- Éditer une Épingle : Les utilisateurs peuvent modifier les détails d'une épingle existante.

- Supprimer une Épingle : Les utilisateurs peuvent retirer une épingle de leur collection.

- Créer un Tableau : Les utilisateurs peuvent créer des collections pour organiser leurs épingles.

- Éditer un Tableau : Les utilisateurs peuvent modifier les détails d'un tableau existant.

- Supprimer un Tableau : Les utilisateurs peuvent supprimer un tableau.

- Gérer le Profil : Les utilisateurs peuvent personnaliser leur profil en ajoutant des informations et une photo de profil.

- Voir les Notifications : Les utilisateurs peuvent consulter les activités récentes liées à leur compte.

- Télécharger une Image : Les utilisateurs peuvent ajouter des images à Pinterest.

- Partager une Épingle : Les utilisateurs peuvent partager des épingles sur les réseaux sociaux.

- Signaler un Contenu Inapproprié : Les utilisateurs peuvent signaler du contenu inapproprié.

- user-PIN (1).png : represente le premier acteur dans le diagramme de cas d'utilisation



-------------Acteur2: Admin---------------------------
- Adresser une infraction au droit d'auteur: l'admin peut identifier l'infraction
- Manager le contenu: l'admin a le pouvoir et les autorisations nécessaires pour superviser, contrôler, modifier, organiser ou supprimer le contenu de l'application
- Sécurité des données: l'admin d'une application a la responsabilité de mettre en place et de maintenir des mesures de sécurité et de protection des données pour garantir la confidentialité, l'intégrité et la disponibilité des informations stockées et traitées par cette plateforme
- Gérer les utilisateurs: l'admin a la capacité et l'autorisation de superviser et de contrôler les comptes et les activités des utilisateurs de l'application.

---------Le reste des acteurs-------
-Acteur : Visiteur (Non enregistré)

- Parcourir les épingles - Les visiteurs peuvent parcourir et afficher des épingles sur Pinterest sans être enregistrés.
- Rechercher des épingles - Les visiteurs peuvent rechercher des épingles en utilisant des mots-clés sans avoir besoin de créer un compte.
- Explorer les catégories - Les visiteurs peuvent explorer des épingles basées sur différentes catégories.
- Inscription - Les visiteurs ont la possibilité de s'inscrire pour créer un compte Pinterest et devenir des utilisateurs.

-Acteur : Système de Stockage Externe d'Images

-Télécharger une Image : Le système de stockage externe d'images reçoit les téléchargements d'images depuis Pinterest, que ce soit directement des utilisateurs ou dans le cadre de la création de pins.

-Stocker une Image : Il stocke les images téléchargées de manière sécurisée et efficace, veillant à ce qu'elles soient disponibles pour une récupération future.

-Supprimer une Image : Le système externe permet à Pinterest de supprimer des images, que ce soit à la demande de l'utilisateur ou en cas de violation des politiques.

-Traitement d'Images : Il peut effectuer des tâches de traitement d'images, telles que le redimensionnement, le recadrage ou l'optimisation des images, pour garantir qu'elles répondent aux exigences d'affichage de Pinterest.

---------------------------------------- Diagram de classe ------------------------------------------------------

-> La création d'un diagramme de classe pour une application complexe comme Pinterest est un processus détaillé qui nécessite une compréhension approfondie de l'architecture de l'application. Voici les étapes générales:

.Étape 1 : Comprendre les besoins
Avant de commencer, on comprend bien les besoins et les fonctionnalités de Pinterest que nous souhaitons représenter dans le diagramme de classe. Cela implique une analyse des fonctionnalités clés de l'application, de la gestion des utilisateurs, de la création et du partage de pins, de la gestion des tableaux, etc.

.Étape 2 : Identifier les classes
Identifiez les classes majeures du système. Pour Pinterest, cela pourrait inclure des classes telles que User (Utilisateur), Pin (Épingle), Board (Tableau), Comment (Commentaire), Tag (Tag)... 
Ces classes représentent les entités clés du système.

.Étape 3 : Identifier les attributs
Pour chaque classe, on identifiezles attributs  associés à cette classe. Par exemple, la classe User pourrait avoir des attributs tels que UserID, Username, Email, Password ...

.Étape 4 : Identifier les méthodes
Identifiez les méthodes (comportements) associées à chaque classe. Par exemple, la classe Pin pourrait avoir des méthodes telles que CreatePin(), Like(), Comment(), Share() ...

.Étape 5 : Identifier les associations
Identifiez les associations entre les classes. Par exemple, un utilisateur peut avoir plusieurs épingles (Pin), ce qui indique une association entre les classes User et Pin.

.Étape 6 : Spécifier les multiplicités
Déterminez les multiplicités des associations pour indiquer combien d'objets d'une classe sont liés à un objet d'une autre classe. Par exemple, un utilisateur peut avoir plusieurs épingles, donc l'association entre User et Pin aurait une multiplicité de "0..*".

.Étape 7 : Ajouter les attributs et les méthodes aux classes
Pour chaque classe, on ajoute les attributs et les méthodes que vous avez identifiés dans les étapes précédentes.

.Étape 8 : Organiser les classes
On organise les classes dans le diagramme de classe de manière logique, en tenant compte des associations entre les classes.

.Étape 9 : Ajouter les commentaires et les notes
On ajoute des commentaires et des notes pour expliquer les détails importants et les comportements spécifiques des classes, des attributs et des méthodes.

.Étape 10 : Réviser et valider
Je passe en revue le diagramme de classe pour vous assurer qu'il reflète correctement l'architecture et les fonctionnalités de Pinterest. On assurons que toutes les classes, attributs, méthodes et associations sont correctement documentés.

.Étape 11 : Documenter
Finalisez la documentation du diagramme de classe en fournissant une légende, des descriptions de classes et des explications pour rendre le diagramme compréhensible pour d'autres personnes.
On  suivons ces étapes, nous obtiendrons un diagramme de classe décrivant l'architecture de Pinterest

-> Digramme-de-Classe.png : represente le diagramme de classe

  


