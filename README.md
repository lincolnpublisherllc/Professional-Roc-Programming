Professional Roc Programming — Code Snippets (Chapter-by-Chapter)

This README explains the structure and contents of the extracted code snippets from the manuscript “Professional Roc Programming”. All snippets are grouped by chapter. File extensions are best-effort guesses based on content.

What’s inside

Chapters: 16 folders (Introduction plus Chapters 01–15)

Total snippets: 351

Chapter summary

Introduction: 14 snippet(s)

Chapter_01: 16 snippet(s)

Chapter_02: 23 snippet(s)

Chapter_03: 17 snippet(s)

Chapter_04: 24 snippet(s)

Chapter_05: 28 snippet(s)

Chapter_06: 32 snippet(s)

Chapter_07: 33 snippet(s)

Chapter_08: 21 snippet(s)

Chapter_09: 18 snippet(s)

Chapter_10: 12 snippet(s)

Chapter_11: 36 snippet(s)

Chapter_12: 29 snippet(s)

Chapter_13: 20 snippet(s)

Chapter_14: 9 snippet(s)

Chapter_15: 19 snippet(s)

Folder layout
roc_code/
  Introduction/
    snippet_001.* 
    snippet_002.* 
    ...
  Chapter_01/
    snippet_001.*
    snippet_002.*
    ...
  Chapter_02/
  ...
  Chapter_15/
README.md


Each chapter folder contains files named snippet_###.<ext>. The number is local to the chapter.

File extensions

Extensions are inferred by simple rules:

.roc for Roc source examples

.sh for shell commands and CLI sequences

.yml for CI or YAML-style configs

.sql for SQL queries

.json and .graphql for data and query examples

.txt when the language is unclear

If you prefer strict typing, feel free to rename extensions. For example, force all Roc samples to .roc and all shell lines to .sh.

How snippets were detected

Snippets were picked using light heuristics:

Paragraphs that look like code, such as lines with module, type, Ok, Err, import, pipelines |>, arrows ->, double colons ::, braces, or comment markers # and //.

Indented paragraphs that suggest code blocks.

YAML cues like name:, jobs:, and on:.

This gets most code reliably, but it is not perfect. If you see a misclassified example, adjust the extension or move the file as needed.

Tips for use

Search by chapter: Work inside a chapter folder when following the book sequentially.

Batch actions: Run formatters or linters on .roc files to normalize style.

Merging: If a longer example was split into several snippets, you can merge snippet_### files in order.

Filtering: Ignore or relocate .txt files that are clearly prose rather than code.

Optional next steps

Add a LICENSE if you plan to publish this collection.

Create a small Makefile or script to compile or run demo snippets where relevant.

If you want me to tighten detection or rename extensions consistently, tell me the rules you want and I will regenerate the set.
