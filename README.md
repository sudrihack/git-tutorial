# git-tutorial

Ce *repo* a pour but d'intoduire le logiciel git aux étudiants de 
l'association **Sudrihack** de l'ESME Sudria de Lille.

## commandes de base

récupérer un *repo* à distance pour créer une copie local :

```
    git clone https://github.com/sudrihack/git-tutorial.git
```
pour indexer un fichier au suivi de version ou mettre à jour 
un fichier déjà existant :
```
    git add <fichier1> <fichier2>
```

pour valider les modifications :
```
    git commit -m "message relatif à la modification"
```

pour réaliser l'indéxation et la validation en une seule phase:
```
git commit -a -m "message relatif à la modification"
```

## glossaire :

* repository (ou repo) : projet versionner par git se trouvant sur un 
                         serveur à distance. 
