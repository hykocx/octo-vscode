# Octo VSCode

Thèmes VSCode épuré, disponible en variante claire et sombre.

![preview](/assets/preview.jpg)

## Variantes

| Thème | Style |
|-------|-------|
| **Octo Dark** | Très sombre, reposant pour les longues sessions |
| **Octo Light** | Clair, parfait pour développer durant la journée |

Coloration sémantique activée sur les deux variantes.

## Installation

### Via le marketplace (recommandé)

Recherche **Octo Theme** dans l'onglet Extensions de ton éditeur, ou installe directement depuis :

- **VS Code** : [marketplace.visualstudio.com](https://marketplace.visualstudio.com/items?itemName=hykocx.octo-vscode)
- **VSCodium / Open VSX** : [open-vsx.org](https://open-vsx.org/extension/hykocx/octo-vscode)

### Via un fichier VSIX

1. Télécharge le fichier `.vsix` depuis les [releases](https://git.hyko.cx/hykocx/octo-vscode/releases).
2. Ouvre la palette de commandes (`Ctrl+Shift+P` / `Cmd+Shift+P`).
3. Cherche **Extensions: Installer depuis un fichier VSIX...** et sélectionne le fichier téléchargé.

## Appliquer le thème

1. Ouvre la palette de commandes.
2. Cherche **Préférences : Thème de couleur**.
3. Sélectionne **Octo Dark** ou **Octo Light**.

> **Astuce** : C'est encore mieux quand tu configures les deux ! Dans tes paramètres VSCode :
> 1. Définis **Octo Light** pour `workbench.preferredLightColorTheme` et **Octo Dark** pour `workbench.preferredDarkColorTheme`.
> 2. Active `window.autoDetectColorScheme` → VSCode suivra alors automatiquement ton thème système.

## Développement

```bash
npm install
npm run package  # génère le .vsix
```
