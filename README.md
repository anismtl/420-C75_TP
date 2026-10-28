# 420-C75_TP
TP - 420-C75-BB Analyse exploratoire et transformation de données

## Dataset — BankSim

Source : Kaggle — ealaxi/banksim1, « Synthetic data from a financial payment system » (https://www.kaggle.com/datasets/ealaxi/banksim1)

Fichier principal : `bs140513_032310.csv` — 594 643 transactions.

## Description des colonnes — bs140513_032310.csv

- **step** : Étape de la simulation correspondant au jour de la transaction. Valeurs de 0 à 179, soit 180 jours (environ six mois).
- **customer** : Identifiant unique du client qui effectue la transaction, formé de la lettre C suivie de 10 chiffres. Le jeu de données compte 4 112 clients distincts.
- **age** : Tranche d'âge du client, codée ainsi : 0 = moins de 18 ans ; 1 = 19 à 25 ans ; 2 = 26 à 35 ans ; 3 = 36 à 45 ans ; 4 = 46 à 55 ans ; 5 = 56 à 65 ans ; 6 = plus de 65 ans ; U = inconnu.
- **gender** : Genre du client, codé ainsi : F = femme (Female) ; M = homme (Male) ; E = entreprise (Enterprise) ; U = inconnu (Unknown).
- **zipcodeOri** : Code postal du client. Valeur présente dans le fichier : 28007.
- **merchant** : Identifiant unique du commerçant qui reçoit la transaction, formé de la lettre M suivie de 9 chiffres. Le jeu de données compte 50 commerçants distincts.
- **zipMerchant** : Code postal du commerçant. Valeur présente dans le fichier : 28007.
- **category** : Catégorie de la transaction. 15 catégories : es_transportation, es_food, es_health, es_wellnessandbeauty, es_fashion, es_barsandrestaurants, es_hyper, es_sportsandtoys, es_tech, es_home, es_hotelservices, es_otherservices, es_contents, es_travel, es_leisure.
- **amount** : Montant de la transaction. Valeurs de 0 à 8 329,96 ; moyenne de 37,89.
- **fraud** : Indicateur de fraude : 0 = transaction normale (587 443 transactions) ; 1 = transaction frauduleuse (7 200 transactions).
