# sesam-media

Les fichiers de communication de Sesam, et rien d'autre : scènes générées,
musiques, captures destinées aux films, films montés. Dépôt public, séparé du
code, pour que les fichiers soient lisibles par leur adresse brute.

**Ce dépôt ne contient jamais** de code, de données, de clé, ni aucune capture
montrant un compte, une adresse ou un commerce réels.

## Où va quoi

| dossier | ce qu'il reçoit |
|---|---|
| `scenes/` | images générées pour les films |
| `musiques/` | bandes-son et nappes |
| `captures/` | captures d'écran de l'application et des consoles |
| `films/` | montages finis |

Rien ne s'y dépose à la main : `tools/media/deposer.mjs`, dans le dépôt du code,
vérifie le type et la taille du fichier, le range, commite et pousse.
