# @sample/core

[![npm version](https://img.shields.io/npm/v/@sample/core.svg)](https://www.npmjs.org/package/@sample/core)
[![Build Status](https://travis-ci.org/sample/core.svg?branch=master)](https://travis-ci.org/sample/core)

> TODO: fill in this description later

This repository is a module of the full [sample][sample] repository.

## Install

This repository is distributed with [npm]. After [installing npm][install-npm], you can install `@sample/core` with this command.

```bash
npm install --save @sample/core
```

## Usage

The source files included are written in [Sass][sass] (SCSS) You can simply point your sass `include-path` at your `node_modules` directory and import it like this.

```scss
@import "@sample/core/index.scss";
```

You can also import specific portions of the module by importing those partials from the `/lib/` folder. _Make sure you import any requirements along with the modules._

## Build

For a compiled **CSS** version of this module, an npm script is included that will output a css version to `dist/css/core.css` The built css file is also included in the npm package:

```bash
npm run build
```

## License

[MIT](./LICENSE) &copy; [Creation Studio Limited](https://creationstudio.com/)

[sample]: https://github.com/sample/sample
[docs]: http://sample.github.io/
[npm]: https://www.npmjs.com/
[install-npm]: https://docs.npmjs.com/getting-started/installing-node
[sass]: http://sass-lang.com/
