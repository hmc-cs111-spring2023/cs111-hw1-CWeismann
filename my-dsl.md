# Language

_What is the name of the language? Link the name to its webpage
(if appropriate)._

Gherkin
https://cucumber.io/docs/gherkin/reference/

# Domain

_Describe the language's domain in five words._

Human-readable Cucumber test suites

# Computational model

_We don't yet have a great definition of the term "computational model".
For now, try to come up with the clearest, most concise explanation of
what happens when a program in your DSL runs._

A test case or test cases are generated fitting the specification. The test case(s)
check if the program is run on some specific inputs, whether it will give some specific output.


# DSL-ness

_Fowler writes about a spectrum of languages, from general-purpose languages to
"purely" domain-specific. Where does the DSL you chose fall on this spectrum,
and why?_

This language is extremely domain-specific. There are almost no recognizable features
like loops or conditionals, and most of the work is done with the Given, And, When, Then,
and But keywords. However, it's domain is quite broad, as test suites are written for most
large software projects.

# Internal or external?

_Is the language implemented as an internal or external DSL?
Justify your answer._

Gherkin is an external DSL. Its commands are not valid in any other language, like
internal DSLs commands are; rather, it has a custom syntax designed for a specific use.

# Host language

_What language(s) was (were) used to implement the DSL?_

Gherkin (and Cucumber), were originally implemented in Ruby, but now also have other 
implementations, including Java.

# Benefits

_Identify one potential benefit of the DSL: how is a programmer's life made
easier by the existence of this language?_

It is easier to read and explain to those with little-to-no technical background.

# Drawbacks

_Identify one potential drawback of the DSL: what does a programmer
lose by using this DSL instead of a general-purpose language?_

Extremely complex test suites may be more difficult to write than in a
general-purpose language.
