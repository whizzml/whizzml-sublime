# WhizzML for Sublime Text 3

BigML's DSL for Machine Learning WhizzML syntax highlighting, autocompletions,
and settings for Sublime Text.

![WhizzML-Sublime](https://raw.githubusercontent.com/whizzml/whizzml-sublime/master/whizzml-sublime.gif "WhizzML-Sublime")

## Instalation

### Using Package Control

Install it through Package Control: Install Package > WhizzML. Open Command
Palette panel from Tools > Command Palette (cmd+shift+P).

### Manually

Copy `WhizzML.sublime-syntax`, `WhizzML.sublime-completions`, and
`WhizzML.sublime-settings` or clone this repository inside the User directory
in Sublime Text's Packages directory.

## Features

- Syntax highlighting
- Autocomplete
- Syntax settings (auto-indent, tab size, etc.)
- **Future** _Snippets_
- **Future** _Code linter_

## Development

Copy `WhizzML.sublime-syntax`, `WhizzML.sublime-completions`, and
`WhizzML.sublime-settings` into
`<path-to-sublime-installation>/Packages/User`
(`~/Library/Application\ Support/Sublime\ Text\ 3/Packages/User` in Mac).
Modify the desired definitions. When you're done make sure that tests on syntax
highlighting pass using the test file `syntax_test.whizzml`. Open it and using
Command Palette panel run the command "Build With: Syntax Tests - All
Syntaxes".

#### Dev resources

- Sublime Text syntax higlighting:
    - [Official Docs](http://www.sublimetext.com/docs/3/syntax.html)
    - [Unofficial Documentation](http://docs.sublimetext.info/en/latest/extensibility/syntaxdefs.html)
- Sublime Text autocompletion:
    - [Unofficial Documentation](http://docs.sublimetext.info/en/latest/extensibility/completions.html)
- Sublime Text packages:
    - [Official Docs](https://www.sublimetext.com/docs/3/packages.html)
    - [PackageControl.io: Submitting a package](https://packagecontrol.io/docs/submitting_a_package)

## Current WhizzML Version supported
    0.27.1 (04-27-2018)
