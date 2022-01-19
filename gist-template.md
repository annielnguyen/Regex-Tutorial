# Regex Tutorial: Matching an Email
* Email Regex: `/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`

This is a tutorial on the use of regex to match an email using the email regex: `/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`. The purpose of this regex is to validate emails. For example, if you have a form on your website or dialogue box in your application that prompts the user to submit an email adddress, you would want to use this regex to validate the email before trying to send an email to it. Validating an email reduces the number of undeliverable emails sent back to you. 

## Summary

"A regex, which is short for regular expression, is a sequence of characters that defines a specific search pattern. When included in code or search algorithms, regular expressions can be used to find certain patterns of characters within a string, or to find and replace a character or sequence of characters within a string. They are also frequently used to validate input. (README.md)"
This tutorial walks through the components of a regex and how it applies to matching an email. 


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

The anchors of the expression begin with "^" which starts the string and the "$" is what ends the string. 

### Quantifiers

The quantifier "+" connects the user's email name + email service + .com. {2,6} is also a quantifier which allows a match range of 2-6 characters for this character set: [a-z\.]. 

### Grouping & Capturing Constructs 

Capturing group 1: [a-z0-9_\.-] -- matches the user's email name
Capturing group 2: ([\da-z\.-]+) -- matches the email service
Capturing group 3: ([a-z\.]{2,6}) -- captures the .com
### Bracket Expressions

[a-z0-9_\.-]-- matching any letter a-z and is case senstive. It also matches a character 0-9 and matches the characters "_" , "-" , and "."

[\da-z\.-] -- matching a single digit from 0-9, any character a-z (case senstive), and the characters "." and "-".

[a-z\.] --matching any character a-z (case senstive) and the character "."


## Author

My GitHub profile link is: https://github.com/annielnguyen. If you have any questions regarding this app, please contact directly at: anguyen.aln@gmail.com.



