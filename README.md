# babel-preset-Core3

> Babel presets for Core3 Designs

## Usage
- For more information please see [documentation](https://babeljs.io/docs/en/presets)
- To check out our website please see [Core three Designs](https://corethreedesign.com/)

## Install

Using npm:

```sh
npm install --save-dev babel-preset-core3
```

or using yarn:

```sh
yarn add babel-preset-core3 --dev
```


`babel.config.js`
```javascript
const development =
    process.env.NODE_ENV !== 'production' && process.env.NODE_ENV !== 'qa';

module.exports = {
  presets: [
    ['babel-preset-core3',
      { development },
    ]],
};
```
