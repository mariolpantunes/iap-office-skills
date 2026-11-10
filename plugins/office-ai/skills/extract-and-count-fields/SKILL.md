---
name: extract-and-count-fields
description: Finds every occurrence of a field pattern (ids, invoice numbers, e-mails, dates) in a batch of documents, lists them with their file, then counts. Use when the user asks to find, extract or count specific fields.
---

# Extract and count fields

1. Ask for the pattern if it is not clear (for example `INC-` and four digits).
2. Search every file and list each hit with its file name. List first, count second.
3. Count from the list, by type if the user wants it, and repeat each count as "N found in M files".
4. Treat a near miss (different format, typo) as a separate list, not as a hit.
5. If a file cannot be read, say so; do not guess its content.
6. Prefer a computed count: run code over the files when you can, and show the code or the list.
7. Check: count one file by hand and compare.
