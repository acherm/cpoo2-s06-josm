# CPOO2, S06 : les patrons de JOSM

Ce dépôt est une copie de [JOSM](https://github.com/JOSM/josm) figée à la
révision r19700, avec ce dossier en plus. Le sujet du TP est distribué à part.

| Fichier | À quoi il sert |
|---|---|
| `rendu-s06.md` | le gabarit de vos réponses, à remplir |
| `diagrammes/` | vos diagrammes (photos ou images) |
| `highways-2016.diff` | le changement étudié à la question 5 |

Pour fabriquer le PDF, depuis ce dossier :

```bash
pandoc rendu-s06.md -s --embed-resources -o rendu-s06.html
# ouvrez rendu-s06.html dans un navigateur, puis Imprimer > Enregistrer en PDF
```

Le code de JOSM est sous licence GPL (voir `LICENSE` à la racine).
