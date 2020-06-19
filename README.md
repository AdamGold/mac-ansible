# mac-ansible

I use this project to configure my macOS the way I like it. That way I can wipe
and re-install with less effort.

## Getting Started

1. Install [homebrew](http://brew.sh/) with the command from the site
2. `brew install pipx`
3. `pipx install ansible`
4. Then `./playbook.yml`

## What's left to do?

1. Install VSCode Extensions:

-   [Vim](https://marketplace.visualstudio.com/items?itemName=vscodevim.vim)
-   [vscode-icons](https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons)
-   [TabNine](https://marketplace.visualstudio.com/items?itemName=TabNine.tabnine-vscode)
-   [Settings Sync](https://marketplace.visualstudio.com/items?itemName=Shan.code-settings-sync)
-   [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python)
-   [Monokay Dark Soda Modified](https://marketplace.visualstudio.com/items?itemName=DengSir.monokai-dark-soda-modified)
-   [Bracket Pair Colorizer](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer)

2. Set Alfred directory to Dropbox

3. Install Alfred Workflows:

-   [Currency](https://github.com/jin5354/alfred3-workflow-CurrencyConvert)
-   [fkill](https://github.com/SamVerschueren/alfred-fkill#readme)
-   [git repos](https://github.com/deanishe/alfred-repos)
-   [appcleaner](https://github.com/asendra/mac-app-configs/blob/master/alfred-workflows/alfred-appcleaner.alfredworkflow)

4. Set `gitrepos` extension settings to (`alfred/workflow data/git-repos/settings.json`):

```
{
	"__workflow_last_version": "2.1.2",
	"app_cmd": "iTerm",
	"app_default": "Visual Studio Code",
	"global_exclude_patterns": [],
	"search_dirs": [
		{
			"depth": 4,
			"name_for_parent": 1,
			"path": "~/Documents/Development"
		}
	]
}
```
