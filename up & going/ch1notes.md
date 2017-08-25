Comments should explain *why*, not *what*. They can optionally explain *how* if that's particularly confusing.

```js
console.log( amount );				// 215.9784
console.log( amount.toFixed( 2 ) );	// "215.98"
```

The newest version of JavaScript at the time of this writing (commonly called "ES6") includes a new way to declare *constants*, by using `const` instead of `var`:

**Note:** Unlike most other statements like `console.log(amount);`, a block statement does not need a semicolon (`;`) to conclude it.

JavaScript defines a list of specific values that are considered "falsy" because when coerced to a `boolean`, they become `false` -- these include values like `0` and `""`. Any other value not on the "falsy" list is automatically "truthy" -- when coerced to a `boolean` they become `true`. Truthy values include things like `99.99` and `"free"`.

"falsy" because when coerced to a `boolean`, they become `false`
"truthy" -- when coerced to a `boolean` they become `true`
