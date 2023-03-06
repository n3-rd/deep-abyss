
# Deep Abyss VS Code theme

![Deep Abyss VS Code theme](https://raw.githubusercontent.com/n3-rd/deep-abyss/main/theme-image.png)

## Install

1. Go to [VS Marketplace](https://marketplace.visualstudio.com/items?itemName=n3-rd.deep-abyss).
2. Click on the "Install" button.
3. Then [select the theme](https://code.visualstudio.com/docs/getstarted/themes#_selecting-the-color-theme).

## Override this theme

To override this (or any other) theme in your personal config file, please follow the guide in the [color theme](https://code.visualstudio.com/api/extension-guides/color-theme) documentation. This is handy for small tweaks to the theme without having to fork and maintain your own theme.

## Contribute

1. Clone and open this [repo](https://github.com/n3-rd/deep-abyss) in VS Code
2. Run `npm install` or `yarn` or `pnpm install` to install the dependencies.
3. Press `F5` to open a new window with your extension loaded
4. Open `Code > Preferences > Color Theme` [`⌘k ⌘t`] and pick the "Dark Abyss" theme.
5. Make changes to the [`/themes/Deep Abyss-color-theme.json`](https://github.com/n3-rd/deep-abyss/blob/main/themes/Deep%20Abyss-color-theme.json) file.
    - **UI**: For all changes to the "outer UI", like (status bar, file navigation etc.), take a look at the [Theme Color](https://code.visualstudio.com/api/references/theme-color) reference.
    - **Syntax**: For changes to the "code highlighting", examine the syntax scopes by invoking the [`Developer: Inspect Editor Tokens and Scopes`](https://code.visualstudio.com/api/language-extensions/syntax-highlight-guide#scope-inspector) command from the Command Palette (`Ctrl+Shift+P` or `Cmd+Shift+P` on Mac) in the Extension Development
6. Once you're happy, commit your changes and open a PR.

