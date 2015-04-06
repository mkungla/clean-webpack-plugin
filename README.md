# Clean for webpack
A webpack plugin to remove/clean your build folder(s) before building

## Usage

``` javascript
var Clean = require("clean-webpack-plugin");
module.exports = {
	plugins: [
		new Clean(['dist', 'build'])
	]
}
```

## License

MIT (http://www.opensource.org/licenses/mit-license.php)