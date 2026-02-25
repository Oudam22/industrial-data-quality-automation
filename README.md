# Industrial Data Quality Automation – Aivancity Paris

## Contexte
Mémoire réalisé à **Aivancity Paris** dans le cadre de la **gestion des marchés publics**.  
L’objectif était d’**optimiser le suivi des projets de cadrage**, en particulier pour les sous-traitants (DC4) et les acteurs principaux, à la fois en **passation** et en **exécution**.  
Le projet répond au besoin de fiabiliser les données critiques et de réduire le temps consacré au contrôle manuel.

---

## Objectifs du projet
- **Automatiser le contrôle qualité** des fichiers Excel liés aux marchés publics.  
- **Réduire le temps de traitement** des DC4 et autres documents de suivi.  
- **Fiabiliser les indicateurs** pour les équipes métiers et les décideurs (finance, achats, gestion des marchés).  
- **Standardiser les processus** pour les sous-traitants et acteurs principaux.

---

## Stack technique
- **Python** : pandas, numpy, dateutil (analyse, validation, automatisation)  
- **Excel** : nettoyage et manipulation des données  
- **Power BI** : visualisation des indicateurs clés  
- **ERP / SAP / OPC** : accès et extraction des données

---

## Scripts disponibles

### `data_quality_checks.py`
- Contrôle des **dates, montants financiers et SIRET** dans les fichiers Excel DC4.  
- Détecte les anomalies et retourne un **résumé par type et lignes concernées**.  

**Exemple de sortie :**
