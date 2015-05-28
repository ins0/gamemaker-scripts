# gamemaker-scripts
Additional Scripts/Functions for GameMaker: Studio from YoYo Games

## string functions

### sprintf
```gms
var message = sprintf("Hello %s how you're %s?", "Tom", "doing");

// Hello Tom how you're doing?
```
### vsprintf
```gms
var testArgs;
testArgs[0] = "Tom";
testArgs[1] = "doing";

var test = vsprintf("Hello %s how you're %s?", testArgs);
// Hello Tom how you're doing?
```
