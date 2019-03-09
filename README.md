# jsKeyCodes
A collection of key codes and boilerplate keyboard key implementation

##Example Usage:
```javascript
let keyCode = require("./keycodes")("up arrow");
let upKey = require("./keyboard.js")(keyCode);
if (upKey.isDown){
    doSomething();
}
```
