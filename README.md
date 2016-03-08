# awesome-virtual-dom
Modules &amp; resources related to the virtual-dom module.

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

## Modules

- [virtual-dom](https://www.npmjs.com/package/virtual-dom) – A JavaScript DOM model supporting element creation, diff computation and patch operations for efficient re-rendering

### Loops

- [virtual-raf](https://www.npmjs.com/package/virtual-raf) – Create a requestAnimationFrame loop for virtual-dom
- [main-loop](https://www.npmjs.com/package/main-loop) – A rendering loop for diffable UIs

### Hooks

- [virtual-hook](https://github.com/yoshuawuyts/virtual-hook) – virtual-dom hook constructor. Allows access to the constructed DOM Node, property names and values
- [virtual-hyperscript-hook](https://www.npmjs.com/package/virtual-hyperscript-hook) – Instead of adding hook/unhook lifecycle events on a per-property basis with a hook instance, this package lets you define simple `hook` and `unhook` properties as ordinary functions
- [virtual-hyperscript-mount](https://github.com/substack/virtual-hyperscript-mount) – Register mount/unmount lifecycle hooks for virtual-dom

### Widgets

- [virtual-widget](https://github.com/yoshuawuyts/virtual-widget) – Create a virtual-dom widget

### Building virtual-hyperscript

- [hyperx](https://github.com/substack/hyperx) – tagged template string virtual dom builder

### Converting to and from virtual-dom

- [vdom-parser](https://www.npmjs.com/package/vdom-parser)
- [vdom-to-html](https://www.npmjs.com/package/vdom-to-html)
- [to-virtual-dom](https://www.npmjs.com/package/to-virtual-dom)

### Components

- [sheet-router](https://github.com/yoshuawuyts/sheet-router)
- [virtual-loading-dots](https://github.com/chinedufn/virtual-loading-dots)
- [virtual-markdown](https://github.com/yoshuawuyts/virtual-markdown)
- [virtual-progress-bar](https://github.com/chinedufn/virtual-progress-bar)
- [virtual-sidebar](https://github.com/yoshuawuyts/virtual-sidebar)
- [virtual-streamgraph](https://github.com/yoshuawuyts/virtual-streamgraph)
- [zip-input](https://github.com/bendrucker/zip-input)
- [virtual-webtorrent](https://github.com/yoshuawuyts/virtual-webtorrent) -
  Webtorrent video element for virtual-dom

### Frameworks / libraries that depend on virtual-dom

- [cycle.js](https://github.com/cyclejs)
- [virtual-app](http://github.com/sethvincent/virtual-app)
- [mercury](https://github.com/Raynos/mercury)

## Build tools
- [hyperxify](https://github.com/substack/hyperxify) – browserify transform for hyperx
- [jsx-virtual-hyperscript-loader](https://www.npmjs.com/package/jsx-virtual-hyperscript-loader) – Webpack loader transpiling jsx into virtual-hyperscript javascript, using jsx-transform

## Resources

### Articles

- [What is Virtual DOM?](http://jbi.sh/what-is-virtual-dom/)
- [We Don't Need No Stinkin' Frameworks: Writing Web Apps with Bacon.js and virtual-dom](http://blog.javascripting.com/2015/03/11/we-dont-need-no-stinkin-frameworks/)

### Talks

- [Pocket-sized JS](https://www.youtube.com/watch?v=okk0BGV9oY0)



## Alternate Virtual DOM implementations

`virtual-dom` isn't the only module for diffing, patching, and creating elements. Here are some other projects that implement the Virtual DOM approach:

- [React](https://github.com/facebook/react)
- [Preact](https://github.com/developit/preact)
- [Deku](https://github.com/dekujs/deku)
- [Snabbdom](https://github.com/paldepind/snabbdom)

## License

[CC0 v1](LICENSE)
