# web_services_persistance

## REST

Quelles sont les 6 contraintes et Expliquer le rôle de chacune des contraintes : 

1. Client-Server – Un mode de communication avec séparation de rôles entre client et serveur.
2. Stateless Server – Les requêtes doivent contenir toutes les informations nécessaires au traitement. Il ne doit pas y avoir une notion de session côté serveur. Cette contrainte est indispensable pour rendre une API scalable.
3. Cache – La réponse du serveur doit être cacheable côté client.
4. Uniform interface – La méthode de communication entre client et serveur doit être uniforme avec des ressources identifiables, représentables et auto-descriptives. Autrement dit, en vocabulaire HTTP, avec une URL et une réponse contenant un body et une entête.
5. Layered System – Le système doit permettre le rajout de couches intermédiaires (proxy server, firewall, CDN, etc …).
6. Code-on-Demand Architecture (optionnelle) – L’architecture doit permettre d’exécuter du code côté client.



## API

5 principaux éléments composant une requête Http : Les éléments composant une requête http sont :
- method
- uri
- http version
- header
- body

5 principaux verbes HTTP : POST, GET, PUT, DELETE, OPTIONS


## JAVA

Rôle d'une annotation java : une annotation Java est une façon d'ajouter des méta-données à un code source Java. Elles peuvent être ajoutées aux classes, méthodes, attributs, paramètres, variables locales et paquets. Cela évite d'écrire ces fichiers à la main car c'est un procédé ennuyeux et sujet à erreur. Leur but est de définir des annotations couramment utilisées et ainsi d'éviter leur redéfinition pour chaque outil qui en aurait besoin.

Rôle du try catch : L'instruction try catch regroupe des instructions à exécuter et définit une réponse si l'une de ces instructions provoque une exception.

Pourquoi faut il fermer ses ressources en informatique (ie: fichiers, connexions ...) : ❌

Rôle du try with ressources : ❌

A quoi sert Lombok ? : Lombok se connecte automatiquement à votre éditeur et à des outils de construction et crée des outils Java. Il fournit un ensemble d’annotations utiles pour éliminer une grande quantité de code standard. il sert à réduire les répétitions de blocs de codes dans les nombreuses parties d’une application en les remplaçant par de simples annotations.

Quelles sont les annotations Lombok  : ❌


## Lexique

Cache : Un cache Web conserve des copies de documents transitant par son biais. Le cache peut, dans certaines conditions, répondre aux requêtes ultérieures à partir de ses copies, sans recourir au serveur Web d'origine. réduit la consommation de bande passante, la charge du serveur web, améliore la rapidité de consultation lors de l'utilisation d'un navigateur web.

Interropérabilité : le fait qu'un système ou produit puisse fonctionné avec d'autres systèmes et produit sans restriction d'accès ou de mise en œuvre.

Scalabilité : capacité d'un produit à s'adapter à un changement d'ordre de grandeur de la demande, en particulier sa capacité à maintenir ses fonctionnalités et ses performances en cas de forte demande.

Scalabilité horizontale : afin de répondre à un changement d'ordre de grandeur de la demande la scalabilité reviens a dupliquer un produit pour repondre a cette demande. Exemple ajouter un nouveau serveur avec repartition des charges

Scalabilité verticale : afin de répondre à un changement d'ordre de grandeur de la demande la scalabilité reviens a améliorer un produit pour repondre a cette demande. Exemple upgrader un serveur avec plus de ram

Stateless : qui n'a pas d'état,
exemple: un protocole sans état est un protocole de communication qui n'enregistre pas l'état d'une session de communication entre deux requêtes successives.

