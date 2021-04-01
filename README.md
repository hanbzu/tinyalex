# tinyalex



```js
function patternOne(context) {
  if (!match(context) throw new Error("Can't apply this pattern")
  // Modify the context
  return modifiedContext
}

const endContext = take(context)
  .apply(patternOne)
  .apply(patternTwo)
  .apply(patternThree)
```
