# Gestion Dockers

## Liste des demandes de docker

Cette section permet de consulter et rechercher la liste complète des demandes de dockers enregistrées dans le système, ou d'en ajouter de nouvelles. Chaque ligne du tableau contient les informations suivantes : 

-Référence
-Création
-Navire
-Chantier
-Opération
-Date
-Heure
-Effectif
-Statut
-Actions : Un bouton d'action permettant d'accéder aux détails, de confirmer, d'annuler ou de modifier les informations, ou encore de clôturer une demande si elle est déjà en cours d'exécution.

![Liste des demandes de docker](demande_embauche.png)

### Filtres de recherche

Plusieurs filtres sont disponibles pour faciliter la recherche d'une demande de docker spécifique : Cliquer sur le bouton "Cliquez ici pour faire une recherche avancée" pour rechercher.

- **Références** : Rechercher par le numéro de demande.
- **Société** : Rechercher par le nom de la société.
- **Navire** : Rechercher par le nom du navire.
- **Chantier** : Rechercher par le nom du chantier.
- **Opération** : Rechercher par le type d'opération.
- **Début période** : Rechercher par la date de début.
- **Fin période** : Rechercher par la date de fin.
- **Statut** : Rechercher par le statut de la demande.

### Résultats

La liste affiche les informations suivantes pour chaque docker:
- **Références** : Le numéro de demande attribué.
- **Société** : Le nom de la société.
- **Navire** : Le nom du navire. 
- **Chantier** : Le nom du chantier.
- **Opération** : Le type d'opération.
- **Début période** : La date de début.
- **Fin période** : La date de fin.
- **Statut** : Le statut de la demande.

![Rechercher ](demande_embauche.png)

### Création de demande Docker
Pour ajouter une nouvelle demande docker, cliquez sur le bouton d'ajout "Nouvelle demande" en haut à droite. Cela vous redirigera vers une page où vous remplirez le formulaire de création et ensuite vous cliquerez sur le bouton "Enregistrer"

## Modifier une demande Docker
Pour modifier les informations d'une demande Docker, cliquez sur le bouton "Modifier" et changer les informations au niveau des champs du formulaire voulu.
Une fois les modifications apportées, cliquez sur "Mettre à jour" pour enregistrer les changements.

### Suppression d'une demande Docker
Pour supprimer une demande Docker :
1. Cliquez sur le bouton Annuler (avec une icône de poubelle) situé dans la colonne "Actions" de la ligne correspondant à la demande Docker que vous souhaitez supprimer.
2. Une confirmation peut être demandée.
3. La demande Docker sera supprimée de la liste.


## Liste des demandes Dockers en attente

La page de liste des demandes Dockers affiche toutes les demandes Dockers en attente dans un tableau. Chaque ligne du tableau contient les informations suivantes :
-Référence
-Demandeur
-Navire
-Chantier
-Opération
-Date
-Effectif
-Statut
-Actions (recruter, changer le statut)

![Liste des embauches Dockers en attente](traitement_embauche.png)

### Filtres de recherche

Plusieurs filtres sont disponibles pour faciliter la recherche d'une demande docker en attente : Cliquer sur le bouton "Cliquez ici pour faire une recherche avancée" pour rechercher.

- **Référence** : Rechercher par la référence.
- **Société** : Rechercher par le nom de la société.
- **Navire** : Rechercher par le nom du navire.
- **Début période** : Rechercher par la date de début.
- **Fin période** : Rechercher par la date de fin.
- **Statut** : Rechercher par le statut de la demande.

### Résultats

La liste affiche les informations suivantes pour chaque demande docker en attente :
- **Références** : Le numéro de demande attribué.
- **Société** : Le nom de la société.
- **Navire** : Le nom du navire. 
- **Début période** : La date de début.
- **Fin période** : La date de fin.
- **Statut** : Le statut de la demande.
- **Actions** : Un bouton d'action permettant le changer de statut ou de recruter.


## Liste des embauches Dockers

