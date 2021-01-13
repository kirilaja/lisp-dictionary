# lisp-dictionary
user definitions for lisp commands

Most books on programming languages use prose to explain built-in functions. However, functions explain themselves. Unfortunately, the functions as defined for the programming language itself oftentimes seem too complicated for beginners. This educational guide attempts to present two ways of categorizing simpler definitions of functions. These simpler definitions may not have the full functionality of the built-in definitions.

The first way of categorizing these functions is via combinations of lisp primitives: atom, eq, car, cdr, cons. A more intricate function may rely on previously defined functions, therefore masking the primitives that it uses. If a reader comes across a function that does not obviously come under a certain subsection, they should locate and read the functions upon which the first one depends; then, all will become more clear.

The second way of categorizing these functions is by listing them in the order they must be created for actual use. All necessary functions are defined prior to further functions, except for the primitives. This alters the order of the functions as listed in the first way of categorizing. This way of categorizing has yet to be implemented.
