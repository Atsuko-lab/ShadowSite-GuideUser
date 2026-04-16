# Shadow Quiz — Pokémon Edition

Quiz PWA gratuit : devine le Pokémon caché par son ombre ! 1025 Pokémon (Gen I–IX), 6 modes de jeu, classements en ligne, succès, quêtes quotidiennes, système shiny et bien plus. Jouable sur mobile et desktop, en 4 langues (🇫🇷 🇬🇧 🇪🇸 🇯🇵).

🔗 [Shadow SITE - Pokémon Edition](https://shadowsitepoke.vercel.app/)

---

## 🎮 Modes de jeu

### Mode Normal
Devine le Pokémon caché derrière son ombre. La difficulté augmente progressivement en 11 paliers, jusqu'au mode **Chaos** (600+) où le niveau est aléatoire à chaque question :

| Palier | Score | Choix | Temps | Effet visuel |
|--------|-------|-------|-------|--------------|
| 🟢 Débutant | 0–20 | 4 | 10s | Silhouette normale |
| 🟡 Novice | 21–50 | 4 | 5s | Tempo rapide |
| 🟠 Chasseur | 51–74 | 6 | 10s | 6 choix |
| 🔴 Dresseur | 75–100 | 6 | 5s | 6 choix, tempo rapide |
| 🟣 Expert | 101–150 | 4 | 10s | 🌫️ Silhouette floue |
| ⚫ Maître | 151–200 | 4 | 10s | 🪞 Miroir inversé |
| 💀 Élite | 201–280 | 4 | 10s | 🔄 Rotation aléatoire |
| 👁️ Légendaire | 281–380 | 6 | 10s | 🪞 Miroir + 6 choix |
| ⭐ Champion | 381–500 | 6 | 10s | 🔄 Rotation + 6 choix |
| 🌑 Ombre Pure | 501–599 | Saisie libre | 15s | Silhouette noire classique |
| 🎲 Chaos | 600+ | Aléatoire | Aléatoire | Palier aléatoire ! |

- **Bonus vitesse / combo** : réponse rapide en moins de 2 secondes ; combo actif dès 2 réponses rapides d'affilée ; gain plafonné à 5 pts maximum par bonne réponse
- Mauvaise réponse ou temps écoulé = fin de partie
- La rotation aléatoire a été améliorée pour limiter les répétitions fréquentes des mêmes Pokémon

### ⏱️ Contre-la-Montre
60 secondes pour deviner un maximum de Pokémon. 4 choix par question, pas de pénalité sur erreur.

### 🔗 Avec un Ami
Même série de Pokémon (seed partagé), comparez vos scores en temps réel. Crée une partie, partage le code, et c'est parti ! Difficulté fixe : 4 choix · 10s. Détection de déconnexion par heartbeat.

### 🎓 Entraînement
Apprends sans pression : pas de timer, pas de score. Choisis la génération à entraîner (Gen I à IX ou toutes). Ne compte pas dans le Pokédex.

### 🌑 Mode Inversé
Tu vois le **nom** du Pokémon, tu dois reconnaître sa **silhouette** parmi 4 images. 10s par question. Teste ta mémoire visuelle !

### 🔊 Mode Son
Le **cri** du Pokémon est joué automatiquement. Devine son **nom** parmi 4 choix. 12s par question. Appuie sur 🔊 pour réécouter.

---

## ✨ Système Shiny

Les Pokémon shiny apparaissent **uniquement en Mode Normal** — ils s'affichent en couleur (sans filtre ombre), il faut les reconnaître à vue.

Le taux de base est **1/750** et diminue par paliers de score, avec un cap à **1/50** dès 250 points :

| Score | Taux shiny |
|-------|-----------|
| 0–19 | 1/750 |
| 20–49 | 1/650 |
| 50–79 | 1/550 |
| 80–109 | 1/400 |
| 110–139 | 1/300 |
| 140–169 | 1/200 |
| 170–199 | 1/150 |
| 200–229 | 1/100 |
| 230–249 | 1/75 |
| 250+ | 1/50 (max) |

Le taux est identique pour tous les Pokémon, légendaires inclus. Les shiny trouvés sont visibles dans la section **Shiny** du Pokédex.

## 🐉 Pokémon Légendaires

Les légendaires (~80 Pokémon) sont **plus rares à rencontrer** en Mode Normal.

Le taux de base est **1/25** et **double à chaque badge** obtenu :

| Badges | Taux légendaire |
|--------|----------------|
| 0 | 1/25 |
| 1 (🌱) | 1/12 |
| 2 (⚔️) | 1/6 |
| 3 (🏅) | 1/3 |
| 4+ (💎…) | ~100% |

---

## 📅 Daily Challenge

Un Pokémon par jour, identique pour tous les joueurs. 5 essais max en saisie libre. Maintiens ta streak quotidienne pour grimper dans le classement Streaks !

## 📋 Quêtes quotidiennes

5 quêtes renouvelées chaque jour, piochées parmi 58 quêtes possibles sur 5 niveaux de difficulté (facile → légendaire). Exemples : deviner X Pokémon, faire un speed bonus, jouer un mode spécifique, trouver un légendaire… Chaque quête terminée rapporte de l'XP (10 à 200 XP).

---

## 🏅 Badges & Niveau XP

L'XP s'accumule en jouant et en complétant des quêtes. La formule est exponentielle : `XP(n) = 10 × n^1.6`.

| Badge | Niveau requis |
|-------|--------------|
| 🌱 Dresseur Débutant | 1 |
| ⚔️ Challenger | 5 |
| 🏅 Champion | 10 |
| 💎 Élite | 20 |
| 👑 Maître Pokémon | 35 |
| 🌟 Légendaire | 50 |

**Poké Balls** associées au niveau : Poké Ball (1) → Super Ball (5) → Hyper Ball (10) → Premier Ball (20) → Luxury Ball (30) → Master Ball (50) → Cherish Ball (75).

Plus tu as de badges, plus tu as de chances de croiser un légendaire.

---

## 🏆 Succès

**72 succès** répartis en 10 catégories :

| Catégorie | Nombre | Exemples |
|-----------|--------|----------|
| 🎮 Classique | 7 | 1er Pokémon, 100 pts, 500 pts, 1000 pts… |
| ⏱️ Chrono | 3 | 10, 20, 30 Pokémon en 60s |
| 📅 Daily | 6 | 1er daily, 1er essai, streak 7j/30j/100j |
| 📖 Pokédex | 5 | 10, 151, 300, 500 Pokémon + Pokédex complet |
| 🔥 Type | 18 | 50 Pokémon découverts par type |
| 🎓 Entraînement | 9 | Compléter chaque génération |
| 🎲 Général | 3 | 10, 50, 100 parties classiques |
| ⭐ Spécial | 5 | Jouer de nuit, le dimanche, trouver Rayquaza… |
| 🌑 Inversé | 3 | 10, 25, 50 pts en Inversé |
| 🔊 Son | 3 | 10, 25, 50 pts en Son |

20 succès débloquent des fonds d'écran.

## 🖼️ Fonds d'écran (22)

- **Défaut** (toujours débloqué)
- **18 types** — Découvrir 50 Pokémon de chaque type
- **Évoli** — Découvrir les 9 Évolitions
- **Rayquaza** — Découvrir Rayquaza
- **All** — Compléter le Pokédex

---

## 🏆 Classements (6 onglets)

| Onglet | Classement |
|--------|------------|
| 🏆 Top | Meilleurs scores classiques |
| ⏱️ Chrono | Meilleurs scores contre-la-montre |
| 🔥 Streaks | Plus longues streaks daily |
| 📅 Semaine | Scores de la semaine (reset lundi) |
| 🌑 Inversé | Meilleurs scores inversé |
| 🔊 Son | Meilleurs scores son |

Cache 30s, pagination (100 par page), clic sur un joueur pour voir son profil.

---

## 👤 Profil

- Barre d'XP avec niveau et Poké Ball
- Meilleurs scores par mode
- Stats : Pokémon devinés, best streak, taux de réussite, score moyen, streak daily, nombre de succès
- Historique des 10 dernières parties
- **Pokédex** avec filtres (Tous / Découverts / Inconnus / Favoris / Shiny)
- Popup détaillé par Pokémon (stats, types, shiny)
- Système de favoris ❤️
- **Carte de profil partageable** (image générée en Canvas)
- Profil public via `?uid=<id>`

---

## 🎨 Fonctionnalités

- 🌙 **Mode sombre** avec bascule dans les paramètres
- 🌍 **4 langues** : français, anglais, espagnol, japonais
- 📱 **PWA installable** avec mode offline, page de fallback, et mise à jour automatique
- 🔔 **Notifications push** : rappel du daily (00h) + rappel ciblé si daily/quêtes non faits (20h)
- 🔊 **4 pistes musicales** + effets sonores, volume réglable
- 📳 **Vibration haptique** au bon/mauvais choix
- 🎆 **Confetti** sur les événements spéciaux
- 🖼️ **22 fonds d'écran** déblocables
- 🔒 **Validation serveur** des scores via Cloud Function

---

## 🛠️ Stack technique

| Composant | Technologie |
|-----------|-------------|
| Frontend | HTML / CSS / JS vanilla (ES Modules) |
| Backend | Firebase (Firestore + Auth anonyme + Google Sign-In) |
| Cloud Functions | Firebase Functions v2 (Node.js 20) |
| Push | Web Push (VAPID) via `web-push` |
| Mobile | Capacitor 6 (Android) |
| PWA | Service Worker + manifest + offline fallback |
| Données | 1025 Pokémon (JSON statique, Gen I–IX) |

## 📂 Structure

```
├── index.html              Page principale
├── offline.html            Page offline (fallback SW)
├── sw.js                   Service Worker (v2.7.3)
├── manifest.json           Manifest PWA
├── firestore.rules         Règles de sécurité Firestore
├── functions/
│   └── index.js            Cloud Functions (notifications + validation)
├── js/
│   ├── core/               Modules fondamentaux
│   │   ├── config.js       Configuration Firebase + App Check
│   │   ├── data.js         Chargement des données Pokémon
│   │   ├── auth.js         Authentification (anonyme + Google)
│   │   ├── i18n.js         Internationalisation (4 langues)
│   │   ├── utils.js        Fonctions utilitaires
│   │   ├── toast.js        Notifications toast
│   │   ├── badges.js       Système de badges
│   │   ├── xp.js           Système de niveaux XP
│   │   ├── quests.js       Quêtes quotidiennes
│   │   ├── migration.js    Migration des données locales
│   │   ├── audio.js        Gestion audio (Web Audio API)
│   │   └── ads.js          Gestion publicités
│   ├── modes/              Modes de jeu
│   │   ├── game.js         Mode Normal (ombres, shiny, légendaires)
│   │   ├── daily.js        Daily Challenge
│   │   ├── timerGame.js    Contre-la-montre (60s)
│   │   ├── friendGame.js   Mode Ami (multijoueur temps réel)
│   │   ├── inverseGame.js  Mode Inversé (nom → silhouette)
│   │   ├── soundGame.js    Mode Son (cri → nom)
│   │   └── training.js     Entraînement (par génération)
│   └── ui/                 Interface utilisateur
│       ├── main.js         Initialisation, navigation, SW
│       ├── profile.js      Profil, Pokédex, carte partageable
│       ├── leaderboard.js  Classements (cache + pagination)
│       ├── settings.js     Paramètres, thème, fonds d'écran
│       ├── achievements.js Logique des 72 succès
│       ├── achievements_screen.js  Écran des succès
│       └── quests_screen.js Écran des quêtes du jour
├── css/
│   ├── base/               base.css · buttons.css · dark.css
│   ├── components/         header · modal · rules · achievements · quests · ads
│   └── screens/            game · daily · leaderboard · profile
├── data/                   pokemon.json · quests.json · names_*.json · scripts Python
├── image/                  icons · types · wallpapers · pokeballs · badges
└── audio/                  Musiques (.ogg) et effets sonores (.mp3)
```

## 📝 Licence

Projet personnel — Pokémon est une marque déposée de Nintendo/Game Freak/Creatures.
