
# Title (replace with your title)

Regular expressions (or "Regex") are patterns used to match character combinations in strings.  A Regex itself is a sequence of characters that defines a particular search pattern. Regex can be used to find certain patterns of characters within a string, to find and replace a character (or sequence of characters), and can be used to validate input data. For this tutorial, we will discuss how to use a regex to match email addresses.

## Summary

/^([a-z0-9_.-]+)@([\da-z.-]+).([a-z.]{2,6})$/

While this may look like an alien language, in this tutorial we will break down and explain what each component of this regex does. The end product is that this regex verifies that a given string matches the template for an email address. 



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


 Regex anchors assert something about the string or the matching process. They do not match any character, but they do match a position before or after characters. The two anchors in regex are ^ and $, where: 

        ^ means that the following code must appear at the beginning of the string, and

        $ means that the preceding code must appear at the end of the string.

Our regex contains both anchors, so therefore a given string must match all the given specifications exactly. If not, the stringit won't be a match.

### Quantifiers

### Grouping Constructs

### Bracket Expressions

### Character Classes

### The OR Operator

### Flags

### Character Escapes

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
