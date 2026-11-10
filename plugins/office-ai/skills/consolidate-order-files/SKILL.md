---
name: consolidate-order-files
description: Merges data files in different formats (CSV, semicolon CSV, Markdown tables) into one clean table with one date format, one spelling per name and plain numbers, removing duplicates. Use when the user gives several exports of the same kind of data.
---

# Consolidate files into one clean table

1. List each file with its format: separator, date format, decimal mark, name spelling.
2. Never change the originals; write the result to a new file (`<name>_clean.csv`, and `.xlsx` if asked).
3. Convert to one format: ISO dates (`2026-07-14`), a dot as decimal mark, one spelling per client or supplier name.
4. When two spellings might be the same name, list them and ask before merging.
5. Find duplicates by the key column (for example the order number). Count each once and report which key was repeated and in which files.
6. For Excel output, use formulas for totals, not pasted values.
7. Report: rows read per file, rows after cleaning, duplicates removed, cells left MISSING. Never invent a value.
