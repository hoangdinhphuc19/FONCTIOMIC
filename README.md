# 🌟 FONCTIOMIC 🌟

## 📚 Description du projet

Ce projet vise à réaliser une **analyse comparative** entre l'inférence fonctionnelle du **métabarcoding** et la **métagénomique**. L'objectif est de comparer les résultats obtenus par ces deux approches pour mieux comprendre les différences et les similitudes dans l'inférence fonctionnelle des communautés microbiennes.

## 🎯 Objectifs du projet

Le projet est organisé comme suit : 
- 🗂️ Database de référence => KO, EC, MetaCyc
- 🧬 COG, EC abondance relative par la métagénomique shotgun
- 🔬 KO, EC abondance relative inférrés par PICRUSt2 à partir des données de la métabarcoding 16S rARN 

## 🎯 Structure des données
- FONCTIOMIC_MGS : Analyses différentiels sur les résultats de MGS (PCA Plot, Test DAG, Heatmap)
- FONCTIOMIC_P2 : Analyses différentiels sur les résultats de PICRUSt2 (PCA Plot, Test DAG, Heatmap)
- test_value_0 : essais des modèles mathématiques -> corrélation des données sortants des 2 méthodes (Important pour Seb + Léo)
- campare_EC_MGS_PIC : essais des analyses comparatives (Dinh)


## 📊 Résultats attendus

Les résultats de cette analyse comparative permettront de :

- Identifier les différences et similitudes entre les deux approches.
- Évaluer la précision de l'inférence fonctionnelle du métabarcoding par rapport à la métagénomique.
- Fournir des recommandations pour l'utilisation de ces approches dans des études futures.
