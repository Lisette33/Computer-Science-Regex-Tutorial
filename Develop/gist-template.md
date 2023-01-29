# Regex Tutorial: Matching an Email 

The tutorial explains a regular expression (regex) /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/ for matching an email. It is a helpful aspect for emails.

## Summary

The regex refers to a sequence of characters that explains a certain search pattern. In particlar, the tutorial describes the regex for matching an email. The tutorial also explains every section of the regex.

/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

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
The Regex for matching an email:
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

### Anchors
The Anchors are ^ and $ characters. The ^ anchor character represents the string beginning with characters following them. In addition, the $ anchor character refers to the string ending with characters that come before them.

### Quantifiers
The Quantifiers are {2,6}, +, and .com . The quantifiers establish limits for the string the regex match. Specifically, {2,6} quantifier presents the match between 2-6 pertaining to the [a-z\.] section. The + is a connector to the username email and service of email or domain name with the .com section.

### Grouping Constructs
The Grouping Constructs help break the parts in the regex from utilizing parentheses (). In the regex, the grouping constructs include:

([a-z0-9_\.-]+) for the username email;
([\da-z\.-]+) for the service of email or domain name;
([a-z\.]{2,6}) for the .com 

### Bracket Expressions
The regex has Bracket Expressions ([]) that refer to characters to match. In particular, the regex bracket expressions include:

[a-z0-9_\.-] that matches a-z and 0-9 characters;
[\da-z\.-] that matches a-z, (.), and (-) characters;
[a-z\.] that matches a-z and (.) characters

### Character Classes
The character classes include \d which is the match of characters for 0-9 numbers.

### The OR Operator
For the regex, the OR operator occurs within the expression for [\da-z\.-]. It is a search for characters within the pattern. The OR operator represents a result or another.

### Flags
The Flags occur at the end of the regex. For the regex, the flags take place of the slash (/). Amongst the 6 flags, there are 3 primary flags including Case-insensitive search (i), Global search (g), and Multi-line search (m).

### Character Escapes
The regex contains Character Escapes, which is a backlash (\) searching for the dot (.) that occurs after the backlash. This occurs in the regex including, First: ([a-z0-9_\.-]+) Second: ([\da-z\.-]+) Third: ([a-z\.]{2,6})


## Author
Lisette Morales
https://github.com/Lisette33

