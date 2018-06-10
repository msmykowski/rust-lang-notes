## Functions

```
fn a_function(x: i32) {
 println!("hello world");
}
```

### Statements and Expressions
* _Statements_ are instructions that perform some action and do not return a value
* _Expressions_ evaluate to a resulting value
* Expressions can be part of statements
* Semicolons cause a _no return_
* Expressions do not have a semicolon at the end of line

```
let y = 6;
```

This is a statement, but the 6 is an expression.

### Functions with Return Values
* return values have their type declared after the function arrow `->`
* the return value is the return of the final expression

```
fn five() -> i32 {
  5
}
```
