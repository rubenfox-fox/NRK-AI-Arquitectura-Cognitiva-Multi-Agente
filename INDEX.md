# Index et Guide du Répertoire: NRK-AI Architecture Multi-Agente

Ce répertoire contient l'architecture, les modules de consignes et les flux de travail pour la coordination de systèmes multi-agents. Les composants sont classés par strates d'exécution, agents hybrides et modules de traitement spécialisé.

## 1. Modules d'Agents ERA (Exécution et Raisonnement Avancé)
Les fichiers `ERA_X*.txt` définissent les instructions, les rôles et les protocoles de comportement pour les agents de la strate ERA :
* **ERA_X1 à ERA_X3 :** Protocoles d'initialisation, cadrage contextuel et amorçage du raisonnement logique pour l'orquestrateur.
* **ERA_X4 à ERA_X7 :** Sous-routines d'exécution avancée, vérification de cohérence et boucles de rétroaction pour la résolution de tâches complexes.

## 2. Modules d'Agents MER (Mémoire et Évaluation de Réponses)
Les fichiers `MER_R*.txt` contiennent les spécifications pour la gestion de l'état, la critique interne et le filtrage des réponses :
* **MER_R1 et MER_R2 :** Protocoles d'évaluation et de pondération des hypothèses générées.
* **MER_R5 :** Module de validation finale et de colapsage des états pour la sortie structurée.

## 3. Configurations Hybrides (`HIBRIDO_*.txt`)
* **HIBRIDO_ALPHA.txt :** Configuration de fusion pour l'interfaçage entre les couches de raisonnement symbolique et les moteurs neuronaux.
* **HIBRIDO_BETA.txt :** Paramétrage avancé pour l'orquestración en parallèle de sous-agents spécialisés.

---
*Tous les codes sources de ce répertoire sont régis par la licence MIT, tandis que la documentation et les schémas conceptuels relèvent de la licence CC BY 4.0.*

```
