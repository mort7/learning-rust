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
- 