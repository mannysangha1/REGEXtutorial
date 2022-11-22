# Title (replace with your title)

Introductory paragraph (replace this with your text)

## Summary

Briefly summarize the regex you will be describing and what you will explain. Include a code snippet of the regex. Replace this text with your summary.

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [The OR Operator](#the-or-operator)
- [Flags](#flags)
- [Character Escapes](#character-escapes)

## Regex Components

### Anchors

These are special sequences that match an empty substring. Used to match a position before or after characters. 

^ matches at the beginning of the target string
$ matches at the end of the target string
\b matches on a word boundary, i.e., the previous or subsequent character is not a word character

### Quantifiers

Quntifiers specifies examples of the previous element (character, a group or a character class) must be present to match to a input string.

* = Matches the previous element zero or more times

+ = Matches the previous element one or more times.

? = Matches the previous element zero or one time.

### Grouping Constructs

Grouping Constructs set forth the subexpressions of a regular expression and capture substrings of an input string.

- Match subexpression that's repeated in the input string

- Apply quantifier to subexpression that has multiple regular expression language elements.

### Bracket Expressions

Characters that have a special meaning. The regex engine is instructed to search for these character classes that contain brackets.

- upper, lower and special characters in brackets are examples of this.

### Character Classes

### The OR Operator

### Flags

### Character Escapes

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
