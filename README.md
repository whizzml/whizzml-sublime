# WhizzML for SublimeText 3

BigML's DSL for Machine Learning WhizzML syntax highlighting, autocompletions,
and settings for Sublime Text.

## Instalattion

### Using Package Control

Install it through Package Control: Install Package > WhizzML. Open Command
Palette panel from Tools > Command Palette (cmd+shift+P).

### Manually

Copy `WhizzML.sublime-syntax`, `WhizzML.sublime-completions`, and
`WhizzML.sublime-settings` or clone this repository inside SublimeText
Packages directory.

## Features

- Syntax highlighting
- Autocomplete
- Syntax settings (auto-indent, tab size, etc.)
- **Future** __Snippets__
- **Future** __Code lintener__

## Development

Copy `WhizzML.sublime-syntax`, `WhizzML.sublime-completions`, and
`WhizzML.sublime-settings` into
`<path-to-sublime-installation>/Packages/User`. Modify the desired definitions.
When you're done make sure that tests on syntax highlighting pass using the
test file `syntax_test.whizzml`. Open it and using Command Palette panel run
the command "Build With: Syntax Tests - All Syntaxes".
