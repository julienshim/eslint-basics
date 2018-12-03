# ESLint Basics

Personal ESLint Configuration

### Global Dependencies (for terminal use)

- eslint

### VSCode Extensions

- ESLint (Dirk Baeumer)
- Prettier - Code Formatter (Esben Petersen)

### Project devDependencies

- eslint
- eslint-config-airbnb
- eslint-config-prettier
- eslint-plugin-import
- eslint-plugin-jsx-a11y
- eslint-plugin-prettier
- eslint-plugin-react
- prettier

### VSCode User Settings

`Command + ,` > `...` > `Open settings.json`, then add the following:

```
{
  "editor.formatOnSave": true,
  "[javascript]": {
      "editor.formatOnSave": false
  },
  "eslint.autoFixOnSave": true,
  "eslint.alwaysShowStatus": true,
  "prettier.disableLanguages": [
      "js"
  ],
  "files.autoSave": "onFocusChange",
}
```
