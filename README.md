# Regex Mini Assignment (Java)

This is a CSC207 (Software Design, University of Toronto) mini assignment.

## What it does

- Validates passwords with one regular expression that requires a lowercase letter, an uppercase letter, a digit, and a minimum length (`Main.checkForPassword`).
- Extracts University of Toronto email addresses (`utoronto.ca` and `mail.utoronto.ca`) from free text using `Pattern` and `Matcher.find` (`Main.extractEmails`).
- Detects whether a string contains the same capital letter twice, using `String.matches` with a backreference (`Main.checkForDoubles`).

## Key concepts

- Choosing between `Pattern.matches`, `Matcher.find`, and `String.matches`
- Lookahead assertions and character classes
- Capture groups and backreferences
- Null-safe input handling
- Writing JUnit 5 tests for both matching and non-matching strings

## Running the tests

From the project root (JDK 11 or newer, with Maven):

    mvn test

The provided `MainTest` suite passes with the current implementation.

---

Course starter code provided by the CSC207 teaching team; implementation by Aaryan Patel.
