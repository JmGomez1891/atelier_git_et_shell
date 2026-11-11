# Dotfiles_kickstarter

Tout-en-un : dotfiles, script d'installation et script de configuration
pour l'atelier Git et shell de l'UQODE.

## Installation rapide

Exemple dans le terminal avec Ubuntu :

```sh
cd ubuntu

chmod +x install_script1_ubuntu.sh
chmod +x install_script2_ubuntu.sh

./install_script1_ubuntu.sh
./install_script2_ubuntu.sh
```

Testé sur : Ubuntu 24.04 LTS, WSL, macOS

## Déroulement de l'atelier

### Partie 1 : le shell

#### 1. Installation

- [ ] Ouvrir un terminal (Ubuntu, WSL ou macOS)
- [ ] Récupérer ce dépôt (`git clone` ou téléchargement ZIP)
- [ ] Lancer les scripts d'installation du dossier `ubuntu/` ou `mac/`
- [ ] Redémarrer le terminal et vérifier le shell actif : `echo $SHELL`

#### 2. Commandes de base

Terrain de jeu : le dossier `films/`.

- [ ] Se repérer : `pwd`, `ls`, `ls -la`
- [ ] Se déplacer : `cd films`, `cd ..`, `cd ~`
- [ ] Créer : `mkdir`, `touch`
- [ ] Lire : `cat`, `less`, `head`
- [ ] Copier, déplacer, renommer : `cp`, `mv`
- [ ] Supprimer : `rm`, `rm -r` (attention : pas de corbeille)
- [ ] Trouver de l'aide : `man`, `--help`
- [ ] Trucs utiles : complétion avec Tab, historique (flèche du haut), pipe `|`, redirection `>`
- [ ] Exercice : ajouter un genre et un film dans `films/`

### Partie 2 : Git et GitHub

Support : `Présentation_Git_GitHub.pptx`

- [ ] Théorie : Git vs GitHub, snapshots, branches

#### 1. Installation

- [ ] Vérifier l'installation : `git --version`, `gh --version`
- [ ] Configurer son identité :
  - [ ] `git config --global user.name "Mon Nom"`
  - [ ] `git config --global user.email "moncourriel@exemple.com"`
- [ ] Connecter son compte GitHub : `gh auth login`

#### 2. Commandes de base

- [ ] Cloner un dépôt : `git clone`
- [ ] Créer un dépôt local : `git init`
- [ ] Voir l'état : `git status`
- [ ] Sauvegarder : `git add .`, `git commit -m "premier commit"`
- [ ] Consulter l'historique : `git log --oneline`
- [ ] Travailler sur une branche : `git switch -c ma-branche`, `git merge`
- [ ] Créer le dépôt sur GitHub (site web ou `gh repo create`)
- [ ] Lier le projet local à GitHub : `git remote add origin <url>`
- [ ] Envoyer et récupérer : `git push -u origin main`, `git pull`
- [ ] Bonne pratique : ouvrir une pull request plutôt que pousser directement dans `main`

### Partie 3 (si le temps le permet) : shell scripting

Les scripts sont dans `bin/`, rendus accessibles partout grâce au `.zshrc`.

- [ ] Anatomie d'un script : shebang, `chmod +x`, exécution (`bin/helloworld.sh`)
- [ ] Variables et arguments : `bin/meteo.sh` (ville par défaut si aucun argument)
- [ ] Ajouter `bin/` au `PATH` dans le `.zshrc`, puis `source ~/.zshrc`
- [ ] Créer un alias dans le `.zshrc`
- [ ] Automatiser la création d'un dépôt : `bin/createGitRepo.sh`

### Dotfiles_kickstarter (si le temps de permet)

Tout-en-un : dotfiles, script d'installation et script de configuration
pour l'atelier Git et shell de l'UQODE.

## Installation rapide

Exemple dans le terminal avec Ubuntu :

```sh
cd ubuntu

chmod +x install_script1_ubuntu.sh
chmod +x install_script2_ubuntu.sh

./install_script1_ubuntu.sh
./install_script2_ubuntu.sh
```

Testé sur : Ubuntu 24.04 LTS, WSL, macOS

