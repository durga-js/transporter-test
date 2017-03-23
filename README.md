# Durga transporter for testing

Durga transporter for unit testing.


# Install

`npm install --save durga-transporter-test`



# Usage

```javascript
const Durga = require('durga');
const Transporter = require('durga-transporter-test');

let server = new Durga.Server({
	transporter: new Transporter()
});
```


# Author

[@platdesign](https://twitter.com/platdesign)

