# Tournicotti | Natacha Balet

Site web de la compagnie de danse Tournicotti dirigée par Natacha Balet.

## Structure du projet

```
tournicotti/
├── index.html              # Page d'accueil avec diaporama
├── contacts.html           # Page de contact
├── css/
│   └── style.css          # Feuille de styles principale
├── js/
│   └── main.js            # JavaScript pour interactions
├── images/                # Dossier pour vos images
│   ├── slide1.jpg        # Image diaporama 1
│   ├── slide2.jpg        # Image diaporama 2
│   ├── slide3.jpg        # Image diaporama 3
│   └── slide4.jpg        # Image diaporama 4
├── compagnie/
│   ├── histoire.html
│   ├── artistes.html
│   ├── passassions.html
│   └── partenaires.html
├── oeuvres/
│   ├── et-puis-danser.html
│   ├── lunimaginaire.html
│   ├── a-cran.html
│   └── les-autres.html
└── agenda/
    ├── a-venir.html
    └── archives.html
```

## Fonctionnalités

- **Menu sticky** : Le menu se fixe en haut de la page au scroll avec un fade noir élégant
- **Diaporama** : Slider automatique d'images en pleine largeur avec navigation
- **Navigation responsive** : Menu adaptatif pour mobile et desktop
- **Sous-menus** : Menus déroulants avec effet hover
- **Design sobre** : Typographie élégante blanc sur noir

## Installation

### Option 1 : Déploiement sur Vercel (Recommandé)

1. Installez Git si ce n'est pas déjà fait
2. Initialisez un dépôt Git :
   ```bash
   cd tournicotti
   git init
   git add .
   git commit -m "Initial commit"
   ```

3. Créez un compte sur [Vercel](https://vercel.com) (gratuit)

4. Installez Vercel CLI :
   ```bash
   npm install -g vercel
   ```

5. Déployez :
   ```bash
   vercel
   ```

6. Suivez les instructions. Votre site sera en ligne en quelques secondes !

### Option 2 : Déploiement sur Netlify

1. Créez un compte sur [Netlify](https://www.netlify.com) (gratuit)

2. Deux méthodes :
   - **Via l'interface** : Glissez-déposez le dossier `tournicotti` sur Netlify
   - **Via Git** : Connectez votre dépôt GitHub et Netlify déploiera automatiquement

### Option 3 : Hébergement FTP classique

1. Connectez-vous à votre serveur FTP avec un client comme FileZilla
2. Uploadez tous les fichiers du dossier `tournicotti` vers votre serveur
3. Assurez-vous que `index.html` est à la racine de votre domaine

## Test en local

Pour tester le site en local avant déploiement :

```bash
cd tournicotti
# Avec Python 3
python3 -m http.server 8000

# Ou avec Node.js (installez d'abord : npm install -g http-server)
http-server
```

Puis ouvrez `http://localhost:8000` dans votre navigateur.

## Personnalisation

### Ajouter vos images

1. Placez vos images dans le dossier `images/`
2. Nommez-les : `slide1.jpg`, `slide2.jpg`, `slide3.jpg`, `slide4.jpg`
3. Format recommandé : 1920x1080px minimum, JPG ou PNG

### Modifier le contenu

Éditez les fichiers HTML pour ajouter votre contenu. Les zones à personnaliser sont marquées par :
```html
<p>Ajoutez ici le contenu...</p>
```

### Changer les couleurs

Dans `css/style.css`, modifiez les variables CSS :
```css
:root {
    --color-bg: #0a0a0a;      /* Couleur de fond */
    --color-text: #ffffff;     /* Couleur du texte */
    --color-accent: #ffffff;   /* Couleur d'accentuation */
}
```

### Ajouter les liens réseaux sociaux

Dans chaque fichier HTML, remplacez les `#` par vos vraies URLs :
```html
<a href="https://instagram.com/votre-compte" ...>Instagram</a>
<a href="https://facebook.com/votre-page" ...>Facebook</a>
```

## Technologies utilisées

- HTML5 sémantique
- CSS3 moderne (Grid, Flexbox)
- JavaScript vanilla (pas de frameworks lourds)
- Design responsive

## Support navigateurs

- Chrome/Edge (dernières versions)
- Firefox (dernières versions)
- Safari (dernières versions)
- Mobile (iOS Safari, Chrome Android)

## Maintenance

Le site est conçu pour être simple à maintenir. Pour ajouter du contenu :
1. Éditez les fichiers HTML concernés
2. Ajoutez vos images dans le dossier `images/`
3. Poussez vos modifications sur Git
4. Le site se met à jour automatiquement (si Vercel/Netlify)

## Contact

Pour toute question : contact@tournicotti.com
