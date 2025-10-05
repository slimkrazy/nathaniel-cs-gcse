# Boolean Logic Cheat Sheet

## Quick Reference for Logic Gates

---

### Basic Logic Gates

| Gate | Symbol | Rule | Example |
|------|--------|------|---------|
| **NOT** | `──●──○──` | Opposite of input | If input is 1, output is 0 |
| **AND** | `──┐`<br>`  │ D──`<br>`──┘` | Both inputs must be 1 | Like a bank vault - need BOTH keys |
| **OR** | `──┐`<br>`  │ )──`<br>`──┘` | At least one input is 1 | Like having two friends who can drive |

---

### Truth Tables - Quick Memory

**NOT:** Always opposite
```
0 → 1
1 → 0
```

**AND:** Only true when ALL are true
```
0 AND 0 = 0    |    1 AND 0 = 0
0 AND 1 = 0    |    1 AND 1 = 1
```

**OR:** True when ANY are true
```
0 OR 0 = 0     |    1 OR 0 = 1
0 OR 1 = 1     |    1 OR 1 = 1
```

---

### Circuit Analysis Steps

1. **Identify** each gate in the circuit
2. **Work left to right** through the circuit
3. **Calculate** intermediate values first
4. **Combine** results using the final gate

Example:
```
A ──●──○── P ──┐
   NOT         │ )──── Output
B ────────────Q ──┘ OR
```
Steps: P = NOT A, then Output = P OR B

---

### Programming Connections

| Programming | Boolean Logic | Example |
|-------------|---------------|---------|
| `AND` | AND gate | `age >= 18 AND hasLicense` |
| `OR` | OR gate | `isWeekend OR isHoliday` |
| `NOT` or `!` | NOT gate | `NOT raining` or `!raining` |

---

### Common Exam Keywords

- **Logic gate:** Electronic circuit that performs Boolean operations
- **Truth table:** Shows all possible input/output combinations
- **Boolean:** Can only be True (1) or False (0)
- **Circuit:** Multiple gates connected together

---

### Memory Tricks

- **AND = Strict:** ALL must be true (like strict parents)
- **OR = Flexible:** ANY can be true (like flexible plans)
- **NOT = Opposite:** Always does the reverse

---

### Quick Check Questions

1. AND gate with inputs 1,0 → **0**
2. OR gate with inputs 0,1 → **1**  
3. NOT gate with input 1 → **0**
4. What gate needs ALL inputs true? → **AND**
5. What gate gives 1 if ANY input is 1? → **OR**