# C64 Brutalist

A dark, low-glare theme for Visual Studio Code and Cursor. Calm blue-gray surfaces keep the interface readable; saturated early-PC colors make syntax structure obvious without turning the whole workbench into neon.

## Palette

| Role | Color |
| --- | --- |
| Editor | `#202430` |
| Raised surface | `#262b38` |
| Selection | `#394254` |
| Text | `#b6bac8` |
| Secondary text | `#939bac` |
| Accent | `#a2abcf` |
| Comment | `#77aaaa` |
| Keyword | `#ff66ff` |
| Function | `#55ddff` |
| Variable | `#bbccff` |
| String | `#66dd66` |
| Number | `#ff9955` |
| Type | `#7799ff` |
| Operator | `#ffcc55` |
| Error | `#ff7777` |

The integrated terminal uses the same ANSI palette. Semantic highlighting is enabled, so language servers retain the same type/function/variable distinctions as TextMate grammars.

## Install

Download `c64-brutalist-theme-1.0.0.vsix` from the latest GitHub release, then run either:

```powershell
code --install-extension .\c64-brutalist-theme-1.0.0.vsix
cursor --install-extension .\c64-brutalist-theme-1.0.0.vsix
```

Select **C64 Brutalist** with **Preferences: Color Theme**. The extension changes colors only; it does not modify fonts, keybindings, editor behavior, or extensions.

## Develop

Open this repository in VS Code or Cursor and press `F5` to launch an Extension Development Host. Package locally with:

```sh
npx --yes @vscode/vsce package
```

## License

MIT
