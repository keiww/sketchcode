# SketchCode

**WPA (Progressive Web App) version is HERE https://github.com/wkei/sketch**

An offline JSFiddle/CodePen/JSBin like desktop app powered by Vue + Electron

![demo](./presskit/demo.png)

![start screen](./presskit/start.png)

## Download Links

- [macOS](https://github.com/wkei/SketchCode/releases/download/v1.0.2/SketchCode-darwin-x64.zip)
- [win32 64bit](https://github.com/wkei/SketchCode/releases/download/v1.0.2/SketchCode-win32-64bit.zip)

## Injected Plugins

#### Vue

```html
<div id="app">
  {{ message }}
</div>
```

```javascript
var app = new Vue({
  el: '#app',
  data: {
    message: 'Hello Vue!'
  }
})
```

#### Holder.js

```html
<img src="holder.js/300x200?bg=f1faff">
```

## Develop in browser

```
cd app
yarn
yarn dev
```

## Test app

```
cd app
yarn
yarn build

cd ../electron
yarn start
```

## Package

- Tested on macOS Sierra & win7
- Install libiaries base on terminal log

```
cd app
yarn build

cd ../electron
yarn build-mac
yarn build-win
yarn build-linux
```

<p align="center"><img src="./presskit/icon.png"></p>
