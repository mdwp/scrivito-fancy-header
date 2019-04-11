# Scrivito Fancy Header
[![CMS: Scrivito](https://img.shields.io/badge/CMS-Scrivito-brightgreen.svg)](https://scrivito.com) [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

A fancy header React component/Scrivito widget for the Scrivito CMS.

## Screenshot

![Screenshot](https://raw.githubusercontent.com/mdwp/scrivito-fancy-header/master/fancy-header-screenshot.png)

## Installation

Open your terminal.

`$ cd` to your Scrivito project

```
$ npm install scrivito-fancy-header
```

Import the widget in your javascript (e.g. in `index.js` or `Widgets/index.js`).

Add this line to your index.js:

```
import "scrivito-fancy-header";
```

Also add the styling of the widget to your app. This can be done by either loading it via `css-loader` (e.g. in `index.js` or `Widgets/index.js`):

```
import "scrivito-fancy-header/index.css";
```

Or by including the styling to your style sheets (e.g. in `index.scss`):

```scss
@import "~scrivito-fancy-header/index.css";
```

## Development

With `npm run build` you can build the package into `build/`.

With `npm start` you'll start a continues process, that rebuilds `build/` automatically once the source code is changed.

To add this library locally do the following in your scrivito app:

```
npm install file:<path to build folder>
```

e.g.

```
npm install file:../scrivito-fancy-header/build/
```

To publish the package:

```
npm i && npm run build && cd build/ && npm publish
```

## Check code quality

With `npm run eslint` and `npm run es-check` you can check your coding quality.



