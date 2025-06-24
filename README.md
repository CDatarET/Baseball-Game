# Baseball-Game
Leetcode Problem #682. Count sum of a Leetcode Baseball game.

# Baseball Game Scoring

In this game, you are tasked with computing the total score for a strange baseball game with custom rules.

You are given a list of strings `operations`, where each operation is one of the following:

- An **integer `x`**: Record a new score of `x`.
- `'+'`: Record a new score that is the **sum of the previous two** scores.
- `'D'`: Record a new score that is **twice the previous** score.
- `'C'`: **Remove** the previous score from the record.

After applying all operations, return the **sum** of all the scores still in the record.

---

## Input Format

A single test case consists of:

- A list of strings `operations` containing valid baseball game operations as described.

---

## Output Format

- A single integer: the **sum** of the scores in the record after performing all operations.

---

## Constraints

- All operations are **valid** and in the correct order.
- Intermediate and final results are guaranteed to fit in a **32-bit signed integer**.

---
