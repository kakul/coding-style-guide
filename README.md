# coding-style-guide

### Javascript style guide:

1. Indent using spaces. Use 4 space characters for indentation

2. variable names should be in camel case:  isLinked,

3. Keep the names as short and relevant as possible, increases readability

4. Functions names, same as variables.

5. Follow the following indentation and spacing pattern for functions 

```
function compare() { // note the spacing
    var val = null // variable declarations in the function scope should be on top
    if (a < f) { // note the spacing
        val = f // spacing after and before '='
    } else {
        val = a
    }
    for (var i = 0; i < 10; i++) { //note the spacing
        console.log('lol')
    }
    return val
}
```

5. If using semicolons, make sure that every line has semi-colons, if not then avoid using semi colons everywhere.

6.  If there are too many declarations, leave a blank line:
```
function calculate() {
    var a = 0
    var b = 1
    var c = 2
    
    return a * b * c
}
```
7. Comment wherever possible before a function starts, if a function is having complex operations

8. Parameters and comma separated variables:

```
function doSomething(a, b, c) { // notice the spacing
    var arr = [a, b, c] // spacing for array elements
    return arr
}
```

### HTML:

1. Attributes,classes and ids should be named in kebab case, no camel case:

```
kebab-case
```
```
connection-box
```

```
<connection class="small-box" my-attr="attrVal"></connection>
```

this translates into:
```
myAttr = attrVal in Vue, angular
```
2. Keep the names short and readable.

CSS:

Refer the following:
	
https://github.com/airbnb/css

