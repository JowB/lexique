## REST
### Les 6 contraintes
Client-serveur, sans état, cache, interface uniforme, organisation en couches et code à la demande

### Rôle de chacune des contraintes
- Client-serveur: Séparation des responsabilités entre le client et le serveur. Le serveur s’occupe de la gestion du code métier et des données et le client se concentre sur l’interface utilisateur
- Sans état: La communication entre le client et le serveur doit se faire sans dépendre d’un contexte lié au serveur ou d'un état spécifique
- Cache: Afin d’améliorer les performances de l’application, possibilité de mise en cache des données ou non
- Interface uniforme: Pour les requêtes si on as des produits chaque requêtes sur la table des produits aura l'uri produit, seul le verbe changera
- Organisation en couches: Isolation des responsabilités. Chaque couche à sa spécificitée. Chaque chose à une place particulière dans le service, le controller, etc... 
- Code à la demande: Possibilité de passer du code JavaScript depuis notre API vers les clients web


## API
### 5 éléments qui composent une requête HTTP
- Le verbe
- L'url
- Version http
- Header
- Body

### 5 principaux verbes HTTP
- GET
- POST
- PUT
- PATCH
- DELETE


## JAVA
### Rôle d'une annotation Java
- Permet d'ajouter des méta-données à un code source Java. Elles ajoutent des fonctionnalités de Java ou des méthodes de base typiquement pour un controller si on ajoute l'annotation @GetMapping on va pouvoir préciser que notre méthode est une requête get avec un uri etc...

### Rôle du try catch
- Permettre d'éxécuter du code dans le try et pouvoir gérer et intercepter les erreurs avec le catch

### Pourquoi faut il fermer ses ressources en informatique 
- Dans un soucis de performances plus on as de ressources ouvertes moins le serveur ou client sera efficace et dans un soucis également de confidentialité et de sécurité pour ne pas laisser des ressources accessible à des personnes qui ne devraient pas avoir accés à ses informations

### Rôle du try with ressources
- A utiliser quand une ressource à besoin d'être fermé quand on en as plus besoin comme une connection à la BDD ou des appels réseau

### A quoi sert Lombok
- C'est une librairie qui facilite le développement en Java, par exemple pas besoin d'écrire de Getter et Setter une fois lombok installé les annotations le feront pour nous

### Quelles sont les annotations Lombok
- @Getter @Setter sur un argument va pouvoir créer automatique les getter et setter dans notre programme sans avoir à les écrire


## LEXIQUE
### Cache
- Système de sauvegarde temporaire d'informations ou de programmes

### Interropoérabilité
- Possibilité de communication entre plusieurs éléments

### Scalabilité
- Une API scalable est une API qu'on va pouvoir faire montée en charge donc grossir au fur et a mesure sans poser de prolbème de rapidité

### Scalabilité horizontale
- Ajouter des serveurs pour répartir la charge

### Scalabilité verticale
- Améliorer un serveur pour améliorer la puissance

### Stateless
- Pas d'enregistrement d'état de session

### URI
- Ensemble d'information pour trouver une adresse pas uniquement une url mais également des query des verbes de requêtes

### URL
- Adresse d'un site ou serveur

### Représentation d'une ressource
- Une ressource peut être un élément de notre ordinateur comme un élément d'une application

### Proxy
- Logiciel pour surveiller les échanges entre deux hôtes

### Gateway
- Dispositif permettant de relier deux réseaux informatiques de types différents

### Http Header
- Permet de transmettre des informations complémentaires pour une requête http

### Http version
- 

### Http body
- Le corp de notre requête, les informations qu'on envoi à notre API

### Content-type
- Sert à indiquer le type de contenu qu'on envoi

### Http méthode (verb)
- Permet d'exécuter différentes actions sur des requêtes HTTP

### GET
- Verbe de requête pour récupérer des données

### PUT
- Verbe de requête pour modifier des données

### DELETE
- Verbe de requête pour supprimer une ou des données

### POST
- Verbe de requête pour l'envoi de données

### OPTIONS
- Verbe de requête pour lister les méthodes autorisées

### Code dé réponse HTTP + principaux
- Code associé au retour d'une requête pour signifier l'état. 200 requête réussi, 404 not found requête non trouvé, 500 le serveur a eu un problème qu'il ne sait pas résoudre 

### Spring
- Spring est un framework Java pour nous aider à coder et qui contient plusieurs framework, Spring Boot, Spring Security, etc...

### JDBC
- Java Database Connectivity, permet l'accès au base de donnée

### JPA
- API permettant la persistence de donnée vers la base de donnée

### ORM
- Permet de faciliter la relation entre une base de donnée et un programme

### Maven
- Outil permettant la construction d'un projet Java en automatisant et facilitant certaines tâches

### Gestionnaire de projet
- Fichier POM d'un projet Java dans lequel nous allons lister l'ensemble des dépendances utile pour notre projet

### Intégration continue
- Permet de développer, d'ajouter de nouvelles fonctionnalités sans devoir mettre hors ligne notre projet

### Principes SOLID
- Responsabilité unique, Ouvert/fermé, substitution de liskov, ségrégation des interfaces, inversion des dépendances

### Proprités ACID
- Atomicité, cohérence, isolation, durabilité

### Base de donnée relationnelle
- Base de donnée avec des tables qui peuvent être liées entre elles

### Base de donnée non relationnelle
- Base sans table tout est stocké au même endroit

### IDE
- Editeur de texte sur lequel on va écrire notre code (IntelliJ, Visual Studio Code, etc...)

### VCS
- Gestion de version de code (Git)

### Lombok
- Librairie Java pour faciliter le développement

### Annotation
- Permet d'exécuter des actions sur des méthodes ou arguments pour faciliter le code et la compréhension par l'application

### Port informatique
- Points de connexion pour l'échange d'informations et la transmission de données

### Endpoint
- L'élément après notre verbe HTTP dans notre api pour un produit notre endpoint sera "/product"

### Connection Pool
- Réutilisation des connections plutôt que d’ouvrir et de fermer systématiquement

### JVM
- Machine virtuelle java qui exécute des programmes

### ByteCode
- Regroupement d'instructions pour exécution de JVM

### Code source
- Un texte qui présente les instructions composant un programme

### Compilation
- Il faut compiler le code source pour le transformer en bytecode pour qu'il soit exécutable par la JVM

### Fichier jar
- Archive de notre projet Java

### API
- Programme sur lequel on va pouvoir intéragir avec de la donnée

### Statement
- L'interface Statement fournit des méthodes pour exécuter des requêtes avec la base de données

### Chaîne de connexion à une base de donnée
- Les chaînes de connexion constituent la représentation textuelle des propriétés de connexion pour un fournisseur de données

### Connextion
- Connexion à une base de donnée

### Commit (transaction)
- Etapes sauvegardé d'avancement d'un développement

### Mapper
- Le mappage d'objets facilite la conversion d'un modèle en un autre
