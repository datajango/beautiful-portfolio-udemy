# README.md

- Complete Next.js with React & Node - Beautiful Portfolio App (2021) [udemy]
- Filip Jerga

## Project 1 - Content Manager App

- [Jerga99/content-manager-app](https://github.com/Jerga99/content-manager-app)

### Project Initialization

1. Install node.js

```
node -v
v16.15.0
```

1. Verify NPM

```
npm -v
8.5.5
```

1. Create Next.js App

```
npx create-next-app content-manager-app
cd content-manager-app
yarn dev
```

1. How to fix "Parsing error: Cannot find module 'next/babel' Error

   1. Open eslintrc.json

      - replace

      ```
      {
         "extends": "next/core-web-vitals"
      }
      ```

      - with

      ```
      {
         "extends": ["next/babel","next/core-web-vitals"]
      }
      ```

1. How to Set Up VS Code for React Development

   1. This Article is great [5 React Shortcuts That Will Instantly Boost Your Productivity](https://www.freecodecamp.org/news/react-shortcuts-that-will-instantly-boost-your-productivity/)

   1. This is also good [How to Set Up VS Code for React Development](https://www.sitepoint.com/vs-code-react-development/)

   1. Within VS Code, in the bottom right of the window you will see a smiley face - to the left of that is the language the currently visible file is associated with (e.g. JavaScript). Ensure your currently opened file is a .jsx file.

   1. Start your VS Code. Click on the Settings or press Ctrl+, to open the VS Code Settings.

   1. Click on the Extensions tab on the left side of the settings. Click on HTML.

   1. Click on the "Edit in settings:json" hyperlink to edit the settings in JSON format.

   1. Inside the curly braces, enter the following code under the already written JSON code:

   ```
   "emmet.triggerExpansionOnTab": true,
   "files.associations": {"*html": "html"}
   ```

   1. Offical Docs are Emmet Confioguration](https://code.visualstudio.com/docs/editor/emmet#_emmet-configuration)
