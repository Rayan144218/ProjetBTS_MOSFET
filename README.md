# Projet MOSFET
# ⚡ Projet BTS - Simulation de Transistor MOSFET

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

## 🔌 Schéma du montage
Voici le principe de connexion pour le test de "stress" du MOSFET :

| Composant | Rôle dans le test |
| :--- | :--- |
| **Alimentation** | Génère la tension $V_{ds}$ |
| **Générateur d'impulsion** | Contrôle la grille ($V_{gs}$) pour l'attaque |
| **Shunt** | Mesure le courant $I_d$ sans perturber le circuit |

> [!TIP]
> Le test de conformité SOA est effectué à l'aide d'une impulsion unique de 10ms pour éviter l'échauffement excessif.
