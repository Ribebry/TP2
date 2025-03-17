# TP2

### Quelles étapes (steps) sont réalisées par cette action ?

    Checkout du code (actions/checkout@v4)
    Installation de Python (actions/setup-python@v3)
    Installation des dépendances
    Exécution des tests avec pytest

### Une étape est définie au minimum par 2 éléments, lesquels sont-ils et à quoi servent-ils ?

    name : Nom de l’étape | run : Commande exécutée

### La première étape contient le mot-clé ‘with’, a quoi sert-il ?
Il permet de passer des arguments à l’action utilisée (exemple : choisir la version de Python).

### Quels sont les 4 indicateurs de l’onglet Summary ?

    Bugs → Problèmes de code qui peuvent provoquer des erreurs.
    Vulnerabilities → Failles de sécurité potentielles.
    Code Smells → Mauvaises pratiques affectant la maintenabilité.
    Coverage → Pourcentage de code testé.

### À quoi sert l’indicateur Quality Gate ?

Il détermine si le code respecte les critères de qualité définis (ex. couverture minimale, absence de bugs critiques).

### Quelle est la différence entre New Code et Overall Code ?
    New Code → Changements récents
    Overall Code → Tout le code du projet

Y a-t-il des Code Smells ? 
Y a-t-il des Security Hotspots ?