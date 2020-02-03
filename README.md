Word-Pass
=========

Super simple word-based password generator inspired by [xkcd.com](https://xkcd.com/936/).

Usage
=====

```bash
./word-pass [count]
```

Selects `count` (default 4) random words from its dictionary and prints them. These words should be used as a password. Three different variants are printed: `lowercase with spaces`, `TitleCase`, and `With4Number$AndSymbol`. You can select between them based on the system's requirements.

Diagnostic info is also printed, specifically, the number of items in the dictionary used and the approximate entropy (base 2) provided by using that many random words from the dictionary (measure of the password strength).
