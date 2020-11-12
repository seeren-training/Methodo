# Spécifications

* 🔖 **Fonctionnelles**
* 🔖 **Techniques**

___

## 📑 Fonctionnelles

Dans un cadre itératif les spécifications peuvent se limiter au backlog product rédigé par un responsable produit. L'étude d'un cadre de travail agile n'est pas notre préoccupation actuelle et nous allons synthétiser l'expression du besoin.

Avant chaque séquence de développement la demande est complétée et se rédige de façon itérative également.

> Découvrons certains termes en rapport avec le recueille de la demande.

### 🏷️ **Epic**

Les epics sont des corpus de tâches importantes qui peuvent être subdivisés en plus petites tâches (appelées stories).

### 🏷️ **User story**

Une histoire utilisateur est une brèves exigences ou requêtes écrites du point de vue de l'utilisateur final,  elle doit avoir au minimum un rôle, une tache et un objectif. 

> Une histoire utilisateur appartient au responsable produit qui est le seul à pouvoir la rédiger et la prioriser dans le product backlog.

![image](https://raw.githubusercontent.com/seeren-training/Agile/master/wiki/resources/03/07-User-Story.jpg)

> Une user story doit être priorisée, évaluée, estimée, un retour sur investissement doit être calculé puis elle doit être découpée en tache, mais ce n'est pas notre préoccupation.

### 🏷️ **Requirements**

Une exigence est quelque chose que le produit doit faire ou une qualité qu'il doit avoir.

Souhaitant rattacher aux histoires utilisateurs des documents de conception, le requirement diagramme met en relation demande fonctionnelle et les éléments de conception.

![image](https://raw.githubusercontent.com/seeren-training/Methodo/master/wiki/resources/requirement.jpg)

___

👨🏻‍💻 Manipulation

Après avoir identifié un responsable du produit, accompagnez le dans la rédaction des histoires utilisateur. L'équipe de développement est responsable de rédiger les diagrammes de contraintes pour l'**Epic et les user stories**. 

> Ce fichier doit être collégial et accessible par tous en modification. Il aura la responsabilité de réceptionner les différents diagrammes et les mettre en association avec les contraintes. 

___

## 📑 Techniques

La spécification technique de besoin  est une expression consacrée à indiquer le besoin suivant des critères techniques. La spécification technique vient de manière générale après l'expression fonctionnelle du besoin.

Vous devez détailler langage, framework, serveurs, protocole et tout choix techniques appropriés au projet.

___

👨🏻‍💻 Manipulation

Ajouter des **requirements** sur votre diagramme de contraintes pour exprimer vos choix techniques. Différenciez les requirements, stories, epic des stéréotypes, organisation, couleurs.

___

### 🏷️ **Data Flow**

Cet outil est souvent utilisé comme étape préliminaire dans la conception d’un système afin de créer un aperçu de ce système d’information. De plus, il est également utilisé pour visualiser le traitement de données. 

* **External Entity**: Également appelées acteurs, sources ou puits, les entités externes produisent et consomment des données qui circulent entre l'entité et le système schématisé.

* **Process**: Une activité qui change ou transforme les flux de données. Puisqu'ils transforment les données entrantes en données sortantes, tous les processus doivent avoir des entrées et des sorties.

* **Data Store**: Les flux d'entrée vers un magasin de données incluent des informations ou des opérations qui modifient les données stockées. Les flux de sortie seraient des données extraites du magasin.

* **Data flow**: Le mouvement des données entre les entités externes, les processus et les magasins de données est représenté par un symbole de flèche, qui indique la direction du flux. Les flux de données d'entrée et de sortie sont étiquetés en fonction du type de données ou de son processus ou magasin de données associé, et ce nom est écrit à côté de la flèche.

![image](https://raw.githubusercontent.com/seeren-training/Methodo/master/wiki/resources/dataflow.png)

___

👨🏻‍💻 Manipulation

Concluez vos spécifications par la rédaction collégiale d'un Data Flow Diagram, mis en relation sur votre diagramme de contrainte.

___