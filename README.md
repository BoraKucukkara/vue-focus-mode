# vue-focus-mode Theme


You can override colors. Add these lines into your user > settings.json

```json
    "editor.tokenColorCustomizations": {
        "textMateRules": [
            {
                "scope": "variable.other.object.js, variable.other.object.property.js, variable.other.property.js",
                "settings": {"foreground": "#d1bb98"}
            },
            {
                "scope": "entity.other.attribute-name, punctuation.separator.key-value.html, punctuation.definition.string.begin.html, punctuation.definition.string.end.html",
                "settings": {"foreground": "#629f95"}
            },
            {
                "scope": "punctuation.definition.string",
                "settings": {"foreground": "#00CC77"}
            },
            {
                "scope": "entity.name.tag, punctuation.definition.tag.begin.html, punctuation.definition.tag.end.html",
                "settings": {"foreground": "#8f796c", "fontStyle": "italic"}
            },
            {
                "scope": "punctuation.attribute-shorthand.bind.html.vue, variable.other.readwrite.alias.js, keyword.operator.spread.js, punctuation.attribute-shorthand.event.html.vue, keyword.operator.comparison.ts, meta.attribute.directive.vue, entity.other.attribute-name.html.vue, keyword.control.conditional.vue, keyword.control.loop.vue, punctuation.definition.string.begin.html.vue, punctuation.definition.string.end.html.vue, punctuation.separator.key-value.html.vue",
                "settings": {"foreground": "#00CC77","fontStyle": "bold"}
            },
            {
                "scope": "keyword.control.import.js, keyword.control.export.js, keyword.control.from.js, keyword.control.default.js",
                "settings": {"foreground": "#618476"}
            },
            {
                "scope": "keyword.control.conditional.js, keyword.control.flow.js, storage.modifier.async.js",
                "settings": {"foreground": "#00CC77"}
            },
            {
                "scope": "meta.object-literal.key.js",
                "settings": {"foreground": "#e8c082"}
            },
            {
                "scope": "variable.language.this.js",
                "settings": {"foreground": "#e97941"}
            },
            {
                "scope": "punctuation.definition.interpolation.begin.html.vue, punctuation.definition.interpolation.end.html.vue,",
                "settings": {"fontStyle": "bold"}
            }
        ]
    }
```