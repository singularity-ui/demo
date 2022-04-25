# Contributing

- [Development](#development)
  - [Getting Started](#getting-started)
- [IDE](#ide)
  - [Visual Studio Code](#visual-studio-code)

## Development

### Getting Started

```sh
yarn
yarn dev
```

## IDE

### Visual Studio Code

Recommended settings (`.vscode/settings.json`):

```json
{
  "editor.codeActionsOnSave": {
    "source.fixAll": true
  },
  "editor.defaultFormatter": "dbaeumer.vscode-eslint",
  "editor.formatOnSave": true,
  "eslint.codeActionsOnSave.mode": "all",
  "eslint.format.enable": true,
  "eslint.packageManager": "yarn",
  "[css]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[json]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  }
}
```
