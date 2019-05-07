---

copyright:
  years: 2015, 2019
lastupdated: "2019-01-31"

subcollection: assistant

---

{:curl: #curl .ph data-hd-programlang='curl'}
{:javascript: #javascript .ph data-hd-programlang='javascript'}
{:java: #java .ph data-hd-programlang='java'}
{:python: #python .ph data-hd-programlang='python'}
{:swift: data-hd-programlang='swift'}
{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:screen: .screen}
{:pre: .pre}
{:codeblock: .codeblock}
{:download: .download}
{:deprecated: .deprecated}
{:important: .important}
{:note: .note}
{:deprecated: .deprecated}
{:important: .important}
{:note: .note}
{:tip: .tip}

# Récapitulatif des méthodes d'API 
{: #api-methods}

Les tableaux suivants répertorient les méthodes disponibles à l'aide des API {{site.data.keyword.conversationshort}}.

## Méthodes d’exécution 
{: #api-methods-runtime}

| Méthode | Description | Ver API | Référence |
|:-------|:------------|:-------:|:---------:|
| **Créer une session** | Création d'une session. Une session permet d'envoyer une entrée utilisateur à une compétence et de recevoir des réponses. Elle gère également l'état de la conversation. | v2 | [cURL](https://{DomainName}/apidocs/assistant-v2#create-a-session){: new_window} [node](https://{DomainName}/apidocs/assistant-v2?language=node#create-a-session){: new_window} [java](https://{DomainName}/apidocs/assistant-v2?language=java#create-a-session){: new_window} [python](https://{DomainName}/apidocs/assistant-v2?language=python#create-a-session){: new_window} |
| **Supprimer une session** | Suppression explicite d'une session avant son expiration. | v2 | [cURL](https://{DomainName}/apidocs/assistant-v2#delete-session){: new_window} [node](https://{DomainName}/apidocs/assistant-v2?language=node#delete-session){: new_window} [java](https://{DomainName}/apidocs/assistant-v2?language=java#delete-session){: new_window} [python](https://{DomainName}/apidocs/assistant-v2?language=python#delete-session){: new_window} |
| **Envoyer une entrée utilisateur à l'assistant** | Envoi d'une entrée utilisateur à un assistant et réception d'une réponse. | v2 | [cURL](https://{DomainName}/apidocs/assistant-v2#send-user-input-to-assistant){: new_window} [node](https://{DomainName}/apidocs/assistant-v2?language=node#send-user-input-to-assistant){: new_window} [java](https://{DomainName}/apidocs/assistant-v2?language=java#send-user-input-to-assistant){: new_window} [python](https://{DomainName}/apidocs/assistant-v2?language=python#send-user-input-to-assistant){: new_window} |
| **Obtenir une réponse à l'entrée utilisateur** | Envoi d'une entrée utilisateur à un espace de travail et réception d'une réponse. | v1 | [cURL](https://{DomainName}/apidocs/assistant#get-response-to-user-input){: new_window} [node](https://{DomainName}/apidocs/assistant?language=node#get-response-to-user-input){: new_window} [java](https://{DomainName}/apidocs/assistant?language=java#get-response-to-user-input){: new_window} [python](https://{DomainName}/apidocs/assistant?language=python#get-response-to-user-input){: new_window} |

## Méthodes de création 
{: #api-methods-authoring}

| Méthode | Description | Ver API | Référence |
|:-------|:------------|:-------:|:---------:|
| **Répertorier les espaces de travail** | Liste des espaces de travail associés à une instance de service de Watson Assistant. | v1 | [cURL](https://{DomainName}/apidocs/assistant#list-workspaces){: new_window} [node](https://{DomainName}/apidocs/assistant?language=node#list-workspaces){: new_window} [java](https://{DomainName}/apidocs/assistant?language=java#list-workspaces){: new_window} [python](https://{DomainName}/apidocs/assistant?language=python#list-workspaces){: new_window} |
| **Créer un espace de travail** | Création d'un espace de travail basé sur des objets de composant. Vous devez fournir des composants d'espace de travail définissant le contenu du nouvel espace de travail. | v1 | [cURL](https://{DomainName}/apidocs/assistant#create-workspace){: new_window} [node](https://{DomainName}/apidocs/assistant?language=node#create-workspace){: new_window} [java](https://{DomainName}/apidocs/assistant?language=java#create-workspace){: new_window} [python](https://{DomainName}/apidocs/assistant?language=python#create-workspace){: new_window} |
| **Obtenir des informations sur un espace de travail** | Obtention d'informations sur un espace de travail, y compris éventuellement tout son contenu. | v1 | [cURL](https://{DomainName}/apidocs/assistant#get-information-about-a-workspace){: new_window} [node](https://{DomainName}/apidocs/assistant?language=node#get-information-about-a-workspace){: new_window} [java](https://{DomainName}/apidocs/assistant?language=java#get-information-about-a-workspace){: new_window} [python](https://{DomainName}/apidocs/assistant?language=python#get-information-about-a-workspace){: new_window} |
| **Mettre à jour un espace de travail** | Mise à jour d'un espace de travail existant avec des données nouvelles ou modifiées. Vous devez fournir des objets de composant définissant le contenu de l'espace de travail mis à jour. | v1 | [cURL](https://{DomainName}/apidocs/assistant#update-workspace){: new_window} [node](https://{DomainName}/apidocs/assistant?language=node#update-workspace){: new_window} [java](https://{DomainName}/apidocs/assistant?language=java#update-workspace){: new_window} [python](https://{DomainName}/apidocs/assistant?language=python#update-workspace){: new_window} |
| **Supprimer un espace de travail** | Suppression d'un espace de travail de l'instance de service. | v1 | [cURL](https://{DomainName}/apidocs/assistant#delete-workspace){: new_window} [node](https://{DomainName}/apidocs/assistant?language=node#delete-workspace){: new_window} [java](https://{DomainName}/apidocs/assistant?language=java#delete-workspace){: new_window} [python](https://{DomainName}/apidocs/assistant?language=python#delete-workspace){: new_window} |
| **Répertorier les intentions** | Liste des intentions pour un espace de travail. | v1 | [cURL](https://{DomainName}/apidocs/assistant#list-intents){: new_window} [node](https://{DomainName}/apidocs/assistant?language=node#list-intents){: new_window} [java](https://{DomainName}/apidocs/assistant?language=java#list-intents){: new_window} [python](https://{DomainName}/apidocs/assistant?language=python#list-intents){: new_window} |
| **Créer une intention** | Création d'une intention. | v1 | [cURL](https://{DomainName}/apidocs/assistant#create-intent){: new_window} [node](https://{DomainName}/apidocs/assistant?language=node#create-intent){: new_window} [java](https://{DomainName}/apidocs/assistant?language=java#create-intent){: new_window} [python](https://{DomainName}/apidocs/assistant?language=python#create-intent){: new_window} |
| **Obtenir une intention** | Obtention d'informations sur une intention, y compris éventuellement tout son contenu. | v1 | [cURL](https://{DomainName}/apidocs/assistant#get-intent){: new_window} [node](https://{DomainName}/apidocs/assistant?language=node#get-intent){: new_window} [java](https://{DomainName}/apidocs/assistant?language=java#get-intent){: new_window} [python](https://{DomainName}/apidocs/assistant?language=python#get-intent){: new_window} |
| **Mettre à jour une intention** | Mise à jour d'une intention existante avec des données nouvelles ou modifiées. Vous devez fournir des objets de composant définissant le contenu de l'intention mise à jour. | v1 | [cURL](https://{DomainName}/apidocs/assistant#update-intent){: new_window} [node](https://{DomainName}/apidocs/assistant?language=node#update-intent){: new_window} [java](https://{DomainName}/apidocs/assistant?language=java#update-intent){: new_window} [python](https://{DomainName}/apidocs/assistant?language=python#update-intent){: new_window} |
| **Supprimer l'intention** | Suppression d'une intention d'un espace de travail. | v1 | [cURL](https://{DomainName}/apidocs/assistant#delete-intent){: new_window} [node](https://{DomainName}/apidocs/assistant?language=node#delete-intent){: new_window} [java](https://{DomainName}/apidocs/assistant?language=java#delete-intent){: new_window} [python](https://{DomainName}/apidocs/assistant?language=python#delete-intent){: new_window} |
| **Répertorier des exemples d'entrées utilisateur** | Liste des exemples d'entrée utilisateur pour une intention, en incluant éventuellement des mentions d'entités contextuelles. | v1 | [cURL](https://{DomainName}/apidocs/assistant#list-user-input-examples){: new_window} [node](https://{DomainName}/apidocs/assistant?language=node#list-user-input-examples){: new_window} [java](https://{DomainName}/apidocs/assistant?language=java#list-user-input-examples){: new_window} [python](https://{DomainName}/apidocs/assistant?language=python#list-user-input-examples){: new_window} |
| **Créer un exemple d'entrée utilisateur** | Ajout d'un nouvel exemple d'entrée utilisateur à une intention. | v1 | [cURL](https://{DomainName}/apidocs/assistant#create-user-input-example){: new_window} [node](https://{DomainName}/apidocs/assistant?language=node#create-user-input-example){: new_window} [java](https://{DomainName}/apidocs/assistant?language=java#create-user-input-example){: new_window} [python](https://{DomainName}/apidocs/assistant?language=python#create-user-input-example){: new_window} |
| **Obtenir un exemple d'entrée utilisateur** | Extraction des informations sur un exemple d'entrée utilisateur. | v1 | [cURL](https://{DomainName}/apidocs/assistant#get-user-input-example){: new_window} [node](https://{DomainName}/apidocs/assistant?language=node#get-user-input-example){: new_window} [java](https://{DomainName}/apidocs/assistant?language=java#get-user-input-example){: new_window} [python](https://{DomainName}/apidocs/assistant?language=python#get-user-input-example){: new_window} |
| **Mettre à jour un exemple d'entrée utilisateur** | Mise à jour du texte d'un exemple d'entrée utilisateur. | v1 | [cURL](https://{DomainName}/apidocs/assistant#update-user-input-example){: new_window} [node](https://{DomainName}/apidocs/assistant?language=node#update-user-input-example){: new_window} [java](https://{DomainName}/apidocs/assistant?language=java#update-user-input-example){: new_window} [python](https://{DomainName}/apidocs/assistant?language=python#update-user-input-example){: new_window} |
| **Supprimer un exemple d'entrée utilisateur** | Suppression d'un exemple d'entrée utilisateur d'un intention. | v1 | [cURL](https://{DomainName}/apidocs/assistant#delete-user-input-example){: new_window} [node](https://{DomainName}/apidocs/assistant?language=node#delete-user-input-example){: new_window} [java](https://{DomainName}/apidocs/assistant?language=java#delete-user-input-example){: new_window} [python](https://{DomainName}/apidocs/assistant?language=python#delete-user-input-example){: new_window} |
| **Répertorier les contre-exemples** | Liste des contre-exemples pour un espace de travail. Les contre-exemples sont des exemples qui ont été marqués comme des entrées non pertinentes. | v1 | [cURL](https://{DomainName}/apidocs/assistant#list-counterexamples){: new_window} [node](https://{DomainName}/apidocs/assistant?language=node#list-counterexamples){: new_window} [java](https://{DomainName}/apidocs/assistant?language=java#list-counterexamples){: new_window} [python](https://{DomainName}/apidocs/assistant?language=python#list-counterexamples){: new_window} |
| **Créer un contre-exemple** | Ajout d'un nouveau contre-exemple à un espace de travail. Les contre-exemples sont des exemples qui ont été marqués comme des entrées non pertinentes. | v1 | [cURL](https://{DomainName}/apidocs/assistant#create-counterexample){: new_window} [node](https://{DomainName}/apidocs/assistant?language=node#create-counterexample){: new_window} [java](https://{DomainName}/apidocs/assistant?language=java#create-counterexample){: new_window} [python](https://{DomainName}/apidocs/assistant?language=python#create-counterexample){: new_window} |
| **Obtenir un contre-exemple** | Obtention d'informations sur un exemple de compteur. Les contre-exemples sont des exemples qui ont été marqués comme des entrées non pertinentes. | v1 | [cURL](https://{DomainName}/apidocs/assistant#get-counterexample){: new_window} [node](https://{DomainName}/apidocs/assistant?language=node#get-counterexample){: new_window} [java](https://{DomainName}/apidocs/assistant?language=java#get-counterexample){: new_window} [python](https://{DomainName}/apidocs/assistant?language=python#get-counterexample){: new_window} |
| **Mettre à jour un contre-exemple** | Mise à jour du texte d'un contre-exemple. Les contre-exemples sont des exemples qui ont été marqués comme des entrées non pertinentes. | v1 | [cURL](https://{DomainName}/apidocs/assistant#update-counterexample){: new_window} [node](https://{DomainName}/apidocs/assistant?language=node#update-counterexample){: new_window} [java](https://{DomainName}/apidocs/assistant?language=java#update-counterexample){: new_window} [python](https://{DomainName}/apidocs/assistant?language=python#update-counterexample){: new_window} |
| **Supprimer un contre-exemple** | Suppression d'un contre-exemple dans un espace de travail. Les contre-exemples sont des exemples qui ont été marqués comme des entrées non pertinentes. | v1 | [cURL](https://{DomainName}/apidocs/assistant#delete-counterexample){: new_window} [node](https://{DomainName}/apidocs/assistant?language=node#delete-counterexample){: new_window} [java](https://{DomainName}/apidocs/assistant?language=java#delete-counterexample){: new_window} [python](https://{DomainName}/apidocs/assistant?language=python#delete-counterexample){: new_window} |
| **Répertorier les entités** | Liste des entités pour un espace de travail. | v1 | [cURL](https://{DomainName}/apidocs/assistant#list-entities){: new_window} [node](https://{DomainName}/apidocs/assistant?language=node#list-entities){: new_window} [java](https://{DomainName}/apidocs/assistant?language=java#list-entities){: new_window} [python](https://{DomainName}/apidocs/assistant?language=python#list-entities){: new_window} |
| **Créer une entité** | Création d'une entité ou activation d'une entité système. | v1 | [cURL](https://{DomainName}/apidocs/assistant#create-entity){: new_window} [node](https://{DomainName}/apidocs/assistant?language=node#create-entity){: new_window} [java](https://{DomainName}/apidocs/assistant?language=java#create-entity){: new_window} [python](https://{DomainName}/apidocs/assistant?language=python#create-entity){: new_window} |
| **Obtenir une entité** | Obtention d'informations sur une entité, y compris éventuellement tout son contenu. | v1 | [cURL](https://{DomainName}/apidocs/assistant#get-entity){: new_window} [node](https://{DomainName}/apidocs/assistant?language=node#get-entity){: new_window} [java](https://{DomainName}/apidocs/assistant?language=java#get-entity){: new_window} [python](https://{DomainName}/apidocs/assistant?language=python#get-entity){: new_window} |
| **Mettre à jour une entité** | Mise à jour d'une entité existante avec des données nouvelles ou modifiées. Vous devez fournir des objets de composant définissant le contenu de l'entité mise à jour. | v1 | [cURL](https://{DomainName}/apidocs/assistant#update-entity){: new_window} [node](https://{DomainName}/apidocs/assistant?language=node#update-entity){: new_window} [java](https://{DomainName}/apidocs/assistant?language=java#update-entity){: new_window} [python](https://{DomainName}/apidocs/assistant?language=python#update-entity){: new_window} |
| **Supprimer une entité** | Suppression d'une entité d'un espace de travail ou désactivation d'une entité système. | v1 | [cURL](https://{DomainName}/apidocs/assistant#delete-entity){: new_window} [node](https://{DomainName}/apidocs/assistant?language=node#delete-entity){: new_window} [java](https://{DomainName}/apidocs/assistant?language=java#delete-entity){: new_window} [python](https://{DomainName}/apidocs/assistant?language=python#delete-entity){: new_window} |
| **Répertorier les mentions d'entité** | Liste des mentions pour une entité contextuelle. Une mention d'entité est l'occurrence d'une entité contextuelle dans le cadre d'un exemple d'entrée d'utilisateur d'intention. | v1 | [cURL](https://{DomainName}/apidocs/assistant#list-entity-mentions){: new_window} [node](https://{DomainName}/apidocs/assistant?language=node#list-entity-mentions){: new_window} [java](https://{DomainName}/apidocs/assistant?language=java#list-entity-mentions){: new_window} [python](https://{DomainName}/apidocs/assistant?language=python#list-entity-mentions){: new_window} |
| **Répertorier les valeurs d'entité** | Liste des valeurs d'une entité. | v1 | [cURL](https://{DomainName}/apidocs/assistant#list-entity-values){: new_window} [node](https://{DomainName}/apidocs/assistant?language=node#list-entity-values){: new_window} [java](https://{DomainName}/apidocs/assistant?language=java#list-entity-values){: new_window} [python](https://{DomainName}/apidocs/assistant?language=python#list-entity-values){: new_window} |
| **Ajouter une valeur d'entité** | Création d'une valeur pour une entité. | v1 | [cURL](https://{DomainName}/apidocs/assistant#add-entity-value){: new_window} [node](https://{DomainName}/apidocs/assistant?language=node#add-entity-value){: new_window} [java](https://{DomainName}/apidocs/assistant?language=java#add-entity-value){: new_window} [python](https://{DomainName}/apidocs/assistant?language=python#add-entity-value){: new_window} |
| **Obtenir une valeur d'entité** | Obtention d'informations sur une valeur d'entité. | v1 | [cURL](https://{DomainName}/apidocs/assistant#get-entity-value){: new_window} [node](https://{DomainName}/apidocs/assistant?language=node#get-entity-value){: new_window} [java](https://{DomainName}/apidocs/assistant?language=java#get-entity-value){: new_window} [python](https://{DomainName}/apidocs/assistant?language=python#get-entity-value){: new_window} |
| **Mettre à jour une valeur d'entité** | Mise à jour d'une valeur d'entité existante avec des données nouvelles ou modifiées. Vous devez fournir des objets de composant définissant le contenu de la valeur d'entité mise à jour. | v1 | [cURL](https://{DomainName}/apidocs/assistant#update-entity-value){: new_window} [node](https://{DomainName}/apidocs/assistant?language=node#update-entity-value){: new_window} [java](https://{DomainName}/apidocs/assistant?language=java#update-entity-value){: new_window} [python](https://{DomainName}/apidocs/assistant?language=python#update-entity-value){: new_window} |
| **Supprimer une valeur d'entité** | Suppression d'une valeur d'entité. | v1 | [cURL](https://{DomainName}/apidocs/assistant#delete-entity-value){: new_window} [node](https://{DomainName}/apidocs/assistant?language=node#delete-entity-value){: new_window} [java](https://{DomainName}/apidocs/assistant?language=java#delete-entity-value){: new_window} [python](https://{DomainName}/apidocs/assistant?language=python#delete-entity-value){: new_window} |
| **Répertorier les synonymes de valeur d'entité** | Liste des synonymes d'une valeur d'entité. | v1 | [cURL](https://{DomainName}/apidocs/assistant#list-entity-value-synonyms){: new_window} [node](https://{DomainName}/apidocs/assistant?language=node#list-entity-value-synonyms){: new_window} [java](https://{DomainName}/apidocs/assistant?language=java#list-entity-value-synonyms){: new_window} [python](https://{DomainName}/apidocs/assistant?language=python#list-entity-value-synonyms){: new_window} |
| **Ajouter un synonyme de valeur d'entité** | Ajout d'un nouveau synonyme de valeur d'entité. | v1 | [cURL](https://{DomainName}/apidocs/assistant#add-entity-value-synonym){: new_window} [node](https://{DomainName}/apidocs/assistant?language=node#add-entity-value-synonym){: new_window} [java](https://{DomainName}/apidocs/assistant?language=java#add-entity-value-synonym){: new_window} [python](https://{DomainName}/apidocs/assistant?language=python#add-entity-value-synonym){: new_window} |
| **Obtenir un synonyme de valeur d'entité** | Obtention d'informations sur un synonyme de valeur d'entité. | v1 | [cURL](https://{DomainName}/apidocs/assistant#get-entity-value-synonym){: new_window} [node](https://{DomainName}/apidocs/assistant?language=node#get-entity-value-synonym){: new_window} [java](https://{DomainName}/apidocs/assistant?language=java#get-entity-value-synonym){: new_window} [python](https://{DomainName}/apidocs/assistant?language=python#get-entity-value-synonym){: new_window} |
| **Mettre à jour un synonyme de valeur d'entité** | Mise à jour d'un synonyme de valeur d'entité existant avec un nouveau texte. | v1 | [cURL](https://{DomainName}/apidocs/assistant#update-entity-value-synonym){: new_window} [node](https://{DomainName}/apidocs/assistant?language=node#update-entity-value-synonym){: new_window} [java](https://{DomainName}/apidocs/assistant?language=java#update-entity-value-synonym){: new_window} [python](https://{DomainName}/apidocs/assistant?language=python#update-entity-value-synonym){: new_window} |
| **Supprimer un synonyme de valeur d'entité** | Suppression d'un synonyme dans une valeur d'entité. | v1 | [cURL](https://{DomainName}/apidocs/assistant#delete-entity-value-synonym){: new_window} [node](https://{DomainName}/apidocs/assistant?language=node#delete-entity-value-synonym){: new_window} [java](https://{DomainName}/apidocs/assistant?language=java#delete-entity-value-synonym){: new_window} [python](https://{DomainName}/apidocs/assistant?language=python#delete-entity-value-synonym){: new_window} |
| **Répertorier les noeuds de dialogue** | Liste des noeuds de dialogue d'un espace de travail. | v1 | [cURL](https://{DomainName}/apidocs/assistant#list-dialog-nodes){: new_window} [node](https://{DomainName}/apidocs/assistant?language=node#list-dialog-nodes){: new_window} [java](https://{DomainName}/apidocs/assistant?language=java#list-dialog-nodes){: new_window} [python](https://{DomainName}/apidocs/assistant?language=python#list-dialog-nodes){: new_window} |
| **Créer un noeud de dialogue** | Création d'un noeud de dialogue. | v1 | [cURL](https://{DomainName}/apidocs/assistant#create-dialog-node){: new_window} [node](https://{DomainName}/apidocs/assistant?language=node#create-dialog-node){: new_window} [java](https://{DomainName}/apidocs/assistant?language=java#create-dialog-node){: new_window} [python](https://{DomainName}/apidocs/assistant?language=python#create-dialog-node){: new_window} |
| **Obtenir un noeud de dialogue** | Obtention d'informations sur un noeud de dialogue. | v1 | [cURL](https://{DomainName}/apidocs/assistant#get-dialog-node){: new_window} [node](https://{DomainName}/apidocs/assistant?language=node#get-dialog-node){: new_window} [java](https://{DomainName}/apidocs/assistant?language=java#get-dialog-node){: new_window} [python](https://{DomainName}/apidocs/assistant?language=python#get-dialog-node){: new_window} |
| **Mettre à jour un noeud de dialogue** | Mise à jour d'un noeud de dialogue existant avec des données nouvelles ou modifiées. | v1 | [cURL](https://{DomainName}/apidocs/assistant#update-dialog-node){: new_window} [node](https://{DomainName}/apidocs/assistant?language=node#update-dialog-node){: new_window} [java](https://{DomainName}/apidocs/assistant?language=java#update-dialog-node){: new_window} [python](https://{DomainName}/apidocs/assistant?language=python#update-dialog-node){: new_window} |
| **Supprimer un noeud de dialogue** | Suppression d'un noeud de dialogue dans un espace de travail. | v1 | [cURL](https://{DomainName}/apidocs/assistant#delete-dialog-node){: new_window} [node](https://{DomainName}/apidocs/assistant?language=node#delete-dialog-node){: new_window} [java](https://{DomainName}/apidocs/assistant?language=java#delete-dialog-node){: new_window} [python](https://{DomainName}/apidocs/assistant?language=python#delete-dialog-node){: new_window} |
| **Répertorier les événements de journal dans un espace de travail** | Liste des événements issus du journal d'un espace de travail spécifique. | v1 | [cURL](https://{DomainName}/apidocs/assistant#list-log-events-in-a-workspace){: new_window} [node](https://{DomainName}/apidocs/assistant?language=node#list-log-events-in-a-workspace){: new_window} [java](https://{DomainName}/apidocs/assistant?language=java#list-log-events-in-a-workspace){: new_window} [python](https://{DomainName}/apidocs/assistant?language=python#list-log-events-in-a-workspace){: new_window} |
| **Répertorier les événements de journal dans tous les espaces de travail** | Liste des événements issus des journaux de tous les espaces de travail dans l'instance de service. | v1 | [cURL](https://{DomainName}/apidocs/assistant#list-log-events-in-all-workspaces){: new_window} [node](https://{DomainName}/apidocs/assistant?language=node#list-log-events-in-all-workspaces){: new_window} [java](https://{DomainName}/apidocs/assistant?language=java#list-log-events-in-all-workspaces){: new_window} [python](https://{DomainName}/apidocs/assistant?language=python#list-log-events-in-all-workspaces){: new_window} |
| **Supprimer les données libellées** | Suppression de toutes les données associées à un ID client spécifié. La méthode n'a aucun effet si aucune donnée n'est associée à l'ID client. | v1 | [cURL](https://{DomainName}/apidocs/assistant#delete-labeled-data){: new_window} [node](https://{DomainName}/apidocs/assistant?language=node#delete-labeled-data){: new_window} [java](https://{DomainName}/apidocs/assistant?language=java#delete-labeled-data){: new_window} [python](https://{DomainName}/apidocs/assistant?language=python#delete-labeled-data){: new_window} |