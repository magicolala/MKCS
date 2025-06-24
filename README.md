# MKCS Entreprise - Site Web de Pâtisserie Artisanale

## 📋 Description

Site web moderne et élégant pour MKCS Entreprise, une pâtisserie artisanale camerounaise spécialisée dans les gâteaux d'anniversaire personnalisés et les crêpes traditionnelles. Le site présente un design glassmorphisme avec des animations fluides et une expérience utilisateur optimisée.

## ✨ Fonctionnalités

- **Design Glassmorphisme** : Interface moderne avec effets de verre et transparence
- **Responsive Design** : Adaptation parfaite sur tous les appareils (mobile, tablette, desktop)
- **Animations Fluides** : Éléments flottants, transitions et effets de parallaxe
- **Navigation Intuitive** : Menu fixe avec défilement fluide
- **Intégration WhatsApp** : Bouton de commande directe via WhatsApp
- **Optimisé Performance** : Code CSS et JavaScript optimisés

## 🎨 Design & Technologie

### Technologies Utilisées
- **HTML5** : Structure sémantique moderne
- **CSS3** : Animations, gradients, glassmorphisme, flexbox, grid
- **JavaScript Vanilla** : Interactions et animations
- **Google Fonts** : Typographies Playfair Display et Inter

### Palette de Couleurs
- **Gradient Principal** : Orange (#f27121) → Rouge (#e94057) → Violet (#8a2387)
- **Gradient Secondaire** : Rose (#f093fb) → Rouge (#f5576c)
- **Gradient Accent** : Bleu (#4facfe) → Cyan (#00f2fe)
- **Gradient Or** : Jaune (#ffd89b) → Bleu foncé (#19547b)

## 📱 Sections du Site

### 🏠 Accueil (Hero)
- Présentation élégante avec titre principal
- Sous-titre avec gradient coloré
- Description de l'entreprise
- Éléments flottants décoratifs

### 🍰 Créations (Produits)
- **Gâteau d'Anniversaire** : Créations sur mesure (à partir de 20 000 FCFA)
- **Crêpe Tradition** : Crêpe artisanale classique (100 FCFA)
- **Crêpe Chocolat Premium** : Avec chocolat camerounais (150 FCFA)

### 📖 Histoire (À Propos)
- Présentation de la philosophie MKCS
- Engagement qualité et tradition
- Valorisation des ingrédients locaux

### 📞 Contact
- Bouton WhatsApp interactif
- Numéros de téléphone : +237 698 511 478 / +237 694 917 972
- Message pré-rempli pour commandes

## 🚀 Installation & Utilisation

### Prérequis
- Navigateur web moderne (Chrome, Firefox, Safari, Edge)
- Connexion internet (pour les polices Google Fonts)

### Installation
1. Téléchargez le fichier `index.html`
2. Ouvrez le fichier dans votre navigateur web
3. Le site est prêt à utiliser !

### Déploiement
Le site peut être déployé sur :
- **GitHub Pages**
- **Netlify**
- **Vercel**
- **Serveur web traditionnel**

## 📱 Responsive Design

### Points de Rupture
- **Desktop** : > 768px
- **Mobile/Tablette** : ≤ 768px

### Adaptations Mobile
- Navigation compacte
- Grille produits en colonne unique
- Espacement optimisé
- Boutons tactiles agrandis

## 🎯 Optimisations

### Performance
- CSS intégré pour réduire les requêtes HTTP
- Animations GPU-accélérées avec `transform3d`
- Images optimisées (placeholders en attendant les vraies images)
- Code JavaScript minimaliste

### SEO
- Structure HTML sémantique
- Balises meta appropriées
- Titre et description optimisés
- Langue française définie

### Accessibilité
- Contrastes de couleurs respectés
- Navigation au clavier possible
- Textes alternatifs prêts pour les images
- Tailles de police adaptatives

## 🔧 Personnalisation

### Modifier les Couleurs
Les couleurs sont définies dans les variables CSS au début du fichier :
```css
:root {
  --primary-gradient: linear-gradient(320deg, #f27121, #e94057, #8a2387);
  --secondary-gradient: linear-gradient(135deg, #f093fb 0%, #f5576c 100%);
  /* ... autres variables */
}
```

### Ajouter des Produits
Dupliquez la structure `.product-card` dans la section produits :
```html
<div class="product-card">
  <div class="product-image">
    <div class="product-placeholder">Nom du Produit</div>
  </div>
  <div class="product-info">
    <h3 class="product-name">Nom du Produit</h3>
    <p class="product-description">Description...</p>
    <p class="product-price">Prix FCFA</p>
  </div>
</div>
```

### Modifier les Contacts
Changez les numéros WhatsApp dans :
- Le lien du bouton : `href="https://wa.me/NUMERO"`
- Le footer : numéros affichés

## 📞 Contact & Support

**MKCS Entreprise**
- **WhatsApp** : +237 698 511 478 / +237 694 917 972
- **Spécialité** : Pâtisserie artisanale camerounaise
- **Localisation** : Cameroun

## 📄 Licence

© 2025 MKCS Entreprise - Tous droits réservés

---

*Site web créé avec passion pour mettre en valeur l'art de la pâtisserie camerounaise* 🍰✨
