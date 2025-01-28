# Lancement de l'API

- Cloner le repo https://github.com/mathisDeronne/DevOps.git

- Ouvrir un terminal dans le dossier "WIK-DPS-TP01"

- Ajouter un .env pour y mettre la variable qui définit le port utilisé. Si elle n'est pas défini, alors elle prendra la valeur par défaut de "4040"

## Commandes a faire dans le terminal

```
PING_LISTEN_PORT=8080
```

- Installer les dépendences
```
npm install
```

- Compiler le code
```
npx tsc index.ts
```

- Lancer le code
```
node index.js
```