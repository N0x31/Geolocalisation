# Geolocalisation

Récupérer la position GPS et cellulaire dans une appli

1. Crée un nouveau projet Android Studio avec une MainActivity.
2. Implémente la demande de permissions pour l'utilisation de la géolocalisation GPS et cellulaire.
3. Implémente un LocationListener pour écouter la position GPS et cellulaire, en affichant un Toast en cas de nouvelle position reçue.

Critéres de validation

- Les permissions sont demandées dans le manifest et au run time pour GPS et cellulaire.
- La géolocalisation s'arrête lorsque l'activity n'est plus visible par l'utilisateur.
- Le Toast s'affiche dés la réception d'une géolocalisation GPS et cellulaire.
- Le targetSdkVersion est >= 23 (Android 6.0)
