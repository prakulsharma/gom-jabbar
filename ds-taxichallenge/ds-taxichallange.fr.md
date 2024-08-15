Prédiction de la Demande Horaire et Optimisation

Introduction

Bienvenue au Défi Data Science de PHA ! Dans ce défi, vous vous plongerez dans un scénario réel qui combine la complexité du transport urbain avec l’imprévisibilité des conditions météorologiques. Votre mission est de prédire la demande horaire de taxis dans le Bronx, en utilisant un an de données de trajets en taxi et des observations météorologiques horaires. De plus, vous devrez déterminer le nombre optimal de taxis nécessaires pour répondre efficacement à cette demande.

Bien que le défi soit centré sur le transport urbain, les principes de prévision de la demande que vous utiliserez sont essentiels dans de nombreux secteurs, y compris les solutions de dotation en personnel de santé. Prédire et gérer efficacement la demande est au cœur de ce que nous faisons chez PHA, et nous sommes impatients de voir comment vous appliquez ces compétences dans ce contexte.

Scénario

Imaginez que vous êtes un data scientist travaillant pour une grande entreprise de covoiturage. L’entreprise cherche à optimiser ses opérations en prévoyant avec précision la demande dans différentes régions de la ville. L’un des domaines critiques est le Bronx, connu pour ses quartiers dynamiques et diversifiés. Une prévision précise de la demande dans cette zone peut améliorer considérablement la satisfaction des clients et l’efficacité opérationnelle en garantissant qu’un nombre suffisant de taxis est disponible au bon moment et au bon endroit.

Pour relever ce défi, vous disposez de données historiques sur les trajets en taxi, combinées à des données météorologiques horaires. Votre tâche consiste à analyser ces données, à construire des modèles prédictifs, à fournir des insights exploitables et à déterminer le nombre optimal de taxis nécessaires pour répondre à la demande prédite dans le Bronx.

Description des Données

Vous travaillerez avec deux ensembles de données principaux :

	1.	Données de Trajets en Taxi : Données historiques détaillant les trajets individuels en taxi.
	•	tpep_pickup_datetime : La date et l’heure de la prise en charge du client.
	•	tpep_dropoff_datetime : La date et l’heure de la dépose du client.
	•	passenger_count : Le nombre de passagers dans le véhicule. C’est une valeur saisie par le conducteur.
	•	trip_distance : La distance du trajet en miles rapportée par le taximètre.
	•	PULocationID* : Zone de taxi TLC où le taximètre a été activé.
	•	DOLocationID* : Zone de taxi TLC où le taximètre a été désactivé.
*Les zones correspondantes peuvent être trouvées dans la table de recherche des zones.

	2.	Données Météorologiques : Observations météorologiques horaires correspondant à la même période que les données de trajets en taxi.
	•	temperature : Température de l’air en °C.
	•	precipitation : Précipitations totales (pluie, averses, neige) de l’heure précédente en mm.
	•	rain : Précipitations liquides de l’heure précédente, y compris les averses locales et la pluie provenant de systèmes à grande échelle en mm.
	•	snowfall : Quantité de neige de l’heure précédente en cm.

Tâche

Votre objectif est de prédire la demande horaire de taxis dans le Bronx et de déterminer le nombre optimal de taxis nécessaires pour répondre à cette demande. La tâche est divisée en quatre parties, chacune devenant progressivement plus difficile pour mettre en valeur vos compétences en science des données, en apprentissage automatique et en optimisation opérationnelle.

	1.	Modèle de Base :
	•	Construisez un modèle de base simple pour prédire la demande horaire. Expliquez votre choix de modèle de base et les métriques de performance que vous utilisez pour l’évaluer.

	2.	Modèle Amélioré :
	•	Développez un modèle amélioré en incorporant des fonctionnalités supplémentaires, en affinant vos étapes de prétraitement des données ou en utilisant des algorithmes plus sophistiqués. Comparez sa performance avec le modèle de base et expliquez les améliorations. Discutez des techniques d’ingénierie des caractéristiques ou des méthodes de transformation des données que vous avez utilisées.

	3.	Meilleur Modèle :
	•	Optimisez votre modèle amélioré pour obtenir les meilleures performances possibles. Expliquez les étapes entreprises pour améliorer le modèle et les résultats finaux. Fournissez une comparaison claire entre le modèle de base, le modèle amélioré et le meilleur modèle, en soulignant les principales améliorations.

	4.	Prévision de la Première Semaine de Septembre 2024 :
    •	En utilisant votre meilleur modèle, prévoyez la demande horaire de taxis dans le Bronx pour la première semaine de septembre 2024. Expliquez les étapes supplémentaires ou les hypothèses que vous avez prises en compte pour cette tâche de prévision, telles que les tendances saisonnières, les facteurs externes ou les anomalies potentielles. 

    5. Nombre Optimal de Taxis :
	•	Déterminez le nombre optimal de taxis nécessaires pour répondre à la demande horaire prédite dans le Bronx. Faites des hypothèses raisonnables sur des facteurs tels que la durée moyenne des trajets, la disponibilité des taxis et les contraintes opérationnelles. Vous devrez peut-être prendre en compte les coûts potentiels et les avantages dans votre analyse. Expliquez vos hypothèses et la méthodologie utilisée pour calculer le nombre optimal de taxis. Discutez des implications de vos conclusions sur l’efficacité opérationnelle et la satisfaction des clients.

Critères d’Évaluation

Votre soumission sera évaluée en fonction des critères suivants :

	•	Compétences en Programmation : Code propre, efficace et bien documenté.
	•	Capacité de Résolution de Problèmes : Approche logique pour construire et améliorer les modèles.
	•	Explication et Justification : Explication claire et concise des modèles, des choix effectués et des résultats obtenus.
	•	Créativité et Innovation : Approches originales pour l’ingénierie des caractéristiques, l’optimisation des modèles et la résolution de problèmes.
	•	Perspicacité Opérationnelle : Praticabilité et validité des hypothèses et de la méthodologie pour déterminer le nombre optimal de taxis.

Soumission

Votre soumission doit inclure :

	1.	Code : Scripts Python ou notebooks Jupyter avec toutes les étapes et explications ainsi que les références.
	2.	Rapport : Un rapport détaillé expliquant votre approche, les modèles construits, la comparaison des performances et les résultats finaux.
	3.	Fichiers Supplémentaires : Tous les fichiers supplémentaires nécessaires pour reproduire vos résultats.

Veuillez soumettre votre travail soit sous forme de pull request sur GitHub, soit sous forme d’un fichier compressé unique (ZIP) contenant tous les éléments requis pour la reproductibilité.