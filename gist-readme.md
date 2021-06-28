# Regex Tutorial

A regex otherwise known as regular expression, is a set of characters that defines a search pattern. the set of characters define a certian type of characters in  a speficic order to match with.

## Summary

In this tutorial i will be sumerizing a regex as given below,
`rege(x(es)?|xps?)`
this regex will match with the following strings 
`{regex, regexes, regexp, regexps}`
the rest of this tutorial will deinfe in more detail the make up of this regex
## Table of Contents

- [Regex Tutorial](#regex-tutorial)
  - [Summary](#summary)
  - [Table of Contents](#table-of-contents)
  - [Regex Components](#regex-components)
    - [Anchors](#anchors)
    - [Quantifiers](#quantifiers)
    - [Grouping Constructs](#grouping-constructs)
    - [Character Classes](#character-classes)
    - [The OR Operator](#the-or-operator)
    - [Flags](#flags)
    - [Character Escapes](#character-escapes)
  - [Author](#author)

## Regex Components
regex components refers to the special charactesr used in the regex function to define a search pattern. such as the (), ?, |

### Anchors
anchors are special characters that determine a certain posiotn of the word 
for examples `^` refers to the start of a string or multi-line pattern
### Quantifiers
quantifiers specify how many instancces ofa  certain character or character group are pressent for a certain match to be found,
such as the `{5}` meaning it is macthed 5 times
### Grouping Constructs
grouping construst are lettering insaide of brackets that define a certain letter group to be macthed with.
such as the `(x(es))` above which looks for words with x or es within


### Character Classes
a charcetr class is a notion that matches a symbol from a certain character set.
there are multiple such as
`\d` to define a digit characetr from 0 - 9
`\s` for finding spaces in lettering
`\w` for word characters from a - z
### The OR Operator
the or operator which is represented as `|` in regex
is used to define two different outputs of matches such as in the above examples with  `x(es)?|xps?` to match with either a `x/es` ending or a `xps` ending
### Flags
flags are letters that are used to define a specific flag which is used as a function for a more defined searches such as `g` for global searches or `i` for case insensitive searches
### Character Escapes
character letters are used to use a cahracters literal as oppose to the function usualy defined with in a leter
## Author

reuben fevreau js expert
(https://github.com/FevoTheSicko)
