# is-nullish
Returns true if the given value is null or undefined

# Install
```sh
$ npm install @andjsrk/is-nullish
```

# Usage
```js
// for CommonJS
const isNullish = require('is-nullish')

// for ESM
import isNullish from '@andjsrk/is-nullish'
```

```js
isNullish(null) // true
isNullish(undefined) // true
isNullish(0) // false
isNullish("") // false
isNullish(false) // false
isNullish([]) // false
isNullish({}) // false
```
