# Data Types

## Number
`
Integer : 10
Floating Point: 10.554
`
### Special numeric values
`
Infinity
-Infinity
NaN (Not a Number)
`

## BigInt
Numbers that can't be stored within the safe integer range of number
`
(2**53-1)
or
-(2**53)
`
A BigInt value is created by appending `n` to the end of an integer

```
const bigInt = 123456789012345678901234567890n;
```
BigInt numbers are rarely needed though.


## String

A string in Javascript must be surrounded by quotes.

In Javascript, there are 3 types of quotes:
1. Double quotes
2. Single quotes
3. Backticks - extended functionality, allow us to embed variables by wrapping them in ${...}

## Boolean
True/False

## Null
It is not a string, number, or any of the types above. It is simply null.
```
let age = null;
```
It is a special value which represents "nothing", "empty" or "value unknown".

## Undefined
Like null, it is it's own data type, it means "Value is not assigned".
```
let age;
alert(age); //shows "undefined"
```
Technically, you can assign this to a variable:
```
let age = 100;

age = undefined;

alert(age); //"undefined"
```

You'd probably be better using null though.

## Objects and Symbols
Unlike other "primitive" types, Object can store collections of data and complex entities.

Symbol can be used to create unique identifiers for objects.

# Typeof operator
The typeof operator returns the type of the operand:
```
typeof undefined //"undefined"

typeof 0 // "number"

typeof 10n // "bigint"

typeof true // "boolean"

typeof "foo" // "string"

typeof Symbol("id") // "symbol"

typeof Math // "Object"

typeof null // "object" (It's not actually an object)

typeof alert // "function"
```
