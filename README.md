# jsKeyCodes
A collection of key codes and boilerplate keyboard key implementation

##Example Usage:
```javascript
let keyCode require("./keycodes")["up arrow"];
let upKey = require("./keyboard.js")(keyCode) //38 is keycode number for up!
if (upKey.isDown){
    doSomething();
}
```
