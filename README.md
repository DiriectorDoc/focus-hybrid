# README
## This is the README for your extension "focus-hybrid"
You can author your README using Visual Studio Code.  Here are some useful editor keyboard shortcuts:

* Split the editor (`Cmd+\` on macOS or `Ctrl+\` on Windows and Linux)
* Toggle preview (`Shift+CMD+V` on macOS or `Shift+Ctrl+V` on Windows and Linux)
* Press `Ctrl+Space` (Windows, Linux) or `Cmd+Space` (macOS) to see a list of Markdown snippets

### For more information
* [Visual Studio Code's Markdown Support](http://code.visualstudio.com/docs/languages/markdown)
* [Markdown Syntax Reference](https://help.github.com/articles/markdown-basics/)

**Enjoy!**
## Things I used
### Derived from...
This these is an adapttation of [Focus theme for Brackets](https://github.com/brucecantarim/brackets-theme-focus) by brucecantarim.

### settings.json
These are the setting I used in my `settings.json` to develop this theme.

```JSON
"editor.tokenColorCustomizations": {
    "comments": "#AAA",
    "strings": "#FFF",
    "keywords": "#F04",
    "numbers": "#F0C",
    "keyword.operator.new": "#F0C",
    "textMateRules": [
        {
            "scope": [
                "entity.name.tag.html",
                "punctuation.definition.tag",
                "entity.name.type",
                "variable",
                "meta.definition.variable.name",
                "support.variable",
                "entity.name.variable",
                "entity.name.tag.css",
                "entity.name.function",
                "variable.language.arguments.js",
                "variable.other.constant",
                "punctuation.definition.list.begin.markdown",
                "markup.quote.markdown",
                "punctuation.definition.quote.begin.markdown",
                "punctuation.definition.variable.batchfile"
            ],
            "settings": {
                "foreground": "#09F"
            }
        },
        {
            "scope": [
                "entity.other.attribute-name",
                "entity.other.attribute-name.id.css",
                "markup.bold.markdown",
                "entity.other.attribute-name.id.css punctuation.definition.entity.css"
            ],
            "settings": {
                "foreground": "#F80"
            }
        },
        {
            "scope": [
                "punctuation.definition.template-expression.begin",
                "punctuation.definition.template-expression.end",
                "entity.other.attribute-name.class.css",
                "entity.other.attribute-name.class.css punctuation.definition.entity.css",
                "markup.italic.markdown",
                "support.type.property-name.json"
            ],
            "settings": {
                "foreground": "#FE0"
            }
        },
        {
            "scope": [
                "variable.other.property.js",
                "entity.name.function.member",
                "support.type.property-name",
                "variable.other.constant.property.js",
                "variable.other.object.property.js",
                "meta.function-call.js entity.name.function.js",
                "entity.name.type.anchor.yaml",
                "entity.other.document.begin.yaml",
                "keyword.control.at-rule.font-face.css",
                "support.function.json"
            ],
            "settings": {
                "foreground": "#0F0"
            }
        },
        {
            "scope": [
                "constant.language.boolean.true.js",
                "constant.language.boolean.false.js",
                "keyword.other.unit",
                "constant.other.color.rgb-value",
                "support.constant.property-value",
                "constant.language.json.comments",
                "constant.language.null.js",
                "constant.language.undefined.js",
                "constant.character",
                "entity.name.tag.yaml",
                "support.function.url.css",
                "support.function.calc.css",
                "support.function.gradient.css",
                "support.function.misc.css",
                "support.constant.color.w3c-standard-color-name.css",
                "constant.language.batchfile",
                "keyword.operator.at.batchfile"
            ],
            "settings": {
                "foreground": "#F0C"
            }
        },
        {
            "scope": [
                "keyword.operator.new",
                "keyword",
                "keyword.operator.expression",
                "variable.language",
                "invalid.illegal.expected-dictionary-separator.json.comments",
                "support.constant.font-name.css",
                "storage.modifier.async.js",
                "storage.modifier.js",
                "entity.other.attribute-name.pseudo-element.css",
                "entity.other.attribute-name.pseudo-class.css"
            ],
            "settings": {
                "foreground": "#F04"
            }
        },
        {
            "scope": [
                "string.regexp",
                "support.type.vendored.property-name",
                "meta.tag.metadata.doctype.html punctuation.definition.tag.begin.html",
                "meta.tag.metadata.doctype.html punctuation.definition.tag.end.html",
                "meta.tag.metadata.doctype.html entity.name.tag.html",
                "meta.tag.metadata.doctype.html entity.other.attribute-name.html",
                "storage.type.function.arrow.js",
                "punctuation.separator.key-value.js",
                "constant.character.escape",
                "punctuation.definition.entity.css",
                "keyword.operator"
            ],
            "settings": {
                "foreground": "#FFF"
            }
        },
        {
            "scope": [
                "markup.heading"
            ],
            "settings": {
                "foreground": "#A0F"
            }
        },
        {
            "scope": [
                "markup.inline.raw"
            ],
            "settings": {
                "foreground": "#AAA"
            }
        },
        {
            "scope": [
                "keyword.other.js",
                "support.type.object.module.js",
                "support.constant.json"
            ],
            "settings": {
                "foreground": "#5CF"
            }
        },
        {
            "scope": [
                "punctuation.definition.string.begin.markdown",
                "punctuation.definition.string.end.markdown",
                "string.other.link.description.markdown",
                "string.other.link.title.markdown"
            ],
            "settings": {
                "foreground": "#00F"
            }
        }
    ]
},
"editor.semanticTokenColorCustomizations": {
    "enabled": true,
    "rules": {
        "*.declaration": {
            "foreground": "#0F0"
        },
        "parameter.declaration": {
            "foreground": "#0EF"
        },
        "function.defaultLibrary": {
            "foreground": "#5CF"
        },
        "variable.defaultLibrary": {
            "foreground": "#5CF"
        },
        "class.defaultLibrary": {
            "foreground": "#5CF"
        },
        "property.defaultLibrary": {
            "foreground": "#0F0"
        }
    }
}
```