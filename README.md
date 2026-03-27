Voici le playbook. Points clés :
Structure de la policy
policyType: 2 → obligatoire pour le Row Level Filter (0 = Access, 1 = Data Masking, 2 = Row Filter)
filterExpr: "1=0" → la condition appliquée au groupe group1, ce qui retourne zéro ligne
Les ressources ciblent précisément database1 / table1 / toutes colonnes (*)
Logique idempotente
Le playbook vérifie d'abord si la policy existe déjà sur le serveur primaire : il fait un POST pour la créer, ou un PUT pour la mettre à jour — sans doublon.
Double serveur Ranger
Chaque appel (création/mise à jour/vérification) boucle sur les 2 URLs via loop: "{{ ranger_servers }}".
À adapter selon votre environnement
ranger_servers:
  - "https://ranger-server1.example.com:6182"
  - "https://ranger-server2.example.com:6182"
ranger_hive_service: "hive_service"   # nom exact du service dans Ranger
Mot de passe sécurisé — utiliser Ansible Vault :
ansible-vault encrypt_string 'MonMotDePasse' --name 'vault_ranger_password'
