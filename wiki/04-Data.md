# Data

* 🔖 **Règles de gestion**
* 🔖 **Dictionnaire de données**
* 🔖 **Diagrammes**

Vos différentes vues filaires vous permettent de mettre en place les règles de gestion.

___

## 📑 Règles de gestion

Les règles métier ou de gestion sont des déclarations de haut niveau structurées qui permettent de contraindre, contrôler et influencer un aspect du métier. Aussi ces dernières peuvent diminuer ou augmenter l'impact de risque, et encore prendre des décisions rationnelles.

> Avant de pouvoir créer votre couche modèle, les règles de gestion vont permettre de déterminer leur structure, type et contraintes sans être orienté par un système précis. Vous devez suivre les étapes suivantes pour les déterminer.

### 🏷️ **Déterminer un sujet**

* *Utilisateur*

### 🏷️ **Déterminer sa structure**

* Chaque *Utilisateur* possède
    * Un Email
    * Un mot de passe
    * Des messages

### 🏷️ **Déterminer ses contraintes**

|Chaque *Utilisateur* possède|Chaque *Utilisateur* peut|
|-|-|
|Un Email|Être identifié par son email|
|Un mot de passe|Se connecter/déconnecter|
|Des messages| Recevoir/Lire des messages|

___

👨🏻‍💻 Manipulation

De façon collégiale, rédigez vos règles de gestion en  markdown dans un fichier "buisness-rules.md" que vous attachez au final en commentaire sur un diagramme d'entité.

___

## 📑 Dictionnaire de données

Vos règles de gestion ont déterminé des sujets qui deviennent des tables, des attributs qui deviennent des colonnes et des contraintes qui deviennent des tailles, type, options et clefs.

> Vous devez préciser les colonnes suivantes pour chaque sujet.

|Nom|Type|Taille|Contrainte|Calcul|
|-|-|-|-|-|
|**user**|-|-|-|-|
|id|INT|11|PK|+1|
|email|VARCHAR|128|U|-|
|password|CHAR|64|U|-|
|message_id|INT|11|FK|-|

___

👨🏻‍💻 Manipulation

De façon collégiale, rédigez votre dictionnaire de données au même format que les règles de métier et attachés de la même façon.

___

## 📑 Diagrammes

Les prochaines étapes correspondent à créer le Model Conceptuel de Données sur lequel nous passons parce qu'étudié et appartenant à Merise.

<img src="https://raw.githubusercontent.com/seeren-training/Methodo/master/wiki/resources/entity.png" align="left" width="50%"/>

<img src="https://raw.githubusercontent.com/seeren-training/Methodo/master/wiki/resources/class.png" align="left" width="50%"/>

L'Entity Diagram puis enfin le diagramme de classe en ne représentant pas les tables intermédiaires complètent l'analyse du besoin et sont les premiers éléments conceptuels.

___

👨🏻‍💻 Manipulation

Créez en parallèle le diagramme d'entité et le diagramme de classe. Les documents produits doivent être accessibles à tous.

___