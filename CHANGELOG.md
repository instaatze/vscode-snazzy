# Change Log

All notable changes to this theme will be documented in this file.

## [2.9.0] - 2018-02-18

- Java improvements: method parameters, implemented interfaces
- Markdown improvements: refactored all language specific customizations so that they apply to markdown code blocks too, code block highlighting ([#3](https://github.com/alexanderbast/vscode-snazzy/issues/3))

## [2.8.0] - 2017-11-21

- Javascript improvements: import *
- Batch improvements: sigils
- Workbench theming improvements: git decoration colors

## [2.7.0] - 2017-10-01

- Escape sequences highlighting ([#1](https://github.com/alexanderbast/vscode-snazzy/issues/1))
- Workbench theming improvements: diff editor colors

## [2.6.0] - 2017-09-14

- Workbench theming improvements: input validation, colors for modified, added and deleted content in the gutter (left), colors for modified content, errors, warnings and info in the ruler (right)
- Excluded unnecessary files from package (.vscodeignore matches differently than .gitignore)

## [2.5.0] - 2017-07-23

- VS Code update 1.14.1 added the ability to theme the terminal cursor, so now the terminal cursor color reflects the hyper-snazzy cursor color. Unfortunally, it's currently not possible to let the cursor background color (the color of the character behind it with block style) just have the color of the character behind it
- VS Code update July 2017 should add the ability to theme the editor cursor background color, so this is already added to the theme as well
- Added .png icon and changed badge URLs to comply with the new image constraints of VS Code extensions

## [2.4.0] - 2017-06-17

- VS Code update 1.13 introduced JSX/TSX component highlighting, which lead to yellow component tags with this theme. They're red again, but component tags are now underlined to seperate them from HTML tags
- The namespace part of XSLT tags is now underlined too to seperate them from HTML tags. Unfortunally, it's currently not possible to underline the whole tag because of missing language support from VS Code
- Javascript improvements: destructuring parameter type annotion
- TypeScript improvements: import *, destructuring parameter type annotion
- Workbench theming improvements: highlighting, badges, focus borders
- Fixed a slight difference between the terminal colors and the hyper-snazzy colors, which also fixes things like autosuggestions (if using zsh or fish) to be invisible

## [2.3.0] - 2017-05-21

- Generalized more rules so they should affect more languages
- Python def is yellow again to be semantically in line with this theme
- C & C++ improvements: preprocessors, function parameters
- HTML improvements: doctype
- Punctuation improvements: variable definitions, accessors, seperators
- Diff improvements: seperators, line numbers
- Broader constants theming
- Broader method calls theming

## [2.2.0] - 2017-05-17

- Generalized more rules so they should affect more languages
- Class functions & methods are now colored like functions/methods and not like class members
- CSS colors now better reflect HTML/JSX colors
- General improvements: constants, expressions
- Diff file theming

## [2.1.0] - 2017-05-09

- Java improvements: package, import, annotations, method calls, inner-class method, null
- C# improvements: types, get, set
- Python improvements: docstrings, self, import *, def, function arguments, function decorators, True, False, None

## [2.0.0] - 2017-05-06

- Complete rewrite, no longer based on Atom One Dark Theme by Mahmoud Ali
- Better semantic for the colors
- Initial workbench theming, trying to complement the standard VS Code style

## [1.0.0] - 2017-04-23

- Initial release
