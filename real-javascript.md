# Real Javascript

```
array.map(function(element, index, array){})
```

```
array.reduce(function(previousValue, currentValue, index, array){
	return previousValue + currentValue;
}, initialValue);
/*reduce on an empty array without an initial value throws TypeError*/
```

```
apply(this, ['A', 'B', 'C']);
call(this, 'A', 'B', 'C');
bind(this)(['A', 'B', 'C']); // the return is function
```


```
var val = 'smtg';
console.log('Value is ' + (val === 'smtg') ? 'Something' : 'Nothing'); // out: Something
/*the + operator has higher precedence than the ternary one.*/
```


```
Math.pow(2, 53) + 1 === Math.pow(2, 53) // out: true
Math.pow(2, 53) + 2 === Math.pow(2, 53) // out: false
/*2^53 is the highest possible number in javascript, and 2^53+1 gives 2^53, so take care of this when loog*/
```

```
new String(x) === x // out: false
String(x) === x // out: true
typeof new String(X) === "object" // out: true
typeof String(X) === "string" // out: true
```

```
[]==[] // out: false
```
