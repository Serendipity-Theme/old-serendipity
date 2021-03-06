# Serendipiti V1. (Unsupported Version)

## Checkout the new & supported version at:

### [Serendipity Theme Website](https://serendipitytheme.com)

### [Marketplace](https://marketplace.visualstudio.com/items?itemName=wicked-labs.wvsc-serendipity)
## Installation

1. Open **Extensions** sidebar panel in VS Code. `View → Extensions`
2. Search for **`old-serendipity`**
3. Click **Install** to install it.
4. Code > Preferences > Color Theme > **`Serendipity Midnight V1` / `Serendipity Sunset V1` / `Serendipity Morning V1 `**
5. Optional: Use the recommended settings below for best experience

## Themes

### Midnight
You have three themes, Midnight, Sunset and Morning and here the screenshots
![VS Code Marketplace](https://github.com/Serendipity-Theme/old-serendipity/blob/master/midnight-screenshots/midnight-css.png?raw=true)
![VS Code Marketplace](https://github.com/Serendipity-Theme/old-serendipity/blob/master/midnight-screenshots/midnight-gulp.png?raw=true)
![VS Code Marketplace](https://github.com/Serendipity-Theme/old-serendipity/blob/master/midnight-screenshots/midnight-html.png?raw=true)
![VS Code Marketplace](https://github.com/Serendipity-Theme/old-serendipity/blob/master/midnight-screenshots/midnight-javascript.png?raw=true)
![VS Code Marketplace](https://github.com/Serendipity-Theme/old-serendipity/blob/master/midnight-screenshots/midnight-markdown.png?raw=true)
![VS Code Marketplace](https://github.com/Serendipity-Theme/old-serendipity/blob/master/midnight-screenshots/midnight-python.png?raw=true)
![VS Code Marketplace](https://github.com/Serendipity-Theme/old-serendipity/blob/master/midnight-screenshots/midnight-tsx.png?raw=true)
![VS Code Marketplace](https://github.com/Serendipity-Theme/old-serendipity/blob/master/midnight-screenshots/midnight-typescript.png?raw=true)

### Sunset
You have three themes, Midnight, Sunset and Morning and here the screenshots
![VS Code Marketplace](https://github.com/Serendipity-Theme/old-serendipity/blob/master/sunset-screenshots/sunset-css.png?raw=true)
![VS Code Marketplace](https://github.com/Serendipity-Theme/old-serendipity/blob/master/sunset-screenshots/sunset-gulp.png?raw=true)
![VS Code Marketplace](https://github.com/Serendipity-Theme/old-serendipity/blob/master/sunset-screenshots/sunset-html.png?raw=true)
![VS Code Marketplace](https://github.com/Serendipity-Theme/old-serendipity/blob/master/sunset-screenshots/sunset-javascript.png?raw=true)
![VS Code Marketplace](https://github.com/Serendipity-Theme/old-serendipity/blob/master/sunset-screenshots/sunset-markdown.png?raw=true)
![VS Code Marketplace](https://github.com/Serendipity-Theme/old-serendipity/blob/master/sunset-screenshots/sunset-python.png?raw=true)
![VS Code Marketplace](https://github.com/Serendipity-Theme/old-serendipity/blob/master/sunset-screenshots/sunset-tsx.png?raw=true)
![VS Code Marketplace](https://github.com/Serendipity-Theme/old-serendipity/blob/master/sunset-screenshots/sunset-typescript.png?raw=true)


### Morning
![VS Code Marketplace](https://github.com/Serendipity-Theme/old-serendipity/blob/master/morning-screenshots/morning-css.png?raw=true)
![VS Code Marketplace](https://github.com/Serendipity-Theme/old-serendipity/blob/master/morning-screenshots/morning-gulp.png?raw=true)
![VS Code Marketplace](https://github.com/Serendipity-Theme/old-serendipity/blob/master/morning-screenshots/morning-html.png?raw=true)
![VS Code Marketplace](https://github.com/Serendipity-Theme/old-serendipity/blob/master/morning-screenshots/morning-javascript.png?raw=true)
![VS Code Marketplace](https://github.com/Serendipity-Theme/old-serendipity/blob/master/morning-screenshots/morning-markdown.png?raw=true)
![VS Code Marketplace](https://github.com/Serendipity-Theme/old-serendipity/blob/master/morning-screenshots/morning-python.png?raw=true)
![VS Code Marketplace](https://github.com/Serendipity-Theme/old-serendipity/blob/master/morning-screenshots/morning-tsx.png?raw=true)
![VS Code Marketplace](https://github.com/Serendipity-Theme/old-serendipity/blob/master/morning-screenshots/morning-typescript.png?raw=true)

## Recommended Settings

```jsonc
{
  // These are my personal preferences.
  "editor.fontFamily": "'IBM Plex Mono', monospace",
  "editor.fontSize": 18,
  "editor.lineHeight": 38,
  "editor.letterSpacing": 0.5,
  "files.trimTrailingWhitespace": true,
  "editor.fontWeight": "normal",
  "prettier.eslintIntegration": true,
  "editor.cursorStyle": "line",
  "editor.cursorWidth": 5,
  "editor.cursorBlinking": "phase",
  "editor.renderWhitespace": "all"
}
```

## Italics

All themes use italics for certain language tokens by default.
To **disable** italics for all themes, add this snippet to your `settings.json`:

- quotes and _italic_ strings (like in markdown) will be unaffected and still be italic
- if you want to exclude one of the themes from this change, simply remove its name (along with the brackets `[]`) at the top of the snippet

```jsonc
"editor.tokenColorCustomizations": {
  "[Serendipity Light][Serendipity Dark][Serendipity High Contrast]": {
    "textMateRules": [
      {
        "scope": [
          "comment",
          "variable",
          "variable.other.object.js",
          "variable.other.object.property",
          "variable.language",
          "punctuation.accessor",
          "markup.changed",
          "markup.deleted.diff",
          "markup.inserted.diff",
          "keyword",
          "keyword.operator.relational",
          "keyword.operator.comparison",
          "keyword.control.flow.js",
          "keyword.control.flow.ts",
          "keyword.control.flow.tsx",
          "keyword.control.ruby",
          "keyword.control.module.ruby",
          "keyword.control.class.ruby",
          "keyword.control.def.ruby",
          "keyword.control.loop.js",
          "keyword.control.loop.ts",
          "keyword.control.import.js",
          "keyword.control.import.ts",
          "keyword.control.import.tsx",
          "keyword.control.from.js",
          "keyword.control.from.ts",
          "keyword.control.from.tsx",
          "keyword.operator.instanceof.js",
          "keyword.operator.expression.instanceof.ts",
          "keyword.operator.expression.instanceof.tsx",
          "support.constant",
          "support.function",
          "entity.other.attribute-name",
          "entity.other.inherited-class",
          "entity.name.function",
          "entity.name.tag.doctype",
          "entity.name.function",
          "meta.directive.vue",
          "meta.diff.header.git",
          "meta.diff.header.from-file",
          "meta.diff.header.to-file",
          "meta.var.expr",
          "meta.delimiter.period",
          "meta.selector",
          "meta.tag.sgml.doctype",
          "meta.tag.sgml.doctype.html",
          "meta.class meta.method.declaration meta.var.expr storage.type.js",
          "storage",
          "storage.type.property.js",
          "storage.type.property.ts",
          "storage.type.property.tsx",
          "source.elixir .punctuation.binary.elixir",
          "source.go keyword.package.go",
          "source.go keyword.import.go",
          "source.go keyword.function.go",
          "source.go keyword.type.go",
          "source.go keyword.struct.go",
          "source.go keyword.interface.go",
          "source.go keyword.const.go",
          "source.go keyword.var.go",
          "source.go keyword.map.go",
          "source.go keyword.channel.go",
          "source.go keyword.control.go",
          "string.quoted.docstring.multi.python",
        ],
        "settings": {
          "fontStyle": ""
        },
      },
    ],
  },
},
```

## Available Options

- Dark
- High Contrast
- Light

## Contact

Anything you wonder just contact me, @Mike_Andreuzza on twitter.
