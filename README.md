# Projet MOSFET
# ⚡ Projet BTS - Simulation de Transistor MOSFET
Mon fichier : [ProjetFinalRayanBelon.odt](https://github.com/user-attachments/files/24863884/ProjetFinalRayanBelon.odt)


Bienvenue sur mon projet d'électronique !
## 📝 Description
Suite aux problématiques de non-conformité rencontrées, mon projet consiste à concevoir et réaliser un système de test dynamique permettant de vérifier l’intégrité des MOSFET acquis par SPHEREA. L'objectif est de s'assurer que chaque composant respecte rigoureusement son Aire de Sécurité de Fonctionnement (SOA) avant son intégration dans les systèmes de puissance. 
## 🚀 Comment ça marche ?
Le système s'articule autour d'un pupitre de commande centralisant les paramètres de test. Le banc de mesure est constitué des éléments suivants :
    • Alimentation stabilisée : Pour générer les niveaux de tension  et de courant  requis.
    • Shunt de mesure : Pour mesurer avec précision le courant traversant le MOSFET.
    • Instrumentation : Multimètres et ampèremètres pour le relevé des données en temps réel.
    • Interface de contrôle (Pupitre) : Permet à l'opérateur de configurer les points de test.

3. Protocole de test : "L'attaque" du composant
Le principe de vérification repose sur l'application d'une impulsion contrôlée, souvent appelée "attaque" ou "stress test" :
    1. Configuration : L'utilisateur définit via le pupitre une consigne précise de tension, de courant et surtout une durée d'impulsion .
    2. Injection : Le système applique ces contraintes au MOSFET.
    3. Analyse : On vérifie si le composant survit à l'impulsion sans dérive de ses caractéristiques thermiques ou électriques. Si le MOSFET supporte la charge dans le temps imparti, sa conformité à la courbe SOA est validée.

## 🔌 Synoptique


![Capture d’écran 2026-01-26 162815](https://github.com/user-attachments/assets/67da4040-ff8e-4b0b-a80f-2116117b700b)

## SOA 

<img width="725" height="734" alt="SOA" src="https://github.com/user-attachments/assets/d409612f-7d06-4ee0-aeaa-d29482ec7e79" />

<img width="641" height="618" alt="image" src="https://github.com/user-attachments/assets/0b0009a7-0dce-4abc-95fb-3a4d7e26018b" />


