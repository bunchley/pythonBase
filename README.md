# pythonBase

Typical project structure

Beliefs:

- deep hierarchy can be a nightmare to navigate
- flat hierarchy leads to bloat
- organize code based on features, not on types
- when you create a directory it should contain several other files
- init files should be empty most of the time, unless you know what you're doing.

- python requires **init**.py file to be present for the directory to be considered a submodule

- bad idea to create module directory that contains only a **init**.py file.

```
Coding Style and Automated Checks
```

- 4 spaces per indention level
- limit all lines to max of 79 char
  separate top level function and class definitions with two blank lines
  encode files using ASCII or UTF-8
  use one module import per import statement and per line. place import statements at the top of the file, after comments and docstrings, grouped first by standard, then by third party, and finally by local library imports.
- no extra whitespaces between parentheses, square brackets, or braces or before commas
- write class names in camel case (CamelCase), suffix exceptions with Error (if applicable), and name functions in lowercase with words and underscores (separated_by_underscores). Use a leading underscore for \_private attributes or methods.

```
Memorables
```

`import sys`
`import os`
`sys.modules['os']`

- retrieve the list of modules currently imported