URI : Uniform Resource Identifier : route permettant de mener a une ressource sur internet (l'url est une uri)

URL : Uniform Resource Locator : chaîne de caractères uniforme qui permet d'identifier une ressource du World Wide Web par son emplacement et de préciser le protocole internet pour la récupérer.

Représentation d'une ressource : les ressources sont des composants, matériels ou logiciels, connectés à un ordinateur. Tout composant de système interne est une ressource. Les ressources d'un système virtuel incluent les fichiers, les connexions au réseau, et les zones de mémoire.

Proxy : Uniform Resource Locator : chaîne de caractères uniforme qui permet d'identifier une ressource du World Wide Web par son emplacement et de préciser le protocole internet pour la récupérer.

Gateway : passerelle : dispositif permettant de relier deux réseaux informatiques de types différents, par exemple un réseau local et le réseau Internet.

Http Header : L'en-tête http permet de transmettre des informations supplémentaires avec la requête. elle est constitué de son nom et de sa valeur

Http version : ❌

Http body : le body est le contenu du message. autrement dit c'est la requête ou la reponse

Content-type : L'en-tête Content-Type sert à indiquer le type de la ressource (type MIME)

Http méthode (verb) : les méthodes de requête indiquent l'action que l'on souhaite réaliser sur la ressource.

GET : la méthode GET permet de récupérer des données de la ressource

PUT : la méthode PUT permet de remplacé les éléments de la ressource par les éléments de la requête.

DELETE : la méthode DELETE supprime les éléments de la ressource indiqué dans la requête.

POST : la méthode POST permet d'envoyer les éléments de la requête à la ressource.

OPTIONS : la méthode OPTIONS permet de décrire les options de communications avec la ressource.

Code dé réponse HTTP + principaux : Les codes de statut de réponse HTTP indiquent si une requête HTTP a été exécutée avec succès ou non. Les réponses sont regroupées en cinq classes: 

1. Les réponses informatives (100 - 199),
2. Les réponses de succès (200 - 299),
3. Les redirections (300 - 399),
4. Les erreurs du client (400 - 499),
5. Les erreurs du serveur (500 - 599).

Principaux :

- 200 : succès de la requête.
- 301 et 302 : redirection, respectivement permanente et temporaire.
- 401 : utilisateur non authentifié.
- 403 : accès refusé.
- 404 : page non trouvée.
- 500 et 503 : erreur serveur.
- 504 : le serveur n'a pas répondu.

Spring : Spring est un framework open source pour construire et définir l'infrastructure d'une application Java

JDBC : Java Database Connectivity est une interface de programmation pour les programmes utilisant la plateforme Java. Elle permet aux applications Java d'accéder par le biais d'une interface commune à des sources de données pour lesquelles il existe des pilotes JDBC.

JPA : Java Persistence API est une interface de programmation Java permettant aux développeurs d'organiser des données relationnelles dans des applications utilisant la plateforme Java.

ORM : Mapping objet-relationnel est un type de programme informatique permettant de simuler une base de données orientée objet.

Maven : Apache Maven est un outil de gestion et d'automatisation de production des projets logiciels Java en général et Java EE en particulier. Il est utilisé pour automatiser l'intégration continue lors d'un développement de logiciel

Gestionnaire de projet : ❌

Intégration continue : ❌

Principes SOLID : ❌

Proprités ACID : ❌

Base de donnée relationnelle : ❌

Base de donnée non relationnelle : ❌

IDE : integrated development environment ou en français environnement de développement est l'ensemble des outils utilisé afin de développer.

VCS : version control system ou en français logiciel de gestion de versions est un logiciel qui permet de stocker des fichiers en conservant la chronologies de ces fichiers ce qui permet de récupérer les versions précédentes.

Lombok : Lombok est une bibliothèque Java qui se connecte automatiquement à votre éditeur et à des outils de construction et crée des outils Java. Il fournit un ensemble d’annotations utiles pour éliminer une grande quantité de code standard. La vision autour de ce projet est de réduire les répétitions de blocs de codes dans les nombreuses parties d’une application en les remplaçant par de simples annotations.

Annotation : une annotation Java est une façon d'ajouter des méta-données à un code source Java. Elles peuvent être ajoutées aux classes, méthodes, attributs, paramètres, variables locales et paquets.

Port informatique : un port matériel, une prise permettant de brancher des périphériques sur un ordinateur ; un port logiciel, un système permettant aux ordinateurs de recevoir ou d'émettre des informations

Endpoint : un endpoint une extrémité d’un canal de communication. un Endpoint peut inclure une URL d’un serveur ou d’un service. Chaque Endpoint est l’emplacement à partir duquel les API peuvent accéder aux ressources dont elles ont besoin pour exécuter leur fonction.

Connection Pool : un connection pool est un serveur de connexions qui ouvre un certains nombre de connexions avec le serveur de base de données.

JVM : La machine virtuelle Java est un appareil informatique fictif qui exécute des programmes compilés sous forme de bytecode Java.

ByteCode : le bytecode en français code en bytes est un code intermédiaire entre les instructions machines et le code source, qui n'est pas directement exécutable.

Code source : le code source est un texte qui présente les instructions composant un programme sous une forme lisible, telles qu'elles ont été écrites dans un langage de programmation.

Compilation : la compilation est un travail réalisé par un compilateur qui consiste à transformer un code source lisible par un humain en un fichier binaire exécutable par une machine.

Fichier jar : L’extension .jar est une abréviation de « Java Archive », cela contient la plupart du temps des fichiers et métadonnées Java que l’on envoie rassemblées et compressées

API : Application Programming Interface ou en français interface de programmation d'application, est une interface permettant à une application d'utilisé, de modifier supprimer etc.. des données dont elle aurait besoin pour fonctionner. elles rend ces données accessibles via des classes methodes fonctions etc..

Statement : en français déclaration, permet d'indiquer au compilateur l'existence d'une entité informatique, en spécifiant: son identifiant; son type de données; les paramètres.

Chaîne de connexion à une base de donnée : Une chaîne de connexion correspond aux informations nécessaires pour que votre application puisse accéder à votre base de données, par exemple un nom de base de données, un nom d'utilisateur, un mot de passe, un port, etc.

Connexion : la connexion est le fait de connecter un élément à un autre il va souvent de paire avec une authentification.

Commit (transaction) : le commit désignent l’enregistrement effectif d’une transaction.

Mapper : Établir une correspondance entre deux objets de même nature mais pas de même forme.
