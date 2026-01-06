# Guide pour Ajouter Vos Photos

Ce document explique comment ajouter vos propres photos au site ceduweb.

## Structure des Dossiers

Le dossier `images` est déjà créé dans votre projet :
```
ceduweb/
  ├── index.html
  ├── images/              ← Ajoutez vos photos ici
  │   ├── profile.jpg      (à ajouter)
  │   ├── workspace.jpg    (à ajouter)
  │   └── modale-screenshot.jpg (à ajouter)
  ├── PHOTOS_GUIDE.md
  └── README.md
```

## Photos Nécessaires

### 1. Photo de Profil (Hero Section)
**Fichier:** `images/profile.jpg`
**Taille recommandée:** 800x800px (carré)
**Format:** JPG ou PNG
**Description:** Votre photo professionnelle

**Comment l'ajouter:**
1. Prenez une photo professionnelle de vous (fond neutre, bonne lumière)
2. Recadrez-la en format carré (1:1)
3. Sauvegardez-la dans `images/profile.jpg`
4. Dans `index.html` ligne ~121, décommentez cette ligne:
   ```html
   <img src="images/profile.jpg" alt="Cédric Aguettaz" class="w-full h-full object-cover">
   ```
5. Supprimez ou commentez le SVG placeholder (lignes 113-118)

### 2. Photo de Workspace (Section "Comment je travaille")
**Fichier:** `images/workspace.jpg`
**Taille recommandée:** 1200x1200px (carré)
**Format:** JPG ou PNG
**Description:** Votre espace de travail, votre bureau, ou setup de développement

**Idées de photos:**
- Votre bureau avec votre ordinateur
- Vue de votre setup de développement
- Photo de vous en train de coder
- Votre environnement de travail

**Comment l'ajouter:**
1. Prenez une photo de votre espace de travail
2. Sauvegardez-la dans `images/workspace.jpg`
3. Dans `index.html` ligne ~350, décommentez cette ligne:
   ```html
   <img src="images/workspace.jpg" alt="Mon espace de travail" class="w-full h-full object-cover">
   ```
4. Le code illustration sera automatiquement caché par l'image

### 3. Capture d'Écran de modale.ch (Section Projets)
**Fichier:** `images/modale-screenshot.jpg`
**Taille recommandée:** 1920x1080px (16:9)
**Format:** JPG ou PNG
**Description:** Capture d'écran de votre site modale.ch

**Comment faire une belle capture:**
1. Ouvrez https://modale.ch dans un navigateur
2. Utilisez un outil comme [Screely](https://screely.com) ou [Screen.Guru](https://screen.guru) pour ajouter un fond
3. Ou simplement faire une capture d'écran propre de la page d'accueil
4. Sauvegardez dans `images/modale-screenshot.jpg`
5. Dans `index.html` ligne ~580, décommentez cette ligne:
   ```html
   <img src="images/modale-screenshot.jpg" alt="Screenshot modale.ch" class="w-full h-full object-cover">
   ```

## Alternatives si Vous N'avez Pas de Photos

### Sites de Photos Gratuites
- [Unsplash](https://unsplash.com) - Photos professionnelles gratuites
- [Pexels](https://pexels.com) - Photos et vidéos gratuites
- [Pixabay](https://pixabay.com) - Images gratuites

### Sites pour Créer des Mockups
- [Screely](https://screely.com) - Ajouter un fond à vos captures d'écran
- [Screen.Guru](https://screen.guru) - Mockups de browser
- [Shots](https://shots.so) - Créer de beaux mockups

### Outils pour Photo de Profil
- [Remove.bg](https://remove.bg) - Enlever le fond d'une photo
- [Photopea](https://photopea.com) - Éditeur photo en ligne gratuit
- Utilisez votre téléphone avec le mode portrait

## Optimisation des Images

Pour améliorer les performances du site:

1. **Compresser les images:**
   - [TinyPNG](https://tinypng.com) - Compression PNG/JPG
   - [Squoosh](https://squoosh.app) - Outil Google pour compresser

2. **Tailles recommandées:**
   - Photo de profil: max 500 Ko
   - Workspace: max 800 Ko
   - Screenshot: max 1 Mo

3. **Format WebP (optionnel mais recommandé):**
   - Convertissez vos images en WebP pour une meilleure compression
   - Modifiez les extensions dans le HTML de `.jpg` à `.webp`

## Checklist

- [ ] Créer le dossier `images/` (déjà fait ✓)
- [ ] Ajouter `profile.jpg` (votre photo professionnelle)
- [ ] Ajouter `workspace.jpg` (votre espace de travail)
- [ ] Ajouter `modale-screenshot.jpg` (capture de modale.ch)
- [ ] Décommenter les balises `<img>` dans `index.html`
- [ ] Tester que les images s'affichent correctement
- [ ] Optimiser les images pour le web

## Besoin d'Aide ?

Si vous avez des questions sur comment ajouter vos photos ou si vous rencontrez des problèmes:
1. Vérifiez que les chemins des fichiers sont corrects
2. Vérifiez que les noms de fichiers correspondent exactement
3. Assurez-vous que le dossier `images/` est au même niveau que `index.html`
