
## test-script
```
const variable  ="special/var:iable"
await $`echo ${variable}`;
```

## In zx 7.0.4 and 7.0.5

run `npx zx@7.0.5 test.mjs`

expected  output: __special/var:iable__

actual ouput: __$special/var:iable__


## In zx 7.0.3 and lower

run `npx zx@7.0.5 test.mjs`

expected  output: __special/var:iable__

actual output: __$special/var:iable__
