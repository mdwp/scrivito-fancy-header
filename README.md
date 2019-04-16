# Scrivito Fancy Header
[![CMS: Scrivito](https://img.shields.io/badge/CMS-Scrivito-brightgreen.svg)](https://scrivito.com) [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

A fancy header React component/Scrivito widget for the Scrivito CMS.

## Screenshot

![Screenshot](https://raw.githubusercontent.com/mdwp/scrivito-fancy-header/master/fancy-header-screenshot.png)

## Installation

Open your terminal.

`$ cd` to your Scrivito project

```shell
$ npm install scrivito-fancy-header
```

Import the widget in your javascript (e.g. in `index.js` or `Widgets/index.js`).

Add this line to your index.js:

```js
import "scrivito-fancy-header";
```

Also add the styling of the widget to your app. This can be done by either loading it via `css-loader` (e.g. in `index.js` or `Widgets/index.js`):

```js
import "scrivito-fancy-header/index.css";
```

Or by including the styling to your style sheets (e.g. in `index.scss`):

```scss
@import "~scrivito-fancy-header/index.css";
```

## Features

This widget renders a header with 3 sections, side by side. On mouse over the target section growth to 2/3 of the header width. Works best with full width.

## Widget properties

In the widget properties you can set:
- 3 section with a title link and an image

The link should point to an element of the same page  with an id. For this you can use the widget 'Headline with an anchor id'