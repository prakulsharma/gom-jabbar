# Plateforme de vente Rose Apothecary

Ça y est : Rose Apothecary devient viral.

> Si vous ne savez pas ce qu'est le Rose Apothecary de Schitt's Creek... ([suivez ce lien](https://fr.wikipedia.org/wiki/Schitt%27s_Creek)) https://fr.wikipedia.org/wiki/Schitt%27s_Creek

Le défi est que nos fabuleux propriétaires, David et Patrick, ont parfois tendance à mélanger les commandes, surtout quand David est occupé à paniquer à cause d'un pli dans son pull ou que Patrick le sérénade.

Maintenant, nous ne manquerons pas cette opportunité de surpasser toutes les boutiques du continent !

Pour s'assurer que les savons artisanaux de David ne sont pas mélangés avec les "aventures commerciales" douteuses d'Alexis et que les mocktails de Moira sont toujours parfaitement réalisés, nous devons construire une API et un frontend très bien conçus pour évoluer correctement.

Cette plateforme devra être capable de :

- Stocker toutes les informations des clients :
  - Type de client : hors de la ville, en ville, ou membre de la famille Rose
  - Leurs préférences en matière de produits, y compris leur mélange préféré de sarcasme et de sincérité
  - Leurs parfums préférés, que ce soit "Eau de Schitt's Creek" ou "Moira's Mélange"
- Stocker toutes les commandes des clients :
  - L'heure à laquelle la commande a été passée, de préférence pendant une crise de David
  - Le produit commandé, y compris les savons artisanaux de David, les huiles essentielles douteuses d'Alexis et les élixirs mystérieusement efficaces de Moira
  - L'humeur au moment de la commande : en colère, heureux, débordé, enceinte, de mauvaise humeur, ennuyé, excité, ou "Alexis"
  - Le nombre de clients pour la commande, y compris toute apparition surprise de Johnny ou Stevie
  - La répartition de l'addition :
    - par groupe
    - par personne
    - avec des ratios que seul un véritable membre de la famille Rose pourrait apprécier
- Stocker tous les produits disponibles :
  - Le prix, ajusté en fonction des humeurs changeantes de David
  - Le niveau de flair artisanal acceptable par David sur une échelle de 1 à 10
  - La dernière date de réapprovisionnement du produit, probablement autour de la dernière sortie dramatique de Moira
  - La durée de conservation du produit, qui peut varier en fonction des sérénades de Patrick
- Stocker les retours des clients une fois qu'ils ont payé, ce qui inclura sans doute quelques commentaires colorés

## Objectifs

- Démontrer la récupération après un crash complet de toutes les instances ou d'une seule, de préférence pendant une des performances théâtrales de Moira.
- Simuler l'insertion de 10 000 clients effectuant entre 2 et 14 commandes par an sur une période de 2 ans, en supposant que David ne fasse pas une crise entre-temps.
- Optimiser/trouver des solutions pour les questions suivantes :
  - Combien de produits artisanaux notés 8 David a-t-il créés au cours des 6 derniers mois, combien d'argent cela a-t-il rapporté et quelles étaient les notes médianes de ces produits, y compris les critiques douteuses d'Alexis ?
  - Quelle est l'évolution du nombre de vins que Patrick et David ont sélectionnés seuls par rapport à ceux qu'ils ont sélectionnés ensemble au fil du temps, en tenant compte des moments dramatiques de David ?
  - L'évolution des choix de mocktails de Moira par rapport à ses critiques au fil du temps, avec son flair unique pour le drame.
  - Rechercher le nom d'un client hors de la ville, qui sera probablement mal prononcé par Moira.

### Bonus/Optionnel

- Montrer des outils de visualisation et des exemples générés, y compris des camemberts dramatiques et des histogrammes (ou histodrames?) exagérés.
- Choisir différents mécanismes de stockage pour différentes parties et expliquer pourquoi, en utilisant les normes méticuleuses de David.