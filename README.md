# 🫧 Crypto Bubbles PWA

## Installation sur Android

1. **Héberge les fichiers** sur un serveur HTTPS :
   - Option gratuite : [Netlify Drop](https://app.netlify.com/drop) — glisse-dépose le dossier
   - Ou GitHub Pages, Vercel, Firebase Hosting

2. **Sur ton Android** : ouvre Chrome → va sur ton URL
3. Menu ⋮ → **"Ajouter à l'écran d'accueil"**
4. L'app s'installe comme une vraie app !

## Structure des fichiers
```
index.html    ← app principale
manifest.json ← config PWA
sw.js         ← service worker (cache offline)
icons/        ← icônes app
```

## Fonctionnalités
- Top 50 cryptos via CoinGecko (gratuit, sans API key)
- Bulles physiques animées et interactives
- Variation 1H / 24H / 7J
- Vert = hausse, Rouge = baisse
- Touch pour voir le détail de chaque crypto
- Rafraîchissement automatique toutes les 60s
- Mode démo si pas de connexion
