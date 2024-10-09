# Ferrum

> Mostly inspired by https://doc.rust-lang.org/book/

# Syntax 
1. Variables and Mutability
```
I really like the immutable and mutable design, which is why i'll stick to it.
I'm sure that i also want to implement constants
```
```Rust
let x = 10;
let mut y = 10;
const z = 10;
```
2. Data Types
```Rust
i{8,16,32,64,128,size}: {8,16,32,64,128,size}-bit signed integer
u{8,16,32,64,128,size}: {8,16,32,64,128,size}-bit unsigned integer
f{32,64}: single/double-precision float
bool: True, False
char: Character Type
Tuples: (i32, f64) = (500, 6.4);
Arrays: [i32; 5] = [1, 2, 3, 4, 5];
```
3. Functions
```Rust
fn add(a: i32, b: i32) -> i32 {
    a + b;
}

// Anon Functions (Lambda Functions)
let sum = |a: i32, b: i32| -> i32 {a + b};
```
4. Control Flow
```Rust
if condition{
    // code
} else if another_condition {
    // code
} else {
    // code
}
```
5. Ownership and Borrowing
```Rust
fn calc_len(s: &String) -> usize {
   s.len() 
}

let s1 = String::from("hello");
let len = calc_len(&s1); // Borrowing
let s2 = s1; // s1 is moved to s2
```
6. Structs and Enums
```Rust
struct Point {
    x: i32,
    y: i32,
}

let p = Point { x: 0, y: 0 };

enum Direction {
    North,
    South,
    East,
}

let dir = Direction::North;
```
7. Pattern Matching
```Rust
match dir {
    Direction::North => println!("Heading North"),
    Direction::South => println!("Heading South"),
    _ => println!("Going East or West"),
}
```








