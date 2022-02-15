# Neon Noir

![Neon Noir](https://user-images.githubusercontent.com/58347797/153980144-b5d7ed1a-e702-441a-959c-65181dcfa2fd.png)

## About Neon Noir

This theme is a highly customized neon inspired dark theme originally based on [Tokyo Night Storm by enkia](https://github.com/enkia/tokyo-night-vscode-theme).

### Main focus

The theme is focused for working with HTML, CSS, JS and [Svelte](https://github.com/sveltejs) projects

## Installation

Download the latest release from [here](https://github.com/rasmushenneken/neon-noir/releases/) and extract it to `C:\Users\USERNAME\.vscode\extensions`. In Visual Studio Code press <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>P</kbd> (Windows and Linux) or <kbd>Cmd</kbd> + <kbd>Shift</kbd> + <kbd>P</kbd> (macOS) to open the command palette, input `Color Theme`, press enter and choose Neon Noir from the dropdown.

### Useful info

Modify your `settings.json` file to enable additional styles used in the screenshot above.

#### Bracket pairs

    "editor.guides.bracketPairs": "active",
    "editor.bracketPairColorization.enabled": true,
    "workbench.colorCustomizations": {
    "editorBracketHighlight.foreground1": "#7AA2F7",
    "editorBracketHighlight.foreground2": "#DF92E9",
    "editorBracketHighlight.foreground3": "#EC48C9",
    "editorBracketHighlight.foreground4": "#ec486b",
    "editorBracketHighlight.foreground5": "#ec9f48",
    "editorBracketHighlight.foreground6": "#ecdb48",
    "editorBracketHighlight.unexpectedBracket.foreground": "#42ff42"
    }

#### Font

Requires [Fira Code](https://github.com/tonsky/FiraCode) by tonsky

    "editor.fontFamily": "Fira Code",
    "editor.fontLigatures": true

#### Prettier

    "prettier.arrowParens": "avoid",
    "prettier.semi":  false

## After installation

You may need to reload window after installation. To do that, choose `Reload Window` from the command palette.

Feel free to modify the theme however you like ([MIT License](https://github.com/rasmushenneken/neon-noir/blob/main/LICENSE.txt)). Please open an issue if you find something that looks out of place [here](https://github.com/rasmushenneken/neon-noir/issues)!
