**Note**

This library is under heavy refactoring.
The current released version is on [branch v0.2](https://github.com/gcanti/tcomb-form/tree/v0.2)

# Roadmap v0.3.0

- [] custom input
- [] for attribute for labels
- [] aria support
- [] playground
- styles
  - [] foundation
  - [] pure
  - [] ionic
- [x] horizontal forms
- [x] return null if validation failed (but provide a `raw` option to return `ValidationResult`)
- textbox (Str, Num)
  - [x] label as ReactElement
  - [x] help as ReactElement
  - [x] optional label
  - [x] optional placeholder
  - [x] addonBefore
  - [x] addonAfter
  - [x] handle conversion for numbers
  - [x] error message
- checkbox (Bool)
  - [x] label as ReactElement
  - [x] help as ReactElement
  - [x] optional label
  - [x] error message
- select (enums)
  - [x] label as ReactElement
  - [x] help as ReactElement
  - [x] optional label
  - [x] multiple
  - [x] error message
  - [x] opt group
  - [x] custom options
- radio
  - [x] label as ReactElement
  - [x] help as ReactElement
  - [x] renderAs: 'radio'
  - [x] optional label
  - [x] error message
- struct
  - [x] auto labels, none
  - [x] label as ReactElement
  - [x] help as ReactElement
  - [x] subtype
  - [x] error message
  - [x] interleave in `order` option verbatim (ReactElements)
- list
  - [x] label as ReactElement
  - [x] help as ReactElement
  - [x] subtype
  - [x] error message

