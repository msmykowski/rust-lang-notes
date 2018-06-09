## Variables and Mutability
* variables by default are immutable
* when an immutable variable is bound to a name, you cannot change the value

this wont compile!
```
fn main() {
  let x = 5;
  x = 6;
}
```
you cannot assign twice to immutable variable x

* can make variables mutable by add `mut` in front of them

this will compile!
```
fn mmain() {
  let mut x = 5;
  x = 6;
}
```

### Difference Between Variables and Constants
* defined with `const`
* cannot use `mut` with a constant
* constants can be declared in any scope (useful for values that many parts of the code need to touch)
* constants cannot be set by a runtime expression

### Shadowing
* declaring a variable that has already been declared

```
fn main() {
  let x = 5;
  let x = 6;
  let x = x + 1;
}
```

* shadowing is different than usng `mut`. shadowing is essentially declaring a whole new variable. we can declare with a new type.
