# Projet
Modèle de prédiction de la consommation énergétique dans les bâtiments intelligents

Données de travail pour le projet.
[Source : https://archive.ics.uci.edu/dataset/374/appliances+energy+prediction](https://www.data.gouv.fr/fr/datasets/consommation-delectricite-des-entreprises-et-collectivites-locales-dans-les-regions-francaises-non-interconnectees-1/)
Fichier au format xlx.
Les différentes colonnes sont:

year-Wweek : Semaine ISO (ex. : “2023-W01”)
user_id : Identifiant unique pour chaque utilisateur
site_id : Identifiant unique pour chaque site (bâtiment ou groupe de bâtiments)
department : Département où le capteur est situé (Corse-du-Sud, Haute-Corse, Guadeloupe, Martinique, Guyane, Réunion, Mayotte)
nace_code : Code NACE correspondant à l’activité de l’utilisateur
insee_code : Code INSEE de la commune
weekly_E_kWh : Consommation d’énergie hebdomadaire en kWh
weekly_dd_heating_<T0> : Degrés-jours de chauffage hebdomadaires (HDD) pour une température de référence T0
weekly_dd_cooling_<T0> : Degrés-jours de refroidissement hebdomadaires (CDD) pour une température de référence T0
<stats_type>indoor<data_type>_<nn> : Statistiques sur les données de température et d’humidité intérieure
