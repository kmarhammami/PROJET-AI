# Système Intelligent de Recommandation de Destinations de Voyage

## Introduction du projet

Dans le cadre de ce projet académique réalisé à l’IHEC Carthage, nous avons développé  
un **système intelligent de recommandation de destinations de voyage** sous forme  
d’une **application graphique interactive en Python**.

Le système collecte les préférences de l’utilisateur à travers **10 questions Oui / Non**,  
puis utilise un **modèle de Machine Learning (Random Forest)** afin de prédire  
la destination la plus adaptée au profil de l’utilisateur.

L’application propose une interface moderne et intuitive développée avec **Tkinter**,  
intégrant des éléments visuels (images, boutons, labels dynamiques).

---

## Aperçu de l’interface

### Écran principal & interface utilisateur
![Interface principale](images/background.jpg)

---

## Fonctionnement du système intelligent

1. L’utilisateur répond à une série de questions (préférences de voyage)
2. Les réponses sont converties en vecteur de caractéristiques
3. Le modèle **Random Forest** analyse ces données
4. La destination optimale est prédite
5. Le résultat est affiché avec une image représentative

---

## Destinations proposées par le système

Les destinations sont illustrées par des images intégrées à l’application :

| Destination | Aperçu |
|------------|--------|
| Alpes | ![](images/alpes.jpg) |
| Bali | ![](images/bali.jpg) |
| Dubaï | ![](images/dubai.jpg) |
| Islande | ![](images/islande.jpg) |
| Londres | ![](images/londres.jpg) |
| Maldives | ![](images/maldives.jpg) |
| Marrakech | ![](images/marrakech.jpg) |
| Paris | ![](images/paris.jpg) |
| Pérou | ![](images/perou.jpg) |
| Thaïlande | ![](images/Thailand.jpg) |
| Tokyo | ![](images/tokyo.jpg) |

---

## Liens avec les concepts du cours d’Intelligence Artificielle

Ce projet applique directement plusieurs notions vues en cours :

### Agents intelligents
- Le système agit comme un **agent autonome**
- Il perçoit l’environnement via l’interface (questions)
- Il raisonne grâce au modèle ML
- Il agit en affichant une recommandation

### Capteurs
- Boutons **Oui / Non**
- Interaction utilisateur (clavier / souris)

### Actionneurs
- Labels dynamiques
- Images affichées selon la prédiction

Ce fonctionnement illustre les concepts :
- IA distribuée (IAD)
- Systèmes multi-agents (coopération interface + modèle)

---

## Choix du thème

### Pertinence académique
- Représentation des connaissances (dataset)
- Inférence (Machine Learning)
- Agents autonomes et flexibles

### Simplicité & richesse
- Domaine accessible (voyage)
- Problème réel de recherche dans un espace d’états
- Optimisation vers un état objectif (destination idéale)

### Utile pour rapport et soutenance
- Maîtrise complète du cycle IA :
  - État initial
  - Actions
  - Successeurs
  - Décision optimale basée sur probabilités

---

## Technologies utilisées

- **Python**
- **Tkinter** (interface graphique)
- **Scikit-learn**
- **Random Forest Classifier**
- **Pandas / NumPy**
- **Images locales (dossier images)**

---

## Conclusion

Ce projet démontre la capacité à concevoir un **système intelligent complet**,  
combinant **interface graphique**, **raisonnement automatique** et **prise de décision**,  
tout en respectant les concepts fondamentaux de l’Intelligence Artificielle étudiés en cours.
