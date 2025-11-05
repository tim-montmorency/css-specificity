# Spécificité CSS
Un quiz amusant pour apprendre et pratiquer la spécificité en CSS.

## Développement
Installer le projet avec npm :
```
npm i 
```
Démarrer le serveur de développement :
```
npm run dev 
```

## Déploiement
Minifier les fichiers :
```
npm run build
```
Téléverser le contenu du dossier dist sur le serveur

## Structure des niveaux
| Clé | Type | Description |
| --- | ---- | ----------- |
| slug | String | Utilisé dans l'URL et pour les traductions des descriptions |
| html | String | HTML pour ce niveau |
| shuffle | Bool | L'ordre des réponses peut-il être aléatoire? *(true par défaut)* |
| answers | Array | Tableau de réponses |    
| selector | String | Sélecteur CSS pour une réponse |
| specificity | Number | Spécificité du sélecteur correspondant |
| bg | String | Couleur de fond forcée pour cette réponse |
| good | Bool | Est-ce la bonne réponse? | 

## Langue
- Français
