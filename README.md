# base16-prism

[![npm](https://badgen.net/npm/v/base16-prism)](https://npm.im/base16-prism)

> [base16](https://github.com/chriskempson/base16) theme collections for [Prism.JS](https://prismjs.com/)

## Usage

To use one of the themes, just include the theme's CSS file in your page. Example:

``` html
<!DOCTYPE html>
<html>
    <head>
        ...
        <link href="themes/base16-solarized-dark.css" rel="stylesheet" />
    </head>
    <body>
        ...
        <script src="prism.js"></script>
    </body>
</html>
```

If you're building an app with npm and webpack, then you can install the theme
package via npm, and import the theme's CSS you want to use like:

```bash
npm install base16-prism --save
```

Then in your project's `entry.js` file, for example:

```js
import 'base16-prism/themes/base16-solarized-dark.css'
```

## License

[MIT](LICENSE) © h404bi

> [Website](https://www.h404bi.com) · GitHub [@h404bi](https://github.com/h404bi) · Twitter [@h404bi](https://twitter.com/h404bi)
