# React Simple Boilerplate

Already intalled and configured:
* ESLint (airbnb)
* Prettier
* Stylelint (standard)
* Husky with lint-staged

Install with `npm install` or `yarn install`

Run with `npm start` or `yarn start`

Lint with `npm run lint` or `yarn run lint`

# Configure git (only for Windows)

Force git to use LF end of line everywhere:

```bash
git config --global core.eol lf
git config --global core.autocrlf input
```

If you already clone this repository, remove it and clone it again.

# Configure Visual Studio Code

## Install ESLint

1. In Visual Studio Code go to View -> Extensions
2. Search for `eslint`: [EsLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
3. Click Install

## Install Prettier

1. In Visual Studio Code go to View -> Extensions
2. Search for `prettier code formatter`: [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
3. Click Install

## Install Stylelint

1. In Visual Studio Code go to View -> Extensions
2. Search for `stylelint`: [Stylelint](https://marketplace.visualstudio.com/items?itemName=stylelint.vscode-stylelint)
3. Click Install

## Visual Studio Code Settings

1. Go to File -> Preferences -> Settings.
2. Scroll down to `Edit in settings.json`. It will open your IDE settings in json format.
3. Add this after the first opening curly brace (or before the last ending one):

```
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true,
    "source.fixAll.stylelint": true
  },
  "files.eol": "\n",
  "editor.tabSize": 2,
```
