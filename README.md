# Karate Club Okinawa — Programme Officiel des Grades 🥋

Application web interactive dédiée à la révision et au suivi des passages de grade pour les élèves et parents du **Karate Club Okinawa** (*Swiss Shubukan Dojo — 守武館*).

---

## 📖 À propos

Ce site web sert de support pédagogique complet et interactif pour préparer les passages de grade de karaté. Il centralise le programme technique officiel, les objectifs par ceinture, le suivi individuel de l'élève, ainsi que l'accès direct aux fiches d'examen officielles au format PDF.

---

## 🌟 Fonctionnalités principales

### 1. 🥋 Sélecteur interactif des 20 ceintures
- Navigation fluide et visuelle à travers l'ensemble des grades :
  - **Ceintures Juniors & Barrette** : Blanc 1b, Blanc/Jaune, Jaune, Jaune 1b, Jaune/Orange, Orange, Orange 1b, Orange/Verte, Verte, Verte 1, Verte/Bleue, Verte/Bleue 1, Bleue, Bleue 1, Bleue 2, Bleue/Marron, Marron 1, Marron 2.
  - **Ceintures Adultes & Dan** : Marron Adulte, Ceinture Noire (1er Dan Shodan).
- Rendu graphique dynamique des couleurs de ceintures et barrettes.
- Indication de l'âge minimum requis et du niveau Kyu / Dan.

### 2. ✅ Suivi de progression individuel de l'élève
- Pour chaque technique requise (*posture, blocage, attaque, coup de pied, kata, kihon, bunkaï, kumité*), l'élève peut faire évoluer son statut d'apprentissage d'un simple clic :
  1. **À apprendre** (gris)
  2. **À entraîner** (ambre)
  3. **À répéter** (bleu)
  4. **Acquis** (vert)
- Calcul en temps réel du pourcentage de complétion et barre de progression animée.
- **Sauvegarde automatique** dans le navigateur (`localStorage`) : aucune perte de données lors de la fermeture de la page.

### 3. 📄 Téléchargement & Consultation des PDF officiels
- Chaque ceinture dispose d'un accès direct à sa fiche d'examen officielle du club située dans le dossier `/pdf/` :
  - **Téléchargement direct** avec le nom officiel du fichier.
  - **Consultation / aperçu dans le navigateur** en un clic.
  - Bouton d'accès rapide dans l'en-tête du grade sélectionné.
- Affichage des notes explicatives claires pour les grades ne disposant pas de fiche PDF individuelle dédiée (Marron 2, Marron Adulte, Noire).

### 4. 🌿 L'Arbre des 3 Branches de Katas
Visualisation claire de la filiation et de la répartition des katas exigés par le club :
- **Branche Naihanchi** (*ナイハンチ*) : Découpage progressif de *Naihanchi Shodan* (1 à 7, 1 à 12, 1 à 20, Complet) et *Naihanchi Sandan* (1 à 12, Complet).
- **Série des 5 Pinan** (*平安*) : *Pinan Nidan*, *Pinan Shodan*, *Pinan Sandan*, *Pinan Yondan*, *Pinan Godan*.
- **Ordre des Katas Supérieurs Swiss Shubukan** (*守武館*) : Les 10 katas supérieurs dans l'ordre officiel de transmission (*Ananku, Rohai, Kusanku Sho, Jion, Wankan, Itosu no passai, Shuri Sanchin, Wanshu, Chinti, Anan*).

### 5. 📜 Règlement et Charte du Dojo
- Rappels essentiels pour les examens (présence de la licence obligatoire).
- Philosophie de l'école : *« Le Grade Kyu ou le Dan n'est pas une récompense, c'est la constatation d'un niveau dans la pratique. »*
- Explication des distinctions entre barrettes, ceintures bicolores (5.– Frs) et ceintures de couleur (10.– Frs).

---

## 📂 Structure du projet

