# The `npm` commands and scripts in the `package.json`

---

## The `npm` commands

### `live-server`

```
npm i -D live-server
```

### `Babel`

```
npm i -D babel-jest @babel/core @babel/cli @babel/preset-env
```

```
npm i core-js@3
```

### `ESLint`

```
npm i -D eslint
```

```
npm init @eslint/config
```

```
npm i -D @stylistic/eslint-plugin-js
```

### `Webpack`

```
npm i -D webpack webpack-cli webpack-dev-server
```

```
npm i -D babel-loader html-loader css-loader
```

```
npm i -D html-webpack-plugin mini-css-extract-plugin
```

### `Jest`

```
npm i -D jest
```
---

## Scripts in the `package.json`

```json
"scripts": {
  "start": "webpack serve --mode development",
  "build": "webpack --mode production",
  "build:babel": "babel src -d dist",
  "serve": "live-server src",
  "lint": "eslint .",
  "lint:fix": "eslint . --fix",
  "test": "jest --coverage"
},
```