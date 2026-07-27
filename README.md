# Moments — prototype diaporama de voyage

Prototype web statique (HTML/CSS/JS, aucune dépendance) pour tester le concept :
sélection de photos sans limite, tri automatique (flou, doublons, répartition par jour),
récit audio/texte, choix de style et de format, rendu en diaporama / mood board / album.

Tout tourne côté navigateur : aucune photo n'est envoyée à un serveur.

## Utiliser en local
Ouvrir `index.html` dans un navigateur. Pour tester l'enregistrement audio (micro),
il faut le servir via un petit serveur local plutôt que de l'ouvrir en double-clic :

```
python3 -m http.server 8000
```
puis ouvrir http://localhost:8000

## Déploiement
Ce projet est 100% statique : aucun build, aucune dépendance. Vercel le déploie tel quel.
