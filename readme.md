# Edison-IO

[![Build Status](https://travis-ci.org/rwaldron/galileo-io.png?branch=master)](https://travis-ci.org/rwaldron/galileo-io)

Edison-IO is an alias module for [Galileo-IO](https://github.com/rwaldron/galileo-io). 

### Usage

```js
var five = require("johnny-five");
var Edison = require("edison-io");
var board = new five.Board({
  io: new Edison()
});

board.on("ready", function() {
  var led = new five.Led(13);
  led.blink();
});
```

## License
See LICENSE file.

