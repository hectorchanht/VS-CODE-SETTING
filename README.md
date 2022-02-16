
## [Automatically organize TypeScript/JavaScript imports](https://eshlox.net/2019/12/02/vscode-automatically-organize-typescript-imports)
<details>
<summary>DESCRIPTION</summary>

1. remove any unused imports, 
2. sort existing imports by file paths, 
3. sort named imports.

Open the settings (`⇧⌘P` or `Ctrl+Shift+P`), 
find `Preferences: Configure Language Specific Settings...`
and then find the `TypeScript`. It will open the `settings.json` file. 

Now add the configuration.
</details>

<!-- <details> -->
<!-- <summary>CODE</summary> -->

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

<!-- </details> -->

## [Emmet abbreviations](https://medium.com/neverrest/vs-code-emmet-abbreviations-and-snippets-make-your-life-easier-875505550607)
[cheat sheet](https://docs.emmet.io/cheat-sheet/)
[Emmet in Visual Studio Code](https://code.visualstudio.com/docs/editor/emmet)
<details>
<summary>DEMO</summary>

Emmet abbreviation is built-in feature for VS Code, no extension installation required. You may see the abbreviation displayed in the suggestion list when you are typing some code. Wrench icon will be appeared at the start of the Emmet.

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


## [custom snippets](https://medium.com/neverrest/vs-code-emmet-abbreviations-and-snippets-make-your-life-easier-875505550607)
[Snippets in Visual Studio Code](https://code.visualstudio.com/docs/editor/userdefinedsnippets)

<!-- <details> -->
<!-- <summary>HOW</summary> -->

Using custom Emmet snippets
You can create your own snippets by these steps
* Click at a gear icon in left-bottom corner
* Click ‘User Snippets’
* Choose computer language that you prefer
* JSON file in the chosen language will appear
* It would have an example snippet for you

Therefore, you can start create your own snippet by looking at the example. There are 4 components that you have to define.

![image](https://miro.medium.com/max/1200/1*1U9BVFL2EnWPp2q-EarmSA.png)
    
1. Snippet’s name — It is displayed via IntelliSense at the end of the suggestions.
1. prefix — defines one or more trigger words that display the snippet in IntelliSense which make VS Code knows that it is a snippet.
1. body — one or more lines of content that will be generated when you use the snippet and $ is defined to let VS Code know where your cursor will be when you press Tab key.
1. description — is an optional description of the snippet to explain what the snippet does.    
<!-- </details> -->

<details>
<summary>DEMO</summary>

Code snippets are templates that make you easier to enter repeating code patterns. It’s very useful when you have to type the same code every time. Snippets appear in IntelliSense mixed with other suggestions and in front of the snippets will display a block of square which make you know that it’s the snippet.

![image](https://miro.medium.com/max/1400/1*5rRx5Ohe7WFzN0MPhKE7Iw.gif)

</details>

<details>
<summary>DEMO2</summary>

![IMAGE](https://miro.medium.com/max/1400/1*e_gCtqEazISkUfUx0Y0SiQ.png)
![IMAGE](https://miro.medium.com/max/1400/1*r1RxhiNUk3jb716AASgsXg.gif)
</details>






