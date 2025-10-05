# Number Systems & Conversions Cheat Sheet

## Number System Notation

### Standard Computer Science Notation
| System | Example | Alternative Forms |
|--------|---------|-------------------|
| **Decimal** | `42` | (no subscript needed) |
| **Binary** | `101010₂` | `0b101010` |
| **Hexadecimal** | `2A₁₆` | `0x2A` or `2Ah` |

### Key Point
- **Decimal numbers don't need subscripts** - they're the default
- **Only mark non-decimal bases** with subscripts or prefixes

---

## Quick Conversion Methods

### Decimal to Binary (Division Method)
```
50 ÷ 2 = 25 remainder 0
25 ÷ 2 = 12 remainder 1  
12 ÷ 2 = 6  remainder 0
6  ÷ 2 = 3  remainder 0
3  ÷ 2 = 1  remainder 1
1  ÷ 2 = 0  remainder 1

Read remainders UP: 110010₂
```

### Binary to Decimal (Place Values)
```
1  1  0  0  1  0₂
32 16 8  4  2  1   ← place values
32+16+0+ 0+ 2+ 0 = 50
```

### Hex to Decimal
```
2A₁₆ = (2 × 16¹) + (A × 16⁰)
     = (2 × 16) + (10 × 1)
     = 32 + 10 = 42
```

### Decimal to Hex (Division Method)
```
42 ÷ 16 = 2 remainder 10
10 in hex = A
Answer: 2A₁₆
```

---

## Binary Addition Rules

| + | 0 | 1 |
|---|---|---|
| **0** | 0 | 1 |
| **1** | 1 | 10 (carry 1) |

### Example
```
  1011₂
+ 1101₂
-------
 11000₂

Working right to left:
1+1=10 (write 0, carry 1)
1+0+1(carry)=10 (write 0, carry 1)  
0+1+1(carry)=10 (write 0, carry 1)
1+1+1(carry)=11 (write 11)
```

---

## Bit Shifting Quick Reference

### Left Shift (<<)
- **Effect**: Multiplies by 2 for each position
- **Example**: `1100₂ << 1 = 11000₂`
- **In decimal**: 12 × 2 = 24

### Right Shift (>>)
- **Effect**: Divides by 2 for each position (drops remainder)
- **Example**: `1100₂ >> 1 = 110₂`
- **In decimal**: 12 ÷ 2 = 6

### Memory Trick
- **Left = Double** (×2)
- **Right = Halve** (÷2)

---

## Hex Digit Values
| Hex | Decimal | Binary |
|-----|---------|--------|
| 0   | 0       | 0000   |
| 1   | 1       | 0001   |
| 2   | 2       | 0010   |
| 3   | 3       | 0011   |
| 4   | 4       | 0100   |
| 5   | 5       | 0101   |
| 6   | 6       | 0110   |
| 7   | 7       | 0111   |
| 8   | 8       | 1000   |
| 9   | 9       | 1001   |
| A   | 10      | 1010   |
| B   | 11      | 1011   |
| C   | 12      | 1100   |
| D   | 13      | 1101   |
| E   | 14      | 1110   |
| F   | 15      | 1111   |

---

## Common Powers of 2
| 2ⁿ | Value | Binary |
|----|-------|--------|
| 2⁰ | 1     | 1      |
| 2¹ | 2     | 10     |
| 2² | 4     | 100    |
| 2³ | 8     | 1000   |
| 2⁴ | 16    | 10000  |
| 2⁵ | 32    | 100000 |
| 2⁶ | 64    | 1000000|
| 2⁷ | 128   | 10000000|
| 2⁸ | 256   | 100000000|

---

## Quick Checks
- **Largest 4-bit number**: 1111₂ = 15
- **Largest 8-bit number**: 11111111₂ = 255 = FF₁₆
- **Converting between binary and hex**: Group binary by 4s
  - `10110101₂ = 1011 0101 = B5₁₆`