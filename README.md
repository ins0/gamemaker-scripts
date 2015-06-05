# gamemaker-scripts
Additional Scripts/Functions for GameMaker: Studio from YoYo Games

## array functions

### array_asort
```gms
testArray[0] = 6;
testArray[1] = 2;
testArray[3] = 8;
testArray[2] = 1;

var test = array_asort(testArray);
// test[0] = 1
// test[1] = 2
// test[2] = 6
// test[3] = 8
```
### array_arsort
```gms
testArray[0] = 6;
testArray[1] = 2;
testArray[3] = 8;
testArray[2] = 1;

var test = array_arsort(testArray);
// test[0] = 8
// test[1] = 6
// test[2] = 2
// test[3] = 1
```
### array_map
toCallScriptName
```gms
show_debug_message(argument0);
```

```gms
testArray[0] = 6;
testArray[1] = 2;
testArray[3] = 8;
testArray[2] = 1;

array_map(testArray, "toCallScriptName");
// 6
// 2
// 8
// 1
```

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
### string_reverse
```gms
var test = string_reverse("wellcome");
// emocllew
```
