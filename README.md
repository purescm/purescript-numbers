# purescript-numbers
Functions for working with PureScript's builtin `Number` type.

## Examples

``` purs
> 0.1 + 0.2 == 0.3
false

> import Data.Number
> 0.1 + 0.2 ≅ 0.3
true

> fromString "12.34"
(Just 12.34)
```