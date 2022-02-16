
### [Automatically organize TypeScript/JavaScript imports](https://eshlox.net/2019/12/02/vscode-automatically-organize-typescript-imports)
<details>
<summary>OPEN</summary>

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
</details>

### [Emmet Abbreviations](https://medium.com/neverrest/vs-code-emmet-abbreviations-and-snippets-make-your-life-easier-875505550607)

<details>
<summary>OPEN</summary>
    
1. Create initial code in html by using `! + TAB`
![image](https://miro.medium.com/max/1400/1*ayQ9xBrLySC51FIdoQZs-Q.gif)

2. Create class and id by using `.className` and `#idName`
![image](https://miro.medium.com/max/1400/1*ztspDuH5wbh1Z4TsC9mjBg.gif)

3. Create child element by using `>childElement`
![image](https://miro.medium.com/max/1400/1*F9C_rTtBuQJwiStWx_G11g.gif)

4. Create sibling element by using `+siblingName`
Create sibling element
![image](https://miro.medium.com/max/1400/1*TGmPAzHVRoHc0hd0JFguTg.gif)

5. Create multiple lines of code by using `*`
![image](https://miro.medium.com/max/1400/1*PxBcwHLmCebErE6NwcOFYg.gif)

6. Create item numbering by using `$`
![image](https://miro.medium.com/max/1400/1*gpH2m7MO3QUOyn8lbG3VZw.gif)

7. Create text between html tag by using `{}`
![image](https://miro.medium.com/max/1400/1*REqbx7dRv_XJ0XweLk12yg.gif)
</details>














