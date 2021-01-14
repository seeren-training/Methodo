# Data

* 🔖 **Conception Générale**
* 🔖 **Conception détaillée**

Vos différentes vues filaires vous permettent de mettre en place les règles de gestion.

___

## 📑 Conception Générale

Les entités métier étant définies, nous avons besoins de conceptualiser les participants accomplissant les objectifs métiers.

### 🏷️ **Packages**


En fonction de vos choix techniques, utilisez la vue développement pour vous documenter sur les pratiques de vos outils via la représentation des différentes couches.

> Votre méthodologie d'analyse vous permet de vous appuyer sur les vues filaires et les identifiants des systèmes des cas d'utilisation pour packager votre front end

___

👨🏻‍💻 Manipulation

Créez de façon collégiale votre diagramme de package.

___

### 🏷️ **Classes**

Ayant utilisé une vue à grande échelle, affinez la avec le diagramme de classe pour qualifier les participants à l'exécution.

> Votre méthodologie d'analyse vous permet de vous appuyer sur les identifiants des systèmes et les cas d'utilisation pour définir la structures de vos classes controlleurs ou composants

___

👨🏻‍💻 Manipulation

Créez de façon collégiale votre diagramme de classe.

___

### 🏷️ **Séquences**

L'échelle se réduit sur l’exécution. Ayant déterminé les participants vous devez exprimer de quel façon ils participent à atteindre les objectifs métiers.

> Votre méthodologie d'analyse vous permet de vous appuyer sur le data flow et le diagramme de navigation pour rédiger vos séquences à mettre en rapport avec un cas d'utilisation

___

👨🏻‍💻 Manipulation

Créez de façon individuelle un diagramme de séquence pour chaque diagramme de cas d'utilisation. Liez les séquences au diagramme de contrainte pour compléter la conception générale suite à l'expression des besoins.

___

## 📑 Conception Détaillée

La valeur de la modélisation chute et la qualité d'un développeur est maintenant de proposer des solutions syntaxiques pour implémenter les vues exprimées.

### 🏷️ **Séquences**

Des séquences complémentaires peuvent être utiliser pour affiner des concepts.

> Ces séquences ne sont pas liés aux histoires utilisateurs mais aux contraintes de ces histoires utilisateurs. Ils expriment l'exécution nécessaire pour satisfaire une contrainte et il est souvent nécessaire de faire des allez retour avec le diagramme de classe pour ajouter des acteurs non anticipés.

Ces séquences sont là pour palier l'évidence de concepts exprimés dans les contraintes comme par exemple l'échange de jeton pour autorisation, la gestion du CSRF, la mise en cache chez le client ou autre contraintes qui méritent d'être clarifiés.

___

👨🏻‍💻 Manipulation

Créez de façon collégiale un diagramme de séquence pour les contraintes qui méritent d'être clarifiés.

___

### 🏷️ **Activités**

Le diagramme d'activité avec sa représentation des arguments, des évènements et des blocs d’exceptions est la représentation la plus fine offerte.

Il peut être utilisé à plusieurs échelles mais avec le travail accompli précédemment il devrait faire un focus sur une action d'un système, donc un message d'une séquence pour détailler son pas à pas d’exécution.

Il peut être utilisé pour représenter une échelle globale sur un concept comme le cycle de vie d’exécution et les évènements internes, un pattern, les étapes de validation d'un jeton ou autre notion s'appliquant éventuellement à un ensemble de message d'une séquence.

___

👨🏻‍💻 Manipulation

De façon individuelle, créez un diagramme d'activité pour détailler un message ou un concept.

___
