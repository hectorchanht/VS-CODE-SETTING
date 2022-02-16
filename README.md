# VS-CODE-SETTING

automatically organize TypeScript/JavaScript imports

1. remove any unused imports, 
2. sort existing imports by file paths, 
3. sort named imports.

Open the settings (`⇧⌘P` or `Ctrl+Shift+P`), 
find `Preferences: Configure Language Specific Settings...`
and then find the `TypeScript`. It will open the `settings.json` file. 

Now add the configuration.

```
    "[javascript]": {
        "editor.codeActionsOnSave": {
            "source.organizeImports": true
        }
    },
    "[javascriptreact]": {
        "editor.codeActionsOnSave": {
            "source.organizeImports": true
        }
    },
    "[typescript]": {
        "editor.codeActionsOnSave": {
            "source.organizeImports": true
        }
    },
    "[typescriptreact]": {
        "editor.codeActionsOnSave": {
            "source.organizeImports": true
        }
    },
```

That's all. Whenever you save the *.ts or *.tsx file, the VS Code will automatically organize imports.

  [src](https://eshlox.net/2019/12/02/vscode-automatically-organize-typescript-imports)
