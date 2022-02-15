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

#### Terminal

If you're using Git Bash you can modify `C:\Program Files\Git\etc\profile.d\git-prompt.sh` (remember to take a backup). Example:

![Git Bash](https://user-images.githubusercontent.com/58347797/154087922-602b1797-e331-4941-8b61-5b58f9d4fe3d.png)

For this look my `git-prompt.sh` would be modified like this starting from line 11:

    else
    	PS1='\[\033]0;$TITLEPREFIX:$PWD\007\]'	# set window title
    	PS1="$PS1"'\n'							# new line
    	PS1="$PS1"'\[\033[35m\]'				# change to purple
    	PS1="$PS1"'\u'							# user@host<space>
    	PS1="$PS1"' ➡ '
    	PS1="$PS1"'\[\033[34m\]'				# change to blue
    	# PS1="$PS1"'$MSYSTEM '					# show MSYSTEM
    	# PS1="$PS1"'\[\033[33m\]'				# change to brownish yellow
    	PS1="$PS1"'\w '							# current working directory
    	if test -z "$WINELOADERNOEXEC"
    	then
    		GIT_EXEC_PATH="$(git --exec-path 2>/dev/null)"
    		COMPLETION_PATH="${GIT_EXEC_PATH%/libexec/git-core}"
    		COMPLETION_PATH="${COMPLETION_PATH%/lib/git-core}"
    		COMPLETION_PATH="$COMPLETION_PATH/share/git/completion"
    		if test -f "$COMPLETION_PATH/git-prompt.sh"
    		then
    			. "$COMPLETION_PATH/git-completion.bash"
    			. "$COMPLETION_PATH/git-prompt.sh"
    			PS1="$PS1"'🌵'
    			PS1="$PS1"'\[\033[31m\]'		# change to red
    			PS1="$PS1"'`__git_ps1`'			# bash function
    		fi
    	fi
    	PS1="$PS1"'\[\033[31m\]'	# change color
    	PS1="$PS1"'\n'				# new line
    	PS1="$PS1"'$ '				# prompt: always $
    	PS1="$PS1"'\[\033[0m\]'		# change color
    fi

## After installation

You may need to reload window after installation. To do that, choose `Reload Window` from the command palette.

Feel free to modify the theme however you like ([MIT License](https://github.com/rasmushenneken/neon-noir/blob/main/LICENSE.txt)). Please open an issue if you find something that looks out of place [here](https://github.com/rasmushenneken/neon-noir/issues)!
