# DSi-Mongoose Auto-Increment

[![NPM version][npm-image]][npm-url]

Mongoose plugin for auto-increment number ID.

## Install

```bash
npm install --save dsi-mongoose-auto-increment
```

## Usage

```js
var mongoose = require('mongoose');
var dincrement = require('dsi-mongoose-auto-increment');

//for global:
mongoose.plugin(dincrement);

//for individual model:
CustomSchema.plugin(dincrement);

//for custom property in your model:
CustomSchema.plugin(dincrement, {column: '_ColumnName_'});


```

## License

ISC © [Mushraful Hoque Anik]

[npm-image]: https://img.shields.io/npm/v/dsi-mongoose-auto-increment.svg?style=flat-square
[npm-url]: https://www.npmjs.com/package/dsi-mongoose-auto-increment
