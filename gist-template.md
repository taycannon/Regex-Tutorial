# Regex-Tutorial

My name is Taylor Cannon this is my first regex! So bear with me please! 

## Summary

I will be describing a regex pattern for validating and extracting URLs from text. The regex pattern matches URLs that start with "http" or "https" and can contain various characters in the domain and path.

Code:
^(https?://)?([\w.-]+\.[a-z]{2,})?(:\d{1,5})?(/[\w./]*)?$


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

Anchors
Quantifiers
Grouping Constructs
Bracket Expressions
Character Classes
The OR Operator
Flags
Character Escapes

### Anchors
Anchors in regular expressions (regex) are special characters that represent positions within a string. They include ^, which denotes the start of a line or string, and $, which signifies the end of a line or string. Anchors are used to control where a regex pattern should begin or end its matching.

### Quantifiers

Quantifiers specify how many times a character or group should be matched. Common quantifiers include * (matches zero or more occurrences), + (matches one or more occurrences), ? (matches zero or one occurrence), {n} (matches exactly "n" occurrences), {n,} (matches at least "n" occurrences), and {n,m} (matches between "n" and "m" occurrences).

### Grouping Constructs

Parentheses () are used for grouping elements within a regex pattern. They allow you to apply quantifiers or other operations to a group of characters

### Bracket Expressions

Bracket expressions, denoted by square brackets [], define character sets. They match any single character that is within the specified set. 

### Character Classes

Character classes represent predefined sets of characters. Common character classes include \d (digit), \w (word character), and \s (whitespace). They allow you to match specific types of characters easily.

### The OR Operator

The pipe symbol | acts as an OR operator in regular expressions. It allows you to specify alternatives. For example, cat|dog matches either "cat" or "dog."

### Flags

Flags are optional modifiers that can be applied to a regex pattern. They change the behavior of the regex match. Common flags include i (case-insensitive) and g (global, to find all matches).

### Character Escapes

Character escapes are used to match specific characters that have special meanings in regex. For example, . matches any character, but \. matches a literal period.

## Author

GitHub link: https://github.com/taycannon
Gist link: https://gist.github.com/taycannon/d1174779a77353eac58bca72e41b7668

