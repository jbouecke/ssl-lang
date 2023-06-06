# Change Log

All notable changes to the "ssl-lang" extension will be documented in this file.

Check [Keep a Changelog](http://keepachangelog.com/) for recommendations on how to structure this file.

## [0.0.9] - 2022-06-06
- added getDataSet and getDataSetEx to the functions that will 'trigger' Sql syntax highlighting...
- added support for datasources written in SSL and SQL
- added basic T-SQL syntax highlighting in datasources
- introduced a custom theme to make blue functions blue again ;)

## [0.0.8] - 2022-02-20
- added further blue functions and control keywords

## [0.0.7] - 2022-01-27

- add furhter blue functions 
- array detection for syntax highlighting
- add "!=" operator
- fixed file extensions to be set to '.ssl' and '.srvscr'

## [0.0.6] - 2022-01-25

- improved sql syntax inlay (considering 'iif')
- added 'CreateUdObject' as 'blue function' ;-)

## [0.0.5] - 2022-01-25

- improved sql syntax inlay
- added 'runsql' as 'blue function' ;-)

## [0.0.4] - 2021-12-20

- Added try/catch and LIMS transaction snippets
- Added try/catch keywords to language file
- Adding capability to syntax-highlight embedded sql code (a plugin that provides language support for sql needs to be installed)
- Adding 4 more keywords for syntax highlighting: INHERIT / FOR / NEXT / EXITFOR

## [0.0.3] - 2021-12-17

- Adding 3 basic codesnippets (for FOR & WHILE loops and PROCEDURE statements)
- Adding auto-indentation, when pressing enter directly behind a :FOR/:WHILE/:PROCEDURE statement

## [0.0.2] - 2021-12-17

- Adding line comment (even though such doesn't exist in SSL). However, it mimics the known behavior.

## [0.0.1] - 2021-12-16

- Initial release