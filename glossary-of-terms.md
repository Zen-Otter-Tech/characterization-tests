# Glossary of terms

## Refactoring

`“improving the internal structure of an existing program's source code, while preserving its external behaviour”` - Agile Alliance

## Legacy Code

`“profitable code without adequate tests in place”` - J B Reinsberg

## Clean code

`“When we talk about clean code, we talk about a reader-focused development style that produces software that's easy to write, read, and maintain. Clean code is code that is easy to understand and easy to change. ... This means the code is easy to read, whether that reader is the original author of the code or somebody else.”` Ekaterina Novoseltseva

## Test

`“an investigation conducted to provide stakeholders with information about the quality of the software product or service under test.”` - Wikipedia: "Software testing"

Testers verify that code behaves as the business expects, matching documented requirements, without undesirable side effects.

## Types of Testing

- **Critical Path** – tests around the essential behaviours of subject
- **Acceptance** – tests crafted around the “acceptance criteria” analysed for the change. These tests prove whether or not the change has worked
- **Regression** – tests that insure we don’t break key functionality of our subject, or the wider system, as we make other changes
- **Exploratory** – testing “off the beaten path” to find edge cases and understand the way the subject behaves under a broad range of conditions/scenarios - Characterization tests are a type of Exploratory Testing

## Arrange, Act and Assert

Almost universally accepted as the pattern to write good tests:

- **Arrange** – set up the subject under test with necessary dependencies and prepare the test case
- **Act** – execute the action scoped to test
- **Assert** – assess the success of the test by measurement of the actual results against expected results

## Scope of automated tests

- **Unit** – test around an individual structural unit: a function, method, or class
- **Integration** – tests to verify integration points between several units
- **System** - tests to verify the functions and features of a system
- **End to End** – test of flow end to end through an entire business flow of the interconnected systems

## Boilerplate code / boilerplate

`"...sections of code that are repeated in multiple places with little to no variation. When using languages that are considered verbose, the programmer must write a lot of code to accomplish only minor functionality."` - Wikipedia: "Boilerplate code"

## Diff

Short for difference - the difference between the changes in 2 versions of the same file.
