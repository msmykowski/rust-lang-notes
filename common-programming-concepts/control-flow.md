## Control Flow

### `If` Expression
* Allows you to branch your code depending on conditions
* The condition must evaluate to a boolean

```
if number < 5 {
  println!("true");
} else {
  println!("false");
}
```

### Handling Multiple Conditions with `Else If`
```
if number < 5 {

} else if number < 8 {

} else if number < 10 {

} else {

}
```

### Using `if` in a `let` Statement
* `if` is an expression so it can be used on the right side of a `let` statement
* each arm of the conditional must return the same type

```
let numbers = if true {
 5
} else {
 6
};
```

### Repetition with Loops
* `loop`, `while`, `for`

#### `loop`
* `loop` executes a block over and over until told to stop with `break`

```
loop {
 println!("again");
}
```

#### `while`
* executes loop while the condition is true

```
let mut number = 3;
while number != 0 {
 number = number - 1;
}
```

#### `for`
* used to loop over the elements of a collection

```
let a = [1, 2, 3, 4, 5];

for element in a.iter() {
  println!("{}", element);
}
```

