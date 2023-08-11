# Minerva

This extension provides syntax highlighting of the js code of owl templates.
![image](https://github.com/vlst-odoo/minerva/assets/118446179/2cf570ea-6654-49ba-ae7c-98cc1f791e44)

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
