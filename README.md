# Utilisation

## Comment regrouper plusieurs documentations

1. Exécuter la commande ````npm install````
2. Modifier le fichier de configuation dans ````src/docs/openapi-merge.json````
3. Exécuter la commande ````npx openapi-merge-cli```` dans ce dossier
4. Modifier si besoin le début du fichier avec par exemple
 ```json
   "title": "AOS Project",
   "description": "AOS Project documentation"
 ```
4. Copier le json
5. Coller dans `index.html` ligne 42
6. Mettre les fichier sur un serveur web type Nginx/Apache


