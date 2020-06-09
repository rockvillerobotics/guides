:black_nib: Style
=====

A guide for programming in style.

Use [Travis] to automatically review your
GitHub pull requests for
style guide violations.

[Travis]: https://travis-ci.com

In addition to the general guidelines below, we also have the following more
detailed, language/framework-specific style guides:
* [Python](python)

Formatting
----------

* Delete trailing whitespace.
* Spell correctly.
* Use spaces around operators, except for unary operators, such as `!`.
* Use [Unix-style line endings][newline explanation]. Github adds these automatically. (`\n`).

[newline explanation]: http://unix.stackexchange.com/questions/23903/should-i-end-my-text-script-files-with-a-newline

Naming
------

* Avoid abbreviations.
* Avoid object types in names (`user_array`, `email_method` `CalculatorClass`, `ReportModule`).
* Name variables, methods, and classes to reveal intent.

Organization
------------

* Order methods so that caller methods are earlier in the file than the methods
  they call.
* Order methods so that methods are as close as possible to other methods they
  call.
