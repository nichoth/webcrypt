Demonstration of `browser` field in package.json

```
browserify -p esmify index.js > bundle.js,
```

Using [one-webcrypto with a browser field](https://github.com/nichoth/one-webcrypto)
```
-rw-r--r--    1 nick  staff   899B Jul 10 23:17 bundle.js
```

Using [one-webcrypto without browser field](https://www.npmjs.com/package/one-webcrypto)

```
-rw-r--r--    1 nick  staff   716K Jul 10 23:20 bundle.js
```

---------------------------

`890B` vs `716KB`
