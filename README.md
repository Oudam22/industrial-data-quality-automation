# Industrial Data Quality Automation – Aivancity Paris

## 🎓 Contexte
Mémoire réalisé à **Aivancity Paris** dans le cadre de la **gestion des marchés publics**.  
L’objectif était d’**optimiser le suivi des projets de cadrage**, en particulier pour les sous-traitants (DC4) et les acteurs principaux, à la fois en **passation** et en **exécution**.  
Le projet répond au besoin de fiabiliser les données critiques et de réduire le temps consacré au contrôle manuel.

---

## 🎯 Objectifs du projet
- **Automatiser le contrôle qualité** des données liées aux marchés publics.  
- **Réduire le temps de traitement** des DC4 et autres indicateurs de suivi.  
- **Fiabiliser les indicateurs** pour les équipes métiers et les décideurs (finance, achats, gestion des marchés).  
- **Standardiser les processus** pour les sous-traitants et acteurs principaux.

---

## 🛠️ Stack technique
- **Python** : pandas, numpy, dateutil (analyse, validation, automatisation)  
- **Power BI** : visualisation des indicateurs clés  
- **Excel** : manipulation et analyse de données tabulaires  
- **ERP / SAP / OPC** : extraction et traitement des données

---

## 📜 Scripts disponibles

### 1️⃣ `data_quality_checks.py`
- Contrôle des **dates, montants financiers et SIRET**.  
- Détecte les anomalies et retourne un **résumé par type et lignes concernées**.  

**Exemple de sortie :**

dates_invalid (nombre) : 3
financial_invalid (nombre) : 1
siret_invalid (nombre) : 0
dates_invalid_lines : [5, 12, 18]
financial_invalid_lines : [7]

---

### 2️⃣ `compare_excel_files.py`
- Compare automatiquement deux ensembles de données ligne par ligne et colonne par colonne.  
- Exporte les différences dans un fichier récapitulatif pour suivi et audit.  

**Exemple de sortie :**

Dimensions du fichier 1 (Lignes, Colonnes): (100, 12)
Dimensions du fichier 2 (Lignes, Colonnes): (100, 12)
Différences détectées : 4 cellules modifiées, exportées dans le fichier récapitulatif

---

### 3️⃣ `na_detection_and_report.py`
- Détecte les **valeurs manquantes** dans les données.  
- Génère automatiquement un rapport synthétique et peut l’envoyer par email aux acteurs concernés.  

**Exemple de sortie :**

15 ligne(s) avec NA détectées
Fichier NA_Report créé et envoyé à l’équipe

---

## 📈 Résultats & Impact
- **Gain de temps significatif** : réduction des interventions manuelles et contrôle plus rapide  
- **Fiabilité accrue des indicateurs** pour le suivi DC4 et les projets de marché public  
- **Standardisation et reproductibilité** des contrôles qualité  
- **Transparence et traçabilité** des anomalies et écarts

---

## 📂 Structure du projet

industrial-data-quality-automation/
│
├── README.md
├── scripts/
│ ├── data_quality_checks.py
│ ├── compare_excel_files.py
│ └── na_detection_and_report.py
└── requirements.txt

---

## 🔍 Utilisation
1. Exécuter les scripts depuis le dossier `scripts/`  
2. Lire les rapports générés pour détecter anomalies, écarts et valeurs manquantes  
3. Les rapports permettent **un suivi précis et automatisé** des DC4 et des sous-traitants  

---

## 💡 Recommandations pour les recruteurs
- Ce projet démontre des compétences en **automatisation, data quality et reporting**.  
- Capacité à transformer des données brutes en **indicateurs fiables et actionnables** pour les équipes métiers.  
- Expérience concrète dans un environnement **public et privé** avec des **processus complexes de marchés publics**.
