# Regex Tutorial Gist

## Overview
Developers often write code, but they also write about code. This Gist contains a tutorial explaining a specific regular expression (regex), breaking down each part of the expression and describing its functionality.

### Challenge
As a web development student, the goal is to provide a tutorial that explains a specific regex, helping readers understand the search pattern the regex defines.

## Gist Content

### Tutorial Content
- **Title:** Regex Tutorial: Matching an Email
- **Introduction:** Welcome to this tutorial on regular expressions! In this guide, we will break down and explain each component of the regex used for matching email addresses.
- **Summary:** The regex we'll be exploring is `/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`, which ensures a valid email format.
- **Table of Contents:**
    1. [What Is a Regex?](#what-is-a-regex)
    2. [Anatomy of the Email Regex](#anatomy-of-the-email-regex)
        - [Username](#username)
        - [Domain](#domain)
        - [Top-level Domain (TLD)](#top-level-domain-tld)
    3. [Examples](#examples)
    4. [Anchors](#anchors)
    5. [Quantifiers](#quantifiers)
    6. [OR Operator](#or-operator)
    7. [Character Classes](#character-classes)
    8. [Flags](#flags)
    9. [Grouping and Capturing](#grouping-and-capturing)
    10. [Bracket Expressions](#bracket-expressions)
    11. [Greedy and Lazy Match](#greedy-and-lazy-match)
    12. [Boundaries](#boundaries)
    13. [Back-references](#back-references)
    14. [Look-ahead and Look-behind](#look-ahead-and-look-behind)
    15. [About the Author](#about-the-author)

- **What Is a Regex:** A regex, short for regular expression, is a sequence of characters defining a specific search pattern. It is used to find patterns or validate input within strings.

- **Anatomy of the Email Regex:**
    - **Username:** `([a-z0-9_\.-]+)`
    - **Domain:** `([\da-z\.-]+)`
    - **Top-level Domain (TLD):** `([a-z\.]{2,6})`

- **Examples:**
    - **Valid Email:** `john_doe@example.com`
    - **Invalid Email:** `user@.com`

- **Anchors:**
    - In regular expressions, anchors (`^` and `$`) specify the position of a match within a string.

- **Quantifiers:**
    - Control the number of occurrences of a character or group in a regex.

- **OR Operator:**
    - The OR operator (`|`) allows matching one of several alternatives.

- **Character Classes:**
    - Match any one of a set of characters. Examples include `[abc]`, `[^abc]`, `[a-z]`.

- **Flags:**
    - Modify how a regex pattern is applied, such as case-insensitive matching (`i`).

- **Grouping and Capturing:**
    - Parentheses `()` are used for grouping and capturing parts of a regex pattern.

- **Bracket Expressions:**
    - Match any one of a group of characters.

- **Greedy and Lazy Match:**
    - Quantifiers are greedy by default, matching as much as possible. Adding `?` makes them lazy.

- **Boundaries:**
    - Help define where a match should occur in relation to word boundaries.

- **Back-references:**
    - Allow referencing a previously captured group in the regex pattern.

- **Look-ahead and Look-behind:**
    - Assertions ensure that a pattern is or is not followed or preceded by another pattern.

- **About the Author:**
    - This tutorial was created by [Don Patey](https://github.com/Don-Patey). Connect with me on GitHub.

## How to Use This Tutorial
- Clone the Gist repository and explore the tutorial sections based on your interest or need.
- Each section provides insights into a specific aspect of the regex.

## Feedback
If you find any issues, have questions, or want to provide feedback, feel free to [open an issue](#) or connect with the author on [GitHub](https://github.com/Don-Patey).

---

**Note:** Ensure to follow the [instructions](#) for creating a public Gist and making revisions using the GitHub Gist UI.
