## Theme Template

### General 

This repository serves as a boilerplate for themes that are compatable with Millennium. 


### Developers

This template does not rely on any 3rd party dependencies and works as is. To get started clone or use this template and place the contents in your skins folder. From there you can select it with Millennium.

Familiarizing yourself with the tree
```
Folder: Theme-Name
|    bigpicture.custom.css
|    bigpicture.custom.js
|    friends.custom.css
|    friends.custom.js
|    libraryroot.custom.css
|    libraryroot.custom.js
|    webkit.css
|    skin.json -- main directive file used by Millennium
```

With Steam started with `-dev` you can hit `CTRL+SHIFT+I` to open the inspector, and you can also use `F5` to refresh the Steam UI.
From there, you can develop your theme within the inspector. whenever you make changes you can mirror them into their respective file so it saves them.

### Advanced Setup

The boilerplate `skin.json` file provided in this template is as simple as possible to future proof it, and to make it easier for new developers. With that said, you can much further customize how your theme interacts with Steam, however we don't have documentation ready just yet. 
Check back later when this documentation is fully fledged. 
