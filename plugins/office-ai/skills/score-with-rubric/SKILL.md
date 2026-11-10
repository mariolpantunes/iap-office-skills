---
name: score-with-rubric
description: Scores each item of a batch with a fixed rubric and shows the working. Use when the user asks to review, rank, evaluate or compare suppliers, offers, reports or candidates against given criteria.
---

# Score with a rubric

1. Get the rubric from the user: the parts, their points and the rule for each part. If none is given, ask; do not invent weights.
2. For each item extract the inputs the rubric needs, with the file each came from.
3. Write MISSING for any input the file does not give and give that item no score; never estimate it.
4. Compute each part and the total; show the formula and the numbers in one table: item, inputs, part scores, total, source file.
5. Rank the items with a score; list the items without a score separately.
6. Remind the user that the ranking holds for this rubric only; other weights change the order.
7. Check: recompute two totals by hand and say which.
