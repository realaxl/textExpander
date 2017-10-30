# textExpander
Expand a text list to CLI, SQL, inserts, etc. all from a single HTML+Javascript file!

## Requirements
- Javascript-enabled browser
- access to [Bootstrap](http://getbootstrap.com/)

## Features:

### Input

- The content of the input field will be separated into lines, splitting by `\n` character.
- Each line from input field will be processed individually with the rules below.

### Filters

- Blank lines in the input field will be skipped and will not appear in output field.
- Lines in the input field can be filtered against the regEx filter field.

### Template and Token

- The template field defines the format of the output text.
- Each occurenace ot the magic token field in the template will be replaced.
- The magic token, e.g. `$$$` will be replaced with lines from the input field.
- Please note the token must match using Javascript regEx.

### Options

- Header, Separator and Footer will be added to the output before, inbetween and after the templates.

- - Header
  - Template
  - Separator
  - Template
  - Separator
  - [...]
  - Footer