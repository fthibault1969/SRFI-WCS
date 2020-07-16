# Files used to make SRFI for WCS pattern matcher.

## .:

**gauche-grammar** the syntax description from Gauche's documentation

**match-implementations.md** all the documentation and implementation
for scheme pattern matching I could find.

**match.mhtml** the documentation that goes with the Chibi Scheme
implementation of pattern matching

**match.sld** Chibi pattern matching library definition

**match-test.sld** Chibi pattern matching tests

**README.md** this file

**srfi-template.html** the filled-out SRFI

## .gauche0.9.6
**match.scm** Gauche pattern matching library definition

## ./guile2.2:

**match.scm** Guile implementation of library definition, uses define-module
              and include-from-path instead of define-libarary and include and
              defines is-a? macro used in ./match/match.scm

## ./match:

**match.scm** Chibi pattern matching library implementation


## ./test:

**match-test.scm** cond-expand implentation-specific code, then load tests-common.scm.

**hello-test.scm** cond-expand implementation-specific code, then load hello-common.scm.

**hello-common.scm** simple test, will pass if Makefile and cond-expand are set up correctly.

**tests-common.scm** match tests

**Makefile** make check runs all tests

## ./test/logs

**\*.logs** test results
