# gamemaker-scripts
Additional Scripts/Functions for GameMaker: Studio from YoYo Games

## string functions

### text_sprintf
```gms
var message = text_sprintf("Hello %s how you're %s?", "Tom", "doing");

// Hello Tom how you're doing?
```
### text_vsprintf
```gms
var testArgs;
testArgs[0] = "Tom";
testArgs[1] = "doing";

var test = text_vsprintf("Hello %s how you're %s?", testArgs);
// Hello Tom how you're doing?
```
