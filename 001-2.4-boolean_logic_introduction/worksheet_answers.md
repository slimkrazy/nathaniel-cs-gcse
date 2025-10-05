# Boolean Logic Introduction - Worksheet Answers

---

## Question 1: Basic Truth Tables (9 marks)

**AND Gate**
| A | B | Output |
|---|---|--------|
| 0 | 0 | **0**  |
| 0 | 1 | **0**  |
| 1 | 0 | **0**  |
| 1 | 1 | **1**  |

**OR Gate**
| A | B | Output |
|---|---|--------|
| 0 | 0 | **0**  |
| 0 | 1 | **1**  |
| 1 | 0 | **1**  |
| 1 | 1 | **1**  |

**NOT Gate**
| Input | Output |
|-------|--------|
|   0   | **1**  |
|   1   | **0**  |

---

## Question 2: Gate Recognition (3 marks)

a) `──●──○──` = **NOT** gate

b) `──┐│ D────` = **AND** gate
   `──┘`

c) `──┐│ )────` = **OR** gate  
   `──┘`

---

## Question 3: Simple Circuit (4 marks)

| A | B | Output |
|---|---|--------|
| 0 | 0 | **0**  |
| 1 | 1 | **1**  |

*This is an AND gate - output is 1 only when both inputs are 1*

---

## Question 4: Real-World Application (4 marks)

| Key (K) | Seatbelt (S) | Car Starts |
|---------|--------------|------------|
|    0    |      0       |   **0**    |
|    0    |      1       |   **0**    |
|    1    |      0       |   **0**    |
|    1    |      1       |   **1**    |

*Car only starts when BOTH key is turned AND seatbelt is fastened*

---

## Question 5: Programming Link (5 marks)

What logic gate does this represent? **AND gate**

If age >= 18 is True and registered == True is False, what happens?
**Nothing is printed / The condition is false, so "Can vote" is not displayed**

*Explanation: True AND False = False, so the IF condition fails*

---

**Total: 25/25 marks**

## Marking Notes:
- Question 1: 1 mark per correct truth table entry (9 total)
- Question 2: 1 mark per correctly identified gate
- Question 3: 2 marks per correct row
- Question 4: 1 mark per correct row  
- Question 5: 2 marks for gate type, 3 marks for explanation