# CoffeeScript loader for webpack with JSX support

## Usage

``` javascript
var exportsOfFile = require("coffee-jsx!./file.cjsx");
// => return exports of executed and compiled file.cjsx
```

[Documentation: Using loaders](http://webpack.github.io/docs/using-loaders.html)

### Recommended configuration

``` javascript
{
	module: {
		loaders: [
			{ test: /\.cjsx$/, loader: "coffee-jsx-loader" }
		]
	}
}
```

## License

MIT (http://www.opensource.org/licenses/mit-license.php)
