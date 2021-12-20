# SSL-lang Extension

This extension "ssl-lang" is an unofficial syntax highlighting support for the Starlims Scripting Language.

## Features 

For now, the extension just provides the 'SSL' language and basic syntax highlighting via the text mate grammar.

Basic code snippets may be added soon, while sophisticated language support via LSP is required to be added by other extensions.

## Requirements

N/A

## Extension Settings

N/A

## Known Issues

* The highlighting still misses some SSL language concepts...

## Release Notes

### 0.0.4

- Added try/catch and LIMS transaction snippets
- Added try/catch keywords to language file
- Adding capability to syntax-highlight embedded sql code (a plugin that provides language support for sql needs to be installed)
- Adding 4 more keywords for syntax highlighting: INHERIT / FOR / NEXT / EXITFOR

### 0.0.3

- Adding 3 basic codesnippets (for FOR & WHILE loops and PROCEDURE statements)
- Adding auto-indentation, when pressing enter directly behind a :FOR/:WHILE/:PROCEDURE statement

### 0.0.2

Adding line comment (even though such doesn't exist in SSL). However, it mimics the known behavior.

### 0.0.1

Initial release (basic syntax highlighting and language definition)
