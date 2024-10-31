# IUT-SAE1.05-1.06
Module d'initiation au développement simple en BUT1 d'Informatique.

## 📋 Description du Projet
Il s'agit d'une plateforme web présentant un service d'éco-mobilité innovant pour OpenAI, visant à encourager les employés à adopter des modes de transport durables.

## ✅ TODO List
### Structure & Setup
- [x] Initialisation du projet
- [x] Mise en place des polices Söhne
- [ ] Structure HTML de base
- [ ] Configuration des styles globaux

### Page d'accueil
- [ ] Header avec navigation
- [ ] Section hero
- [ ] Présentation des services
- [ ] Footer

### OpenAI Shuttle
- [ ] Design des cartes de navettes
- [ ] Interface de réservation
- [ ] Carte interactive des trajets
- [ ] Horaires dynamiques

### OpenAI Connect (Covoiturage)
- [ ] Interface de recherche
- [ ] Système de matching
- [ ] Profils utilisateurs
- [ ] Système de notification

### Responsive Design
- [ ] Version mobile
- [ ] Version tablette
- [ ] Version desktop

### Documentation
- [ ] Guide d'utilisation
- [ ] Documentation technique
- [ ] Commentaires du code

### Validation & Tests
- [ ] Validation W3C
- [ ] Tests cross-browser
- [ ] Optimisation des performances
- [ ] Vérification de l'accessibilité

## 🚀 Fonctionnalités
- Présentation des navettes autonomes "OpenAI Shuttle"
- Système de covoiturage intelligent "OpenAI Connect"
- Interface utilisateur moderne et responsive
- Design aligné avec l'image de marque OpenAI

## 📁 Structure du Projet
```
project-root/
├── assets/
│   └── fonts/
│       └── stylesheet.css         # Définitions des polices Söhne
├── docs/
│   └── realisation.mdx            # Documentation détaillée du projet
├── styles/
│   └── styles.css                 # Styles globaux
├── index.html                     # Page principale
└── README.md                      # Documentation du projet
```

## 🎨 Design System
### Typographie
La typographie du projet utilise la famille de polices Söhne, qui correspond à l'identité visuelle d'OpenAI :

- **Söhne Buch** : Police principale pour le corps de texte
  ```css
  font-family: 'sohnebuch';
  ```

- **Söhne Extra-Leicht** : Pour les textes légers
  ```css
  font-family: 'shneextraleicht';
  ```
  - Version italique : `font-family: 'shneextraleicht_kursiv';`

- **Söhne Fett** : Pour les titres et textes en gras
  ```css
  font-family: 'shnefett';
  ```
  - Version italique : `font-family: 'shnefett_kursiv';`

- **Söhne Halbfett** : Pour les sous-titres (version italique)
  ```css
  font-family: 'shnehalbfett_kursiv';
  ```

- **Söhne Leicht** : Pour les textes légers (version italique)
  ```css
  font-family: 'shneleicht_kursiv';
  ```