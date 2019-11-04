# Version 0.4 RC du 4 novembre 2019 (QUASI STABLE)

> **ATTENTION** : Il obligatoire de relancer une "Découverte des objets" pour mettre à jour des paramètres pour le bon fonctionnement.

> **VOLET ROULANT** : Il faut supprimer l'objet et relancer une "Découverte des objets" pour avoir un code retour correct du statut de l'ouverture.

- Correction de bogue de l'API
- Quelques changements dans les paramètres des objets
- Corrections sur le code retour des volets roulants


# Version 0.3 beta du 26 octobre 2019 (NON STABLE)

> **ATTENTION** : Il obligatoire de relancer une "Découverte des objets" pour mettre à jour des paramètres pour le bon fonctionnement.

- Correction de bogue de l'API
- Amélioration du mode "Découverte"
- Mise en place d'une tâche planifiée pour mise à jour des statuts des objets
- Essaie de plusieurs tentatives si le serveur Tuya ne répond pas
- Amélioration du code


# Version 0.2 beta du 7 octobre 2019 (NON STABLE)

> **ATTENTION** : Refonte du système de création des objets. Après la mise à jour du plugin, et **avant de cliquer** sur "Découverte", il faut pour chaque objet, recliquer sur "Sauvegarder" pour mettre à jour certains éléments et éviter la création des objets en double lors de la "Découverte".

- Mise à jour de l'API
- Découverte automatique des objets
- Gestion des équipements inconnus
- Optimisation du nombre de requête au Cloud Tuya
- Nouvelle tentative en cas d'echec à la requête au Cloud Tuya
- Gestion des exceptions
- Plus de log en mode debug
- Quelques corrections


# Version 0.1 alpha du 10 août 2019 (NON STABLE)

- Mise à jour de l'API
- Intégration du changement de couleur de la lampe
- Rafraichissement de l'état après une action
- Bug sur problème d'objet non reconnu


# Version 0.0 alpha du 30 mai 2019 (NON STABLE)

- Développement initial
- Ajout des commandes d'informations
- Ajout des commandes On / Off
- Prise en compte des objets (switch, scene, cover, light)
