# Shadow Quiz — Pokémon Edition

Un jeu de quiz PWA où tu dois deviner des Pokémon à partir de leur ombre ! Disponible sur mobile et desktop.

## 🎮 Modes de jeu

### Mode Normal
Devine le Pokémon caché derrière son ombre. La difficulté augmente progressivement en 11 niveaux, jusqu'au mode **Chaos** (600+) où le palier est tiré au hasard à chaque question :

| Palier | Score | Choix | Temps | Effet visuel |
|--------|-------|-------|-------|--------------|
| 🟢 Débutant | 0–20 | 4 | 10s | Silhouette normale |
| 🟡 Novice | 21–50 | 4 | 5s | Silhouette normale, tempo rapide |
| 🟠 Chasseur | 51–74 | 6 | 10s | Silhouette normale |
| 🔴 Dresseur | 75–100 | 6 | 5s | Silhouette normale, tempo rapide |
| 🟣 Expert | 101–150 | 4 | 10s | Silhouette légèrement floue (~5px) |
| ⚫ Maître | 151–200 | 4 | 10s | Miroir inversé |
| 💀 Élite | 201–280 | 4 | 10s | Rotation aléatoire |
| 👁️ Légendaire | 281–380 | 6 | 10s | Miroir inversé |
| ⭐ Champion | 381–500 | 6 | 10s | Rotation aléatoire |
| 🌑 Ombre Pure | 501–599 | Saisie libre | 15s | Silhouette noire classique |
| 🎲 Chaos | 600+ | Aléatoire | Aléatoire | Palier aléatoire parmi tous |

Mauvaise réponse ou temps écoulé = fin de partie.

### Contre-la-Montre
60 secondes pour deviner un maximum de Pokémon. 4 choix par question. Pas de pénalité sur erreur — on passe au suivant.

### Avec un Ami
Même série de Pokémon, comparez vos scores en temps réel. Crée une partie et partage le code. Difficulté fixe : 4 choix · 10s.

### Entraînement
Apprends sans pression : pas de timer, pas de score. Choisis la génération à entraîner. Les Pokémon devinés ne comptent pas dans le Pokédex.

### Mode Inversé 🌑
Tu vois le **nom** du Pokémon, tu dois reconnaître sa **silhouette** parmi 4 images. 10 secondes par question. Mauvaise réponse = fin. Teste ta mémoire visuelle !

### Mode Son 🔊
Le **cri** du Pokémon est joué automatiquement. Tu dois deviner son **nom** parmi 4 choix. 12 secondes par question. Appuie sur 🔊 pour réécouter. Mauvaise réponse = fin.

## ✨ Système Shiny

Les Pokémon shiny apparaissent **uniquement en Mode Normal** — ils s'affichent en couleur (sans filtre ombre), il faut les reconnaître à vue.

Le taux part de **1/750** et double à chaque palier de difficulté, jusqu'à **1/16** max :

| Niveau | Score | Taux shiny |
|--------|-------|-----------|
| 0 – Débutant | 0–20 | 1/750 |
| 1 – Novice | 21–50 | 1/375 |
| 2 – Chasseur | 51–74 | 1/187 |
| 3 – Dresseur | 75–100 | 1/93 |
| 4 – Expert | 101–150 | 1/46 |
| 5 – Maître | 151–200 | 1/23 |
| 6 – Élite | 201–280 | 1/16 |
| 7 – Légendaire | 281–380 | 1/16 |
| 8 – Champion | 381–500 | 1/16 |
| 9 – Ombre Pure | 501–599 | 1/16 |
| 🎲 Chaos | 600+ | 1/16 |

Le taux est **identique** pour tous les Pokémon, légendaires inclus.

Les shiny trouvés sont visibles dans la section **Shiny** du Pokédex.

## 🐉 Pokémon Légendaires

Les légendaires sont **plus rares à rencontrer** en Mode Normal.

Le taux de base est **1/25** et **double à chaque badge** obtenu :

| Badges | Taux légendaire |
|--------|----------------|
| 0 | 1/25 |
| 1 (🌱 Dresseur) | 1/12 |
| 2 (⚔️ Challenger) | 1/6 |
| 3 (🏅 Champion) | 1/3 |
| 4+ (💎 Élite…) | ~100% |

Plus tu as de badges (basés sur ton niveau XP), plus tu as de chances de croiser un légendaire.

## 🏆 Succès

62 succès répartis en 10 catégories :
- **Classique** — Score et progression (7 succès)
- **Chrono** — Performance contre-la-montre (3 succès)
- **Daily** — Défis quotidiens et streaks (6 succès)
- **Pokédex** — Découverte de Pokémon (5 succès)
- **Type** — Maîtriser chaque type (50 Pokémon par type · 18 succès)
- **Entraînement** — Compléter chaque génération (9 succès)
- **Général** — Nombre de parties jouées (3 succès)
- **Spécial** — Événements rares (nuit, dimanche, Rayquaza... · 5 succès)
- **Inversé** — Progresser en Mode Inversé (3 succès)
- **Son** — Progresser en Mode Son (3 succès)

## 🖼️ Fonds d'écran

