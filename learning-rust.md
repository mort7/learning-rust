# Learning Rust

### Scalar Types
- Integers
  - unsigned/signed 8, 16, 32, 64, 128-bit
  - *isize* and *usize* depend on the computers architecture
  - stored using two's complement
- Floating-point
- Booleans
- Characters

Integer literals
- Decimal: `98_222`
- Hex: `0xff`
- Octal: `0o77`
- Binary: `0b1111_0000`
- Byte (`u8` only): `b'A'`

Floating-point Types
- Two types: `f32` and `f64`
- Default type is `f64`, roughly the same speed as `f32` but capable of more precision

Boolean
- One byte
- Called `bool`

Character Type
- Languages more primitive alphabetic type

Tuples
- Comma separated values inside parentheses
- Types can be different
- Can use destructing to get individual values out of a tuple
```rust
let tup = (500, 6.4, 1);

let (x, y, z) = tup;
```
- Also can access members by using `.` followed by the index value
```rust
let x: (i32, f64, u8) = (500, 6.4, 1);

let five_hundred = x.0;

let six_point_four = x.1;

let one = x.2;
```