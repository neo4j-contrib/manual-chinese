# Documentation francophone de Neo4j

Site bientôt disponible

## Outils nécessaires

La documentation utilise le format Asciidoc. Apache Maven et Make sont utilisés pour extraire les parties du manuel et exécuter asciidoc sur celles-ci. Notez que l'exécution d'un processus en parrallèle (option -j) n'est pas supportée.

La version 8.6.3 de Asciidoc est requise, ainsi que ses dépendances comme *docbook*, *w3m*, *fop* et *graphviz*.

Pour installer tous les outils en une fois, voici la ligne de commande (sous ubuntu):
````
sudo apt-get install asciidoc docbook fop graphviz w3m maven libxml2-utils xsltproc
````

## Générer la documentation en local :

### 1. Clonez le dépôt de la documentation francophone:
````
git clone git@github.com:neo4j/manual-french.git
cd manual-french
````

### 2. générez la documentation avec Maven

````
mvn clean package
````

### Liens utiles

* [Documentation Neo4j](http://docs.neo4j.org)
* [Liste de diffusion](https://groups.google.com/forum/?fromgroups#!forum/neo4j)

### Licence

La documentation est soumise à la licence [Creative Commons 3.0](http://creativecommons.org/licenses/by-sa/3.0/deed.fr)

