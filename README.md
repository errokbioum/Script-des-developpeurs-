# Script des developpeurs
# Projet :Script des developpeurs 

## Objectif du TP
L'objectif de ce projet est de maîtriser l'insertion et la récupération de données dans une base de données MySQL ou Oracle en utilisant Java. Cela inclut la manipulation des objets `Connection`, `Statement`, et `ResultSet`, ainsi que la gestion des erreurs potentielles, utulisation de l'entite devdata comme un exempl 

## Structure du projet
Le projet est organisé de la manière suivante :

![image](https://github.com/user-attachments/assets/5b23fcde-4342-4f1d-b515-79a44ed534c6)

  - `src/` : Contient le code source Java : 
     - `projet ` : contient les pachage utulise
     - `Test` : le test de l'application
     - ` connexion` : contient  une class connexion qui va faire liee la connexion avec 
la base de donnee. 
     - `dao ` : contient  une interface générique qui contrôle le comportement du 
service de chaque entité. 
     - ` entité `: contient les entités utulise dans le projet. 
     - ` service `: contient les services que cette application offre, les classes 
présente dans ce package son implémente d’interface dao. 
     - `Test` : ou on va effectuer les test. 



## Méthodes utilisées
Les principales méthodes utilisées dans le projet sont les suivantes :

  - ` creatDtable () ` : permet de créé une table au niveau de la base de donne. 
  
  - ` update(DevData o) `: permet d’insérer des perssone au niveau de la table.

  - ` nbrmaxS () `: la personne ayant réalisé le nombre maximum de script en une journée
    
  - ` requette () `: le nombre de colonnes de la table résultat est affiché;pour chaque colonne, 
son nom et le type des données est affiché;le contenu de la table est affiché ligne par 
ligne. Sinon le nombre de lignes modifiées dans la table DevData est affiché .

   - `trieDec () `:la liste des personnes triée dans l’ordre décroissant selon leur nombre de 
scripts.

   - ` nbrtotalS ( ) ` : calculer et afficher le nombre total de scripts réalisés en une semaine.
  
 
## Test
Pour tester le projet :
1. Assurez-vous que votre serveur MySQL ou Oracle est en cours d'exécution.
3. Compilez et exécutez `Main.java` pour insérer et récupérer des données.


   [exo1-2_edit_0_edit_0.webm](https://github.com/user-attachments/assets/e8addef9-3439-42ee-9b37-90072fbc47f4)



- ` donner une requette  ` :
- 
 [requette.webm](https://github.com/user-attachments/assets/cfe316de-1700-4aa5-93aa-5a581c389de5)

- [Votre Nom](https://github.com/votre_nom)

## Auteurs

uête SQL suivante :
 
