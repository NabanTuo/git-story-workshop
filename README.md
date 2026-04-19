# 🐷 Git Story Workshop — Les 3 Petits Cochons

Bienvenue dans le repo de l'atelier **Git Story** !

Ce repo est votre terrain de jeu pour apprendre Git en écrivant une histoire ensemble.

---

## 🗺️ Structure du repo

```
/
├── histoire.md        → L'histoire commune — c'est ici que tout se passe
├── README.md          → Ce fichier — les règles du jeu
└── /assets            → Images et ressources (ajoutées pendant l'atelier)
```

---

## 🎮 Les règles du jeu

### Votre groupe et votre branche

| Groupe | Personnage | Branche |
|--------|-----------|---------|
| Groupe Paille | Pixel 🐷 | `feature/maison-paille` |
| Groupe Bois | Scrum 🐷 | `feature/maison-bois` |
| Groupe Brique | Deploy 🐷 | `feature/maison-brique` |
| Animateur | Grayson Wolf 🐺 | `main` + branches surprise |

### Les commandements Git de l'atelier

1. **On ne push jamais directement sur `main`** — tout passe par une PR
2. **On commente les PRs des autres** avant de les approuver
3. **On ne merge pas sa propre PR** — un autre groupe doit approuver
4. **En cas de conflit** — on appelle l'animateur, on ne panique pas

---

## ⚡ Commandes Git de survie

```bash
# Cloner le repo
git clone git@github.com:NabanTuo/git-story-workshop.git

# Créer et basculer sur sa branche
git checkout -b feature/maison-paille

# Sauvegarder son travail
git add histoire.md
git commit -m "feat: ajout construction maison de paille"

# Envoyer sur GitHub
git push origin feature/maison-paille

# Récupérer les derniers changements
git pull origin main
```

---

## 🐺 Attention au loup

Grayson Wolf peut ouvrir une PR sur votre branche à tout moment. Reviewez attentivement avant d'approuver — il est vicieux.

---

*Bonne chance. May the merge be with you.* 🚀
