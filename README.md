## Access Data Object ##
# Ce TD avait pour but de manipuler une base de données via un programme C# #

Voici la table sur laquelle nous avons travaillé :

![workbench.png](https://image.noelshack.com/fichiers/2019/14/3/1554298534-workbench.png)

En premier temps on a définit trois classes qui nous serviront à interagir avec la table nommée "anniversaire" 

![table.png](https://image.noelshack.com/fichiers/2019/14/3/1554296802-table.png)

La classe "ConnectionJoyeuxAnniversaire" contiendra notre chaîne de connexion à notre BDD 

![connexion.png](https://image.noelshack.com/fichiers/2019/14/3/1554297023-connexion.png)

Nous avions ensuite créer quelque méthodes dans la classe "TableAnniversaire"

Une méthode CompteOccurences(), elle nous permet de compter le nombre d'élément dans la table "Anniversaire"

![occurence.png](https://image.noelshack.com/fichiers/2019/14/3/1554299383-occurence.png)

Et une méthode appelée LeNomPatronymiqueCommencePar(), elle nous permet de récupérer les noms et prénoms des individus ayant un nom commençant par la chaîne de caractère passée en paramètre de la méthode.

![patronymique.png](https://image.noelshack.com/fichiers/2019/14/3/1554299552-patronymique.png)

# Ce TP nous a permis de nous familiariser avec les notion d'accès à une base de donnée via un objet en C#
