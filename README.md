# Mastermind


## Présentation du projet Mastermind

===== À REMPLIR par YANN. Ensuite, je vais relire. =====

## Réalisation

1. Environnement technique

  - IDE :  [IntelliJ 2018.3](https://www.jetbrains.com/idea/).
  - Langage de programmation : [Java 8/JDK 1.8.0_181](https://openclassrooms.com/fr/courses/26832-apprenez-a-programmer-en-java)


2. Programmation - Concepts techniques

===== À REMPLIR par YANN. Ensuite, je vais relire. =====

## Livrable

1. `mastermind.jar`

    À la fin de la programmation, j'ai généré le fichier `mastermind.jar` qui représente l'exécutable de mon programme.
C'est un archive qui contient :
  - les fichiers `*.class` issus de la compilation des fichiers sources `*.java`,
  - les bibliothèques `*.jar` que j'ai utilisées pour construire le programme (bibliothèques `log4j`).

2. Exécution du fichier `mastermind.jar`  

    Pour exécuter le programme :

    1. Exécution sans argument

    ```
    java -jar mastermind.jar
    ```

    2. Exécution avec arguments

        - Pour exécuter le programme en mode "DEV", taper la commande :

        ```
        java -jar mastermind.jar DEV
        ```

        - Pour exécuter le programme en mode "PROD", taper la commande :

        ```
        java -jar mastermind.jar PROD
        ```


## Remarque


J'ai fait un rework des packages du projet.
L'ancien package "projet3" a été supprimé.
J'ai créé un sous-package "utilities" dans le quel j'y ai mis le contenu de l'ancien
package "projet3".
Ensuite, j'ai posé la classe principale "Main" à la racine du package "fr.oc.projet".
