# Repairkit Script

## Auteur : OwenDev  

## Version : 1.0.0  

---

## Description

Ce script permet d'utiliser l'item `repairkit` pour réparer un véhicule sur un serveur FiveM utilisant **OX Inventory**.  

Il propose deux modes d'utilisation :  

1. L'item peut être utilisé par tous les joueurs.  

2. L'item peut être restreint au job **mechanic**.  

Ce script est conçu pour les serveurs utilisant le framework **ESX**.

---

## Installation

1. **Téléchargez et installez le script** :  

   Placez les fichiers du script dans le répertoire suivant :  





2. **Ajoutez l'item `repairkit` à OX Inventory** :

 -- Démarrer le script dans le server.cfg



-- ensure OwenDev_repairkit

---

-- ## Fonctionnalités

-- Réparation de véhicule : Les joueurs peuvent réparer leur véhicule avec un repairkit.

-- Animation réaliste : Une animation est jouée pendant la réparation pour plus d'immersion.

-- Consommation de l'item : Le repairkit est retiré de l'inventaire après utilisation.

-- Restriction par métier : Limite l'utilisation de l'item à un job spécifique si nécessaire.

-- Pour toute assistance ou question, contactez OwenDev.

-- Discord: fantomasse_

Dans la configuration d'OX Inventory, ajoutez :  


```lua

['repairkit'] = {

    label = 'Kit de réparation',

    weight = 1000,

    stack = false,

    close = true,

}
