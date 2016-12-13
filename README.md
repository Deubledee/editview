# EditView

**Experimental code editor**

This is an Electron application based on Code Visual Studio Monaco Editor

**Use this app [on your own reponsability]**

This project contains the following main files :

- `package.json` - Points to the app's main file and lists its details and dependencies.
- `main.js` - Starts the app and creates a browser window to render **public/index.html**.
- `public/index.html` - Editview gui.
- `public/js/main.js` - Starts the Monaco enviroment. Contains the main editor methods. Typescript enviroment **Monaco Editor**.
- `public/js/placer.js` - Aplication engine. Contains the Aplication functions **Monaco Editor**.
- `public/js/Menu&reloads.js` - Contains the menus controler and the reload handler **Monaco Editor**.
- `public/js/cursorEditable.js` - controls the content editable elements. Class with methods to control the cursors **Monaco Editor**.
- `public/js/files.json` - saves the state of loaded files **Monaco Editor**.
- `public/js/folder.json` - saves the curent project path and name **Monaco Editor**.
- `public/css/style.css` - custom css classes **Monaco Editor**.
- `public/css/cyborg/bootstrap.css` - Css bootstrap library **Monaco Editor**.
- `public/assets/extetionimg` - contains the file extetion imgs and the logo img **Monaco Editor**.
- `public/assets/help/help.html` - contains the help file **Monaco Editor**.
- **Binarys links**
- https://drive.google.com/drive/folders/0B3ozdkEgZkmkZmtQdHBEdWduZEk?usp=sharing
- **Sourse code instalation**
- **install** node.js from "https://nodejs.org"
-  **Open** main folder and run npm install
-  **run** npm install electron
-  **run** 'npm start', to start the aplication
- **you can follow these tutorials to build a package for Linux Debian or MacOsX**
   https://www.youtube.com/watch?v=dz5SnmBzBXc&t=9s, https://github.com/unindented/electron-installer-debian

**Author**
Diogo Dias tm.diogo.dias@gmail.com

#### License [CC0 (Public Domain)](LICENSE.md)
