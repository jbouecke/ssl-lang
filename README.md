# SSL-lang Extension

This extension "ssl-lang" is an unofficial syntax highlighting support for the STARLIMS Scripting Language.

## Features 

The extension provides basic syntax highlighting for the STARLIMS Scripting Language (SSL) and Data Sources written in the STARLIMS SQL format.
Basic code snippets may be added soon, while sophisticated language support via LSP is required to be added by other extensions.

## Requirements

N/A

## Extension Settings

N/A

## Known Issues

* SQL highlighting in separately declared string variables doesn't work.

## Release Notes

## 0.0.9
- fixed line endings for comments in SSL
- added support for datasources written in SSL and SQL
- added basic T-SQL syntax highlighting
- introduced a custom theme to make blue functions blue again ;)

## 0.0.8
- added further blue functions and control keywords

## 0.0.7

- add furhter blue functions 
- array detection for syntax highlighting
- add "!=" operator
- fixed file extensions to be set to '.ssl' and '.srvscr'

### 0.0.6

- improved sql syntax inlay (considering 'iif')
- added 'CreateUdObject' as 'blue function' ;-)

### 0.0.5

- improved sql syntax inlay
- added 'runsql' as 'blue function' ;-)


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
