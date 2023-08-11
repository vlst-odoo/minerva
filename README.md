# Minerva

This extension provides syntax highlighting of the js code of owl templates.

You will have to use the `HTML` syntax highligher for for this to work.


Installing this extension will make all `t-if`, `t-att-`, etc tags white
You can use this code in the settings to make them be any color you want:

```json
  "editor.tokenColorCustomizations": {
    "textMateRules": [
        {
            "scope": "js_in_owl",
            "settings": {
                "foreground": "#0d9769"
            }
        }
    ]
},
```
