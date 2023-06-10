# Regex Tutorial 

This is a tutorial on some basic concepts of RegEx.

## Summary

Briefly summarize the regex you will be describing and what you will explain. Include a code snippet of the regex. Replace this text with your summary.

## Table of Contents

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

## Regex Components

### Anchors
Anchors signify the position in a string where a match must occur. When an anchor is used in a search expression the regular expression engine does not advance throught string or consume any of the characters The anchor looks for a match at that specific position. 

Types of anchors:
 ^   Match must occur at the begining of the string, or at the begining of the line
 $   Match must occur at the end of the string or the end of a line
 \A  Match must occur at the begining of the string only
 \Z  Match must occur at the end of the string or before \n at the end of the string
 \z  Match must occur at the end of the string only
 \G  Match ust start at the position where the previous match ended, of there was no previous match, the position in the string where the matching started.
 \b  Match must occur on a word boundary
 \B Match must not occur on a word boundry
### Quantifiers
Quantifiers specify how many instances of the prtvious element must be present in the input string for a match to occur. 

Types of qualifiers:
 .*  Matches the previous element 0 or more times.
 .+  Matches the previous element 1 or more times.
 .?  Matches the previous element 0 or 1 times.
 {n} Matches the previous elements n times.
 {n,} Matches the previous elemen at least n times.
 {n,m} Matches the previous element n times but no more than m times.
 *?  Matches the previous element 0 or more times but as few as possible.
 +? Matches the previous element 1 or more times but as few as possible.
 ?? Matches the previous element 0 or 1 but as few as possible
 {n}? Matches the proceding element exactly n times.
 {n,}? Matches the previous element atleast n times but as few as possible.
 {n,m}? Matches the previous element between n and m times but as few as possible.
### OR Operator

### Character Classes

### Flags

### Grouping and Capturing

### Bracket Expressions

### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
