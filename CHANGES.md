## 1.2.0 / 2015-03-26

Added customisation of format characters by passing a `formatCharacters` object
as an option to the `InputMask` constructor.

Added the ability for format character definitions to transform valid input.

Changed letter format character to `a`

Added new format characters:
* `A` - letter, which will be transformed to upper case
* `#` - alphanumeric, which will be transformed to upper case

## 1.1.0 / 2015-03-25

Added the ability to escape special pattern characters with a leading backslash
character. As a result, backslashes must also be escaped to be used as static
parts of a mask's pattern.

Added a `mask.emptyValue` property for convenient comparison.

## 1.0.0 / 2015-03-25

Initial realease features:

* Fixed-width masking pattern
* Format characters:
  * `1` - number
  * `A` - letter
  * `*` - alphanumeric
* Editing operations which are aware of cursor position/selection and update
  post-op cursor position:
  * Single character input
  * Pasting a string
  * Backspacing
