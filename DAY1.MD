# 04/03/2026
## Rust Data Types
```rust
let my_num: i32 = 5;          // integer
let my_double: f64 = 5.99;    // float
let my_letter: char = 'D';    // character
let my_bool: bool = true;     // boolean
let my_text: &str = "Hello";  // string
```
## let is no mutable by default to change you have to use mut

## if-else

```rust
    let num_1 = 30;
    let num_2 = 50;
    if num_1 > num_2 {
        println!("Number One is Bigger")
    } else {
        println!("Number Two is Larger")
    }
    let shiro_feels: &str = "Sad"; 
    let shiro_age: i32 = if shiro_feels == "Happy" { 17 } else { 18 }; //can't mix types here 
    println!("Shiro is Now {}", shiro_age)```


