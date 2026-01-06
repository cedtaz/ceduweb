# ceduweb - Site Web Professionnel

Site web professionnel pour ceduweb, spécialisé dans le développement d'applications web et mobiles sur mesure, l'intégration ERP/CRM et les logiciels métiers.

## Caractéristiques

### Design
- **Style moderne et minimaliste** avec des couleurs professionnelles
- **Couleurs principales** :
  - Violet principal : `#8c52ff`
  - Vert secondaire : `#00bf63`
- **Responsive** : Compatible mobile, tablette et desktop
- **Police** : Inter (Google Fonts) pour une lisibilité optimale

### Structure du Site

#### 1. Navigation
- Menu fixe avec liens vers toutes les sections
- Menu mobile responsive avec bouton hamburger
- Logo ceduweb avec dégradé de couleurs

#### 2. Section Hero
- Titre accrocheur : "Concevoir et développer avec vous une application web ou mobile"
- Statistiques clés (490+ projets, 100% Open Source, Support 24/7, RGPD)
- Boutons d'appel à l'action (CTA)

#### 3. Section Services
Présentation détaillée de 6 services principaux :
- ERP / CRM Sur Mesure
- Génération Automatique de Documents
- Workflows & Automatisation
- Tableaux de Bord Intelligents
- Intégration IA & Maintenance Prédictive
- Solutions Santé & Télémédecine

Plus des services complémentaires :
- Planification de Production
- Applications IoT
- Intégration Capteurs
- Migration Cloud
- API REST & GraphQL
- Modernisation IT

#### 4. Section Valeurs
Trois valeurs fondamentales :
- **Souveraineté des Données** : Contrôle total et conformité RGPD
- **Technologies Open Source** : Indépendance des éditeurs
- **Transparence Totale** : Communication claire et méthodes agiles

#### 5. Section Projets
Quatre domaines d'intervention :
- Industrie & Production (Industrie 4.0)
- Santé & Télémédecine (e-Santé)
- Entreprises & Services (B2B)
- Commerce & Distribution (Retail)

#### 6. Section Contact
- Formulaire de contact complet avec validation
- Champs : Nom, Entreprise, Email, Téléphone, Service, Message
- Conformité RGPD avec case à cocher
- Informations de contact (email, téléphone, horaires)

#### 7. Footer
- Branding et description
- Liens sociaux (Facebook, Twitter, LinkedIn)
- Liens rapides vers services et pages entreprise
- Mentions légales, RGPD, Politique de confidentialité

## Technologies Utilisées

- **HTML5** : Structure sémantique
- **Tailwind CSS** : Framework CSS via CDN
- **JavaScript Vanilla** : Interactions et formulaire
- **Google Fonts** : Police Inter

## Fonctionnalités JavaScript

1. **Menu Mobile**
   - Toggle du menu hamburger
   - Fermeture automatique lors du clic sur un lien

2. **Navigation Fluide**
   - Scroll smooth vers les sections
   - Offset pour la navigation fixe
   - Mise en surbrillance de la section active

3. **Formulaire de Contact**
   - Validation HTML5
   - Gestion de la soumission
   - Message de confirmation

## Installation et Utilisation

### Option 1 : Ouverture Directe
Ouvrez simplement `index.html` dans votre navigateur web.

### Option 2 : Serveur Local
Pour un développement plus avancé, utilisez un serveur local :

```bash
# Avec Python 3
python -m http.server 8000

# Avec Node.js (http-server)
npx http-server

# Avec PHP
php -S localhost:8000
```

Puis ouvrez `http://localhost:8000` dans votre navigateur.

## Personnalisation

### Modifier les Couleurs
Les couleurs sont définies dans la configuration Tailwind au début du fichier :
```javascript
tailwind.config = {
    theme: {
        extend: {
            colors: {
                primary: '#8c52ff',    // Violet
                secondary: '#00bf63',  // Vert
            }
        }
    }
}
```

### Modifier le Contenu
Le contenu est directement dans le HTML. Recherchez les sections correspondantes et modifiez le texte.

### Ajouter des Services
Dans la section `#services`, dupliquez un bloc de service existant et modifiez le contenu.

### Personnaliser le Formulaire
Le formulaire se trouve dans la section `#contact`. Modifiez les champs selon vos besoins.

## Intégration Backend

Le formulaire de contact nécessite une intégration backend. Options possibles :

1. **Service tiers** : Formspree, Basin, Netlify Forms
2. **API personnalisée** : Node.js, PHP, Python
3. **Service email** : SendGrid, Mailgun

Exemple d'intégration avec Formspree :
```html
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
```

## Optimisations Recommandées

### Pour la Production

1. **Télécharger Tailwind CSS** localement au lieu d'utiliser le CDN
2. **Optimiser les images** (non présentes actuellement)
3. **Minifier le HTML/CSS/JS**
4. **Ajouter un favicon**
5. **Configurer le SEO** :
   - Meta descriptions
   - Open Graph tags
   - Schema.org markup

### Performance
- Le site utilise le CDN Tailwind qui est mis en cache
- Pas d'images lourdes dans la version actuelle
- JavaScript minimal pour des performances optimales

### Accessibilité
- Utilisation de balises sémantiques HTML5
- Contraste des couleurs conforme WCAG
- Navigation au clavier fonctionnelle
- Labels pour tous les champs de formulaire

## Hébergement

Le site peut être hébergé sur :
- **Services gratuits** : Netlify, Vercel, GitHub Pages
- **Hébergement classique** : OVH, Infomaniak, O2Switch
- **VPS/Cloud** : DigitalOcean, AWS, Google Cloud

### Déploiement sur Netlify (Gratuit)

1. Créez un compte sur [Netlify](https://www.netlify.com/)
2. Glissez-déposez le dossier du site
3. Votre site est en ligne !

## Conformité RGPD

Le site respecte les principes RGPD :
- Case à cocher explicite pour le consentement
- Lien vers la politique de confidentialité
- Transparence sur l'utilisation des données
- Pas de cookies tiers ou trackers

**Important** : Ajoutez une vraie page de politique de confidentialité avant la mise en production.

## Support

Pour toute question ou problème :
- Email : contact@ceduweb.com
- Téléphone : +33 1 23 45 67 89

## Licence

Copyright © 2025 ceduweb. Tous droits réservés.

---

**Version** : 1.0.0
**Dernière mise à jour** : Décembre 2024