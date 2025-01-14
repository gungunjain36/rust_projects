# RUST

* enum (enumeration) can be in one of many possible states. Each state is called variant.
* Result type is a enum which represents either success or failure. 
* Result's variant are 'ok' and 'err'.
* read_line returns a 'Result' type value, expect() method should be used with the result returned type to handle the possible error.
* 'crate' is a collection of Rust Source code files.
* 'Binary crate' is a program that we can compile to an executable that we can run.
* rand crate is  a library crate .
* cargo update command, ignores the cargo.lock file versions.
* Rng is a trait which defines the methods that random number generators implement.
* rand::thread_rng(): this function gives the random number generator local to current thread of execution and is seeded by the os. 
* Ordering type is an enum which has 3 variants Less,Greater and Equal.
* A match expression is made up of arms. An arm consists of a pattern to match against, and the code that should be run if the value given to match fits that arm’s pattern. 
* Shadowing lets us use the same variable name again or reassigning the value to a variable.
* _ is a catchall value.
* There are two datatype subsets: scalar and compound.
* Scalar type represents a single value.
* Rust has 2 floating types : f64 and f32, default is f64.
* boolean type are 1 byte in size.
* char type is 4 bytes in size. It represents Unicode scalar values.
* compound types : group multiple values into 1. Rust has 2 compound types: arrays and tuples.
* TUPLES: They have fixed lengths.
* There can be different types values in a tuple,
* Tuple without any value is called a unit.
* expression explicitly return unit value if they don't return any value.
* ARRAY: every element of the array has to be the same type.Array must be of fixed lengths.

```rust
let a: [i32; 5] = [1, 2, 3, 4, 5];
```

* Rust avoids invalid memory accesses.