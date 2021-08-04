# VS-Code_Setup
### Theme

`One Monokai Theme`

### Extensions used in course videos

For each of the extensions, read the overview page in order to learn how to use it.

`Auto Close Tag` to automatically close HTML tags

`Auto Rename Tag` to automatically change matching HTML tags.

`Beautify` for formatting HTML, Php and ERB

`Code Spell Checker`

`Color Highlight` to, as the name says, highlight colors in CSS.

`Docker`

`Draw.io integration`

`ESLint`

`GitLens - Git Supercharged`

`Helium Icon Theme`

`JavaScript (ES6) code snippets`

`Markdown Preview Enhanced`

`Paste and Indent` to automatically indent pasted code.

`Path Intellisense` to autocomplete filenames.

`Prettier` to automatically format code.

`SCSS IntelliSense`

`Tabnine AI Code Completion`

`vscode-pdf`

`XML Tools`

`YAML`
### Settings

Just go to settings in VSCode, and on the right side, go to `Edit in settings.json`, and pas in this code:
```json
{
  "files.autoSave": "afterDelay",
  "editor.minimap.enabled": true,
  "tabnine.experimentalAutoImports": true,
  "editor.tabSize": 2,
  "workbench.statusBar.visible": true,
  "workbench.activityBar.visible": true,
  "editor.formatOnSave": false,
  "workbench.colorCustomizations": {
    "statusBar.background": "#333333",
    "statusBar.noFolderBackground": "#333333",
    "statusBar.debuggingBackground": "#263238"
  },
  "css.validate": false,
  "scss.validate": false,
  "less.validate": false,
  "editor.wordWrap": "on",
  "json.maxItemsComputed": 10000,
  "cSpell.userWords": ["basesize"],
  "eslint.migration.2_x": "off",
  "files.exclude": {
    "**/.classpath": true,
    "**/.project": true,
    "**/.settings": true,
    "**/.factorypath": true
  },
  "redhat.telemetry.enabled": false,
  "editor.suggestSelection": "first",
  "hediet.vscode-drawio.local-storage": "eyIuZHJhd2lvLWNvbmZpZyI6IntcImxhbmd1YWdlXCI6XCJcIixcImN1c3RvbUZvbnRzXCI6W10sXCJsaWJyYXJpZXNcIjpcImdlbmVyYWxcIixcImN1c3RvbUxpYnJhcmllc1wiOltcIkwuc2NyYXRjaHBhZFwiXSxcInBsdWdpbnNcIjpbXSxcInJlY2VudENvbG9yc1wiOltdLFwiZm9ybWF0V2lkdGhcIjpcIjI0MFwiLFwiY3JlYXRlVGFyZ2V0XCI6ZmFsc2UsXCJwYWdlRm9ybWF0XCI6e1wieFwiOjAsXCJ5XCI6MCxcIndpZHRoXCI6ODI3LFwiaGVpZ2h0XCI6MTE2OX0sXCJzZWFyY2hcIjp0cnVlLFwic2hvd1N0YXJ0U2NyZWVuXCI6dHJ1ZSxcImdyaWRDb2xvclwiOlwiI2QwZDBkMFwiLFwiZGFya0dyaWRDb2xvclwiOlwiIzZlNmU2ZVwiLFwiYXV0b3NhdmVcIjp0cnVlLFwicmVzaXplSW1hZ2VzXCI6bnVsbCxcIm9wZW5Db3VudGVyXCI6MCxcInZlcnNpb25cIjoxOCxcInVuaXRcIjoxLFwiaXNSdWxlck9uXCI6ZmFsc2UsXCJ1aVwiOlwiXCJ9In0=",
  "workbench.editorAssociations": {
    "*.ipynb": "jupyter.notebook.ipynb"
  },
  "workbench.colorTheme": "One Monokai",
  "auto-close-tag.activationOnLanguage": [

    "xml",
    "php",
    "blade",
    "ejs",
    "jinja",
    "javascript",
    "javascriptreact",
    "typescript",
    "typescriptreact",
    "plaintext",
    "markdown",
    "vue",
    "liquid",
    "erb",
    "lang-cfml",
    "cfml",
    "HTML (EEx)",
    "HTML (Eex)",
    "plist"
  ],
  "editor.fontSize": 14,
  "workbench.preferredHighContrastColorTheme": "Monokai",
  "workbench.iconTheme": "helium-icon-theme",
  "auto-close-tag.excludedTags": [
    "area",
    "base",
    "br",
    "col",
    "command",
    "embed",
    "hr",
    "img",
    "input",
    "keygen",
    "link",
    "meta",
    "param",
    "source",
    "track",
    "wbr"
  ],
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "[html]": {
    "editor.defaultFormatter": "HookyQR.beautify"
  },
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "beautify.language": {
    "html": ["htm", "html", "php", "ejs"],
    "js": [],
    "css": []
  },
  "terminal.integrated.fontSize": 12
}
```
