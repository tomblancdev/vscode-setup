# Python

## Settings
```json
{
    // ### Python ###
    "[python]": {
        "editor.formatOnType": true,
        "editor.bracketPairColorization.independentColorPoolPerBracketType": true,
        "editor.bracketPairColorization.enabled": true,
        "editor.matchBrackets": "always",
        "editor.guides.bracketPairs": "active",
        "editor.guides.bracketPairsHorizontal": "active",
        "editor.guides.indentation": true,
        "editor.tabSize": 4,
        "editor.detectIndentation": true,
        "editor.codeActionsOnSave": {
            "source.organizeImports.ruff": true,
            "source.sortImports.ruff": true,
            "source.fixAll.ruff": true,
        },
        "editor.defaultFormatter": "ms-python.black-formatter",
    },
}
```	

## Required Extensions
| Extension                                                                                                                 | Description                | Config                                                                                  |
| ------------------------------------------------------------------------------------------------------------------------- | -------------------------- | --------------------------------------------------------------------------------------- |
| [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python)                                            | Python language support    | [Python.md](../extensions/python/Python.md)                                             |
| [Ruff](https://marketplace.visualstudio.com/items?itemName=charliermarsh.ruff)                                            | Python linter              | [Ruff.md](../extensions/python/Ruff.md)                                                 |
| [Black](https://marketplace.visualstudio.com/items?itemName=psf.black)                                                    | Python formatter           | [Black.md](../extensions/python/Black.md)                                               |
| [Mypy](https://marketplace.visualstudio.com/items?itemName=ms-python.mypy-type-checker)                                   | Python type checker        | [Mypy.md](../extensions/python/Mypy.md)                                                 |
| [Python Environment Manager](https://marketplace.visualstudio.com/items?itemName=donjayamanne.python-environment-manager) | Python environment manager | [Python Environment Manager.md](../extensions/python/Python%20Environment%20Manager.md) |