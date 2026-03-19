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




Voici la transcription complète du contenu de l’image 👇
🔐 Surveillance de la Sécurité et Résilience
Demande d’intégration de logs
4 - PRS-SSI-SOC-Collecte de logs v1.1
Les demandes d’intégration de log doivent, dans tous les cas, respecter les principes suivants :
Toute demande d’intégration doit être justifiée par le demandeur par un scénario d’utilisation (surveillance applicative, alertes prévues, etc.) ;
Les demandes doivent être effectuées via l’outil de ticketing interne « Darwin ».
Les informations suivantes doivent figurer dans la demande :
Le nom de l’application ou du composant système
Le point de contact de l’équipe ayant la responsabilité de l’application ou du composant système (idéalement une liste de diffusion)
Les informations permettant la localisation du fichier de log (nom du serveur, chemin sur le serveur, nom de la base de données, serveur syslog, etc.)
Le format des logs (json, xml, format propriétaire, etc.)
La présence ou non de données personnelles
Un exemple de log
Le demandeur doit également préciser :
La confidentialité des données contenues dans les logs (interne, confidentielle, etc.)
La présence ou non de données personnelles et leurs types
Les accès nécessaires à l’index (ouvert à tous, restreint à une ou plusieurs équipes, etc.)
Le besoin d’anonymiser certains champs en accord avec le RSSI concerné
D’autres informations peuvent être nécessaires et seront demandées lors de son traitement
Les demandes d’intégration de log sont validées et traitées par les administrateurs du SIEM
CDC Informatique
Fondamentaux de l’administration cybersécurité
57
Si tu veux, je peux te transformer ça en page Confluence propre (avec titres, macros, checklist, etc.) 👍
