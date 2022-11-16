# SURENDAR VS CODE THEME

## Please use [Operator mono lig](https://github.com/Bug0017/operator-mono-lig-1) font


## Please copy and path code in VS Code settings.json file this feature implemented in next version by default.

 // @SurendarYama needed implement in Vs code Surendar Theme by default.
 
 
    "editor.tokenColorCustomizations": {
        "textMateRules": [
          {
            "scope": [
              //following will be in italic (=FlottFlott)
              "comment",
              "entity.name.type.class", //class names
              "keyword", //import, export, return…
              "constant", //String, Number, Boolean…, this, super
              "storage.modifier", //static keyword
              "storage.type.class.js", //class keyword
            ],
            "settings": {
              "fontStyle": "italic"
            }
          },
          {
            "scope": [
              //following will be excluded from italics (VSCode has some defaults for italics)
              "invalid",
              "keyword.operator",
              "constant.numeric.css",
              "keyword.other.unit.px.css",
              "constant.numeric.decimal.js",
              "constant.numeric.json"
            ],
            "settings": {
              "fontStyle": ""
            }
          }
        ]
    },
    "workbench.colorCustomizations": {
      "scrollbarSlider.background": "#fecc1b",
      "scrollbarSlider.activeBackground": "#6BD968",
      "scrollbarSlider.hoverBackground": "#D83BD2",
      "scrollbar.shadow": "#3992ff"
    },
