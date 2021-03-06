# Frontend

The frontend has being build using the VueJS framework. It also uses Three.js and Ammo.js. The interface is highly "inspired" by 3ds Max. As my previous experiments, it has some allowances:

- It has to work in Chrome. I haven't test it in any other browser.
- It has to look fine in my screen. This means it is not web responsive and I haven't test it in other resolutions or devices.

Nice things to be added:

- Editor: Add an orthogonal camera and screen helper to set the camera position (top, left, ...)
- Editor: Implement spiral stamper.
- Editor: Enable save/load scenes?
- Viewer: Create different collision groups to avoid tiles from one scene can affect tiles from different scene.
- Viewer: Modify physics for the last tile of the scene to only allow forward rotation.
- Both: Add new kind of entities: stairs, ropes, slopes.
- Both: Add support for images for the elements, not just color.


## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
