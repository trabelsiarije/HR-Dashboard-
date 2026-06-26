# Dashboard RH avec Power BI

## Présentation

Ce projet consiste à concevoir un tableau de bord interactif de Ressources Humaines (RH) sous Power BI afin d'analyser les données des employés et de fournir des indicateurs clés facilitant la prise de décision.

À partir d'un fichier Excel contenant les informations des employés, le projet met en œuvre un processus complet de préparation des données, de modélisation, de création de mesures DAX et de visualisation des indicateurs RH.

---

## Aperçu du Dashboard

> Ajouter ici une capture d'écran du tableau de bord.

```text
/dashboard/dashboard.png
```

---

## Objectifs

Le tableau de bord permet notamment de répondre aux questions suivantes :

* Nombre d'employés par département
* Répartition des employés par centre
* Répartition hommes / femmes
* Répartition géographique des employés
* Évolution des employés par année
* Masse salariale mensuelle totale
* Salaire mensuel pour une année donnée
* Moyenne de la note (Job Rate)

---

## Technologies utilisées

* Power BI Desktop
* Power Query
* DAX
* Microsoft Excel

---

## Étapes du projet

### 1. Importation des données

* Chargement du fichier **Employees.xlsx**
* Vérification de la structure des données
* Identification des types de colonnes

---

### 2. Préparation des données (ETL)

Les données ont été transformées dans **Power Query** afin d'améliorer leur qualité avant leur exploitation.

Les principales opérations réalisées sont :

* Suppression des lignes dupliquées
* Gestion des valeurs nulles
* Nettoyage des espaces inutiles (Trim)
* Uniformisation des formats de données
* Conversion des types de colonnes
* Vérification de la cohérence des données
* Renommage des colonnes pour une meilleure lisibilité
* Validation des données avant chargement dans Power BI

---

### 3. Modélisation des données

Après le nettoyage :

* Chargement du modèle dans Power BI
* Vérification des relations entre les tables
* Optimisation du modèle de données
* Création d'un modèle prêt pour les analyses

---

### 4. Création des mesures DAX

Plusieurs mesures ont été développées afin d'obtenir des indicateurs dynamiques :

* Nombre total d'employés
* Salaire mensuel total
* Salaire mensuel par année
* Moyenne du Job Rate
* Comptage des employés par département
* Comptage des employés par centre
* Comptage des employés par pays
* Comptage des employés par genre

Les mesures DAX permettent de rendre les visualisations entièrement interactives avec les filtres du rapport.

---

### 5. Création des visualisations

Le tableau de bord comprend :

* Graphique en barres : Nombre d'employés par département
* Diagramme en anneau : Répartition par centre
* Diagramme en anneau : Répartition par genre
* Carte géographique : Employés par pays
* Graphique en aires : Employés par année
* Cartes KPI :

  * Nombre total d'employés
  * Salaire mensuel total
  * Moyenne du Job Rate
* Segments (Slicers) :

  * Pays
  * Centre

---

## Fonctionnalités

* Analyse dynamique des effectifs
* Filtrage interactif
* Indicateurs RH en temps réel
* Navigation intuitive
* Analyse géographique des employés
* Analyse de la masse salariale
* Analyse de la performance des employés

---

## Résultats

Le tableau de bord permet aux responsables RH de :

* Suivre les effectifs de l'entreprise
* Comparer les départements
* Étudier la répartition géographique des employés
* Analyser la masse salariale
* Mesurer les performances grâce au Job Rate
* Faciliter la prise de décision grâce à une visualisation claire des données

---

## Structure du projet

```
HR-Dashboard/
│
├── Data/
│   └── Employees.xlsx
│
├── Dashboard/
│   └── HR_Dashboard.pbix
│
├── Images/
│   └── dashboard.png
│
└── README.md
```

---

## Auteur

Projet réalisé dans le cadre du module **Business Intelligence and Data Analytics**.
