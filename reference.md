<div id="header" align="center">
<h1>ace Reference Manual</h1>
</div>

## Index

* [Preface](Preface)
* [Lexical Elements](Lexical-Elements)
* [Datatypes](Datatypes)
* [Expressions & Operators](Expressions-and-Operators)
* [Statements](Statements)
* [Subroutines](Subroutines)
* [Structure and Scope](Structure-and-Scope)
* [Overflow](Overflow)

# Preface
This is the official reference manual for the ace programming language as
implemented by its own creator, Luca Mazza, on `ace`.

This manual documents the 2024 version, known as `ace-24`

### Credits
The ace programming language is heavily inspired by the C programming language.
Please visit the [official reference](https://www.gnu.org/software/gnu-c-manual/gnu-c-manual.html)
to [GNU C](https://gcc.gnu.org).

The code for the official compiler `acec` and the following reference are 
written and come from the idea of [Luca Mazza](https://github.com/lucamazzza) 
as [ace](https://github.com/BProgrammingLanguage).

# Lexical Elements
This chapter describes the lexical elements that 
compose the ace language and the relative source code after preprocessing.
The elements composing a program are called *tokens*.

We find 5 different types of tokens in ace;
* [Identifiers](Identifiers)
* [Keywords](Keywords)
* [Constants](Constants)
* [Operators](Operators)
* [Separators](Separators)
* [White space](Whitespace)

## Identifiers
Identifiers are sequences of characters that define a unique name for variables,
subroutines, data types and preprocessor macros. Decimal digits `0-9`, letters `a-zA-Z` 
and underscores `_` are allowed in such sequences.

It is not allowed and will shout an error an identifier starting with a decimal
and these are case-sensitive; defining a variable identified by the sequence
`some` is distinct to the one defined as `Some` or the constant named `SOME`.

## Keywords
Keywords are reserved identifiers, that are used as part of the language itself.
Their use for any other purpose is strictly prohibited and compile-wise not possible.

Here is a list of keywords recognised by `ace-24`:

```ace
auto break case char const continue default do double else enum extern
float for goto if int long register return short signed sizeof static
struct switch typedef union unsigned void volatile while
```

## Constants

## Operators

## Separators

## Whitespace

# Datatypes


# Expressions and Operators


# Statements


# Subroutines


# Structure and Scope


# Overflow