Débloque des fonds d'écran en progressant :
- **18 types** — Découvrir 50 Pokémon de chaque type
- **Rayquaza** — Attraper Rayquaza
- **All Pokémon** — Compléter le Pokédex

## 📅 Daily Challenge

Un Pokémon par jour, 5 essais max. Maintiens ta streak quotidienne !

## 🏅 Badges & Niveau XP

Le système de progression est basé sur l'XP accumulée en jouant :

| Badge | Niveau requis |
|-------|--------------|
| 🌱 Dresseur | 1 |
| ⚔️ Challenger | 5 |
| 🏅 Champion | 10 |
| 💎 Élite | 20 |
| 👑 Maître Pokémon | 35 |
| 🌟 Légendaire | 50 |

Les Poké Balls associées au niveau (Poké Ball → Super Ball → Hyper Ball → Premier Ball → Luxury Ball → Master Ball → Cherish Ball) sont visibles dans le profil.

Plus tu as de badges, plus tu as de chances de croiser un légendaire en Mode Normal.

## 📖 Pokédex

Découvre les 1025 Pokémon et gère ta collection :
- **Filtres** : Tous / Découverts / Inconnus / Favoris
- **Favoris** : Marque tes Pokémon préférés avec ❤️
- **Shiny** : Retrouve tous les shiny capturés
- Organisé par génération avec statistiques de complétion

## 🕹️ Historique des parties

Les 10 dernières parties sont sauvegardées et visibles dans ton profil : mode, score, Pokémon qui t'a arrêté.

## 🎨 Fonctionnalités visuelles

- **Animation d'apparition** : La silhouette se matérialise à chaque nouvelle question
- **Transition de score** : Le score s'anime visuellement quand il augmente
- **Effets de difficulté** : Révélation progressive, flou croissant, miroir, rotation, miniature, couleurs floues, flash selon le palier atteint
- **Vibration** : Retour haptique au bon/mauvais choix (appareils compatibles)
- **Sons de victoire** : 5 niveaux de sons selon le score final

## 🛠️ Stack technique

- **Frontend** : HTML/CSS/JS vanilla avec ES Modules
- **Backend** : Firebase (Firestore + Auth anonyme)
- **PWA** : Service Worker pour le cache et l'utilisation offline
- **Données** : 1025 Pokémon (Générations I à IX)

## 📂 Structure

```
├── index.html              Page principale
├── sw.js                   Service Worker
├── manifest.json           Manifest PWA
├── firestore.rules         Règles de sécurité Firebase
├── js/
│   ├── core/               Modules fondamentaux
│   │   ├── config.js       Configuration Firebase
│   │   ├── data.js         Chargement des données Pokémon
│   │   ├── auth.js         Authentification Firebase
│   │   ├── utils.js        Fonctions utilitaires
│   │   ├── toast.js        Notifications toast
│   │   ├── badges.js       Système de badges
│   │   ├── xp.js           Système de niveaux XP
│   │   ├── quests.js       Quêtes quotidiennes
│   │   ├── migration.js    Migration des données locales
│   │   └── audio.js        Gestion audio
│   ├── modes/              Modes de jeu
│   │   ├── game.js         Mode Normal (ombres, shiny, pokédex)
│   │   ├── daily.js        Mode Daily
│   │   ├── timerGame.js    Mode Contre-la-montre
│   │   ├── friendGame.js   Mode Ami (multijoueur)
│   │   ├── inverseGame.js  Mode Inversé (nom → silhouette)
│   │   ├── soundGame.js    Mode Son (cri → nom)
│   │   └── training.js     Mode Entraînement
│   └── ui/                 Interface utilisateur
│       ├── main.js         Initialisation et navigation
│       ├── profile.js      Profil et Pokédex
│       ├── leaderboard.js  Classements
│       ├── settings.js     Paramètres et fonds d'écran
│       ├── achievements.js Système de succès
│       └── achievements_screen.js  Écran des succès
├── css/
│   ├── base/               Styles de base
│   │   ├── base.css        Variables, reset, wallpapers
│   │   ├── buttons.css     Boutons
│   │   └── dark.css        Mode sombre
│   ├── components/         Composants UI
│   │   ├── header.css      En-tête
│   │   ├── modal.css       Modales
│   │   ├── rules.css       Info des modes
│   │   ├── achievements.css Succès
│   │   ├── quests.css      Quêtes du jour
│   │   └── ads.css         Publicités & bannières UI
│   └── screens/            Écrans
│       ├── game.css        Écran de jeu
│       ├── daily.css       Écran daily
│       ├── leaderboard.css Classements
│       └── profile.css     Profil
├── image/
│   ├── icons/              Icônes et logo
│   ├── types/              Fonds par type Pokémon
│   └── wallpapers/         Fonds spéciaux
├── data/                   Données Pokémon (JSON + scripts Python)
└── audio/                  Musiques et effets sonores
```

## 🚀 Déploiement

1. Configurer Firebase dans `js/config.js`
2. Déployer les règles Firestore : `firebase deploy --only firestore:rules`
3. Servir les fichiers statiques (Firebase Hosting, Netlify, etc.)

## 📝 Licence

Projet personnel — Pokémon est une marque déposée de Nintendo/Game Freak/Creatures.
