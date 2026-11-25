# Portfolio — Valentin Beaud

Portfolio personnel d’un étudiant en **BTS SIO option SLAM** (Solutions Logicielles et Applications Métiers) au lycée de la CCI de Nîmes. Il présente mon parcours, mes projets, mes compétences et ma veille technologique.

<!-- Ajoute une capture d’écran : ![Aperçu du portfolio](docs/apercu.png) -->

## Pages

| Page | Fichier | Contenu |
| --- | --- | --- |
| Accueil | `index.html` | Présentation, parcours (formation, expériences, objectifs) |
| Projets | `projets.html` | Stage à la DSIN et autres réalisations |
| Compétences | `competences.html` | Langages, outils, systèmes et virtualisation |
| Veille techno | `veille.html` | Veille sur les agents IA : informations clés, dates et sources |
| Contact | `contact.html` | E-mail, GitHub, LinkedIn |

## Fonctionnalités

- Site statique en HTML et CSS, sans JavaScript
- Design responsive (ordinateur, tablette, mobile)
- CV téléchargeable en PDF

## Technologies

- HTML5 et CSS3
- [Bootstrap 5.3](https://getbootstrap.com/) (grille, composants)
- [Font Awesome 6](https://fontawesome.com/) (icônes)
- Police [DM Sans](https://fonts.google.com/specimen/DM+Sans) (Google Fonts)

## Structure du projet

```
Portfolio/
├── index.html
├── projets.html
├── competences.html
├── veille.html
├── contact.html
├── css/
│   └── style.css        # Styles personnalisés (par-dessus Bootstrap)
└── Documents/
    └── CV/              # CV au format PDF
```

## Lancer le site en local

```bash
git clone https://github.com/vbeaud30/<nom-du-depot>.git
cd <nom-du-depot>
```

Ouvre ensuite `index.html` dans ton navigateur, ou lance un petit serveur local :

```bash
python -m http.server 8000
```

Le site est alors disponible sur http://localhost:8000.

## Publier avec GitHub Pages

1. Place les fichiers à la racine du dépôt (`index.html` doit être à la racine).
2. Sur GitHub : **Settings → Pages**.
3. Dans **Source**, choisis **Deploy from a branch**, puis la branche `main` et le dossier `/ (root)`.
4. Le site est publié à l’adresse `https://vbeaud30.github.io/<nom-du-depot>/`.

## Contact

- GitHub : [@vbeaud30](https://github.com/vbeaud30)
- LinkedIn : [Valentin Beaud](https://www.linkedin.com/in/valentin-beaud-25b727423)
- E-mail : valentinbeaud30@gmail.com

&copy; 2026 Valentin Beaud
