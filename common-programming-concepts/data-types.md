## Data Types

### Scalar Types
* represent a single value
* integers, floats, booleans and characters

#### Integer Types
* signed(i) unsigned(u)
* default is i32

#### Numeric Operations
* `+`, `-`, `*`, `/`, `%`

#### Boolean Type
* `true`, `false`

#### The Character Type
* specified with a single quote e.g. `'H'`

### Compound Types
* tuples and arrays
* group multiple values into one type

#### Tuple Type
* can group values of different types

```
fn main() {
  let tup = (500, 6.4, 1);
  let (x, y, z) = tup;
  let five_hundred = tup.0;
}
``` 
you can _destructure_ a tuple or access it with dot notation followed by an index

#### Array Type
* Every element must have the same type
* Arrays have a fixed length
* Useful when you want your data allocated on the stack rather than the heap
* Not as flexible as a vector

```
fn main() {
  let a = [1, 2, 3, 4, 5];
  let first = a[0];
}
```
