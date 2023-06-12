# Regex Tutorial 

This is a tutorial on some basic concepts of RegEx.

## Summary

There are a few examples of the RegEx code in several sections to help you see how the code is applied in regular expressions. 

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

 Example:
 ^ -- $
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

 Exmaple:
 ([a-z0-9_\.-]+)
### OR Operator
The OR Operator mathes searcher for one or the other in the regualr expression engine. for instance "I like (cats | dogs)" will match "I like cars" or "I like dogs"
### Character Classes
A character class defines a set of characters, any of the letters can ocur in the input string. For instance [ aeiou ] will match all the vowels. There are also negative characters, these are characters that must not appear in the search string. the way that negitive chravters are identified is through the ^ opperator.

Example:
a-z0-9_\.-
### Flags
Flags are an optional token that is utilized to search for wither the "g" Global or the "i" ignore. When the "g" flag is used, it evaluates it against all potential matches in the string. 
### Grouping and Capturing
Contents are matched by a groupwithin the parentheses, this an be capture and refrenced later in the regex match. The capturing groups are created by placing parentheses arounf the subpattern.
### Bracket Expressions
Bracket expressions have two different types: the Matching List Expressions and the Non-Matching List Expression. They contain atleast one expression, which can include ordinary characters, symbols, classes and collecting elements. 
Example:
^([-----]--)
### Greedy and Lazy Match
Regulat expressions are greedy, this means that the regular expression will match as much of the string as possible. a lazy match will match as little of the string as possible while still allowing the overall pattern to match.
### Boundaries
Boundaries ate characters that specify positions in the string where matches can occur. They do not match actual characters, just the match position.
### Back-references
Back-refrences in regular expressions are a way to refer back to groups that have been matched earlier in the same pattern.
### Look-ahead and Look-behind
Look-ahead and look-behind are types of assertions that the regular expression uses to match a pattern only if it is followed by another pattern (look-ahead) or proceed by another pattern (look-behind) without including the second pattern in the match. They do not consume characters in the string, only assert whether a match is possible.
## Author

### Evan Sterling Miller
I am a junior developer learning more about coding and coding techniques. Currently I am going through Uconn's Coding Bootcamp in hopes of furthering my career.

GitHub:
https://github.com/EvanSterlingMiller