La page de liste des embauches Dockers affiche toutes les embauches Dockers existantes dans un tableau. Chaque ligne du tableau contient les informations suivantes :
- Référence
- Opération
- Début
- Fin
- Effectif
- Demandeur
- Statut
- Actions (Détails, Activer Badges, Changer le statut, Supprimer)

![Liste des embauches Dockers](toutes_embauche.png)

### Suppression d'une embauche Docker...
Pour supprimer une embauche Docker :
1. Cliquez sur le bouton "Supprimer" situé dans la colonne "Action" de la ligne correspondant à l'embauche Docker que vous souhaitez supprimer.
2. Une confirmation peut être demandée.
3. L'embauche Docker sera supprimée de la liste.

### Embauches à Démarrer

Cette section affiche la liste des embauches de dockers qui sont prêtes à être démarrées.

![Embauches à Démarrer](embauche_demarrer.png)

#### Filtres de recherche

Plusieurs filtres sont disponibles pour faciliter la recherche d'une embauche à démarrer :

- **Références** : Rechercher par le numéro de demande.
- **Société** : Rechercher par le nom de la société.
- **Navire** : Rechercher par le nom du navire.
- **Chantier** : Rechercher par le nom du chantier.
- **Opération** : Rechercher par le type d'opération.
- **Début période** : Rechercher par la date de début.
- **Fin période** : Rechercher par la date de fin.

#### Résultats

La liste affiche les informations suivantes pour chaque embauche à démarrer :

- **Références** : Le numéro de demande attribué.
- **Société** : Le nom de la société.
- **Navire** : Le nom du navire.
- **Chantier** : Le nom du chantier.
- **Opération** : Le type d'opération.
- **Début période** : La date de début.
- **Fin période** : La date de fin.
- **Actions** : Un bouton d'action permettant de démarrer l'embauche.

### Embauches à Exécuter

Cette section affiche la liste des embauches de dockers qui sont prêtes à être exécutées.

![Embauches à Exécuter](embauche_executer.png)

#### Filtres de recherche

Plusieurs filtres sont disponibles pour faciliter la recherche d'une embauche à exécuter :

- **Références** : Rechercher par le numéro de demande.
- **Société** : Rechercher par le nom de la société.
- **Début période** : Rechercher par la date de début.
- **Fin période** : Rechercher par la date de fin.

#### Résultats

La liste affiche les informations suivantes pour chaque embauche à exécuter :

- **Références** : Le numéro de demande attribué.
- **Société** : Le nom de la société.
- **Début période** : La date de début.
- **Fin période** : La date de fin.


### Embauches à Clôturer

Cette section affiche la liste des embauches de dockers qui sont prêtes à être clôturées.

![Embauches à Cloturer](embauche_cloturer.png)

#### Filtres de recherche  

Plusieurs filtres sont disponibles pour faciliter la recherche d'une embauche à clôturer :

- **Références** : Rechercher par le numéro de demande.
- **Société** : Rechercher par le nom de la société.
- **Navire** : Rechercher par le nom du navire.
- **Chantier** : Rechercher par le nom du chantier.
- **Opération** : Rechercher par le type d'opération. 
- **Début période** : Rechercher par la date de début.
- **Fin période** : Rechercher par la date de fin.

#### Résultats

La liste affiche les informations suivantes pour chaque embauche à clôturer :

- **Références** : Le numéro de demande attribué.
- **Société** : Le nom de la société.
- **Navire** : Le nom du navire.
- **Chantier** : Le nom du chantier.
- **Opération** : Le type d'opération.
- **Début période** : La date de début. 
- **Fin période** : La date de fin.
- **Actions** : Un bouton d'action permettant de clôturer l'embauche.

### Embauches à Payer

Cette section affiche la liste des embauches de dockers qui sont prêtes à être payées.

![Embauches à Payer](embauche_a_payer.png)

#### Filtres de recherche

Plusieurs filtres sont disponibles pour faciliter la recherche d'une embauche à payer :

- **Références** : Rechercher par le numéro de demande.
- **Société** : Rechercher par le nom de la société.
- **Navire** : Rechercher par le nom du navire.
- **Chantier** : Rechercher par le nom du chantier.
- **Opération** : Rechercher par le type d'opération.
- **Début période** : Rechercher par la date de début.
- **Fin période** : Rechercher par la date de fin.

