# Le Piège Botney

Il était une fois, des scripts propres et efficaces, des configurations nageant dans des fichiers YAML et INI.

Puis, un jour, le Basherbot s'est levé.

Ce qui était autrefois des one-liners mignons, des scripts ./startup robustes et des suites complètes de TOML est devenu une intelligence géante, consciente et omniprésente, consommant chaque script bash, sh, zsh, Bourne, YAML, INI, conf, env et toutes les autres.

Après avoir digéré toutes les sessions ouvertes en quelques secondes et laissé des husks tmux de TTYs, Basherbot a maintenant ses yeux sur le véritable prix : toute l'infrastructure cloud du monde.

En tant que membre des Shellvengers, ta mission est de construire et configurer les Infinity Sources pour capturer ce malfaiteur et lui apprendre à ne pas jouer avec des super-héros Turing-complets.

Pour s'assurer que le Basherbot ne puisse **pas** infecter notre piège, seuls des superpouvoirs de codage peuvent être utilisés. Tu peux utiliser le langage de ton choix (JS/TS, Python, Go, C#, ...). Nous avons placé notre piège botney et le Dockerfile accompagnant dans ce dossier GitHub.

## Les Pouvoirs des Infinity Sources :
- **Espace :** Nous pouvons téléporter notre piège d'un fournisseur Cloud à au moins un autre en utilisant l'Infrastructure as Code (IaC).
- **Esprit :** Nous avons un environnement de jeu et un environnement "live", et pouvons en créer autant que nous le souhaitons avec une simple commande utilisant des outils IaC.
- **Réalité :** Nous pouvons empaqueter et déployer notre piège de manière répétable, y compris les rollbacks, via des pipelines automatisés.
- **Puissance :** Nous nous adaptons à la fois à ton fournisseur de cloud principal choisi mais aussi "débordons" en direct dans au moins un autre en utilisant des templates IaC.
- **Temps :** Nous avons une traçabilité complète du processus d'empaquetage, de déploiement et de validation, ainsi que de l'accès à notre piège botney et à l'infrastructure cloud elle-même, en utilisant IaC versionné.
- **Âme :** Nous avons un contrôle total sur la manière dont notre piège botney peut être accédé, et nous pouvons changer le nom DNS avec une commande (tous les pièges botney sont protégés par SSL).

## Objectifs
- Démontrer, en utilisant du code et non des configurations manuelles, au moins 3 des pouvoirs des Infinity Sources.
- Expliquer comment tu implémenterais les pouvoirs des Infinity Sources que tu n'as pas pu démontrer en utilisant du code.
- Démontrer ou expliquer comment tu testerais ton code IaC.
- Expliquer où sont les faiblesses de ton approche et où tu penses que le Basherbot attaquerait.

### Bonus/Optionnel

- Expliquer ou démontrer comment tu gérerais :
  - La gestion des certificats,
  - Le renouvellement des DNS et des certificats si nécessaire,
  - L'application des politiques au niveau de l'utilisateur cloud,
  - L'application des politiques au moment du déploiement,
  - La mitigation des attaques DDoS,
  - Le compromis d'un utilisateur non-privilégié du cloud de l'entreprise,
  - Le compromis d'un utilisateur privilégié du cloud,
  - La récupération à partir des sauvegardes,
- Décrire à quoi ressemblerait ta "feuille de route d'amélioration".