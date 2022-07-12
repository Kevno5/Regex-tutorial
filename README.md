# Regex-tutorial



## Summary
Regex short for regular expressions are used to create search patterns to help narrow down and match combinations of text. 
These search patterns can be composed of normal characters, special characters and even both normal and special characters at once. It can be used in string methods such as
search(), split(), replace(), replaceAll(), mmatch(), and matchAll(). Some examples of these pattersn look like are [/xA20-\], and [/ TRv?/]. 


## Table of Contents

- [Anchors](#Anchors)
- [Qualifiers](#Qualifiers)
- [Grouping Constructs](#Grouping-Constructs)
- [Character Classes](#Character-Classes)
- [Character Escapes](#Character-Escapes)
- [Substitution](#Substitution)
- [Resources](#Resources)


## Anchors
Anchors are target only a specific position in a string and looks for a match of characters in regular expressions. There are multiple different anchors that are used to search
for different patterns in a string.

- ^ is used to find matches only in the beggining of a string.
- $ is used to find matches at the end of a string, and must be before the /n anchor.
- \Z is used to find matches at the end of the string and before the line break.
- \A is used to find matches at the beggining of the string and can only be used for strings.
- \z is used to find matches at the end of a string only.
- \G is used to find matches only at the most recent position the last match was.
- \b is used to find a match of strings that consist of full words.
- \B is used to find a match of strings that do not have to be full words.



## Qualifiers
Qualifiers determines how many times the character must be present in order to find a match.

These are all of the qualifiers used in regex.

- + is used whenever a match has to occur 1 or more times.
- ? is used whenever a match has to occur 0 or 1 time.
- * is used whenever a match has to occur 0 or more times.
- {n} is used whenever a match has to occur n number of times.
- {n,) is used whenever a match has to occur at least n number of times.
- {n,m} is used whenever a match has to occur from n to m number of times.


## Grouping Constructs
Grouping constructs allows for the capture of specific information in order by delineating sub expressions of user input strings.

## Character Classes
Character classes are brackets used to distinguish between character sets such as numbers and letters.

## Character Escapes
Character escapes are the backslash that precedes a literal character.

## Substitution
Substitutions are used to replace a pattern in an input string.

## Resources
https://docs.microsoft.com/en-us/dotnet/standard/base-types/regular-expressions
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_Expressions
https://www.jmp.com/support/help/zh/15.2/index.shtml#page/jmp/escaped-characters-in-regular-expressions.shtmlhttps://www.jmp.com/support/help/zh/15.2/index.shtml#page/jmp/escaped-characters-in-regular-expressions.shtml