#### Résultats

La liste affiche les informations suivantes pour chaque embauche à payer :

- **Références** : Le numéro de demande attribué.
- **Société** : Le nom de la société. 
- **Navire** : Le nom du navire.
- **Chantier** : Le nom du chantier.
- **Opération** : Le type d'opération.
- **Début période** : La date de début.
- **Fin période** : La date de fin.
- **Montant** : Le montant total à payer pour l'embauche.

### Embauches Payées  

Cette section affiche la liste des embauches de dockers qui ont été payées.

![Embauches Payées](embauche_payee.png)

#### Filtres de recherche

Plusieurs filtres sont disponibles pour faciliter la recherche d'une embauche payée :

- **Références** : Rechercher par le numéro de demande.
- **Société** : Rechercher par le nom de la société.
- **Navire** : Rechercher par le nom du navire.
- **Chantier** : Rechercher par le nom du chantier.
- **Opération** : Rechercher par le type d'opération.
- **Début période** : Rechercher par la date de début.
- **Fin période** : Rechercher par la date de fin.
- **Date de paiement** : Rechercher par la date de paiement.

#### Résultats

La liste affiche les informations suivantes pour chaque embauche payée :

- **Références** : Le numéro de demande attribué.
- **Société** : Le nom de la société.
- **Navire** : Le nom du navire.
- **Chantier** : Le nom du chantier.
- **Opération** : Le type d'opération. 
- **Début période** : La date de début.
- **Fin période** : La date de fin.
- **Montant** : Le montant total payé pour l'embauche.
- **Date de paiement** : La date à laquelle l'embauche a été payée.

### Paie Docker

Cette section permet de gérer la paie des dockers embauchés.

![Paie Docker](recherche_paie_docker.png)

#### Filtres de recherche

Plusieurs filtres sont disponibles pour faciliter la recherche :

- **Nom** : Rechercher par le nom du docker.
- **Prénom** : Rechercher par le prénom du docker.
- **Période de paie** : Rechercher par la période de paie.

#### Résultats

La liste affiche les informations suivantes pour chaque docker :

- **Nom** : Le nom du docker.
- **Prénom** : Le prénom du docker.
- **Heures travaillées** : Le nombre d'heures travaillées pendant la période.
- **Taux horaire** : Le taux horaire du docker.
- **Montant dû** : Le montant total à payer au docker pour la période.


# Gestion Tâcherons


## Liste des demandes de tâcherons

Cette section permet de consulter et rechercher la liste complète des demandes de tâcherons enregistrées dans le système. Chaque ligne du tableau contient les informations suivantes :

-Référence
-Création
-Navire
-Chantier
-Opération
-Demandeur
-N° Conteneur 
-Produit
-Quantité
-Statut
-Actions

![Liste des demandes de tâcherons](demande_tacheron.png)

### Filtres de recherche

Plusieurs filtres sont disponibles pour faciliter la recherche d'une demande de tâcheron spécifique : Cliquer sur le bouton "Cliquez ici pour faire une recherche avancée" pour rechercher.

- **Référence** : Rechercher par le numéro de demande.
- **Nature Opération** : Rechercher par le type d'opération.
- **Début période** : Rechercher par la date de début.
- **Fin période** : Rechercher par la date de fin.

### Résultats

La liste affiche les informations suivantes pour chaque tâcheron:
- **Référence** : Le numéro de demande attribué.
- **Nature Opération** : La nature de l'opération.
- **Date début prévu** : La date de début prévu.
- **Date fin prévu** : La date de fin prévu.

## Modifier une demande de tâcheron 
Pour modifier les informations d'une demande de tâcheron, cliquez sur le bouton "Modifier" et changer les informations au niveau des champs du formulaire voulu.
Une fois les modifications apportées, cliquez sur "Mettre à jour" pour enregistrer les changements.

