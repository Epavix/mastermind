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
  - Option : `rm -r nom_dossier` pour supprimer un dossier et tous ses enfants.
- `cp [source] [destination]` : Copie un fichier ou un dossier.
- `mv [source] [destination]` : Déplace ou renomme un fichier ou un dossier.