# Regex Tutorial

Regex is a powerful way to work with strings. It has many components such as anchors, qualifiers, or operators, character classes, flags and more.

## Summary

The following regex is an example of a string separator using regex. With this regex patter you can separate any type of phone number layout into first, second and third sections.
```
.?(\\d{3}).*(\\d{3}).*(\\d{4})
```

## Table of Contents

- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)

## Regex Components

### OR Operator

```.?``` - 0 or 1 character to account for the optional open parenthesis

```.*``` - 0 or more characters to account for the optional closing parenthesis, hyphen, and space characters

```.*``` 0 or more characters to account for the optional hyphen and space characters


### Character Classes

```(\\d{3})``` - 3 digit characters (first capture group i.e. first 3 digits)

```(\\d{3})``` 3 digit characters (second capture group i.e. next 3 digits)

```(\\d{4})``` 4 digit characters (third capture group i.e. last 4 digits)



### Grouping and Capturing


```(\\d{3})``` - 3 digit characters (first capture group i.e. first 3 digits)

```(\\d{3})``` 3 digit characters (second capture group i.e. next 3 digits)

```(\\d{4})``` 4 digit characters (third capture group i.e. last 4 digits)



### Bracket Expressions


```.?``` - 0 or 1 character to account for the optional open parenthesis

```.*``` - 0 or more characters to account for the optional closing parenthesis, hyphen, and space characters



## Author

By Jacob Adelman. Github [jakeadelman](https://github.com/jakeadelman)
