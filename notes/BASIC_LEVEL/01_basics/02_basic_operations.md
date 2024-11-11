# Basic Operations

### Arithmetic
`+`, `-`, `*` and `/` work as expected.

Note: The division operation, `/`, always returns a float.
There are method for division and for modulo
- `div(10, 2)` returns 5
- `rem(10, 3)` returns 1. This is the equivalent on modulo.

### Boolean
`||`, `&&`, and `!` work as expected.
In elixir, we can use the words `or`, `and`, and `not` for these operations except the first argument `MUST` be a boolean.

Example:
- `false or 32` return 32
- `32 or false` throws: (BadBooleanError) expected a boolean on left-side of "or", got: 32

### Comparison
`==`, `!=`, `===`, `!==`, `<=`, `>=`, `<`, and `>`.
- `===` enforces strict comparison between integers and floats. `4 === 4.0` returns false

Note: In elixir, any two data types can be compared.

`number < atom < reference < function < port < pid < tuple < map < list < bitstring`

Thus, `:hello > 999` returns true


### String Interpolation
Works like in ruby, `"My name is #{name}."`

### String Concatenation
Uses the `<>` operator. `"My name is " <> name`




