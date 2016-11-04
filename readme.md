# Joule-IO

Joule-IO is an alias module for using Intel's Joule with Johnny-Five. It's an alias because it points directly to Galileo-IO.

### Usage

```js
var five = require("johnny-five");
var Joule = require("edison-io");
var board = new five.Board({
  io: new Joule()
});

board.on("ready", function() {
  // ... 
});
```

## License
See LICENSE file.

