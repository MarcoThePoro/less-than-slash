# </ Less Than-Slash

[![Build Status](https://travis-ci.org/mrhanlon/less-than-slash.png)](https://travis-ci.org/mrhanlon/less-than-slash)

Atom.io package for closing open tags when less-than, slash (`</`) is typed, like in Sublime Text 3.


![Less Than Slash](https://mrhanlon.github.io/images/less-than-slash.gif)

## Installation

`apm install less-than-slash`

## Settings

You can specify a list of "Empty Tags" to be ignored from auto-closing. The default value for "Empty Tags" is:

`br`, `hr`, `img`, `input`, `link`, `meta`, `area`, `base`, `col`, `command`, `embed`, `keygen`, `param`, `source`, `track`, `wbr`

The plugin will automatically ignore any self-closing tags. This is useful for frameworks like Angular.js, which allows the definition of custom elements.

## Contributing

Please follow the guidelines for [Contributing to Atom](https://atom.io/docs/latest/contributing).
