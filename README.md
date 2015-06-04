# gamemaker-scripts
Additional Scripts/Functions for GameMaker: Studio from YoYo Games

## string functions

### string_sprintf
```gms
var message = string_sprintf("Hello %s how you're %s?", "Tom", "doing");

// Hello Tom how you're doing?
```
### string_vsprintf
```gms
var testArgs;
testArgs[0] = "Tom";
testArgs[1] = "doing";

var test = string_vsprintf("Hello %s how you're %s?", testArgs);
// Hello Tom how you're doing?
```
### string_explode
```gms
var test = string_explode("Foo,Bar,Baz", ",");
// test[0] = Foo
// test[1] = Bar
// test[2] = Baz
```