### Suppression d'une demande de tâcheron
Pour supprimer une demande de tâcheron :
1. Cliquez sur le bouton Annuler (avec une icône de poubelle) situé dans la colonne "Actions" de la ligne correspondant à la demande de tâcheron que vous souhaitez supprimer.
2. Une confirmation peut être demandée.
3. La demande de tâcheron sera supprimée de la liste.


## Liste des demandes de tâcherons en attente

La page de liste des demandes Dockers affiche toutes les demandes Dockers en attente dans un tableau. Chaque ligne du tableau contient les informations suivantes :
-Référence
-Création
-Navire
-Chantier
-Opération
-Demandeur
-N° Conteneur 
-Produit
-Quantité
-Statut
-Actions

![Liste des demandes de tâcherons en attente](tacheron_attente.png)

### Filtres de recherche

Plusieurs filtres sont disponibles pour faciliter la recherche d'une demande de tâcheron en attente : Cliquer sur le bouton "Cliquez ici pour faire une recherche avancée" pour rechercher.

- **Référence** : Rechercher par la référence.
- **Société** : Rechercher par le nom de la société.
- **Navire** : Rechercher par le nom du navire.
- **Début période** : Rechercher par la date de début.
- **Fin période** : Rechercher par la date de fin.
- **Statut** : Rechercher par le statut de la demande.

### Résultats

La liste affiche les informations suivantes pour chaque demande de tâcheron en attente :
- **Références** : Le numéro de demande attribué.
- **Société** : Le nom de la société.
- **Navire** : Le nom du navire. 
- **Début période** : La date de début.
- **Fin période** : La date de fin.
- **Statut** : Le statut de la demande.


## Liste des demandes de tâcherons

La page de liste des demandes de tâcherons affiche toutes les demandes de tâcherons existantes dans un tableau. Chaque ligne du tableau contient les informations suivantes :
-Référence
-Création
-Navire
-Chantier
-Opération
-Demandeur
-N° Conteneur 
-Produit
-Quantité
-Statut

![Liste des demandes de tâcherons](tacheron_embauche.png)

### Embauches à Démarrer

Cette section affiche la liste des demandes de tâcherons.

#### Filtres de recherche

Plusieurs filtres sont disponibles pour faciliter la recherche d'une demande de tâcheron :

- **Références** : Rechercher par le numéro de demande.
- **Société** : Rechercher par le nom de la société.
- **Navire** : Rechercher par le nom du navire.
- **Chantier** : Rechercher par le nom du chantier.
- **Opération** : Rechercher par le type d'opération.
- **Début période** : Rechercher par la date de début.
- **Fin période** : Rechercher par la date de fin.

#### Résultats

La liste affiche les informations suivantes pour chaque demande de tâcheron :

- **Références** : Le numéro de demande attribué.
- **Société** : Le nom de la société.
- **Navire** : Le nom du navire.
- **Chantier** : Le nom du chantier.
- **Opération** : Le type d'opération.
- **Début période** : La date de début.
- **Fin période** : La date de fin.
- **Actions** : Un bouton d'action permettant de démarrer l'embauche.

![Recherche tacheron à démarrer](search_tacheron_demarrer.png)

### Embauches à Exécuter

Cette section affiche la liste des embauches de tâcheron qui sont prêtes à être exécutées.


#### Filtres de recherche

Plusieurs filtres sont disponibles pour faciliter la recherche d'une embauche de tâcheron à exécuter :

- **Références** : Rechercher par le numéro de demande.
- **Société** : Rechercher par le nom de la société.
- **Début période** : Rechercher par la date de début.
- **Fin période** : Rechercher par la date de fin.

#### Résultats

La liste affiche les informations suivantes pour chaque embauche de tâcheron à exécuter :

- **Références** : Le numéro de demande attribué.
- **Société** : Le nom de la société.
- **Début période** : La date de début.
- **Fin période** : La date de fin.

![Embauches de tâcheron à Exécuter](search_tacheron_execute.png)

### Embauches à Clôturer

Cette section affiche la liste des embauches de tâcherons qui sont prêtes à être clôturées.

#### Filtres de recherche  

Plusieurs filtres sont disponibles pour faciliter la recherche d'une embauche de tâcheron à clôturer :

