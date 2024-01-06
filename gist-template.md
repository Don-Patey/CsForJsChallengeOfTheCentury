# Regex Tutorial: Matching an Email

## Introduction
Welcome to this tutorial on regular expressions! In this guide, we will break down and explain each component of the regex used for matching email addresses.

## Summary
The regex we will be exploring is:
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/


## What IS a Regex?
A regular expression (regex) is a sequence of characters defining a specific search pattern. It is used to find patterns or validate input within strings.

## Anatomy of an Email Regex
Username: ([a-z0-9_\.-]+)
Domain:  ([\da-z\.-]+)
Top-level Domain (TLD): ([a-z\.]{2,6})

## Example
Valid Email/Example Email: john_doe@example.com
Invalid Email: User@.com

### Table of Contents 

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)
- [Boundaries](#boundaries)
- [Back-references](#back-references)
- [Look-ahead and Look-behind](#look-ahead-and-look-behind)


### Anchors
In regular expressions, anchors are used to specify the position of a match within a string. The two common anchors are:

(^:) The start anchor asserts that the regex match must occur at the beginning of the string.
($:) The end anchor asserts that the regex match must occur at the end of the string.

Example: /^Start/

### Quantifiers
Quantifiers control the number of occurrences of a character or group in a regex.

*: Matches 0 or more occurrences.
+: Matches 1 or more occurrences.
?: Matches 0 or 1 occurrence.
{n}: Matches exactly n occurrences.
{n,}: Matches n or more occurrences.
{n,m}: Matches between n and m occurrences.

Example: /\d+/

### OR Operator
The OR operator, represented by the | symbol, allows for matching one of several alternatives.

Example: /apple|orange|banana/

### Character Classes
Character classes match any one of a set of characters. They are denoted by square brackets.

[abc]: Matches either 'a', 'b', or 'c'.
[^abc]: Matches any character except 'a', 'b', or 'c'.
[a-z]: Matches any lowercase letter.

Example: /[aeiou]/

### Flags
Flags are used to modify how a regex pattern is applied. Common flags include:

i: Case-insensitive matching.
g: Global matching (find all matches).
m: Multi-line matching.

Example: /word/i

### Grouping and Capturing
Parentheses () are used for grouping and capturing parts of a regex pattern.

Example: /(foo)\d{2}/

### Bracket Expressions
Bracket expressions are used to match any one of a group of characters.

Example: /[0-9]
### Greedy and Lazy Match
Quantifiers are greedy by default, matching as much as possible. Adding ? makes them lazy, matching as little as possible.

Example: /<.*?>/
### Boundaries
Boundaries help define where a match should occur in relation to word boundaries.

\b: Word boundary.
\B: Non-word boundary.

Example: /\bword\b/

### Back-references
Back-references allow referencing a previously captured group in the regex pattern.

Example: /(abc)\1/

### Look-ahead and Look-behind
Look-ahead and look-behind assertions are used to ensure that a pattern is or is not followed or preceded by another pattern.

Example: /\d+(?=%)/

## Author
 Don Patey
Github : https://github.com/Don-Patey


A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
