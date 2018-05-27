## 1.18.1

* use hex values instead of hsl for color definition to avoid inconsistent color evaluation

## 1.18.0

* made red, blue, purple, and orange slightly more vibrant for better readability
* make booleans red instead of orange

## 1.17.2

* reverts last change, as it inadvertently targeted other selectors as well.

## 1.17.1

* more hacky CSS fixes. someone plz send help.

## 1.17.0

* fix CSS property-name highlighting bug. This is SUPER hacky... PRs welcome if anyone knows why it's not working!
* adds `prettier` for formatting files

## 1.16.0

* updated links for new GitHub username so screenshots did not break.

## 1.15.0

* make bracket matcher line indicator stand out more by changing background to blue to match background color of selection in tree-view and git panel

## 1.14.0

* increase contrast in gutter selection for `one-dark-syntax` feature parity

## 1.13.1

* fixes typo in package.json for tag info on atom.io

## 1.13.0

* adds syntax highlighting for Elixir function params for `one-dark-syntax` feature parity

## 1.12.0

* fixes incorrect bracket color in PHP files
* fixes TypeScript separator background color
* adds syntax highlighting for Elixir files

## 1.11.0

* highlights all assignment operators consistently using `syntax--assignment` class

## 1.10.0

* adds support for `bracket-matcher` plugin feature that highlights the gutter line of the other bracket

## 1.9.0

* updates monochrome hues 1 and 2 to be AAA and AA compliant for a11y standards

## 1.8.0

* bug with deployment, this was never published

## 1.7.0

* changes link color in markdown files to not be same color as italics text

## 1.6.1

* updates out-of-date screenshot in documentation

## 1.6.0

* supports `highlight-selected` package

## 1.5.0

* Adds `syntax--` to all classes as part of the Shadow DOM removal

## 1.4.4

* moves LESS mixin highlighting from CSS partial into its own LESS partial

## 1.4.3

* adds color for operators in C++

## 1.4.2

* adds color for operators in C and C#

## 1.4.1

* adds 2px border radius to find-and-replace markers

## 1.4.0

* refactors color vars
* removes `@syntax-mix-percent` calculations in favor of straight `hsl`
* brightens some colors

## 1.3.4

* update keywords and engines in package.json

## 1.3.3

* changes color for "this", "arguments", and "super" keywords to differentiate them from normal variables

## 1.3.2

* update semicolon/punctuation.terminator color

## 1.3.1

* update screenshot and changelog

## 1.3.0

* improve find and replace markers on words

## 1.2.0

* tweak cyan and green (promise I'm done, it took me a few tries but I'm happy with it now)

## 1.1.0

* update cyan

## 1.0.1

* new screenshot

## 1.0.0

* Refactors code structure to split language specific styles into their own partials

## 0.9.0

* Brightens cyan

## 0.8.0

* Darkens background color

## 0.7.0

* Modifies colors

## 0.6.0

* Tweaks comment color

## 0.1.0 - First Release

* Every feature added
* Every bug fixed
