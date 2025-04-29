# Linux

## Prompt

Le prompt (invité de commandes) est l'interface où l'utilisateur peut entrer ses commandes. Il se présente sous cette forme :
```
utilisateur@machine:chemin_actuel$
```

## Navigation

- `whoami` : Affiche le nom de l'utilisateur actuel.
- `pwd` : Affiche le chemin complet du répertoire courant.
- `ls` : Liste les fichiers et dossiers dans le répertoire courant.
  - Options :
    - `-a` : Affiche tous les fichiers, y compris les fichiers cachés.
    - `-l` : Affiche les fichiers sous forme de liste détaillée.
    - `-R` : Affiche les fichiers de manière récursive dans les sous-dossiers.
    - `-t` : Trie les fichiers par date de modification.
- `cd [chemin]` : Change de répertoire.

## Répertoires spéciaux

- `.` : Répertoire courant.
- `..` : Répertoire parent.
- `~` : Répertoire personnel de l'utilisateur.
- `/` : Répertoire racine.

## Commandes de base
- `mkdir [nom_dossier]` : Crée un nouveau dossier.
- `touch [nom_fichier]` : Crée un fichier vide.
- `rm nom_fichier` : Supprime un fichier.
  - Option : `-r` pour supprimer un dossier et tous ses enfants.
- `cp [source] [destination]` : Copie un fichier ou un dossier.
- `mv [source] [destination]` : Déplace ou renomme un fichier ou un dossier.