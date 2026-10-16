# Registre de plugins de Nora IDE

Index public lu par Nora IDE (**Plugins › Marketplace**) : sélection curée, suggestions selon le
projet ouvert, et paquets publiés par Nora.

- `index.json` : l'index (format décrit dans la documentation des plugins de Nora IDE).
- `color-schemes/` : jeux de couleurs `.icls` publiés par Nora.
- Releases : paquets de plugins natifs (`<nom>-<version>`), chacun avec son empreinte SHA-256
  inscrite dans l'index et vérifiée par l'IDE avant installation.

Les extensions VS Code référencées par l'index sont téléchargées depuis
[Open VSX](https://open-vsx.org), pas depuis ce dépôt.

## Hello Nora

Le premier plugin natif de Nora et l'exemple de référence de son API expérimentale : une entrée de
menu et un panneau Compose, chargés dans un ClassLoader isolé. Installable depuis Nora IDE 2.2 ou
plus récent, et actif après un redémarrage.

## Licence

Apache-2.0, voir `LICENSE`.
