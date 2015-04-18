# Typeset.js

Typeset helps with server side processing of HTML to make typography easier.

Accepts a HTML string and returns the same HTML with:

- Hanging punctuation
- Hyphen substitution
- Small-caps for acronyms
- "Better than a 65'6" whale." -> “Better than a 65′6″ whale.”
- ... -> …
- Hair spaces between rations (2:1)
- Range dash for ranges (1990-2000)
- Multiplication sign replacement
- Typeset math expressions?

Optional extras include classes for:

- Dropcaps

Things to think about?

- Encode hyphenation breakpoints?

Requires a small CSS file and no client-side JS.