```text
kataweb/
├── index.html              # Application complète (HTML5, Tailwind, JS vanilla)
├── README.md               # Documentation du projet
└── pdf/                    # Fiches officielles d'examen du club
    ├── 1B 1 barrette.pdf
    ├── 1BJ.pdf
    ├── 2J.pdf
    ├── 3 jaune 1 barrette.pdf
    ├── 3j o.pdf
    ├── 4o.pdf
    ├── 5 orange 1 barrette.pdf
    ├── 5o v.pdf
    ├── 6v.pdf
    ├── 7v1.pdf
    ├── 8v b.pdf
    ├── 9v b1.pdf
    ├── 10 bl.pdf
    ├── 11 bl1.pdf
    ├── 12 bl2.pdf
    ├── 13 b m.pdf
    └── 14 m1.pdf
```

---

## 📋 Correspondance Ceintures ↔ Fichiers PDF

| Ceinture | Niveau | Fichier PDF associé |
| :--- | :--- | :--- |
| **Blanc 1b** | 6ème Kyu — Barrette | `pdf/1B 1 barrette.pdf` |
| **Blanc / Jaune** | 6ème Kyu — Intermédiaire | `pdf/1BJ.pdf` |
| **Jaune** | 5ème Kyu | `pdf/2J.pdf` |
| **Jaune 1b** | 5ème Kyu — Barrette | `pdf/3 jaune 1 barrette.pdf` |
| **Jaune / Orange** | 5ème Kyu — Intermédiaire | `pdf/3j o.pdf` |
| **Orange** | 4ème Kyu | `pdf/4o.pdf` |
| **Orange 1b** | 4ème Kyu — Barrette | `pdf/5 orange 1 barrette.pdf` |
| **Orange / Verte** | 4ème Kyu — Intermédiaire | `pdf/5o v.pdf` |
| **Verte** | 3ème Kyu | `pdf/6v.pdf` |
| **Verte 1** | 3ème Kyu — Barrette | `pdf/7v1.pdf` |
| **Verte / Bleue** | 3ème Kyu — Intermédiaire | `pdf/8v b.pdf` |
| **Verte / Bleue 1** | 3ème Kyu — Intermédiaire Barrette | `pdf/9v b1.pdf` |
| **Bleue** | 2ème Kyu | `pdf/10 bl.pdf` |
| **Bleue 1** | 2ème Kyu — Barrette 1 | `pdf/11 bl1.pdf` |
| **Bleue 2** | 2ème Kyu — Barrette 2 | `pdf/12 bl2.pdf` |
| **Bleue / Marron** | 2ème Kyu — Intermédiaire | `pdf/13 b m.pdf` |
| **Marron 1** | 1er Kyu — Niveau 1 | `pdf/14 m1.pdf` |
| **Marron 2** | 1er Kyu — Niveau 2 | *Format image uniquement* |
| **Marron Adulte** | 1er Kyu — Adultes | *Programme combiné (M2 + Kusanku Sho)* |
| **Ceinture Noire** | 1er Dan (Shodan) | *Examen officiel Dan* |

---

## 🚀 Lancement & Déploiement

### En local
Le site est 100% statique et ne requiert aucune installation de dépendances ni commande de build :
1. Clonez ou téléchargez le dépôt.
2. Ouvrez simplement le fichier `index.html` dans n'importe quel navigateur moderne (Chrome, Edge, Firefox, Safari).

### Déploiement sur GitHub Pages
1. Poussez le code sur la branche `main`.
2. Rendez-vous dans les **Paramètres (Settings)** de votre dépôt GitHub &rarr; **Pages**.
3. Sous **Build and deployment**, sélectionnez la branche `main` et le dossier `/ (root)`.
4. Le site sera automatiquement publié en ligne avec accès complet aux fiches PDF.

---

## 🛠️ Technologies utilisées

- **HTML5 & CSS3** modernes et sémantiques.
- **[Tailwind CSS](https://tailwindcss.com/)** (via CDN) pour le design responsive et épuré.
- **[Lucide Icons](https://lucide.dev/)** pour l'iconographie moderne.
- **Google Fonts** : *Inter* (interface claire) et *Noto Serif JP* (calligraphie et symboles japonais).
- **JavaScript Vanilla** (aucun framework lourd, chargement instantané).
- **Web Storage API (`localStorage`)** pour la persistance locale du suivi des objectifs.

---

## ⛩️ Karate Club Okinawa — Swiss Shubukan Dojo (守武館)
*« L'École de la Vie » — Pratique et transmission du Karaté traditionnel d'Okinawa.*
