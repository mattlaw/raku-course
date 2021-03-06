---
prefix: /raku-course
---

# A Complete Course of the Raku programming language

* [About this course]({{page.prefix}}/about-this-course)

{% comment %}{% assign compact_menu = true %}{% endcomment %}
{% include toc.html %}


---

* [About this course](about-this-course)

## Part 1. Raku essentials


### Running Raku

* Command-line options

* Phasers

* Understanding error messages

* The MAIN subroutine


### Variables and data types

* Types of variable containers in Raku (scalar, arrays, etc.)

* Understanding Raku containers

* Integers

* Strings

* Date and Time built-in support

* Other data times

* Understanding a sequence


### Operators

* Types of operators in Raku (infix, prefix, etc.)

* Overview of operators in Raku

* [Meta-operators](metaoperators)

* User-defined operators

* Data type conversion (e.g., prefix operators `+` or `~`, etc.)



## Part 2


### Control flow

* Blocks and scoping 101

* Conditional checks

* Loops

* Block-related phasers (e.g. `LEAVE`)

* Other options (e.g., `gather`, `given`)


### Subroutines

* Creating a subroutine

* Signature

* Calling a subroutine

* Multiple dispatch

* Multiple MAIN subroutines

* Nested subroutines

* Anonymous subroutines


### Modules

* Creating modules

* Using modules

* Different types of importing (`import`, `need`, etc.)

* Introspections

* Installing modules from web



## Part 3


### Object-oriented programming

* Classes in Raku

* Attributes

* Methods

* Class methods

* Subroutines vs methods

* Inheritance

* Roles

* Introspection


### Input and output

* Standard input, output, and errors

* Working with files

* Working with directories

* File streams


### Exceptions

* The `try` block

* What is a soft failure

* The `CATCH` phaser

* Exception objects

* Failure objects

* Multiple dispatch in handling exceptions

* Custom exceptions


## Part 4


### Regexes

* Literals and character classes

* Regexp matching

* Quantifiers

* Captures

* Alternations

* Anchors

* Forward and backward assertions

* Adverbs (such as `:g` etc.)

* String substitution and replacement


### Grammars

* What is a grammar

* Creating grammars

* Rules

* Tokens

* Grammars vs. classes and inheritance

* AST (Abstract syntax tree), `make` and `made`

* Actions

* Inline actions vs. action class


## Part 5


### Functional programming

* Recursion

* Reduction

* Higher-order functions

* Lambdas

* Data feeds

* Iterators

* Lazy and infinite sequences


### Concurrent programming

* Junctions

* Threads

* Promises

* Channels


### Reactive programming

* Supplies

* Live and on-demand supplies

* Understanding `react`

* Understanding `whenever`

* Understanding `await`


### Web programming

* Making remote connections

* Simple HTTP client

* Simple HTTP server

* Cro 101


## Appendix

* [List of problems](problems)
