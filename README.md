# Git

[Git documentation](https://git-scm.com/doc)

`git config --global user.name "votre_nom"`

`git config --global user.email "votre_email"`

`git init nom_de_votre_projet`

`git add fichier`

`git add *` or `git add .`

`git commit -m "court_message_de_commit"`

`git commit -a -m "court_message_de_commit"`

`git commit --amend`


# Modéle de dépôt git

### Création d'un nouveau dépôt en ligne de commande

```
touch README.md
git init
git checkout -b main
git add README.md
git commit -m "first commit"
git remote add origin git@github.com:user/nom_de_votre_depot.git
ou
git remote add origin https://github.com/user/nom_de_votre_depot.git
git push -u origin main
```

### Soumission d'un dépôt existant par ligne de commande

```
git remote add origin git@github.com:user/nom_de_votre_depot.git
ou
git remote add origin https://github.com/user/nom_de_votre_depot.git
git push -u origin main
```

---

