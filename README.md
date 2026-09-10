# ETL Oracle – Débarquements de poissons

## Description
Script SQL réalisé sous Oracle pour contrôler, analyser et nettoyer
les données de débarquements de poissons.

## Environnement
- Oracle Database XE 21c
- Conteneur : XEPDB1
- Utilisateur : USER_ETL
- SQL Developer

## Traitements réalisés
1. Vérification de la connexion et de l'environnement Oracle
2. Vérification de la table DEBARQUEMENTS_POISOONS
3. Contrôle du nombre de lignes
4. Détection des doublons sur ID
5. Analyse des données manquantes
6. Contrôle des valeurs NULL
7. Suppression des doublons
8. Contrôles après nettoyage

## Fichier principal
- `ScriptETL_oracle.sql`

## Versionnement
Projet versionné avec Git.

Commit initial :
`a3f7adc - Ajout du script ETL Oracle`
