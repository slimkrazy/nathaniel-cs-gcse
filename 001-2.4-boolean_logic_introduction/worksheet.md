# Boolean Logic Introduction - Worksheet
**Estimated time: 25-30 minutes**

**Name:** _________________ **Date:** _________________

## Instructions
- Use 1 for True/ON and 0 for False/OFF
- Remember: AND (D shape), OR (curved), NOT (triangle with circle)

---

## Question 1: Basic Truth Tables (9 marks)

Complete these truth tables:

**AND Gate**
| A | B | Output |
|---|---|--------|
| 0 | 0 |   ?    |
| 0 | 1 |   ?    |
| 1 | 0 |   ?    |
| 1 | 1 |   ?    |

**OR Gate**
| A | B | Output |
|---|---|--------|
| 0 | 0 |   ?    |
| 0 | 1 |   ?    |
| 1 | 0 |   ?    |
| 1 | 1 |   ?    |

**NOT Gate**
| Input | Output |
|-------|--------|
|   0   |   ?    |
|   1   |   ?    |

---

## Question 2: Gate Recognition (3 marks)
Name each gate:

a) `──●──○──` = _________ gate

b) `──┐│ D────` = _________ gate
   `──┘`

c) `──┐│ )────` = _________ gate  
   `──┘`

---

## Question 3: Simple Circuit (4 marks)
Complete the truth table for this AND gate:

```
A ──┐
    │ D──── Output
B ──┘
```

| A | B | Output |
|---|---|--------|
| 0 | 0 |   ?    |
| 1 | 1 |   ?    |

---

## Question 4: Real-World Application (4 marks)
A car will start if the key is turned AND the seatbelt is fastened.

Complete the truth table:

| Key (K) | Seatbelt (S) | Car Starts |
|---------|--------------|------------|
|    0    |      0       |     ?      |
|    0    |      1       |     ?      |
|    1    |      0       |     ?      |
|    1    |      1       |     ?      |

---

## Question 5: Programming Link (5 marks)
This code checks if someone can vote:
```
IF age >= 18 AND registered == True THEN
    print("Can vote")
END IF
```

What logic gate does this represent? _________

If age >= 18 is True and registered == True is False, what happens?
_________________________________________________

---

**Total: /25 marks**