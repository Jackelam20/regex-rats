# Password Validation Regular Expression

Introductory paragraph (replace this with your text)

## Summary


The Regular Expression I will be describing is a password validation regular expression. This regular expression will be used to validate passwords to make sure they meet the following criteria:
 8 Charcater minimum, 1 uppercase letter, 1 lowercase letter, 1 number, and 1 special character. The code snippet for this regular expression is as follows: 
    /^(?=.*?[A-Z])(?=.*?[a-z])(?=.*?[0-9])(?=.*?[#?!@$%^&*-]).{8,}$/gmi

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

This Regular Expression can be broken down into the following components:
(?=.*?[A-Z]) - This component is used to check for at least one uppercase letter
(?=.*?[a-z]) - This component is used to check for at least one lowercase letter
(?=.*?[0-9]) - This component is used to check for at least one number
(?=.*?[#?!@$%^&*-]) - This component is used to check for at least one special character
.{8,} - This component is used to check for a minimum of 8 characters

### Anchors
     Anchors are used to match a position before or after characters. The anchors used in this regular expression are ^ and $. 
     This is to make sure that the password contains all of the required characters and is at least 8 characters long.
### Quantifiers
     Quantifiers are used to match a specific number of characters. The quantifiers used in this regular expression are ? and *. The ? is used to match 0 or 1 of the preceding token. The * is used to match 0 or more of the preceding token.

### Character Classes
        Character classes are used to match any character from a specific set. The character classes used in this regular expression are A-Z, a-z, 0-9, and #?!@$%^&*-.
        These are used to match the required characters for the password.
### Flags
        Flags are used to indicate the type of search to be performed. The flags used in this regular expression are g and i. The g flag is used for global search. The m flag is used for the multiline search.  The i flag is used for case-insensitive search.
### Grouping and Capturing
        Grouping and capturing are used to match multiple characters. The grouping and capturing used in this regular expression are () and [].
        The () is used to group multiple tokens together and create a capture group for extracting a substring or using a backreference. The [] is used to match any character from a specific set.
### Bracket Expressions
        Bracket expressions are used to match any character from a specific set. The bracket expressions used in this regular expression are A-Z, a-z, 0-9, and #?!@$%^&*-.
        These are used to match the required characters for the password.
### Greedy and Lazy Match
        Greedy and lazy match are used to match the longest or shortest possible part of a string. The greedy and lazy match used in this regular expression is .{8,}.
        This is used to match the minimum of 8 characters.
### Boundaries
        Boundaries are used to match a position before or after characters. The boundaries used in this regular expression are ^ and $. 
        This is to make sure that the password contains all of the required characters and is at least 8 characters long.
### Back-references
        Back-references are used to match the same text as previously matched by a capturing group. The back-references used in this regular expression are () and [].
        The () is used to group multiple tokens together and create a capture group for extracting a substring or using a backreference. The [] is used to match any character from a specific set.
### Look-ahead and Look-behind
        Look-ahead and look-behind are used to match a group after or before a specified pattern. The look-ahead and look-behind used in this regular expression are (?=) and (?<=).
        The (?=) is used to match a group after the main expression without including it in the result. The (?<=) is used to match a group before the main expression without including it in the result.
