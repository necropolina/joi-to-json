### 4.0.1

- Fixes
  * Missing support on `title` in meta

### 4.0.0

[BREAKING]

- Added Features
  * Supports `If-Then-Else` keyword by default for supported JSON Spec for `when` and `alternatives`
  * Supports `invalid` keyword using `{ not: { enum: [] } }`
  * Supports `has` keyword using `contains`
  * Supports `alternatives().try().match()`

- Misc Change
  * Reorganize Test Fixtures and Cases
  * Better `null` type handling
  * Better `const` type handling

- Fixes
  * Missing support on `readOnly` and `writeOnly` for Draft-2019-09
  * Invalid any type for OpenAPI

### 3.1.1

- Fix Typescript definition.

### 3.1.0

- Add support for relation operator `with` and `without`.

### 3.0.0

- [BREAKING] Default enable feature: relation operator `and`, `or`, `nand`, `xor`, `oxor`.
