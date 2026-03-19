Parfait 👍 Voici une version optimisée pour Confluence, claire, structurée et professionnelle (avec style “procédure + checklist”) 👇
🔐 Surveillance de la Sécurité et Résilience
📥 Demande d’intégration de logs
🎯 Objectif
Cette page définit le processus et les exigences pour toute demande d’intégration de logs dans le SIEM, afin d’assurer :
Une surveillance efficace des systèmes
La conformité aux exigences de sécurité
La protection des données sensibles
📌 Principes généraux
Toute demande doit respecter les règles suivantes :
✅ Être justifiée par un scénario d’utilisation
(ex : supervision, détection d’incident, alerting…)
✅ Être soumise via l’outil de ticketing interne (Darwin)
❌ Aucune intégration sans validation préalable
🧾 Informations obligatoires
Le demandeur doit fournir les éléments suivants :
🔹 Informations générales
Nom de l’application ou composant système
Équipe responsable (contact ou liste de diffusion)
🔹 Localisation des logs
Nom du serveur
Chemin du fichier de log
Nom de la base de données (si applicable)
Serveur syslog (si utilisé)
🔹 Caractéristiques techniques
Format des logs :
JSON
XML
Format propriétaire
Exemple de log (obligatoire)
🔹 Données sensibles
Présence de données personnelles (Oui / Non)
🔐 Exigences de sécurité
Le demandeur doit également préciser :
🔒 Niveau de confidentialité :
Interne
Confidentiel
📊 Types de données personnelles (si présentes)
👥 Accès aux logs :
Ouvert
Restreint (préciser les équipes)
🕶️ Besoin d’anonymisation de certains champs
(à valider avec le RSSI)
⚙️ Processus de traitement
Plain text
1. Soumission via Darwin
2. Vérification de complétude
3. Analyse sécurité (RSSI si nécessaire)
4. Validation
5. Intégration dans le SIEM
6. Tests et mise en production
📋 Checklist (à copier dans ticket)
✅ Scénario d’utilisation fourni
✅ Application identifiée
✅ Contact équipe renseigné
✅ Localisation des logs complète
✅ Format des logs précisé
✅ Exemple de log fourni
✅ Données personnelles identifiées
✅ Niveau de confidentialité défini
✅ Accès aux logs précisé
✅ Besoin d’anonymisation évalué
👮 Gouvernance
Les intégrations sont validées et réalisées par les administrateurs du SIEM
Des informations complémentaires peuvent être demandées
Toute non-conformité peut entraîner un refus
⚠️ Bonnes pratiques
Éviter l’exposition de données sensibles non nécessaires
Minimiser les données collectées (principe de minimisation)
Préférer des logs structurés (JSON recommandé)
Documenter les cas d’usage
