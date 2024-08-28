# Regex-Tutorial for Phone Numbers

A Regex is a regular expression that searches for matching values/patterns within a string. The following regex 
is an example that looks for the string to match the general makeup of a phone number.




## Summary

A Regex, or Regular Expression, is a sequence of characters that forms a search pattern. 

It is often used for string searching, matching, and manipulation tasks in programming and text processing. 

Regex can define complex search criteria, allowing you to find and replace text, validate inputs, and extract information.




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
The example for a Regex ^ anchor indicates the beginning of the string. The dollar $ anchor indicates the end of the string.

Example for a phone number in the United States:

^(\+\d{1,2}\s)?\(?\d{3}\)?[\s.-]\d{3}[\s.-]\d{4}$



### Quantifiers


### Grouping Constructs


### Bracket Expressions
Bracket expressions are used to specify characters to match, they are enclosed in square brackets[].

Example for phone number, (999) 111-2222 would be writen as ^\(\d{3}\) \d{3}-\d{4}$ 

or to find any phone number using a character class also known as [] in regex would be writen as 
^\(?\d{3}\)?[-.\s]?\d{3}[-.\s]?\d{4}?
To understand what is going on in the regex it will be described in a gist linked in my author section of this page.

### Character Classes

- /d -> numbers 0 through 9
- . -> period or dot means any character
- (*) -> star means 0 or more
- /w -> (w stands for word) A though Z a-z and 0-9
- /s -> whitespace



### The OR Operator
The OR operator is represented by the vertical bar symbol |. It will match if any of the alternatives are found.
For example, the regular expression cat|dog will match either "cat" or "dog". The OR operator is not used in this regex.


### Flags
The following flags: g which stands for global search

### Character Escapes


## Author

This tutorial was created by Megan Zimnicki a bootcamp student for UNC. To see a discription on a regex for a phone number 
please click the following link to Gist https://gist.github.com/meg-an321/a94284c6cf420691d16e009e103eccb2
for more of my work on this project please click the link to my GitHub https://github.com/meg-an321/Gist
