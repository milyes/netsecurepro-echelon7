# 🎯 Script de Démonstration & Réponses aux Objections (3 Minutes)

## 1. L'Accroche (0:00 - 1:00)
> « Embaucher 3 analystes SOC coûte **300 000 $/an**. Avec **NetSecurePro IA Échelon 7** (validé par Microsoft), vous avez un agent autonome qui fait ce travail 24/7 pour **497 $/mois**, déployé en 30 jours. »

## 2. La Simulation en Direct (1:00 - 2:00)
Lancer l'attaque critique sur le serveur :
```bash
curl -s -X POST http://127.0.0.1:8090 -d '{"id":"RANSOM-999","cvss":9.8,"sources":4,"asset":"serveur-comptabilite","log":"Tentative chiffrement detectee"}'
```
> « En moins de 2 minutes, l'agent détecte, isole le serveur, applique le correctif et vérifie que la faille est fermée sans réveiller personne. »

## 3. Le Bilan DG en 3 Lignes (2:00 - 3:00)
Montrer le tableau de bord :
* **2 attaques majeures bloquées et réparées en 2 min.**
* **12 tentatives d'intrusion bloquées automatiquement.**
* **0 $ de perte. Équipe pas dérangée. Vous pouvez dormir.**

## 4. Réponses aux Objections PME
* **« On a déjà un antivirus »** ➔ L'antivirus bloque le passé ; Échelon 7 surveille, isole et répare en temps réel 24/7.
* **« On a un prestataire IT »** ➔ Il gère le quotidien le jour ; notre agent absorbe le bruit la nuit et lui mâche le travail en cas d'urgence.
* **« On est trop petits »** ➔ Les attaques sont automatisées par des robots ; il faut un agent autonome pour y répondre à la même vitesse.
