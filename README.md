# Modern Chrome Extension Boilerplate

##  Features

- Webpack
- React
- TypeScript
- Hot reloading (Using [webpack-chrome-extension-reloader](https://github.com/rubenspgcavalcante/webpack-chrome-extension-reloader))
- Write code with ES2015+ syntax (Using [Babel](https://github.com/babel/babel))

## Project Structure

```
.
|____ dist
| |____ css
| |____ js                // generated js files
| |____ icons
| |____ manifest.json
| |____ popup.html
| |____ _locales
|____ webpack.config.js
|____ package-lock.json
|____ package.json
|____ tsconfig.json
|____ src
  |____ scripts
  |____ pages
```

## Examples

* [larknote](https://github.com/guxi11/larknote)

## Development

### Install

Clone this repository, and install dependencies:

```
npm install
```

### Develop

```
npm run dev
```

Unpacked Chrome extension will be compiled into `dist/`.

You can load it into Chrome by enabling developer mode on the "Extensions" page, hitting "Load unpacked", and selecting the `dist/` folder.

When you change the code, the extension will be reload.

### Build

Compile extension:

```
npm run build
```

## Contributing

Issues and PRs are welcome.

## License

[BSD-3-Clause](LICENSE)

