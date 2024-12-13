<br/>
<p align="center">
    <picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://github.com/yannouuuu/IUT-SAE1.01/raw/main/.github/assets/header_univlille_light.png" width="200px">
        <img alt="UnivLilleLogo" src="https://github.com/yannouuuu/IUT-SAE1.01/raw/main/.github/assets/header_univlille_dark.png" width="200px">
    </picture>
  <h1 align="center">IUT-SAE1.05-1.06 | OpenShuttle</h1>
</p>

<p align="center">
    Module d'initiation au développement web simple en BUT1 d'Informatique
    <br/>
    <br/>
    <a href="https://moodle.univ-lille.fr/course/view.php?id=30388&sectionid=262716"><strong>Voir la page sur le moodle »</strong></a>
    <br/>
    <br/>
    <a href="https://github.com/yannouuuu/IUT-SAE1.05-1.06"><strong>Voir le projet complet sur GitHub »</strong></a>
</p>

<br/>

## 📋 Description du Projet
Il s'agit d'une plateforme web présentant un service d'éco-mobilité innovant pour OpenAI, visant à encourager les employés à adopter des modes de transport durables.

## ✅ TODO List
### Structure & Setup
- [x] Initialisation du projet
- [x] Mise en place des polices Söhne
- [x] Structure HTML de base
- [x] Configuration des styles globaux

### Page d'accueil
- [x] Header avec navigation
- [ ] Section hero
- [ ] Présentation des services
- [x] Footer

### OpenAI Shuttle
- [x] Design des cartes de navettes
- [x] Interface de réservation
- [ ] Carte interactive des trajets
- [x] Horaires dynamiques

### OpenAI Connect (Covoiturage)
- [x] Interface de recherche
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
