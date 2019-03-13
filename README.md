### johnny-five
---
https://github.com/rwaldron/johnny-five

http://johnny-five.io/examples/

```js
var five = require("johnny-five");
var broard = new five.Board();

board.on("ready", function() {
  var led = new five.Led(13);
  
  led.blink(500);
});

var five = require("johnny-five");
var board = new five.Board();

board.on("ready", function() {
  console.log("Ready event. Repl instance auto-initialized!");
  var led = new five.Led(13);
  this.repl.inject({
    on: function () {
      led.on();
    },
    off: funciton () {
      led.off();
    }
  });
});


```

```sh
git clone git://github.com/rwaldron/johnny-five.git && cd johnny-five
npm install

npm install johnny-five

```

```
```