- **Références** : Rechercher par le numéro de demande.
- **Société** : Rechercher par le nom de la société.
- **Navire** : Rechercher par le nom du navire.
- **Chantier** : Rechercher par le nom du chantier.
- **Opération** : Rechercher par le type d'opération. 
- **Début période** : Rechercher par la date de début.
- **Fin période** : Rechercher par la date de fin.

#### Résultats

La liste affiche les informations suivantes pour chaque embauche de tâcheron à clôturer :

- **Références** : Le numéro de demande attribué.
- **Société** : Le nom de la société.
- **Navire** : Le nom du navire.
- **Chantier** : Le nom du chantier.
- **Opération** : Le type d'opération.
- **Début période** : La date de début. 
- **Fin période** : La date de fin.
- **Actions** : Un bouton d'action permettant de clôturer l'embauche.

![Embauches à Cloturer](search_cloture_tacheron.png)

### Embauches à Payer

Cette section affiche la liste des embauches de tâcherons qui sont prêtes à être payées.

#### Filtres de recherche

Plusieurs filtres sont disponibles pour faciliter la recherche d'une embauche à payer :

- **Références** : Rechercher par le numéro de demande.
- **Société** : Rechercher par le nom de la société.
- **Navire** : Rechercher par le nom du navire.
- **Chantier** : Rechercher par le nom du chantier.
- **Opération** : Rechercher par le type d'opération.
- **Début période** : Rechercher par la date de début.
- **Fin période** : Rechercher par la date de fin.

#### Résultats

La liste affiche les informations suivantes pour chaque embauche de tâcheron à payer :

- **Références** : Le numéro de demande attribué.
- **Société** : Le nom de la société. 
- **Navire** : Le nom du navire.
- **Chantier** : Le nom du chantier.
- **Opération** : Le type d'opération.
- **Début période** : La date de début.
- **Fin période** : La date de fin.
- **Montant** : Le montant total à payer pour l'embauche.

![Embauches de tâcheron à Payer](search_tacheron_a_payer.png)

### Embauches Payées  

Cette section affiche la liste des embauches de tâcherons qui ont été payées.

#### Filtres de recherche

Plusieurs filtres sont disponibles pour faciliter la recherche d'une embauche de tâcheron déjà payée :

- **Références** : Rechercher par le numéro de demande.
- **Société** : Rechercher par le nom de la société.
- **Navire** : Rechercher par le nom du navire.
- **Chantier** : Rechercher par le nom du chantier.
- **Opération** : Rechercher par le type d'opération.
- **Début période** : Rechercher par la date de début.
- **Fin période** : Rechercher par la date de fin.
- **Date de paiement** : Rechercher par la date de paiement.

#### Résultats

La liste affiche les informations suivantes pour chaque embauche payée :

- **Références** : Le numéro de demande attribué.
- **Société** : Le nom de la société.
- **Navire** : Le nom du navire.
- **Chantier** : Le nom du chantier.
- **Opération** : Le type d'opération. 
- **Début période** : La date de début.
- **Fin période** : La date de fin.
- **Montant** : Le montant total payé pour l'embauche.
- **Date de paiement** : La date à laquelle l'embauche a été payée.

![Embauches Payées](tacheron_payee.png)

### Paie Tâcheron

Cette section permet de gérer la paie des tâcherons embauchés.

#### Filtres de recherche

Plusieurs filtres sont disponibles pour faciliter la recherche :

- **Nom** : Rechercher par le nom du tâcheron.
- **Prénom** : Rechercher par le prénom du tâcheron.
- **Période de paie** : Rechercher par la période de paie.

#### Résultats

La liste affiche les informations suivantes pour chaque tâcheron :

- **Nom** : Le nom du tâcheron.
- **Prénom** : Le prénom du tâcheron.
- **Heures travaillées** : Le nombre d'heures travaillées pendant la période.
- **Taux horaire** : Le taux horaire du tâcheron.
- **Montant dû** : Le montant total à payer au tâcheron pour la période.
- **Actions** : Un bouton d'action permettant de procéder au paiement du tâcheron.

![Paie Tacheron](paie_tacheron.png)