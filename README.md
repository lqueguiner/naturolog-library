# naturolog-library

---

## Mise à jour de la librairie library.json

D’abord aller dans le dossier export :

```cd C:\naturolog\library\library-export```

Puis générer le JSON :

```node export-library.mjs```

Puis vérifier qu’il existe :

```dir library.json```

Ensuite copier le fichier dans le repo cloné :

```copy C:\naturolog\library\library-export\library.json C:\naturolog\library\naturolog-library\library.json```

Puis aller dans le repo :

```cd C:\naturolog\library\naturolog-library```

Ajouter le fichier :

```git add library.json```

Faire le commit :

```git commit -m "Update library.json"```

Envoyer sur GitHub :

```git push```

---

## Mise à jour du répertoire complet

Va dans le repo :
```cd C:\naturolog\library\naturolog-library```

Vérifie ce qui a changé :
```git status```

Ajoute TOUTES les modifications (nouveaux fichiers + modifications) :
```git add .```

Fais un commit :
```git commit -m "Update library content"```

Pousse sur GitHub :
```git push```