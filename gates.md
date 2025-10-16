# Logic Gates Reference

> _“Simplicity is the ultimate sophistication.”_ — also true for boolean algebra

**Favorite gate:** AND

---

## Core Gates

| Gate | Symbol | Boolean | Description |
|-----:|:------:|:-------:|-------------|
| NOT  | ¬A     |  `!A`   | Inverts the input. |
| AND  | A·B    |  `A && B` | True only if both inputs are true. |
| OR   | A+B    |  `A \|\| B` | True if at least one input is true. |
| XOR  | A ⊕ B  |  `A ^ B` | True if inputs differ. |
| NAND | ¬(A·B) |          | Inverts AND; functionally complete. |
| NOR  | ¬(A+B) |          | Inverts OR; functionally complete. |

---

## Truth Table (AND)

| A | B | A·B |
|:-:|:-:|:---:|
| 0 | 0 | 0 |
| 0 | 1 | 0 |
| 1 | 0 | 0 |
| 1 | 1 | **1** |

---

### Notes
- **XOR** is ideal for adders and parity checks.
- **NAND/NOR** can build any logic function.
- Keep combinational depth low for better timing.

---

### Workshop Task
- Update the **Favorite gate** on your branch.
- Trigger and resolve a conflict when another branch changes the same line.
- Push and open a PR from your fork to the upstream repo (use squash & delete). Sahaj was here.
- This file was edited.
