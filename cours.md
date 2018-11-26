# Django le framework !

1. Introduction à Django
    1. Qu’est ce qu’un framework ?
    2. Types de frameworks
    3. Frameworks : Quels avantages et quels inconvénients ?
    4. Django, c'est quoi ?
    5. Design patterns et bonnes pratiques
    6. Ecosystème d'une application Django
2. Créer son premier projet sur Django
    1. Créer un projet et une première application
    2. Conception des premiers modèles
    3. Le traitement des données avec les vues et le routage d'URL
    4. Présentation du contenu avec les templates
    5. Administration du projet avec le scaffolding

# I - Introduction à Django

## 1 - Qu'est ce qu'un framework ?  
Un framework est l'ensemble de composants logiciels à la base d'un logiciel ou d'une application( bibliothèques,classes, helpers..etc).Il décrit les types de programmes à concevoir et leur mode d'interaction.  
Un framework permet de **simplifier le travail des développeurs informatiques** en offrant une architecture réutilisable et adaptée à leurs besoins. En outre, il peut être amélioré par l'expérience des développeurs.Les frameworks sont utilisés pour développer une application mobile, un site web, un jeu,..etc 

## 2 - Types de frameworks  
On peut classer les frameworks de la manière suivante:  
* **Frameworks d'infrastructure système** utilisés pour le développement des systèmes d'exploitation et des interfaces graphiques (Microsoft .Net, Apache Struts,...).
* **Frameworks d'intégration intergicielle** permettent l'interconnexion de systèmes divers.
* **Frameworks d'entreprises** sont spécifiques aux applications utilisées par les entreprises. 
* **Frameworks de gestion de contenu** sont les fondations d'un système de gestion de contenu — pour la création, la collecte, le classement, le stockage et la publication de « biens numérisés ».

Source : [Wikipedia](https://fr.wikipedia.org/wiki/Framework)

## 3 - Frameworks : Quels avantages et quels inconvénients ?  
En utilisant les frameworks, les développeurs codent de façon homogène. Ainsi, quand un développeur rejoint un projet basé sur un framework qu'il connaît, la compréhension de l'architecture lui sera plus simple et plus rapide que s'il avait dû s'approprier les outils au préalable. De plus, l'adoption d'une structure commune garantit un code organisé et facilement réutilisable. 

En revanche, les frameworks doivent être souples et modulables afin qu'ils soient adaptés à différents projets. Certains nécessitent cependant un temps d'apprentissage plus long que d'autres. 

Source: [Openclassrooms](https://openclassrooms.com/fr/courses/1871271-developpez-votre-site-web-avec-le-framework-django/1871361-creez-vos-applications-web-avec-django)  

## 4 - Django, c'est quoi ?  

Django est l'un des  frameworks applicatifs Python destinés au développement d’applications web. Créé en 2003 dans une agence de presse, Lawrence Journal-World, le framework est proposé au grand public deux ans plus tard. En 2008, la fondation Django Software a été créée. Aujourd'hui, Django est très populaire. Il est utilisé dans des applications web très célèbres comme *Instagram* ou *Pinterest*.  

Django permet le développement rapide de meilleures et plus performantes applications web. Il automatise des tâches répétitives  telles que l'écriture de requêtes destinées à une base de données. Il propose d'autres fonctionnalités comme une bibliothèque de traduction on un espace membres.

## 5 - Design patterns et bonnes pratiques

Django est l'un des  frameworks applicatifs Python destinés au développement d’applications web.Créé en 2003 dans une agence de presse, Lawrence Journal-World, le framework est proposé au grand public deux ans plus tard.En 2008, la fondation Django Software a été créée.Aujourd'hui, Django est très populaire.Il est utilisé dans des applications web très célèbres comme *Instagram* et  *Pinterest*.  

Django permet le développement rapide de meilleures et plus performantes applications web.Il automatise des tâches répétitives  telles que l'écriture de requêtes destinées à une base de données.Il propose d'autres fonctionnalités comme une bibliothèque de traduction on un espace membres.
## 5- Design patterns et bonnes pratiques:  
   1-**Don't repeat yourself**:  
   Don't repeat yourself ou DRY est un principe important en développement consistant à factoriser des portions de code en utilisant des fonctions ou des méthodes au lieu d'avoir à les dupliquer plusierus fois.  
   2-**MVC/MVT**:  
   Le Modèle-vue-contrôleur ou MVC est un type d'architecture logicielle destiné aux interfaces graphiques lancé en 1978 et très populaire pour les applications web. Le motif est composé de trois types de modules assurant différents rôles:  
   * Un modèle (Model) contient les données à afficher.
   * Une vue (View) contient la présentation de l'interface graphique.  
   * Un contrôleur (Controller) contient la logique concernant les actions effectuées par l'utilisateur.source: [Wikipédia](https://fr.wikipedia.org/wiki/Mod%C3%A8le-vue-contr%C3%B4leur)  
   Django utilise l'architecture MVT (modèle-vue-template)qui s'inspire de MVC.  
   * Le modèle interagit avec une base de données.Un ORM (Object Relational Mapping) traduit les réponses à une requête SQL ( langage de consultation de base de données) en objets Python exploitables par le programme.Tous les modèles sont 
   
   3-**Active record**:
## 6- Ecosystème d'une application Django

# II - Créer son premier projet sur Django
## 1 - Créer un projet et une première application
## 2 - Conception des premiers modèles
## 3 - Le traitement des données avec les vues et le routage d'URL
## 4 - Présentation du contenu avec les templates
## 5 - Administration du projet avec le scaffolding

